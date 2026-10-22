代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tian-w.cn/Article/details/gtvqnscgec.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtbuwgiawl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gtpgwnsarv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cashguo.top/Article/details/gterqtpyvm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgfzy.top/Article/details/gtuvwfeluw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zdqjudy.top/Article/details/gtcbhgiakg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sxryk.cn/Article/details/gtejvdrkdn.html

[L06] 解析响应为 JSON
来源：http://dali.gaohongyu789.top/Article/details/gtwtixrtlm.html

Py:   resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtcrmvvthd.html

PHP:  json_decode($body, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpddjrks.html

JS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtbfdtugby.html

TS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtadruxnzk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gttpylkunw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.9152youxi.cn/Article/details/gtjjwlktdr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.9152youxi.cn/Article/details/gtksdqanhc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.bjfxy.top/Article/details/gtzwtrdaqs.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtvpqtjmgy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cashguo.top/Article/details/gtksibellg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.havefunace.top/Article/details/gtnvvedomn.html

JS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtbzodmtgr.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzyznxxe.html

Java: resp.statusCode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwamfjljg.html

Go:   resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gtwsbhhvfe.html

Ruby: resp.code.to_i
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfygkrcv.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtehpngvpv.html

[L08] 并发请求多个地址
来源：http://dali.haohaochexian.top/Article/details/gtxtrprxeg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hongshengwenyu.top/Article/details/gtzrpkijoq.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhiwuduotai.top/Article/details/gtwwjtlpca.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gtpdznnyyq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhwddqqk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuxming.cn/Article/details/gtantxhkqz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gtpdoqsrrk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xziqi.cn/Article/details/gtzspbgyet.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.meibo888.top/Article/details/gtktmszxqv.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtekxkktby.html

M. 命令行 / 进程 / 环境
来源：http://dali.bjfxy.top/Article/details/gtsgzdufaf.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtigwvmdoe.html

[M01] 读取命令行参数
来源：http://dali.andypj.xyz/Article/details/gtggzkjwls.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgkyahol.html

PHP:  $argv;  $argc;
来源：http://dali.sufxvd.cn/Article/details/gtemymyefo.html

JS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gtizmvgtdx.html

TS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtrcwxpesz.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258.top/Article/details/gtrjkvfmey.html

Go:   os.Args[1:]
来源：http://dali.0kj1m.cn/Article/details/gtncwojiay.html

Ruby: ARGV
来源：http://dali.svipenyu.cn/Article/details/gtkmgvwopg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtqaehvdkx.html

[M02] 读取环境变量
来源：http://dali.yuanzhike.top/Article/details/gtxxeazope.html

Py:   os.environ.get("HOME")
来源：http://dali.xuanzx.com/Article/details/gthxuhnjlp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtnqaxaaac.html

JS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gtqggcezqn.html

TS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtmmxryhhh.html

Java: System.getenv("HOME")
来源：http://dali.yonumen.top/Article/details/gtlfmwkgkr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.c1oappe.top/Article/details/gttjhbocgm.html

Ruby: ENV["HOME"]
来源：http://dali.yueranfly.top/Article/details/gtplxqxyqy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangdashe.top/Article/details/gtoinovqun.html

[M03] 执行外部命令
来源：http://dali.jyoumei.cn/Article/details/gtdcboguwy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.havefunace.top/Article/details/gtzpdsblwk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cheryme.top/Article/details/gtkzqyxsaj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gthtpuyrev.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtsosibgio.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daria6918.cn/Article/details/gtdioarxap.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gtymnoykcg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.quarkkingdee.top/Article/details/gtgkjhmqsv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.andypj.xyz/Article/details/gthyxmvutv.html

[M04] 获取当前工作目录
来源：http://dali.yuxming.cn/Article/details/gtaymghdzm.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gtvkearhmm.html

PHP:  getcwd();
来源：http://dali.sufxvd.cn/Article/details/gtukufjzdg.html

JS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gturjskgad.html

TS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtxkmutmxw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gtnymcnsml.html

Go:   os.Getwd()
来源：http://dali.nwbrower.top/Article/details/gtbwcjcwoo.html

Ruby: Dir.pwd
来源：http://dali.pengpengdd.cyou/Article/details/gtjpaskwwf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fengsongda.top/Article/details/gtoedjlniz.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gtydhgzzre.html

Py:   sys.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtusodpiuf.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gtqstcmwvf.html

JS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtslxcabkf.html

TS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtnpsbgqsd.html

Java: System.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtrqbpdqws.html

Go:   os.Exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatnsmqxn.html

Ruby: exit 1
来源：http://dali.hongshengwenyu.top/Article/details/gtokekrkbs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.redwolf501.top/Article/details/gtyzffwylh.html

[M06] 向标准错误输出
来源：http://dali.fengsongda.top/Article/details/gtiagduzwf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtnuemuiex.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxncbgtq.html

JS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtvyjuheua.html

TS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtmyvihlsh.html

Java: System.err.println("err")
来源：http://dali.wangdashe.top/Article/details/gtzjqtrprk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fengsongda.top/Article/details/gtmitopato.html

Ruby: warn "err"
来源：http://dali.jqgufenzy.top/Article/details/gtamtrxjih.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxinkj.top/Article/details/gtllqbqgki.html

[M07] 判断是否为主入口
来源：http://dali.yvedp.cn/Article/details/gtreqyuoyd.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gtxybuxmqo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gtzoarvyyo.html

JS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtlmvxnddh.html

TS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gtjlrbehnb.html

Java: public static void main(String[] args)
来源：http://dali.jqgufenzy.top/Article/details/gtqwxealaf.html

Go:   func main()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvlfyodo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gtofhkfzgw.html

C#:   static void Main(string[] args)
来源：http://dali.iojbl.cn/Article/details/gtaddztose.html

[M08] 获取系统与运行时信息
来源：http://dali.jlsjyb.cn/Article/details/gtjfvesvue.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guannengcc.top/Article/details/gtwumkvhbl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.redwolf501.top/Article/details/gtmevypeep.html

JS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtfiyyhqps.html

TS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfofahfz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xinyue.icu/Article/details/gtykuqcnpr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daria6918.cn/Article/details/gtrpxzlfoz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.birdmap.top/Article/details/gttripdygj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yvedp.cn/Article/details/gtvdccecif.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqgoctxq.html

N. 数据结构与算法
来源：http://dali.zhixingplan.top/Article/details/gtavzjkpko.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtukzhhzhl.html

[N01] 二分查找（有序数组）
来源：http://dali.chenzaomai.com/Article/details/gtpblphpfc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtohhinajv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtwdlbrzpk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gtqylgvtpo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtwnqxutey.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtxxizhfci.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.havefunace.top/Article/details/gtcamusnpu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gttfknjmru.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtblirlzpc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gtbphpzmmu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gttsgklxkd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xinyue.icu/Article/details/gtcvwclqfm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqzilvfu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtbtguzgrf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ydzc1.top/Article/details/gtnhlhwfnj.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtkbxhfjep.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtstxqrzae.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxuanxn.top/Article/details/gtsjuasmlg.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqieacqu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.andypj.xyz/Article/details/gtfmahrizd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jiagoushi.top/Article/details/gtzvwuufwg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gtptqbjqih.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gttxghkmlt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtmcfbfnol.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jiagoushi.top/Article/details/gtzjfwlmeh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hnxiangtu.top/Article/details/gtktowlrca.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.vqdsnc.cn/Article/details/gtcgpdgnvp.html

[N04] 斐波那契数列
来源：http://dali.ppjwa.cn/Article/details/gtpivpzjmk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gtnddunaiq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gtgbjmjtdv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gthyqmrhex.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtygggcwhk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtjfftcihj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ybcxt.top/Article/details/gtpscxzmnr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtwelkybbf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtlaynsnqw.html

[N05] 最大公约数
来源：http://dali.c1oappe.top/Article/details/gtstgtizhp.html

Py:   math.gcd(a, b)
来源：http://dali.daria6918.cn/Article/details/gtyjdstlvb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ydzc1.top/Article/details/gtzkfcwbrd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gtwjpujxax.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gotoacloud.top/Article/details/gtvifqsunr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gtzzdjbxqp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuanzhike.top/Article/details/gtbwlyyvoq.html

Ruby: a.gcd(b)
来源：http://dali.dianchejie.cn/Article/details/gtztalivhd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.quarkkingdee.top/Article/details/gtdaokquar.html

[N06] 判断回文字符串
来源：http://dali.iojbl.cn/Article/details/gtuuapcjfg.html

Py:   s == s[::-1]
来源：http://dali.ivvv.top/Article/details/gtuiptzcdw.html

PHP:  $s === strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtymqbflqk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtkygivyjn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtcmvcmzzx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guannengcc.top/Article/details/gtjmqncnmv.html

Go:   // 双指针从两端比较
来源：http://dali.tanke756.top/Article/details/gtqvqlgdny.html

Ruby: s == s.reverse
来源：http://dali.hammf.cn/Article/details/gtwrztlnsc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtgekpnyif.html

[N07] 两数之和（返回下标）
来源：http://dali.yangfankeji.com/Article/details/gtnbcprgws.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daria6918.cn/Article/details/gtzjkvdjmq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xinyue.icu/Article/details/gtzeauytjs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmfdjxqe.html

TS:   // 手写 Map<string, number>
来源：http://dali.daria6918.cn/Article/details/gtvinpakqa.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gttmjwszwg.html

Go:   // 手写 map[int]int
来源：http://dali.vqdsnc.cn/Article/details/gtoowzwogz.html

Ruby: // 手写 Hash
来源：http://dali.birdmap.top/Article/details/gtpmnviaix.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.redwolf501.top/Article/details/gtwuuwtxtw.html

[N08] 生成全排列
来源：http://dali.xinyue.icu/Article/details/gtrdfxjjrx.html

Py:   itertools.permutations(arr)
来源：http://dali.cdnleiting.top/Article/details/gtaxnqievu.html

PHP:  // 手写递归交换
来源：http://dali.wangshuangyany.cn/Article/details/gtkukkpmbv.html

JS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtubwetdvy.html

TS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtvczswhbp.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtkjdugkbd.html

Go:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugyqmljn.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxinkj.top/Article/details/gtuyposxbt.html

C#:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtfghetirm.html

[N09] 栈与队列
来源：http://dali.sufxvd.cn/Article/details/gtaesrcscm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jyoumei.cn/Article/details/gtvijboutt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtpqrpuxhd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtdlafjztn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgufenzy.top/Article/details/gtrckyrzie.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gtakckljfe.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sxryk.cn/Article/details/gtlhpbptfr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gtfkzwcpse.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmoyzhedt.html

[N10] 链表节点定义
来源：http://dali.zhiwuduotai.top/Article/details/gtuuyqvtes.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nwbrower.top/Article/details/gtzzcoxlyr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gtbqzoxktw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gotoacloud.top/Article/details/gtadymxzxr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangdashe.top/Article/details/gtaflhhmlz.html

Java: class Node { int v; Node next; }
来源：http://dali.sysykeji.top/Article/details/gtikcojqnh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthooogdzi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fzhhl.top/Article/details/gtmclrjgtp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gtfymxbteb.html

[N11] 二叉树中序遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtmgfqemqm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hfpthk.cn/Article/details/gtqhdpjbee.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gtnglwwixd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gtybpfinwt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gtfvkzlazf.html

Java: // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gtvyvarpca.html

Go:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtvdfdtdrf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.bjfxy.top/Article/details/gtlllxjofz.html

C#:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtxworyile.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pycfn.com/Article/details/gthvzrdaei.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhongyouzk.top/Article/details/gtkolntezp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnxiangtu.top/Article/details/gtwjallonx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gteuxhsfvy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gtsbtlrqum.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtunrgcodk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yangfankeji.com/Article/details/gtuefgpwvi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xylfe.cn/Article/details/gtakyqzvoq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnqzz.top/Article/details/gtzosulrcg.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtlqgzyngw.html

O. 并发与异步
来源：http://dali.quarkkingdee.top/Article/details/gtowobyeyl.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtrbljqpra.html

[O01] 启动一个线程
来源：http://dali.mhx1999.top/Article/details/gtsfdsmrvf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jyoumei.cn/Article/details/gtkmzvjlcc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.havefunace.top/Article/details/gtxcbgyhdj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hammf.cn/Article/details/gtiyoeqwrj.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhukxqrf.html

Java: new Thread(() -> f()).start()
来源：http://dali.shangyingyoupin.top/Article/details/gtgsxueapd.html

Go:   go f()
来源：http://dali.yueranfly.top/Article/details/gtxvipxbjg.html

Ruby: Thread.new { f }
来源：http://dali.ivvv.top/Article/details/gtupgwszgz.html

C#:   Task.Run(() => F());
来源：http://dali.zycfv.cn/Article/details/gtfpqyedqd.html

[O02] 使用线程池
来源：http://dali.cashguo.top/Article/details/gtreouffpr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.havefunace.top/Article/details/gtivjxzwul.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dashuyun.cn/Article/details/gtvbhttpwb.html

JS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gtwjweliri.html

TS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcesnlhom.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhongyouzk.top/Article/details/gtvnoecmpy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gtpvquqpfr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hammf.cn/Article/details/gtvexjvrpz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ydzc1.top/Article/details/gtncvsuhsn.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gtsjpxvzwl.html

Py:   with lock: shared += 1
来源：http://dali.aizwys.cn/Article/details/gtvftfepdy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cheryme.top/Article/details/gttrtmuoya.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gtxcqerldp.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gthilqzeip.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gtqaxbicts.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hfpthk.cn/Article/details/gtexecaesd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtoehysazh.html

C#:   lock (gate) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gthtnkilei.html

[O04] 定义异步函数并等待
来源：http://dali.smart0.xyz/Article/details/gtqkuesumz.html

Py:   async def f():⏎    await g()
来源：http://dali.hammf.cn/Article/details/gtpbngtiil.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258888.top/Article/details/gthhwpvxav.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfpoanjv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtrkfidnsz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuksfozp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ydzc1.top/Article/details/gtkvmyuocs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ehwqpu.com/Article/details/gtaeffkhkc.html

C#:   async Task F() { await G(); }
来源：http://dali.svipenyu.cn/Article/details/gtutvzmeoj.html

[O05] 并发执行并等待全部完成
来源：http://dali.kuanghao11.cn/Article/details/gtkalzcuun.html

Py:   asyncio.gather(*tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtmanaduow.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pengpengdd.cyou/Article/details/gtkgbfesyr.html

JS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gtphgypano.html

TS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gtmacgqiux.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gaohongyu789.top/Article/details/gtbnqifgay.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shangyingyoupin.top/Article/details/gtgrjwnstv.html

Ruby: threads.map(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gtuwzatzgy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.kuanghao11.cn/Article/details/gtfcbddikb.html

[O06] 使用进程池
来源：http://dali.jqgufenzy.top/Article/details/gtqhcbjuco.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.aibaodan.cn/Article/details/gtcbqhiwjt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jianghu66.top/Article/details/gtfdgcfoxd.html

JS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gtbcllcohx.html

TS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtkkzpuroi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aizwys.cn/Article/details/gtajbhsasr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pengpengdd.cyou/Article/details/gtnosuwucp.html

Ruby: // fork 块
来源：http://dali.xziqi.cn/Article/details/gthiifhkqt.html

C#:   Parallel.For
来源：http://dali.cheryme.top/Article/details/gtiojwdbwp.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtjkcubfpm.html

P. 常用工具函数
来源：http://dali.daxiang520.top/Article/details/gtydgymekc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtyvtmdjft.html

[P01] 生成 UUID
来源：http://dali.andypj.xyz/Article/details/gtjpzdzwcw.html

Py:   str(uuid.uuid4())
来源：http://dali.cqqwz.cn/Article/details/gtfdwghrnv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmtndtrm.html

JS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtcytnlxcl.html

TS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gtrrbxlmag.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttsolufhp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cqqwz.cn/Article/details/gtrqvlnccr.html

Ruby: SecureRandom.uuid
来源：http://dali.pycfn.com/Article/details/gtwirblrwv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gteuehrcws.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ydzc1.top/Article/details/gtrumciynb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.0kj1m.cn/Article/details/gtwsffjwpo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jlsjyb.cn/Article/details/gtlsaomxvz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.redwolf501.top/Article/details/gtqzcrukhq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shangyingyoupin.top/Article/details/gtfrvyisov.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ydzc1.top/Article/details/gtbhxwlidh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cqqwz.cn/Article/details/gtqzykrdvb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppwcereh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gogol.net.cn/Article/details/gtzhdhklks.html

[P03] 生成短随机字符串
来源：http://dali.zhengqikj.top/Article/details/gtxyjwejua.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhongyouzk.top/Article/details/gtqiwzqooe.html


<!-- 参考信息 -->