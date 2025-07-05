# My 100 Days of GPU Learning Journey

## About This Challenge

I am participating in the **100 Days of GPU Challenge**, an initiative inspired by the community at [hkproj/100-days-of-gpu](https://github.com/hkproj/100-days-of-gpu).

My personal goal for this challenge is to learn and master **Mojo 🔥**, a new programming language for all AI developers. I will be following the learning path provided by Modular through their interactive **[Mojo 🔥 GPU Puzzles](https://builds.modular.com/puzzles/introduction.html)**.

## My Goal

The objective is to consistently code and learn for 100 days, documenting my progress as I solve the puzzles and explore the capabilities of Mojo for GPU programming.

I will create a new folder for each day to store my code and learning notes.

## Key Resources

- **The 100 Days of GPU Challenge**: [https://github.com/hkproj/100-days-of-gpu/blob/main/CUDA.md](https://github.com/hkproj/100-days-of-gpu/blob/main/CUDA.md)
- **My Learning Material**: [Mojo 🔥 GPU Puzzles](https://builds.modular.com/puzzles/introduction.html)

Let the learning begin! 🔥

Modular 與 Mojo 詳細介紹

Modular 是什麼？

Modular 是一間美國矽谷新創公司，致力於打造統一、快速且可擴展的生成式 AI 推論平台。其目標是消除 AI 軟體生態的碎片化與複雜性，讓 AI 開發與部署變得簡單、可攜、跨平台，並推動 AI 普及化與民主化。Modular 由 Chris Lattner（LLVM、Swift、MLIR 之父）與 Tim Davis（前 Google Brain/TF/XLA 領導人）共同創辦，團隊成員多來自全球頂尖 AI 軟硬體企業。

核心產品與特色
	•	MAX (Modular Accelerated Xecution)：統一的 AI 推論引擎，支援多種硬體（Nvidia/AMD/Intel/ARM/RISC-V），可將 TensorFlow、PyTorch 等模型自動最佳化，部署於雲端或本地。
	•	Mojo 語言：為 AI 時代打造的高效能、強型別、Python 風格的編譯型程式語言，兼具 Python 的易用性與 C++/Rust 的效能與安全性。
	•	服務模組：統一的服務框架，讓模型快速部署到雲端、支援 REST API、支援 500+ Hugging Face 開源模型。
	•	開發者生態：完整文件、範例、社群、VSCode 擴充套件、GPU Puzzles 練習題、Mojo Playground 線上體驗等。

Modular 的願景
	•	打造一個橫跨所有硬體、軟體層的 AI 統一堆疊，讓開發者「一次撰寫、到處執行」。
	•	讓 AI 技術從大型企業下放到每個人與每個組織，降低雲端運算成本、提升效率與創新速度。
	•	用簡單易學的工具與語言（如 Mojo）消弭 Python/C++/CUDA 等多語言分裂，讓 AI 開發「一語到底」${DIA-SOURCE} ↗、${DIA-SOURCE} ↗。

Mojo 是什麼？

Mojo 是 Modular 公司開發的新一代程式語言，定位為 Python 的超集合（Superset），又被稱為「Python++」。它融合了 Python 的易用性、C++ 的速度、Rust 的安全性，以及 MLIR 編譯器技術的強大能力，專為 AI、機器學習與高效能運算設計${DIA-SOURCE} ↗。

語言特性與優勢
	•	語法高度相容 Python：新手可直接用 Python 語法寫 Mojo 程式，進階用戶可逐步引入型別、結構、泛型等高效能元素。
	•	漸進式型別系統：支援動態與靜態型別，開發者可依需求選擇型別檢查強度，兼顧靈活性與效能。
	•	零成本抽象：內建結構體（struct）、泛型（generics）、編譯時元編程（metaprogramming），能寫出與硬體無關的高效能演算法。
	•	所有權與借用檢查器：借鑑 Rust 設計，提供記憶體安全但不犧牲效能。
	•	可攜式並行運算：原生支援 SIMD、thread、AI 加速器等異質硬體，無需 CUDA 也可寫 GPU/TPU 程式。
	•	自動調優（Auto-tuning）：語言層級支援自動尋找最佳參數，發揮目標硬體最大潛力。
	•	完整 Python 生態互操作：可直接調用 Numpy、Matplotlib 等 Python 套件，並可與現有 Python 3.x 程式碼互通。
	•	極致效能：官方實測，Mojo 在數值運算上可較 Python 提升數千至數萬倍效能${DIA-SOURCE} ↗。

典型應用場景
	•	AI/機器學習模型訓練與推論
	•	高效能數值計算與科學運算
	•	GPU/TPU/多核心 CPU 程式設計
	•	自訂 AI 內核、加速自有演算法
	•	跨硬體平台部署與最佳化

開發與生態
	•	由 LLVM/Swift/MLIR 團隊打造，2023 年 5 月首度發表，現支援 Linux/macOS/雲端 Notebook。
	•	官方提供 VSCode 擴充、Mojo Playground 線上體驗、Mojo SDK、範例程式、文件與社群支援。
	•	安裝簡單，可透過 pip、conda 或官方腳本一鍵安裝${DIA-SOURCE} ↗。

語法範例print('Hello, World!')  # 與 Python 完全相同

fn add(a: Int, b: Int) -> Int:
    return a + b

struct MyPair:
    var first: Int
    var second: F32
    def __init__(self, first: Int, second: F32):
        self.first = first
        self.second = second

Modular + Mojo 的價值與未來
	•	一語到底解決「兩語言問題」：AI 開發不再需要 Python + C++/CUDA 雙語言協作，Mojo 一語橫跨從高階到底層。
	•	效能與生產力兼得：用 Python 風格寫高效能程式，無痛遷移、快速學習，適合從初學者到專業開發者。
	•	完整開源與社群生態：MAX 引擎、Mojo 語言、GPU Kernels、AI 模型等多數已開源，社群活躍、資源豐富。
	•	跨平台、跨硬體、未來導向：支援主流 CPU/GPU/AI 加速器，未來將涵蓋更多嵌入式/雲端/新架構。
	•	推動 AI 民主化：降低進入門檻，讓更多開發者、企業能參與 AI 創新。

參考與延伸閱讀
	•	Modular 官方網站 ↗
	•	Mojo 官方手冊 ↗
	•	Mojo 維基百科條目 ↗
	•	Mojo 中文社群 ↗
	•	Mojo 中文網 ↗
	•	電子工程專輯：Modular與Mojo專題 ↗
