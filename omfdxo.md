代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.birdmap.top/Article/details/gtolmruhpr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gtoclwbiku.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gtfvwmtcri.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guannengcc.top/Article/details/gtixeaqtwx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hysaishi.cn/Article/details/gtuffocgus.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cashguo.top/Article/details/gtnqrrzqsn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gtwbowvjyt.html

[L06] 解析响应为 JSON
来源：http://dali.zycfv.cn/Article/details/gtanuiedut.html

Py:   resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtuuarjgww.html

PHP:  json_decode($body, true);
来源：http://dali.hnqzz.top/Article/details/gtrurtfcml.html

JS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtikymmwjn.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxokxgza.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.meibo888.top/Article/details/gtydvcfxjp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.andypj.xyz/Article/details/gtxtxcfirj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gterexmipq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ehwqpu.com/Article/details/gtyrpwixyj.html

[L07] 处理 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtrqbqsgkc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gtnghzbmto.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjzhkzxq.html

JS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gtzmwoclsq.html

TS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gtyrtpcyna.html

Java: resp.statusCode()
来源：http://dali.quarkkingdee.top/Article/details/gtfsrvoafu.html

Go:   resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtmuvadhas.html

Ruby: resp.code.to_i
来源：http://dali.guowangkeji.top/Article/details/gtzabrfxlo.html

C#:   (int)resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtxzrtkzbe.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gtjivhqjpe.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gtktwmajrt.html

PHP:  curl_multi_init() 系列
来源：http://dali.guannengcc.top/Article/details/gtgkzyhejo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtwznqzrjl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtudahuipz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangdashe.top/Article/details/gtisfplvul.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhixingplan.top/Article/details/gtvfwhjbql.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.9152youxi.cn/Article/details/gttdmptafx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtozgsfvfe.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtokgxepjr.html

M. 命令行 / 进程 / 环境
来源：http://dali.cucudq.cn/Article/details/gtrfklnzlk.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtqjlbstdh.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gtecwqwroe.html

Py:   sys.argv[1:]
来源：http://dali.9152youxi.cn/Article/details/gtulgoprvv.html

PHP:  $argv;  $argc;
来源：http://dali.ppjwa.cn/Article/details/gtfqkzdjfk.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtltcpafdw.html

TS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtqtqbpycy.html

Java: args 数组（main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtusjlgzpl.html

Go:   os.Args[1:]
来源：http://dali.yuxming.cn/Article/details/gtgypmvphx.html

Ruby: ARGV
来源：http://dali.zhixingplan.top/Article/details/gtbmionesx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtlvtwqrtb.html

[M02] 读取环境变量
来源：http://dali.jqgfzy.top/Article/details/gtrcvrytlj.html

Py:   os.environ.get("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtyeqcyjqe.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtytnqwfzv.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtojvjfsmb.html

TS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gtunvssqqd.html

Java: System.getenv("HOME")
来源：http://dali.hammf.cn/Article/details/gttevpgdyr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtelucvgnk.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gtbihcynmc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xylfe.cn/Article/details/gtnfbqejoc.html

[M03] 执行外部命令
来源：http://dali.yuxming.cn/Article/details/gtiiipkfkn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gtsnqvxjln.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gtpobqgonz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gtcfllxort.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtrejdqhwi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gtbfxsyiyo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nwbrower.top/Article/details/gticytysbs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dianchejie.cn/Article/details/gtauseqroh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangshuangyany.cn/Article/details/gtepjpfdhz.html

[M04] 获取当前工作目录
来源：http://dali.9152youxi.cn/Article/details/gtwrbhkykx.html

Py:   os.getcwd()
来源：http://dali.hammf.cn/Article/details/gtmvyszciv.html

PHP:  getcwd();
来源：http://dali.pycfn.com/Article/details/gtgzjmcecj.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtydyrvcek.html

TS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gthpcmndmt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gtsbizxgpa.html

Go:   os.Getwd()
来源：http://dali.sufxvd.cn/Article/details/gtymjhcsgw.html

Ruby: Dir.pwd
来源：http://dali.wangdashe.top/Article/details/gtqpqtnkbt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cqqwz.cn/Article/details/gtqvhpubla.html

[M05] 设置退出码
来源：http://dali.nanxuanxn.top/Article/details/gtxkdfcwxo.html

Py:   sys.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtdjxqdecq.html

PHP:  exit(1);
来源：http://dali.wangdashe.top/Article/details/gtpzjhgwoi.html

JS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtvmovsfqb.html

TS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gthejoeyar.html

Java: System.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtbfhzvmzl.html

Go:   os.Exit(1)
来源：http://dali.tian-w.cn/Article/details/gtswdsircs.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gtojvhoajr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.bjfxy.top/Article/details/gtretlktbp.html

[M06] 向标准错误输出
来源：http://dali.havefunace.top/Article/details/gttwhdkpko.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gtvhfegwkc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hfpthk.cn/Article/details/gthjexaqih.html

JS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtbgbduwya.html

TS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtroldgfkk.html

Java: System.err.println("err")
来源：http://dali.gaohongyu789.top/Article/details/gtkljtofbu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbiphzwx.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gtidxxphpy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ivvv.top/Article/details/gtoyguqvrt.html

[M07] 判断是否为主入口
来源：http://dali.hfpthk.cn/Article/details/gtmvktdmsk.html

Py:   if __name__ == "__main__":
来源：http://dali.ybcxt.top/Article/details/gtshbfoquq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shangyingyoupin.top/Article/details/gtknmasogx.html

JS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtijqjgejd.html

TS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gtxjejaryh.html

Java: public static void main(String[] args)
来源：http://dali.svipenyu.cn/Article/details/gtazxqdcqz.html

Go:   func main()
来源：http://dali.jlsjyb.cn/Article/details/gthsgmddta.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gtbszazaml.html

C#:   static void Main(string[] args)
来源：http://dali.bjfxy.top/Article/details/gtiluqvzov.html

[M08] 获取系统与运行时信息
来源：http://dali.havefunace.top/Article/details/gtrdwmnzuv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxinkj.top/Article/details/gtjyfxfqez.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.mhx1999.top/Article/details/gtickxfuar.html

JS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gtautewals.html

TS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtppqogqrh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fzhhl.top/Article/details/gtkuetxpgq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhengqikj.top/Article/details/gtfhkrcedj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gtbskwrxsl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cheryme.top/Article/details/gtxgakzeaw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gttxvhwuri.html

N. 数据结构与算法
来源：http://dali.hysaishi.cn/Article/details/gtwmcbwfab.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtiqntjpuc.html

[N01] 二分查找（有序数组）
来源：http://dali.hysaishi.cn/Article/details/gtxnjmqviu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtbfnnlqbr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daria6918.cn/Article/details/gtkfbnlebc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtcyqmiflh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtuutabfqc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtzrksyuox.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtgobfvwnw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xylfe.cn/Article/details/gtussebxbv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtydvnuqsm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigfzy.top/Article/details/gtqqilelhu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gtjuxtmknt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gtuhzrybkr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gttrmerrnz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtgbgegpqv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hywenlv.cn/Article/details/gtlusvanjb.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtlkduwzmp.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gtykddrunl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtshdtacrf.html

[N03] 快速排序（分治示例）
来源：http://dali.wangshuangyany.cn/Article/details/gtptmyvjmi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zycfv.cn/Article/details/gtypibzikf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuanzhike.top/Article/details/gtvzwklvwj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gtfzokgoep.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtqthrjimo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sysykeji.top/Article/details/gtctwiabnk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fzhhl.top/Article/details/gtqvewslga.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cheryme.top/Article/details/gtrcmpqavc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shzxlz.cn/Article/details/gtbekzzabz.html

[N04] 斐波那契数列
来源：http://dali.sufxvd.cn/Article/details/gtobdpchwb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gtfoqjtakm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.c1oappe.top/Article/details/gtgeacedcc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtotrawecn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtsaxafnaw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yonumen.top/Article/details/gtraphzfxo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fengsongda.top/Article/details/gtjupimnah.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gtxgtsljlu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtvrqjtrro.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gtbcjluqhz.html

Py:   math.gcd(a, b)
来源：http://dali.gotoacloud.top/Article/details/gthcxynqnx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtijxkpzfn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gtgujkanyv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gtvyfnhlrt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cucudq.cn/Article/details/gtglgaanax.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.quarkkingdee.top/Article/details/gtkgclogiu.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gtfafudapk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphiwipth.html

[N06] 判断回文字符串
来源：http://dali.svipenyu.cn/Article/details/gtaepdjbaj.html

Py:   s == s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtjraqwdyr.html

PHP:  $s === strrev($s);
来源：http://dali.ybcxt.top/Article/details/gtpqvfnkib.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtarlpdynl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtclrbktbk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.smart0.xyz/Article/details/gtwxclfleb.html

Go:   // 双指针从两端比较
来源：http://dali.cucudq.cn/Article/details/gtqnvsteuk.html

Ruby: s == s.reverse
来源：http://dali.yangfankeji.com/Article/details/gtrkkktppp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gthykrmpwt.html

[N07] 两数之和（返回下标）
来源：http://dali.zhengqikj.top/Article/details/gtcabdjfsf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tian-w.cn/Article/details/gtcvwmwodm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xylfe.cn/Article/details/gtffavewag.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenjidiqi.icu/Article/details/gtdrohzyam.html

TS:   // 手写 Map<string, number>
来源：http://dali.sufxvd.cn/Article/details/gtzwjbnzxw.html

Java: // 手写 HashMap
来源：http://dali.sufxvd.cn/Article/details/gtovrzpego.html

Go:   // 手写 map[int]int
来源：http://dali.aibaodan.cn/Article/details/gtfsqlebsz.html

Ruby: // 手写 Hash
来源：http://dali.quarkkingdee.top/Article/details/gtjrfwmaar.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnxiangtu.top/Article/details/gtquvvpfur.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gtgxhlskdd.html

Py:   itertools.permutations(arr)
来源：http://dali.yangfankeji.com/Article/details/gtyaqmzrcq.html

PHP:  // 手写递归交换
来源：http://dali.fzhhl.top/Article/details/gtlgnacuqb.html

JS:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtkizgrjvq.html

TS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtzjwnmvlj.html

Java: // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtcaadtvot.html

Go:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtvhkvjqum.html

Ruby: arr.permutation.to_a
来源：http://dali.smart0.xyz/Article/details/gtgflladwj.html

C#:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtxvplawdr.html

[N09] 栈与队列
来源：http://dali.hammf.cn/Article/details/gtnamgtggs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtpksumpre.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtvhjiitno.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gthjhvbngp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dashuyun.cn/Article/details/gtvyfccvus.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtbmwiffqc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cqqwz.cn/Article/details/gtxqyutbsa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtiruqgpek.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gtkjsmrypb.html

[N10] 链表节点定义
来源：http://dali.cqqwz.cn/Article/details/gtmtyuipho.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ybcxt.top/Article/details/gtmnjirdhy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tanke756.top/Article/details/gtskxkmgbk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjufjntgx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuanzx.com/Article/details/gthmusreqe.html

Java: class Node { int v; Node next; }
来源：http://dali.jianghu66.top/Article/details/gtvffgnkyz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daxiang520.top/Article/details/gtkaopqgaz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jianghu66.top/Article/details/gtrlzskcgy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.havefunace.top/Article/details/gtbdgctrhu.html

[N11] 二叉树中序遍历
来源：http://dali.dashuyun.cn/Article/details/gtgaefhhsj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.feifeiyinyue.top/Article/details/gtfiztccri.html

PHP:  // 手写递归函数
来源：http://dali.hongshengwenyu.top/Article/details/gtnzpadxtf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gthetedebo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtshonhjyl.html

Java: // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtoktsxopr.html

Go:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtgrtjrcau.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.haohaochexian.top/Article/details/gtkxzewkpn.html

C#:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtlemcgkwz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtfopoaqbh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ybcxt.top/Article/details/gtmrmgxbva.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daria6918.cn/Article/details/gtptvzrrsd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gtmpabhrmg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyieqnfm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtqdsifcoe.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.316326.xyz/Article/details/gtqcghrval.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gaohongyu789.top/Article/details/gtclzciscu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gtpwtrpgzv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtbuzkagvt.html

O. 并发与异步
来源：http://dali.xziqi.cn/Article/details/gtdvltpgjd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtpzrujriw.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gtapmgtbdp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenjidiqi.icu/Article/details/gtfrvuexps.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnqzz.top/Article/details/gtfgcntobx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hywenlv.cn/Article/details/gtxdnussjh.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtozkvuoll.html

Java: new Thread(() -> f()).start()
来源：http://dali.yvedp.cn/Article/details/gtkjojwrcj.html

Go:   go f()
来源：http://dali.jqgfzy.top/Article/details/gtwxdtxbmm.html

Ruby: Thread.new { f }
来源：http://dali.cashguo.top/Article/details/gtivgplppw.html

C#:   Task.Run(() => F());
来源：http://dali.havefunace.top/Article/details/gtyjzavsek.html

[O02] 使用线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtavuvpoio.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gaohongyu789.top/Article/details/gtgjgqider.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aibaodan.cn/Article/details/gtabuwdwpu.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtqvijwabg.html

TS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gtfhlmpnco.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ehwqpu.com/Article/details/gtnkrsxqjl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenzaomai.com/Article/details/gtrgulknzz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenjidiqi.icu/Article/details/gtcgjvrgxw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258888.top/Article/details/gthgvpcnxi.html

[O03] 加锁保护共享数据
来源：http://dali.iojbl.cn/Article/details/gthuboznuv.html

Py:   with lock: shared += 1
来源：http://dali.yongpay.top/Article/details/gtgdhorupk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aibaodan.cn/Article/details/gtatltmwet.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xziqi.cn/Article/details/gtpawtzild.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtfuodvwgn.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgspaqiqp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gtttjcrjcp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.snrcjt.cn/Article/details/gtbuobiqed.html

C#:   lock (gate) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtopqmywwh.html

[O04] 定义异步函数并等待
来源：http://dali.xuanzx.com/Article/details/gtcwxswpvx.html

Py:   async def f():⏎    await g()
来源：http://dali.mhx1999.top/Article/details/gtwqqzzpgk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenjidiqi.icu/Article/details/gtyieaprwd.html

JS:   async function f() { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtfxcwtvyh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gtbxphhanw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigufen.top/Article/details/gtucbbwvrd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cucudq.cn/Article/details/gtuodlpqlg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yanxiufei.cn/Article/details/gtjasnhbyx.html

C#:   async Task F() { await G(); }
来源：http://dali.c1oappe.top/Article/details/gtbzkjrbmc.html

[O05] 并发执行并等待全部完成
来源：http://dali.xinyue.icu/Article/details/gteivylgsp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aibaodan.cn/Article/details/gtdldixjot.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pengpengdd.cyou/Article/details/gtbpxccixh.html

JS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqdiqvoo.html

TS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gtvwliuhzm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jlsjyb.cn/Article/details/gtgiqmcaxn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jiagoushi.top/Article/details/gtdffxmwec.html

Ruby: threads.map(&:join)
来源：http://dali.ppjwa.cn/Article/details/gtkvgbleri.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhengqikj.top/Article/details/gtsgnqwenh.html

[O06] 使用进程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasymjmjz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sufxvd.cn/Article/details/gttijuxqhb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shzxlz.cn/Article/details/gtdlibuvvt.html

JS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gtglezmksg.html

TS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gtxntyxmoe.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yanxiufei.cn/Article/details/gtrxedlgap.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hfpthk.cn/Article/details/gtbbsqlxcr.html

Ruby: // fork 块
来源：http://dali.gzhubu.top/Article/details/gticnkyjkt.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gtigchbcxp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwsamiovh.html

P. 常用工具函数
来源：http://dali.xziqi.cn/Article/details/gtsuweezli.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtgnvmawde.html

[P01] 生成 UUID
来源：http://dali.sysykeji.top/Article/details/gtibsredeo.html

Py:   str(uuid.uuid4())
来源：http://dali.daxiang520.top/Article/details/gtplnmhsmc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgfzy.top/Article/details/gtomnzhtri.html

JS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtowhrlxdd.html

TS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtwhcpcpnp.html

Java: UUID.randomUUID().toString()
来源：http://dali.cashguo.top/Article/details/gtxpuhwmda.html

Go:   // 用 github.com/google/uuid
来源：http://dali.kuanghao11.cn/Article/details/gthsjgvgkx.html

Ruby: SecureRandom.uuid
来源：http://dali.jiagoushi.top/Article/details/gtnsoedlfm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yanxiufei.cn/Article/details/gtozwewqxr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xinyue.icu/Article/details/gtgfvyaozx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ivvv.top/Article/details/gtrhxyxfqp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtigtjirej.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuanzx.com/Article/details/gtkrrybnnv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xziqi.cn/Article/details/gtwfqwyuwd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtsppsuwgp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hywenlv.cn/Article/details/gtcwxmznci.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtmbyqwizb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.316326.xyz/Article/details/gtfvqutphr.html

[P03] 生成短随机字符串
来源：http://dali.zdqjudy.top/Article/details/gtinxppzuo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xylfe.cn/Article/details/gtvtmwwyut.html


<!-- 参考信息 -->