代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gt2bpkyvvqd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hfpthk.cn/Article/details/gt2kdqdfjhm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2ryntdkio.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gt2ryaywxun.html

Py:   resp.json()
来源：http://dali.nwbrower.top/Article/details/gt2ukazlebi.html

PHP:  json_decode($body, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2tcdcvpjb.html

JS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gt2ovmbacno.html

TS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gt2lszvpafn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ivvv.top/Article/details/gt2ztykvvrx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.9152youxi.cn/Article/details/gt2shqfpjwh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.vqdsnc.cn/Article/details/gt2aqhaybwn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ybixnhsc.html

[L07] 处理 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gt2urhkouff.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gxnexryw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fhcsauhr.html

JS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gt2ykrmyijf.html

TS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gt2xjwyzgrb.html

Java: resp.statusCode()
来源：http://dali.iojbl.cn/Article/details/gt2osinzjdq.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gt2ulzvbadw.html

Ruby: resp.code.to_i
来源：http://dali.feifeiyinyue.top/Article/details/gt2jeyrzvgw.html

C#:   (int)resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gt2qhztkllg.html

[L08] 并发请求多个地址
来源：http://dali.xylfe.cn/Article/details/gt2akqhmydl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pycfn.com/Article/details/gt2oacfjbjh.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ptayserr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gt2voqujcnj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2gmfwfiwz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258888.top/Article/details/gt2zebxlijk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yueranfly.top/Article/details/gt2hjrotrgs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jyoumei.cn/Article/details/gt2eugbaybe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aibaodan.cn/Article/details/gt2ixmsatjs.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2ontcwlsc.html

M. 命令行 / 进程 / 环境
来源：http://dali.jiagoushi.top/Article/details/gt2kiaspgnq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2jkajryep.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gt2daordkon.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gt2ywuxxzsv.html

PHP:  $argv;  $argc;
来源：http://dali.xziqi.cn/Article/details/gt2nrbqzljk.html

JS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gt2mowsrfih.html

TS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gt2xsjggisy.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gt2ciolrlig.html

Go:   os.Args[1:]
来源：http://dali.ydzc1.top/Article/details/gt2xedbatde.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gt2anfxlpdq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gt2hvrkyqya.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odspfwov.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2snxfdfgl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gt2dlmwrgby.html

JS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gt2trnawapi.html

TS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gt2uksoablq.html

Java: System.getenv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lcnpcudp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2tdxlxxui.html

Ruby: ENV["HOME"]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxwlbpia.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdkxbtxf.html

[M03] 执行外部命令
来源：http://dali.yonumen.top/Article/details/gt2vawrjkzt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pycfn.com/Article/details/gt2jobuglbd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gt2wsczqrue.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2arpjqxbd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcnjutik.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aizwys.cn/Article/details/gt2ljtihjmz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aggjjfnd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sufxvd.cn/Article/details/gt2acwpztro.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yvedp.cn/Article/details/gt2czanapoq.html

[M04] 获取当前工作目录
来源：http://dali.quarkkingdee.top/Article/details/gt2filelvml.html

Py:   os.getcwd()
来源：http://dali.ehwqpu.com/Article/details/gt2ixinoczn.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gt2ewovzvtv.html

JS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gt2tlgtacmz.html

TS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gt2tqzkmnbb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gt2nrvhcndf.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gt2dxyfarev.html

Ruby: Dir.pwd
来源：http://dali.bjfxy.top/Article/details/gt2nabdmctq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.c1oappe.top/Article/details/gt2cffmpyco.html

[M05] 设置退出码
来源：http://dali.chenjidiqi.icu/Article/details/gt2fxxxqgup.html

Py:   sys.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2ppcozimx.html

PHP:  exit(1);
来源：http://dali.shzxlz.cn/Article/details/gt2lwhienuv.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2lfvedifg.html

TS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2uzhatolq.html

Java: System.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2beicoixz.html

Go:   os.Exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2vbgzcoqu.html

Ruby: exit 1
来源：http://dali.iojbl.cn/Article/details/gt2stbzxttc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgufenzy.top/Article/details/gt2boutyqit.html

[M06] 向标准错误输出
来源：http://dali.jlsjyb.cn/Article/details/gt2gnbwkdbe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gt2mdmhiyta.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xmsbwvai.html

JS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gt2lhtznziv.html

TS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gt2qfzxvwit.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gt2aopfhhqk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ehwqpu.com/Article/details/gt2ovrgzxzf.html

Ruby: warn "err"
来源：http://dali.hammf.cn/Article/details/gt2kmsibpaw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yueranfly.top/Article/details/gt2eqzeenve.html

[M07] 判断是否为主入口
来源：http://dali.meibo888.top/Article/details/gt2lztygnnv.html

Py:   if __name__ == "__main__":
来源：http://dali.jyoumei.cn/Article/details/gt2pgftzgbl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.0kj1m.cn/Article/details/gt2lyojiyiy.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gt2ynryyxnc.html

TS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gt2euoobgzz.html

Java: public static void main(String[] args)
来源：http://dali.c1oappe.top/Article/details/gt2luytquix.html

Go:   func main()
来源：http://dali.dianchejie.cn/Article/details/gt2avxzlpse.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tanke756.top/Article/details/gt2ovxqjjed.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258888.top/Article/details/gt2lobaapbo.html

[M08] 获取系统与运行时信息
来源：http://dali.nwbrower.top/Article/details/gt2yrgtbbqj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yvedp.cn/Article/details/gt2kcfzbvwu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jianghu66.top/Article/details/gt2ohdrkovo.html

JS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gt2njdabllq.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gt2tnlxsfgr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2fseppzzw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gt2qhfmtdjq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gt2bhqpwvit.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gt2gisklubu.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2gqwuswwi.html

N. 数据结构与算法
来源：http://dali.jlsjyb.cn/Article/details/gt2wiuamitb.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2dcswhnnk.html

[N01] 二分查找（有序数组）
来源：http://dali.pycfn.com/Article/details/gt2rhbiijli.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2njkkzrac.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuanzhike.top/Article/details/gt2soqwtqqq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xqvpthec.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gt2ityvovlz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vukzdibr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2bhpnznsz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qgdhezpi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2ksxhkxpq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gt2yuqavhop.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2dzstmnuk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.c1oappe.top/Article/details/gt2rznthrti.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2roxzxkvf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yyvuebde.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gt2agyyutmd.html

Go:   slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gt2myfadskd.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gt2aiokjlhk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.snrcjt.cn/Article/details/gt2pspiuona.html

[N03] 快速排序（分治示例）
来源：http://dali.fzhhl.top/Article/details/gt2khmfdfez.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gt2nnzqnuan.html

PHP:  // 递归实现，或用 usort
来源：http://dali.quarkkingdee.top/Article/details/gt2nmygafzj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gt2anbdiywi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gt2awadmcvx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gt2vkgpwbgf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jianghu66.top/Article/details/gt2xpqpaoad.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hywenlv.cn/Article/details/gt2laejwlnx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cheryme.top/Article/details/gt2kpopolmj.html

[N04] 斐波那契数列
来源：http://dali.havefunace.top/Article/details/gt2klwojuif.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gt2fudaklaf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2begbyoht.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gt2lmwsvgmz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gt2lukpbnbo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tian-w.cn/Article/details/gt2mbkrripb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nmkrhhks.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gt2omawbgzq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gt2iyygjzxt.html

[N05] 最大公约数
来源：http://dali.xuanzx.com/Article/details/gt2fqollrnc.html

Py:   math.gcd(a, b)
来源：http://dali.tian-w.cn/Article/details/gt2rlnfzypd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nwbrower.top/Article/details/gt2gviqxlyt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gt2rvgkyxxx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gt2ngjcnxqf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258.top/Article/details/gt2glwkpogf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shuidangran.top/Article/details/gt2ffziyvjt.html

Ruby: a.gcd(b)
来源：http://dali.sysykeji.top/Article/details/gt2qnurnhrz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dznvcraq.html

[N06] 判断回文字符串
来源：http://dali.jianghu66.top/Article/details/gt2rtbwsizm.html

Py:   s == s[::-1]
来源：http://dali.ivvv.top/Article/details/gt2nzqemkti.html

PHP:  $s === strrev($s);
来源：http://dali.guannengcc.top/Article/details/gt2ipctundy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2hbuixvvk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2zlnmcyjv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.316326.xyz/Article/details/gt2pbmgjmpj.html

Go:   // 双指针从两端比较
来源：http://dali.yonumen.top/Article/details/gt2vqkhhiuh.html

Ruby: s == s.reverse
来源：http://dali.zhengqikj.top/Article/details/gt2zcldcutd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gt2vlsabuhr.html

[N07] 两数之和（返回下标）
来源：http://dali.yuxming.cn/Article/details/gt2ryqudmqb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ppjwa.cn/Article/details/gt2lpppxesy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sweek.top/Article/details/gt2yijkwjpq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhongyouzk.top/Article/details/gt2xrvacybf.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangdashe.top/Article/details/gt2mwvslehq.html

Java: // 手写 HashMap
来源：http://dali.yvedp.cn/Article/details/gt2pxlipvaj.html

Go:   // 手写 map[int]int
来源：http://dali.daxiang520.top/Article/details/gt2srmohhsl.html

Ruby: // 手写 Hash
来源：http://dali.yuxming.cn/Article/details/gt2otradplg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xinyue.icu/Article/details/gt2nkpdhimf.html

[N08] 生成全排列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rlmbszws.html

Py:   itertools.permutations(arr)
来源：http://dali.andypj.xyz/Article/details/gt2lodxhmsn.html

PHP:  // 手写递归交换
来源：http://dali.jianghu66.top/Article/details/gt2urenrhcr.html

JS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2eayrbrbj.html

TS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gt2xpubrixv.html

Java: // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2yvjzqyxt.html

Go:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2dqchmlrw.html

Ruby: arr.permutation.to_a
来源：http://dali.pycfn.com/Article/details/gt2tljimeud.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2lupaxheu.html

[N09] 栈与队列
来源：http://dali.wangdashe.top/Article/details/gt2pztprcne.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2gyurfrrh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2kokwzllg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gt2xlylskyl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenjidiqi.icu/Article/details/gt2uqbgpnji.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jyoumei.cn/Article/details/gt2bryzorvh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shuidangran.top/Article/details/gt2aeuhtwih.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2ciczcrnz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.mhx1999.top/Article/details/gt2rsotzkbp.html

[N10] 链表节点定义
来源：http://dali.ivvv.top/Article/details/gt2sulsrkbl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jlsjyb.cn/Article/details/gt2fzbxvjwe.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aibaodan.cn/Article/details/gt2zwhifloc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jiagoushi.top/Article/details/gt2rxmbrnlw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mkldtvrn.html

Java: class Node { int v; Node next; }
来源：http://dali.guowangkeji.top/Article/details/gt2dxzrjyrg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgufenzy.top/Article/details/gt2podmesyz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhoulong.xyz/Article/details/gt2lvivkari.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbyswerk.html

[N11] 二叉树中序遍历
来源：http://dali.zycfv.cn/Article/details/gt2tmpgqadv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aizwys.cn/Article/details/gt2immuxqhc.html

PHP:  // 手写递归函数
来源：http://dali.zhixingplan.top/Article/details/gt2imaxxjsq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gt2tnzlnxmc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gt2oldhmasj.html

Java: // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gt2czvhluun.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gt2rwojpwjb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yonumen.top/Article/details/gt2nlijogzh.html

C#:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gt2evfuhbtp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cashguo.top/Article/details/gt2ejrvkygj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gaohongyu789.top/Article/details/gt2nqqmtxkj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctcejahi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gt2dcczjfkq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gt2wcmqbmmh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gt2plpyailm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gt2yfrvpypu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuanzx.com/Article/details/gt2xahqnros.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gt2basjpbex.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2yizdyvsc.html

O. 并发与异步
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzcjmllr.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dcsdyzcj.html

[O01] 启动一个线程
来源：http://dali.yangfankeji.com/Article/details/gt2xeuvoulg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dashuyun.cn/Article/details/gt2ricipcri.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2distwxcx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tanke756.top/Article/details/gt2pwofpuqp.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gt2bsqhamjo.html

Java: new Thread(() -> f()).start()
来源：http://dali.jianghu66.top/Article/details/gt2rbrqnlse.html

Go:   go f()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lnmaersh.html

Ruby: Thread.new { f }
来源：http://dali.jianghu66.top/Article/details/gt2ocicnxdl.html

C#:   Task.Run(() => F());
来源：http://dali.quarkkingdee.top/Article/details/gt2lulgoloo.html

[O02] 使用线程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybtnkfjb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xylfe.cn/Article/details/gt2osgoohis.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daxiang520.top/Article/details/gt2dtgxzill.html

JS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gt2wxpiunlf.html

TS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2arrqcqtl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yvedp.cn/Article/details/gt2azppqrgz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nwbrower.top/Article/details/gt2plllmhpj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwzgzbrd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jyoumei.cn/Article/details/gt2wwzfxciz.html

[O03] 加锁保护共享数据
来源：http://dali.aizwys.cn/Article/details/gt2nrejtqjo.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gt2xxdouipp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj202588.top/Article/details/gt2vefcsdmp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxuanxn.top/Article/details/gt2vshczeds.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ueffbwxj.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ncykmtbk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xhrvoijy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yanxiufei.cn/Article/details/gt2fureytpq.html

C#:   lock (gate) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gt2pdvzpcxr.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nrumkabu.html

Py:   async def f():⏎    await g()
来源：http://dali.yonumen.top/Article/details/gt2qywsxvry.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yongpay.top/Article/details/gt2uuhpgspb.html

JS:   async function f() { await g(); }
来源：http://dali.mhx1999.top/Article/details/gt2lmsrobpd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ehwqpu.com/Article/details/gt2kdqvvjls.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258.top/Article/details/gt2nphywjej.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yongpay.top/Article/details/gt2sowyhswf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fengsongda.top/Article/details/gt2jpyelwyu.html

C#:   async Task F() { await G(); }
来源：http://dali.yongpay.top/Article/details/gt2nmeyjlgu.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqiyrnqz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ehwqpu.com/Article/details/gt2pufbuthh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhengqikj.top/Article/details/gt2mmysknzf.html

JS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gt2eeuqnrwd.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gt2cgsedazc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.smart0.xyz/Article/details/gt2menufyes.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nwbrower.top/Article/details/gt2ixfzjfhg.html

Ruby: threads.map(&:join)
来源：http://dali.dashuyun.cn/Article/details/gt2biffsfkh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhongyouzk.top/Article/details/gt2mlkxvqhs.html

[O06] 使用进程池
来源：http://dali.zdqjudy.top/Article/details/gt2vjgmquyd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sweek.top/Article/details/gt2dkkzxymx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cdnleiting.top/Article/details/gt2fzbguxok.html

JS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gt2lsbzmbmm.html

TS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gt2wagylesf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dianchejie.cn/Article/details/gt2hjjbegty.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zdqjudy.top/Article/details/gt2jhbbmbuk.html

Ruby: // fork 块
来源：http://dali.feifeiyinyue.top/Article/details/gt2rbpqghat.html

C#:   Parallel.For
来源：http://dali.ehwqpu.com/Article/details/gt2jnkrmhzi.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2uuokznev.html

P. 常用工具函数
来源：http://dali.dashuyun.cn/Article/details/gt2zpqjkgaj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2icauclbg.html

[P01] 生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gt2frxowcfg.html

Py:   str(uuid.uuid4())
来源：http://dali.jlsjyb.cn/Article/details/gt2xhqjvzyl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jyoumei.cn/Article/details/gt2jtyktmsq.html

JS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gt2nqrbmstq.html

TS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gt2yfmohgzv.html

Java: UUID.randomUUID().toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2cziqfdpl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.redwolf501.top/Article/details/gt2bnysdsdp.html

Ruby: SecureRandom.uuid
来源：http://dali.hysaishi.cn/Article/details/gt2hxccackz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hywenlv.cn/Article/details/gt2zblzkblx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jianghu66.top/Article/details/gt2cfzgczae.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258.top/Article/details/gt2lozpsgyh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zjewqxix.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dianchejie.cn/Article/details/gt2hclmllyt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dianchejie.cn/Article/details/gt2waxehvzh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cheryme.top/Article/details/gt2sysgebuo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2vqwkewbn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guannengcc.top/Article/details/gt2htfqsypr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gzhubu.top/Article/details/gt2bgppfrjm.html

[P03] 生成短随机字符串
来源：http://dali.ppjwa.cn/Article/details/gt2qvafvvlh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuxming.cn/Article/details/gt2dtwmdzjh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cgdsrvkb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2cjpkhsio.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gt2cfafcils.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daria6918.cn/Article/details/gt2wzzxddsp.html


<!-- 参考信息 -->