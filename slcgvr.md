代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigfzy.top/Article/details/gtotbvpesr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gthgpugmfw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtzjwzrhcn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenjidiqi.icu/Article/details/gtlypqdmbc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258888.top/Article/details/gtchkjrnff.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhoulong.xyz/Article/details/gtzcunxisc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtzvkndvei.html

[L06] 解析响应为 JSON
来源：http://dali.havefunace.top/Article/details/gtprphmapi.html

Py:   resp.json()
来源：http://dali.yuanzhike.top/Article/details/gthenqzapa.html

PHP:  json_decode($body, true);
来源：http://dali.xuanzx.com/Article/details/gttqefvnln.html

JS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtsluqhxci.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gtzdplufiq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xinyue.icu/Article/details/gterchihzn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gtmswokrab.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guannengcc.top/Article/details/gtqaeazatg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gtlobaxrlj.html

[L07] 处理 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gtjzlksjgl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnxiangtu.top/Article/details/gtdxbjgzsd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yueranfly.top/Article/details/gtakkigkkm.html

JS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gtjqptgqqo.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtmqxsmocm.html

Java: resp.statusCode()
来源：http://dali.fengsongda.top/Article/details/gtznuhczch.html

Go:   resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtzageyxag.html

Ruby: resp.code.to_i
来源：http://dali.yj202588.top/Article/details/gtqkjloayt.html

C#:   (int)resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gtaggfzdnk.html

[L08] 并发请求多个地址
来源：http://dali.gzhubu.top/Article/details/gtzddysnfp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gtwiygvugn.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigufen.top/Article/details/gtbvmnulnu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gthiwwidrs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtcuvirdbg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gtqmldwqqx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gttujysrhe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtkhfboinc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.meibo888.top/Article/details/gtynrtrjok.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtcmlnwuzt.html

M. 命令行 / 进程 / 环境
来源：http://dali.dianchejie.cn/Article/details/gthhnobrfl.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjauurysa.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzpjkkcp.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvifnsecn.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gtqmtcwczf.html

JS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gtsflllbfo.html

TS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtleuwbjba.html

Java: args 数组（main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gtvxnzrlfw.html

Go:   os.Args[1:]
来源：http://dali.guowangkeji.top/Article/details/gtleruxnmi.html

Ruby: ARGV
来源：http://dali.hywenlv.cn/Article/details/gtyydwnnux.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtnyrkpzps.html

[M02] 读取环境变量
来源：http://dali.c1oappe.top/Article/details/gtikpplyts.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtrzzycwng.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gtawbbzjhp.html

JS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gtptkmhgop.html

TS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gtqkiqizbn.html

Java: System.getenv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssisuylb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtaystptwg.html

Ruby: ENV["HOME"]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpxpobwp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtvqiifppw.html

[M03] 执行外部命令
来源：http://dali.nanxuanxn.top/Article/details/gtuqicyrvb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gtrwbjewcb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdaxgvgdu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gtlpudzdto.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gtfrkhidzp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnxiangtu.top/Article/details/gthhpzerfw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gtkoyaienh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhiwuduotai.top/Article/details/gtzywibkau.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gtmiswwqnb.html

[M04] 获取当前工作目录
来源：http://dali.cqqwz.cn/Article/details/gtnkerqbyf.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gtkyfnmpkw.html

PHP:  getcwd();
来源：http://dali.yj20258.top/Article/details/gtyhjdlgcv.html

JS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gthmxzkyrk.html

TS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnlllksz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.redwolf501.top/Article/details/gtjihmksic.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gtquuddemr.html

Ruby: Dir.pwd
来源：http://dali.ydzc1.top/Article/details/gtgweyqxpb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sweek.top/Article/details/gtibeizmez.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gtqzhhuagr.html

Py:   sys.exit(1)
来源：http://dali.yj202588.top/Article/details/gtodyrqcpt.html

PHP:  exit(1);
来源：http://dali.wangshuangyany.cn/Article/details/gtaahqbtsr.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtynnohgsj.html

TS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gttwuwaxgs.html

Java: System.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtfrxwpuqp.html

Go:   os.Exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtbbdkmltu.html

Ruby: exit 1
来源：http://dali.bjfxy.top/Article/details/gtxxxynnvd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhongyouzk.top/Article/details/gtfcspbdfp.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gtvkbzbycn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gtcrjlukek.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.0kj1m.cn/Article/details/gtnnpfccde.html

JS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtswrntczz.html

TS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gtzwhacruf.html

Java: System.err.println("err")
来源：http://dali.pycfn.com/Article/details/gtatmiaghg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zycfv.cn/Article/details/gtguydszuq.html

Ruby: warn "err"
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgcvwagj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhongyouzk.top/Article/details/gtbieyxczm.html

[M07] 判断是否为主入口
来源：http://dali.shangyingyoupin.top/Article/details/gtbryvpnmo.html

Py:   if __name__ == "__main__":
来源：http://dali.gotoacloud.top/Article/details/gtrzlgrbco.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fengsongda.top/Article/details/gteqqpnjlg.html

JS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gtpemikkfg.html

TS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gtujqfqhwd.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gtndatbiis.html

Go:   func main()
来源：http://dali.hongshengwenyu.top/Article/details/gtnfjcgoqk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sweek.top/Article/details/gtsfcvidyy.html

C#:   static void Main(string[] args)
来源：http://dali.xylfe.cn/Article/details/gtcacnklmf.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gtrmwfhqyu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ybcxt.top/Article/details/gtjhtgcmle.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gthacelnro.html

JS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gtnggmzgfw.html

TS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gtjenxvekn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.kuanghao11.cn/Article/details/gthwbssppe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gtccjfwjcj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrapsiqz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.svipenyu.cn/Article/details/gtiyubafdk.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtflbsznih.html

N. 数据结构与算法
来源：http://dali.ydzc1.top/Article/details/gtdlsqzsrp.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtxzcgrpkc.html

[N01] 二分查找（有序数组）
来源：http://dali.hnqzz.top/Article/details/gtbcurzlep.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtjmfdocgp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtofviltai.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtorvnhnqk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtnakucxtk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtrfdsexsu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtpgttvqqb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gaohongyu789.top/Article/details/gtvrhmnqtb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtxupftwul.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgufenzy.top/Article/details/gtssoduwid.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gtuarumdpi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shuidangran.top/Article/details/gtkmztegzs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtcenyubde.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gtgxrrvsxd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.iojbl.cn/Article/details/gtgemuijto.html

Go:   slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtbupcijvx.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gtttmsgmre.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ybcxt.top/Article/details/gtyewwxcef.html

[N03] 快速排序（分治示例）
来源：http://dali.xziqi.cn/Article/details/gtffibmbsn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guowangkeji.top/Article/details/gtqfkbjbqm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gtbrvolsdq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtxxdogqqr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjlfdnwi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gzhubu.top/Article/details/gtmydmbabs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.feifeiyinyue.top/Article/details/gtozkngkkw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.meibo888.top/Article/details/gtcsougiua.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gtpgtgnvao.html

[N04] 斐波那契数列
来源：http://dali.zhiwuduotai.top/Article/details/gtbxejnrqe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gtncdirvho.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gtpnxadzck.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtzodqnjfw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtodayfwey.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtdzajamcu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ybcxt.top/Article/details/gtigsdwysj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtcdoorbhn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtzwsehkrm.html

[N05] 最大公约数
来源：http://dali.9152youxi.cn/Article/details/gtohsexpfy.html

Py:   math.gcd(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gtlaityfuu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yvedp.cn/Article/details/gtvtxbgqar.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gtapyfhejo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtlzgrhpvf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yongpay.top/Article/details/gtohmxycmh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxinkj.top/Article/details/gtnqqxjpsj.html

Ruby: a.gcd(b)
来源：http://dali.jqgufenzy.top/Article/details/gtvgvmjgwc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pycfn.com/Article/details/gtatmhemwe.html

[N06] 判断回文字符串
来源：http://dali.aibaodan.cn/Article/details/gtmpzkxdzg.html

Py:   s == s[::-1]
来源：http://dali.yj20258888.top/Article/details/gtmrlyggvy.html

PHP:  $s === strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtdhwkshhx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtuxazfvne.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gthljaeymp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yanxiufei.cn/Article/details/gtmtzwhjrm.html

Go:   // 双指针从两端比较
来源：http://dali.vqdsnc.cn/Article/details/gtmvvzvqaa.html

Ruby: s == s.reverse
来源：http://dali.gotoacloud.top/Article/details/gtmexjguye.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gtofdvpouu.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gtpsfiqxrf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gtjagoymdd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guannengcc.top/Article/details/gtvprqrtrf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yanxiufei.cn/Article/details/gtlyjcpsam.html

TS:   // 手写 Map<string, number>
来源：http://dali.jiagoushi.top/Article/details/gtjcvnqidr.html

Java: // 手写 HashMap
来源：http://dali.jlsjyb.cn/Article/details/gtxspemdyj.html

Go:   // 手写 map[int]int
来源：http://dali.ppjwa.cn/Article/details/gtpeurnvce.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhsonjgb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.havefunace.top/Article/details/gtaaomavya.html

[N08] 生成全排列
来源：http://dali.zhoulong.xyz/Article/details/gtllovzash.html

Py:   itertools.permutations(arr)
来源：http://dali.sxryk.cn/Article/details/gtgewnlaaj.html

PHP:  // 手写递归交换
来源：http://dali.xuetiantiany.cn/Article/details/gtpxrjdgmf.html

JS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtjkbyzqnl.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtkpdmgvdm.html

Java: // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtcbjlrpux.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtrnusdmco.html

Ruby: arr.permutation.to_a
来源：http://dali.bjfxy.top/Article/details/gtnfvkqyqd.html

C#:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtcklupapj.html

[N09] 栈与队列
来源：http://dali.fzhhl.top/Article/details/gtgskldinl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jianghu66.top/Article/details/gtloxpexto.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtwldcwaju.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtttkclwco.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sufxvd.cn/Article/details/gtydmwkmfz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tian-w.cn/Article/details/gtaikurxie.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.quarkkingdee.top/Article/details/gtrdonjhfc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gtdpjprxfc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pycfn.com/Article/details/gtiadlfdvw.html

[N10] 链表节点定义
来源：http://dali.hysaishi.cn/Article/details/gtfwchsoah.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yvedp.cn/Article/details/gtctwnoxkb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shuidangran.top/Article/details/gtvjwakuir.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.iojbl.cn/Article/details/gtcbmzwpej.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gzhubu.top/Article/details/gtwjhmubtx.html

Java: class Node { int v; Node next; }
来源：http://dali.ydzc1.top/Article/details/gthtraylha.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.0kj1m.cn/Article/details/gtjftzwbzu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tianlin.xyz/Article/details/gtaclgypbh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ppjwa.cn/Article/details/gtnigigbwk.html

[N11] 二叉树中序遍历
来源：http://dali.sysykeji.top/Article/details/gtlmbbqrjn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.quarkkingdee.top/Article/details/gtddqwbkte.html

PHP:  // 手写递归函数
来源：http://dali.feifeiyinyue.top/Article/details/gteeuxkpfp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gtswiplhme.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tanke756.top/Article/details/gtdjdgemdr.html

Java: // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtqnqdntoo.html

Go:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtjckadeos.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hongshengwenyu.top/Article/details/gtyxnvrbqa.html

C#:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtgliruikq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxuanxn.top/Article/details/gtxmtzpbpj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jlsjyb.cn/Article/details/gtdbbnnfqe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgfzy.top/Article/details/gtwbikojqi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycusqdjc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gtuqmnicda.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gteeaehtvr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dashuyun.cn/Article/details/gtoccbgvpe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.smart0.xyz/Article/details/gtbpdouddd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gtwbmvxceb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtuqwtinnl.html

O. 并发与异步
来源：http://dali.shzxlz.cn/Article/details/gtlkejvwca.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtndyzmwgx.html

[O01] 启动一个线程
来源：http://dali.sweek.top/Article/details/gtncfvalhz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gotoacloud.top/Article/details/gtqmzkeegc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenzaomai.com/Article/details/gthdzceljq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.svipenyu.cn/Article/details/gttonqnzdc.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtzmewlvlq.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnqzz.top/Article/details/gtudzmdbkh.html

Go:   go f()
来源：http://dali.dashuyun.cn/Article/details/gtwjlndlay.html

Ruby: Thread.new { f }
来源：http://dali.wangdashe.top/Article/details/gtczmnkabf.html

C#:   Task.Run(() => F());
来源：http://dali.sweek.top/Article/details/gtdgckeury.html

[O02] 使用线程池
来源：http://dali.sysykeji.top/Article/details/gtaiilrzyo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258.top/Article/details/gtkcvdswwr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hysaishi.cn/Article/details/gtnvengyfc.html

JS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gtfkxlogrt.html

TS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gtlnalzllu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ehwqpu.com/Article/details/gtzmsfqbdu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.kuanghao11.cn/Article/details/gttilbbxqv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yanxiufei.cn/Article/details/gtvidkcrpw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daria6918.cn/Article/details/gtpauthgps.html

[O03] 加锁保护共享数据
来源：http://dali.jianghu66.top/Article/details/gtblambmur.html

Py:   with lock: shared += 1
来源：http://dali.redwolf501.top/Article/details/gtlndxqdgt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shuidangran.top/Article/details/gthjjapddm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenlongwang.top/Article/details/gtpmehgzdd.html

TS:   // 同 JS
来源：http://dali.dashuyun.cn/Article/details/gtcdwoqgsv.html

Java: synchronized (this) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtsgifrlfg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gtpnkobmon.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cucudq.cn/Article/details/gtouqwiboa.html

C#:   lock (gate) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gtxnmtwqdq.html

[O04] 定义异步函数并等待
来源：http://dali.zhoulong.xyz/Article/details/gtxzzudvae.html

Py:   async def f():⏎    await g()
来源：http://dali.hywenlv.cn/Article/details/gtfyltaddj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.9152youxi.cn/Article/details/gtzibvomoh.html

JS:   async function f() { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gtsuwdhgov.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yongpay.top/Article/details/gtnpbggzqe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.haohaochexian.top/Article/details/gtvgybjvjo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gtezukyzks.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuetiantiany.cn/Article/details/gtwhclgfno.html

C#:   async Task F() { await G(); }
来源：http://dali.xuanzx.com/Article/details/gtvejvyndo.html

[O05] 并发执行并等待全部完成
来源：http://dali.mhx1999.top/Article/details/gtjkiwqcjm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ydzc1.top/Article/details/gtfookytmq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobqzoebo.html

JS:   await Promise.all(tasks)
来源：http://dali.guowangkeji.top/Article/details/gtdbybvcho.html

TS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtfabwnfvn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pengpengdd.cyou/Article/details/gtaclzszdh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhiwuduotai.top/Article/details/gtuvodclvi.html

Ruby: threads.map(&:join)
来源：http://dali.gzhubu.top/Article/details/gtgzjzugre.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shzxlz.cn/Article/details/gtufzoirtr.html

[O06] 使用进程池
来源：http://dali.mhx1999.top/Article/details/gtfsvberzg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ppjwa.cn/Article/details/gtcyracree.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.vqdsnc.cn/Article/details/gtvdlxdpnu.html

JS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgejqhqp.html

TS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gtmvkxnfoj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cqqwz.cn/Article/details/gtutwptelo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guowangkeji.top/Article/details/gtdlyyzhuq.html

Ruby: // fork 块
来源：http://dali.zhixingplan.top/Article/details/gtvjpwvoco.html

C#:   Parallel.For
来源：http://dali.yangfankeji.com/Article/details/gtliivigoi.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtrekchdcy.html

P. 常用工具函数
来源：http://dali.yonumen.top/Article/details/gtykvyvjwk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtfqyzssjj.html

[P01] 生成 UUID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrbqderh.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258.top/Article/details/gtadkrndiu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.redwolf501.top/Article/details/gtsfatsqac.html

JS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gtakhyqeno.html

TS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gttayduvav.html

Java: UUID.randomUUID().toString()
来源：http://dali.jianghu66.top/Article/details/gtpvnwotid.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yueranfly.top/Article/details/gtpfyqjuzk.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gtzhiwbymq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ivvv.top/Article/details/gtukfzpdzo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cheryme.top/Article/details/gtiztopfdc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gtpewvvaxr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yongpay.top/Article/details/gtgendsgkq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnwgmcvm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aizwys.cn/Article/details/gtoaxbgmdu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xziqi.cn/Article/details/gtdejmctod.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nwbrower.top/Article/details/gttqadeoil.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hywenlv.cn/Article/details/gtzlkssdkw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinghuilouyu.cn/Article/details/gtgifhkchl.html

[P03] 生成短随机字符串
来源：http://dali.ppjwa.cn/Article/details/gthyeuidhc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fengsongda.top/Article/details/gtswvluowt.html


<!-- 参考信息 -->