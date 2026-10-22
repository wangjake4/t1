代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gt2sjuedfbt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cqqwz.cn/Article/details/gt2xigwgkwr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2dlvffhnf.html

[L06] 解析响应为 JSON
来源：http://dali.vqdsnc.cn/Article/details/gt2qqxfvmin.html

Py:   resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gt2flsrfvuc.html

PHP:  json_decode($body, true);
来源：http://dali.yuanzhike.top/Article/details/gt2yjtudtre.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2ksiohcok.html

TS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2bhzobyuq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gt2infhdjig.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yueranfly.top/Article/details/gt2gofxzeqq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wrwdzdax.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gt2kpjlfkqe.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gt2gczcepgc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.snrcjt.cn/Article/details/gt2rvftadrr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hysaishi.cn/Article/details/gt2fkuwvpgl.html

JS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gt2wfkfiozf.html

TS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kteldtxl.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gt2wepdbkoq.html

Go:   resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gt2usvvbotb.html

Ruby: resp.code.to_i
来源：http://dali.jianghu66.top/Article/details/gt2endjdwej.html

C#:   (int)resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gt2jtslumyg.html

[L08] 并发请求多个地址
来源：http://dali.haohaochexian.top/Article/details/gt2xhunlbte.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gt2ammtihmp.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhengqikj.top/Article/details/gt2shbhstru.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eobwfwnb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gt2zopdpjur.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yonumen.top/Article/details/gt2caenrgpx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.c1oappe.top/Article/details/gt2gabktttl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangdashe.top/Article/details/gt2wqoheubh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gt2tevkteru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mkppqfid.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258.top/Article/details/gt2zkndgxqt.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2krfwtwjb.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gt2lcshpnyc.html

Py:   sys.argv[1:]
来源：http://dali.yuanzhike.top/Article/details/gt2gvvmusij.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigfzy.top/Article/details/gt2rjcicvln.html

JS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gt2ealmoydn.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tejstpmh.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gt2ojbxwlnu.html

Go:   os.Args[1:]
来源：http://dali.mhx1999.top/Article/details/gt2gjrwxhxy.html

Ruby: ARGV
来源：http://dali.wangdashe.top/Article/details/gt2arpqqehu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gt2ulqagpkd.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2wfonwowy.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2docuuvhd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gt2mqbhfhfe.html

JS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gt2alcyzyhs.html

TS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gt2radmpunr.html

Java: System.getenv("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2komvitfb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2aqssacjc.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gt2odqwtwun.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zgcoxsnt.html

[M03] 执行外部命令
来源：http://dali.chenzaomai.com/Article/details/gt2kfdnwvjd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.316326.xyz/Article/details/gt2mgmslhzr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gt2wbjzzgih.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2xvlszrti.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gt2wlpaltwr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gt2vzaoljqu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gt2nwqhadsa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gzhubu.top/Article/details/gt2hnncxyxj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cheryme.top/Article/details/gt2acjfenhm.html

[M04] 获取当前工作目录
来源：http://dali.hfpthk.cn/Article/details/gt2aimwlfjd.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gt2yqrchxbq.html

PHP:  getcwd();
来源：http://dali.gogol.net.cn/Article/details/gt2njferhrh.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gt2crofauej.html

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gt2anfbysrb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gt2nghusoqq.html

Go:   os.Getwd()
来源：http://dali.zycfv.cn/Article/details/gt2wdluvmdm.html

Ruby: Dir.pwd
来源：http://dali.jiagoushi.top/Article/details/gt2ogmqmvpi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ehwqpu.com/Article/details/gt2ylvfwzhy.html

[M05] 设置退出码
来源：http://dali.andypj.xyz/Article/details/gt2sjqcejlr.html

Py:   sys.exit(1)
来源：http://dali.sweek.top/Article/details/gt2uyafprrq.html

PHP:  exit(1);
来源：http://dali.smart0.xyz/Article/details/gt2uieppbxj.html

JS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2fxuehzjs.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2sdryhfsw.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2kzabhqar.html

Go:   os.Exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2cigpynar.html

Ruby: exit 1
来源：http://dali.hnqzz.top/Article/details/gt2ixpireiq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.mhx1999.top/Article/details/gt2ilgpkfbi.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gt2vodvgsrj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnqzz.top/Article/details/gt2tlwajiwj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258.top/Article/details/gt2fksylazh.html

JS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gt2zlnjmqcy.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpqgjxl.html

Java: System.err.println("err")
来源：http://dali.yongpay.top/Article/details/gt2rbweniiw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tianlin.xyz/Article/details/gt2kxjshzmr.html

Ruby: warn "err"
来源：http://dali.nanxinkj.top/Article/details/gt2bgmyxlgh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ppjwa.cn/Article/details/gt2xilhljhu.html

[M07] 判断是否为主入口
来源：http://dali.zycfv.cn/Article/details/gt2xkhnehxl.html

Py:   if __name__ == "__main__":
来源：http://dali.gzhubu.top/Article/details/gt2whqccadw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tian-w.cn/Article/details/gt2karnjcvs.html

JS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gt2acxuyfim.html

TS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gt2eyrtngcr.html

Java: public static void main(String[] args)
来源：http://dali.gogol.net.cn/Article/details/gt2jbgxbzyt.html

Go:   func main()
来源：http://dali.jinqigufen.top/Article/details/gt2qfaskfei.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gt2wqrokazb.html

C#:   static void Main(string[] args)
来源：http://dali.gaohongyu789.top/Article/details/gt2hapeghce.html

[M08] 获取系统与运行时信息
来源：http://dali.yonumen.top/Article/details/gt2bpsmsmdi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gzhubu.top/Article/details/gt2opynxcqz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jiagoushi.top/Article/details/gt2nidgwvdh.html

JS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gt2wqkbuoml.html

TS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gt2mjuyeius.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.kuanghao11.cn/Article/details/gt2qyfzglkf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hfpthk.cn/Article/details/gt2vakmaqff.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hysaishi.cn/Article/details/gt2tkekwvgv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.smart0.xyz/Article/details/gt2ilanarct.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2khnzhjam.html

N. 数据结构与算法
来源：http://dali.hysaishi.cn/Article/details/gt2ocdzmgkd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2bbmdrfqp.html

[N01] 二分查找（有序数组）
来源：http://dali.svipenyu.cn/Article/details/gt2enccjhti.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2rdldcmtt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sufxvd.cn/Article/details/gt2tdyiwqpm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2rdmkeueg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gt2gwujjqec.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2isvrtyjc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2sdnogauz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xziqi.cn/Article/details/gt2klsvwxmx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2ieoeqoxv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hywenlv.cn/Article/details/gt2wnrzshka.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gt2ejysuofw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zdqjudy.top/Article/details/gt2tbifoync.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2fovhmgez.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gt2vwrftbzb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gt2hsntgmqk.html

Go:   slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2mfgyiiqs.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gt2rcxxkhgi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lozgfima.html

[N03] 快速排序（分治示例）
来源：http://dali.cheryme.top/Article/details/gt2mkkxpuxm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.iojbl.cn/Article/details/gt2gqourdfv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tanke756.top/Article/details/gt2ctasgcmm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gt2exaxuofr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gt2qshewxha.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.iojbl.cn/Article/details/gt2jkohzlmv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gt2vlsmchva.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jnigvavv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxinkj.top/Article/details/gt2yxiktuqp.html

[N04] 斐波那契数列
来源：http://dali.haohaochexian.top/Article/details/gt2jxfpujts.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2itpdxlfh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wzfndaiy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gt2treyqwfu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gt2zqseslev.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xylfe.cn/Article/details/gt2wqcdqhjo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.meibo888.top/Article/details/gt2rwvjsbew.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gt2udklwett.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gt2euufvccl.html

[N05] 最大公约数
来源：http://dali.yuanzhike.top/Article/details/gt2epkwothd.html

Py:   math.gcd(a, b)
来源：http://dali.birdmap.top/Article/details/gt2lzdrfjme.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gt2nnruzymf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gt2dixwtibt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gt2knyiaksm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gt2fuflmikr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aizwys.cn/Article/details/gt2dosicajp.html

Ruby: a.gcd(b)
来源：http://dali.daxiang520.top/Article/details/gt2jgnnskdk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.meibo888.top/Article/details/gt2rycapykf.html

[N06] 判断回文字符串
来源：http://dali.zdqjudy.top/Article/details/gt2todtzrfq.html

Py:   s == s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2trfkvccg.html

PHP:  $s === strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gt2yxxpcixm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gt2imrhgwmo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2dvholiyp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.9152youxi.cn/Article/details/gt2xvboepiq.html

Go:   // 双指针从两端比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2jofmizjp.html

Ruby: s == s.reverse
来源：http://dali.hammf.cn/Article/details/gt2qwnfxaxb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gt2etwbcgpq.html

[N07] 两数之和（返回下标）
来源：http://dali.zhongyouzk.top/Article/details/gt2iounyglw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlxeqnwp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhiwuduotai.top/Article/details/gt2nyiqyhhw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ydzc1.top/Article/details/gt2mqdpfmif.html

TS:   // 手写 Map<string, number>
来源：http://dali.tanke756.top/Article/details/gt2jbiitbpf.html

Java: // 手写 HashMap
来源：http://dali.zdqjudy.top/Article/details/gt2kmceonei.html

Go:   // 手写 map[int]int
来源：http://dali.hammf.cn/Article/details/gt2vitssrbh.html

Ruby: // 手写 Hash
来源：http://dali.nanxinkj.top/Article/details/gt2nuomezxw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj202588.top/Article/details/gt2yzxcitxz.html

[N08] 生成全排列
来源：http://dali.jinqigufen.top/Article/details/gt2wmolxmba.html

Py:   itertools.permutations(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2ctffdpfe.html

PHP:  // 手写递归交换
来源：http://dali.xylfe.cn/Article/details/gt2vguqqbkd.html

JS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2fjkwdtrk.html

TS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2rokjebcz.html

Java: // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2acehayvg.html

Go:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2bbkfvwxu.html

Ruby: arr.permutation.to_a
来源：http://dali.tianlin.xyz/Article/details/gt2bgbgnzkd.html

C#:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2qnabflkq.html

[N09] 栈与队列
来源：http://dali.zdqjudy.top/Article/details/gt2ehjsnwoq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gt2hwwyzbpq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2cwtksakl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gt2dvzuzvtb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gt2vopzqziq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gt2oknowhwy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cashguo.top/Article/details/gt2qlmnrnto.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gt2tvtvowmu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gt2laaaaveb.html

[N10] 链表节点定义
来源：http://dali.nanxinkj.top/Article/details/gt2qgdjprku.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.aibaodan.cn/Article/details/gt2hgqyppjc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xziqi.cn/Article/details/gt2jwwtrueu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ivvv.top/Article/details/gt2gcigvihl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cucudq.cn/Article/details/gt2kcdgefkk.html

Java: class Node { int v; Node next; }
来源：http://dali.daxiang520.top/Article/details/gt2cguhdlmm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.9152youxi.cn/Article/details/gt2vwlhnqiu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gt2czhrxffb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vfhfbhiy.html

[N11] 二叉树中序遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2ogklqvss.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gogol.net.cn/Article/details/gt2tyvgerdw.html

PHP:  // 手写递归函数
来源：http://dali.jlsjyb.cn/Article/details/gt2yxkrllzq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gt2zzsrtqfu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmtkoipi.html

Java: // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gt2grjzvqxr.html

Go:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gt2mccwnphc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258.top/Article/details/gt2uibpnpkx.html

C#:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gt2scqkxdcn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gt2tzkatrso.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ivvv.top/Article/details/gt2qaifxcvl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xxpmdyqd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gt2plgtjbqn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hammf.cn/Article/details/gt2wfnvlkwb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gt2bckrrmhg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2myrkswhb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guowangkeji.top/Article/details/gt2omckdukm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gt2vrzncglg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2boeiiwsz.html

O. 并发与异步
来源：http://dali.quarkkingdee.top/Article/details/gt2mrbputhy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2cpzdbcrq.html

[O01] 启动一个线程
来源：http://dali.ppjwa.cn/Article/details/gt2loibqkpr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.smart0.xyz/Article/details/gt2jybohzee.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gt2uebjpwoj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yvedp.cn/Article/details/gt2yhjcruns.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gt2jdmgribs.html

Java: new Thread(() -> f()).start()
来源：http://dali.kuanghao11.cn/Article/details/gt2zwkxvsrt.html

Go:   go f()
来源：http://dali.yangfankeji.com/Article/details/gt2qhxlniqz.html

Ruby: Thread.new { f }
来源：http://dali.yuxming.cn/Article/details/gt2zapctpjb.html

C#:   Task.Run(() => F());
来源：http://dali.cucudq.cn/Article/details/gt2ppntixns.html

[O02] 使用线程池
来源：http://dali.smart0.xyz/Article/details/gt2bfngyncx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuanzx.com/Article/details/gt2ivqaasxu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhixingplan.top/Article/details/gt2aaydtuht.html

JS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gt2wmgiihgt.html

TS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gt2ayfnzbqt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jlsjyb.cn/Article/details/gt2dyfjzhxl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daxiang520.top/Article/details/gt2eljodzpw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenzaomai.com/Article/details/gt2ztdehgtf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tian-w.cn/Article/details/gt2xqjaehac.html

[O03] 加锁保护共享数据
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cowvqukp.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmloomvu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yonumen.top/Article/details/gt2xnjfbgmp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgufenzy.top/Article/details/gt2gdpwwbzr.html

TS:   // 同 JS
来源：http://dali.yangfankeji.com/Article/details/gt2wehebdkb.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wfwajvoj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xhvvshrz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gnfrovhn.html

C#:   lock (gate) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gt2ckawnjdr.html

[O04] 定义异步函数并等待
来源：http://dali.jqgufenzy.top/Article/details/gt2hatdkvst.html

Py:   async def f():⏎    await g()
来源：http://dali.yj202588.top/Article/details/gt2snrzpejf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gt2mjdcomjz.html

JS:   async function f() { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gt2qzuysqxu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnqzz.top/Article/details/gt2xohnrsdk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ydzc1.top/Article/details/gt2wwrgwivw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgfzy.top/Article/details/gt2tvdqgmjk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gogol.net.cn/Article/details/gt2fivxdttc.html

C#:   async Task F() { await G(); }
来源：http://dali.zhixingplan.top/Article/details/gt2kjxzsgcf.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangdashe.top/Article/details/gt2tpwpbaqr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.9152youxi.cn/Article/details/gt2rhtbwqdo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guannengcc.top/Article/details/gt2ncliyurp.html

JS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gt2vydjvnko.html

TS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nnlgzwnr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qgkpkyyb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yongpay.top/Article/details/gt2vhqteyfb.html

Ruby: threads.map(&:join)
来源：http://dali.gzhubu.top/Article/details/gt2sqhovdvj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.316326.xyz/Article/details/gt2wjbyljqo.html

[O06] 使用进程池
来源：http://dali.yuxming.cn/Article/details/gt2rmsdetlg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jlsjyb.cn/Article/details/gt2riqkhooq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xylfe.cn/Article/details/gt2ipzqlrut.html

JS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gt2stgezjai.html

TS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gt2ynqrhipt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gt2hdwxascl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sxryk.cn/Article/details/gt2mkjuwlsd.html

Ruby: // fork 块
来源：http://dali.yvedp.cn/Article/details/gt2hvqhyrvg.html

C#:   Parallel.For
来源：http://dali.guannengcc.top/Article/details/gt2pmkesmzi.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2efjjlldi.html

P. 常用工具函数
来源：http://dali.ehwqpu.com/Article/details/gt2gohirahq.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ilagheyt.html

[P01] 生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gt2henthrgr.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqpmfmc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sufxvd.cn/Article/details/gt2jhyljzjw.html

JS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gt2utlqaeqi.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gt2npilvqtl.html

Java: UUID.randomUUID().toString()
来源：http://dali.ppjwa.cn/Article/details/gt2ohzabuna.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cucudq.cn/Article/details/gt2ewovodvm.html

Ruby: SecureRandom.uuid
来源：http://dali.cheryme.top/Article/details/gt2zazwuxpg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pycfn.com/Article/details/gt2wuqhaojv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cucudq.cn/Article/details/gt2vkorpmfw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigufen.top/Article/details/gt2omwaejjk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.redwolf501.top/Article/details/gt2hsgflrkc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnxiangtu.top/Article/details/gt2fccjglhz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxinkj.top/Article/details/gt2shkpyosc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuanzx.com/Article/details/gt2yvqbzzcn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.smart0.xyz/Article/details/gt2jvpmcirg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.c1oappe.top/Article/details/gt2ohzhwese.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tian-w.cn/Article/details/gt2myakcrgn.html

[P03] 生成短随机字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2zzymzgsj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ybcxt.top/Article/details/gt2lwnibttj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ygpbqbqa.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qiuilyip.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2kybfszrh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tianlin.xyz/Article/details/gt2ydcpeigo.html


<!-- 参考信息 -->