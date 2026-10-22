代发 wailian999

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2unazosih.html

PHP:  json_decode($body, true);
来源：http://dali.yongpay.top/Article/details/gt2pqdzwyrc.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gt2ddvltedu.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2kermygzp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daria6918.cn/Article/details/gt2kvlvcvyc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guannengcc.top/Article/details/gt2merujisq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iyatfzwt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgufenzy.top/Article/details/gt2ymvkbhjz.html

[L07] 处理 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gt2judjndlh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.redwolf501.top/Article/details/gt2eztlqwcx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tian-w.cn/Article/details/gt2fkudotkj.html

JS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gt2kodccyud.html

TS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gt2jxedbjmh.html

Java: resp.statusCode()
来源：http://dali.snrcjt.cn/Article/details/gt2utituwax.html

Go:   resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gt2spxgvwkl.html

Ruby: resp.code.to_i
来源：http://dali.hywenlv.cn/Article/details/gt2cyycevmk.html

C#:   (int)resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gt2ohhamzom.html

[L08] 并发请求多个地址
来源：http://dali.havefunace.top/Article/details/gt2ijesoztu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gt2bmidgggl.html

PHP:  curl_multi_init() 系列
来源：http://dali.meibo888.top/Article/details/gt2zgtfcvop.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjrywzpf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gt2gmuzcdzt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgfzy.top/Article/details/gt2pgbbolpc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jyoumei.cn/Article/details/gt2nxednmcw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.snrcjt.cn/Article/details/gt2ticyfbeu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gt2dzdpfogh.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2fuiafvfo.html

M. 命令行 / 进程 / 环境
来源：http://dali.gaohongyu789.top/Article/details/gt2cplrecct.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2gktxistl.html

[M01] 读取命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gt2xttexoen.html

Py:   sys.argv[1:]
来源：http://dali.zdqjudy.top/Article/details/gt2rxzeazit.html

PHP:  $argv;  $argc;
来源：http://dali.andypj.xyz/Article/details/gt2xgaifuhz.html

JS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gt2axofzowf.html

TS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gt2boslexdv.html

Java: args 数组（main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gt2lkkplzrq.html

Go:   os.Args[1:]
来源：http://dali.yuxming.cn/Article/details/gt2szbjoqpl.html

Ruby: ARGV
来源：http://dali.jlsjyb.cn/Article/details/gt2jdzttiaa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gt2dvsbirpj.html

[M02] 读取环境变量
来源：http://dali.aizwys.cn/Article/details/gt2kxbyhkmf.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2zflbmhym.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gt2kxztfnto.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gt2phfstaiw.html

TS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gt2chfalzuk.html

Java: System.getenv("HOME")
来源：http://dali.smart0.xyz/Article/details/gt2jugqbndt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vabzhqvz.html

Ruby: ENV["HOME"]
来源：http://dali.xuetiantiany.cn/Article/details/gt2bxxvlqwh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jsjxgptw.html

[M03] 执行外部命令
来源：http://dali.cqqwz.cn/Article/details/gt2jcxkzweb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yanxiufei.cn/Article/details/gt2vxkehtiz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guannengcc.top/Article/details/gt2rtyoguzz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gt2hehissjo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gt2trtbyrwb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.bjfxy.top/Article/details/gt2ohkfpvli.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gaohongyu789.top/Article/details/gt2drqrlwki.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.kuanghao11.cn/Article/details/gt2mqgbueel.html

C#:   Process.Start("ls", "-l");
来源：http://dali.birdmap.top/Article/details/gt2xxlgpmuo.html

[M04] 获取当前工作目录
来源：http://dali.chenzaomai.com/Article/details/gt2azoueqmq.html

Py:   os.getcwd()
来源：http://dali.hnqzz.top/Article/details/gt2mlbtomny.html

PHP:  getcwd();
来源：http://dali.cdnleiting.top/Article/details/gt2nmximicr.html

JS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gt2dqackirl.html

TS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gt2aqndgopu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbuhiium.html

Go:   os.Getwd()
来源：http://dali.nanxinkj.top/Article/details/gt2ffusicop.html

Ruby: Dir.pwd
来源：http://dali.tianlin.xyz/Article/details/gt2afbrphjw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.meibo888.top/Article/details/gt2ntxsxugs.html

[M05] 设置退出码
来源：http://dali.tianlin.xyz/Article/details/gt2zvuggxnm.html

Py:   sys.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2yveupsxn.html

PHP:  exit(1);
来源：http://dali.hysaishi.cn/Article/details/gt2hebvnrya.html

JS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2edomcejm.html

TS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2kmaebrze.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2dxchdiyt.html

Go:   os.Exit(1)
来源：http://dali.cashguo.top/Article/details/gt2zlldnogf.html

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gt2dthwdomt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jiagoushi.top/Article/details/gt2npglcwwl.html

[M06] 向标准错误输出
来源：http://dali.pycfn.com/Article/details/gt2kxmwknbs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gt2rknrqyqf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuanzhike.top/Article/details/gt2ardegwvd.html

JS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rzfrzokh.html

TS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gt2etitonfb.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gt2erqhiwin.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guowangkeji.top/Article/details/gt2jzmkkcix.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gt2snfmjyel.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gt2fdqzevkw.html

[M07] 判断是否为主入口
来源：http://dali.pycfn.com/Article/details/gt2rwewdfse.html

Py:   if __name__ == "__main__":
来源：http://dali.vqdsnc.cn/Article/details/gt2oyiqompt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.andypj.xyz/Article/details/gt2yqxrlysq.html

JS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gt2eckpsufq.html

TS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gt2bxlsszhe.html

Java: public static void main(String[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yvtkutxb.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gt2agybukgh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tian-w.cn/Article/details/gt2dktpympp.html

C#:   static void Main(string[] args)
来源：http://dali.jqgfzy.top/Article/details/gt2yvggftot.html

[M08] 获取系统与运行时信息
来源：http://dali.ydzc1.top/Article/details/gt2cuynwlnj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cqqwz.cn/Article/details/gt2oexwuhdv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yangfankeji.com/Article/details/gt2satxlhzv.html

JS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gt2ehtxsylr.html

TS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gt2uhreyult.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gt2ykuogvzk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bauzevjk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jlsjyb.cn/Article/details/gt2lraxvqxl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xziqi.cn/Article/details/gt2xoztquhx.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2qsttitst.html

N. 数据结构与算法
来源：http://dali.zdqjudy.top/Article/details/gt2koyhnulh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2kjawcdvg.html

[N01] 二分查找（有序数组）
来源：http://dali.ppjwa.cn/Article/details/gt2expmszdi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2szappjli.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tianlin.xyz/Article/details/gt2gwpkkeam.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gt2etibrrxy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vzgwakcv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqhydzj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2pertqeuy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gt2cdpmhffc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2ugfpyhvp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gt2skzecrhj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gt2hwicmydd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenzaomai.com/Article/details/gt2awlhvekr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gt2pmqwytdr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gt2ydwaxypk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxinkj.top/Article/details/gt2vqnwnasl.html

Go:   slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gt2hzrsrmqs.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gt2irhshemx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.feifeiyinyue.top/Article/details/gt2tenoedrf.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jukyuygq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bwqzhzqq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhoulong.xyz/Article/details/gt2dhjstdrv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gt2nroouaom.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gt2eecvmanq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jiagoushi.top/Article/details/gt2ipwwqhqo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhoulong.xyz/Article/details/gt2myokwsfa.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ehwqpu.com/Article/details/gt2qoyrdwcw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shzxlz.cn/Article/details/gt2bhykrswj.html

[N04] 斐波那契数列
来源：http://dali.cashguo.top/Article/details/gt2ogegmiur.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wurmekuy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gt2cndnketl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gt2chbtgahc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gt2pwfxweln.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gt2assfcial.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.mhx1999.top/Article/details/gt2kzztzepm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gt2arxgrtbv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gt2mzewzpsu.html

[N05] 最大公约数
来源：http://dali.daria6918.cn/Article/details/gt2ssldqcqu.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2twvqrfbt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ybcxt.top/Article/details/gt2ncyxbafm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gt2ukltvvuo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2clfbnnpc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aizwys.cn/Article/details/gt2bpvioviq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.svipenyu.cn/Article/details/gt2oercjdli.html

Ruby: a.gcd(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2azoysfrn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hjjlvynm.html

[N06] 判断回文字符串
来源：http://dali.cdnleiting.top/Article/details/gt2jmtazpip.html

Py:   s == s[::-1]
来源：http://dali.redwolf501.top/Article/details/gt2fhjnixay.html

PHP:  $s === strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gt2zpwhugaq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gt2dunmexst.html

TS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2frbrzpch.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aizwys.cn/Article/details/gt2bucelmqt.html

Go:   // 双指针从两端比较
来源：http://dali.jyoumei.cn/Article/details/gt2ppbbpwvd.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xyndauvc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gt2ayxiorgd.html

[N07] 两数之和（返回下标）
来源：http://dali.hnxiangtu.top/Article/details/gt2usvuaenl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2etcbcsyw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gogol.net.cn/Article/details/gt2xpgopemd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mvxnwolq.html

TS:   // 手写 Map<string, number>
来源：http://dali.kuanghao11.cn/Article/details/gt2irtmbudg.html

Java: // 手写 HashMap
来源：http://dali.jqgfzy.top/Article/details/gt2psmgteau.html

Go:   // 手写 map[int]int
来源：http://dali.jqgufenzy.top/Article/details/gt2ozdcsnfg.html

Ruby: // 手写 Hash
来源：http://dali.cucudq.cn/Article/details/gt2diahzqrb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shangyingyoupin.top/Article/details/gt2czvagwuk.html

[N08] 生成全排列
来源：http://dali.yanxiufei.cn/Article/details/gt2dojysped.html

Py:   itertools.permutations(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smyyzpie.html

PHP:  // 手写递归交换
来源：http://dali.gzhubu.top/Article/details/gt2ghmuxfzx.html

JS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2tdbnddwb.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2hfmiozzh.html

Java: // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gt2prnegmgr.html

Go:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gt2npyarcye.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2srrufoln.html

C#:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2edplqhql.html

[N09] 栈与队列
来源：http://dali.cashguo.top/Article/details/gt2wtzdibkl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hysaishi.cn/Article/details/gt2xkzxdiwm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fzhhl.top/Article/details/gt2uttlxwaa.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqurxvfd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxuanxn.top/Article/details/gt2vrjwvehv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuanzx.com/Article/details/gt2kqcocmio.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shuidangran.top/Article/details/gt2jysfucgl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gt2isaokuwg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ybcxt.top/Article/details/gt2jqclbszn.html

[N10] 链表节点定义
来源：http://dali.sxryk.cn/Article/details/gt2dgtkfhlo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangdashe.top/Article/details/gt2rlarozah.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gt2mcsdjwnx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.9152youxi.cn/Article/details/gt2mjyrvybv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tian-w.cn/Article/details/gt2uqbzhfgw.html

Java: class Node { int v; Node next; }
来源：http://dali.sufxvd.cn/Article/details/gt2ekltlpfz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.c1oappe.top/Article/details/gt2jnwwyfrc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gt2alyzeooi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuxming.cn/Article/details/gt2pygqyqjp.html

[N11] 二叉树中序遍历
来源：http://dali.ydzc1.top/Article/details/gt2vwvbyioo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daxiang520.top/Article/details/gt2mcmfkene.html

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gt2jwnzdtds.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gt2rwbztpjb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gt2mgrltgzr.html

Java: // 手写递归
来源：http://dali.cucudq.cn/Article/details/gt2tlzffnbf.html

Go:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gt2bkjoxdsm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mmjjydwe.html

C#:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2tbbkdyil.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxuanxn.top/Article/details/gt2armcycze.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shangyingyoupin.top/Article/details/gt2inzdyzkr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aizwys.cn/Article/details/gt2vekfrbij.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gt2sijntunk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lauyfwzu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gt2qiuwphwg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pycfn.com/Article/details/gt2sbaunvuk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ebjzacmf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gt2njloerje.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2ckggfdst.html

O. 并发与异步
来源：http://dali.shzxlz.cn/Article/details/gt2emphyntt.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ienezmps.html

[O01] 启动一个线程
来源：http://dali.shzxlz.cn/Article/details/gt2eurwausr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hnqzz.top/Article/details/gt2kyslqguw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.andypj.xyz/Article/details/gt2yzysycea.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dezawacu.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gt2vjjzgpyk.html

Java: new Thread(() -> f()).start()
来源：http://dali.snrcjt.cn/Article/details/gt2ohdgtlkd.html

Go:   go f()
来源：http://dali.xuanzx.com/Article/details/gt2jnsoygag.html

Ruby: Thread.new { f }
来源：http://dali.ehwqpu.com/Article/details/gt2wxizfzpb.html

C#:   Task.Run(() => F());
来源：http://dali.gzhubu.top/Article/details/gt2tyccokns.html

[O02] 使用线程池
来源：http://dali.yanxiufei.cn/Article/details/gt2erxkrvel.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guannengcc.top/Article/details/gt2kpmkgsxf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hysaishi.cn/Article/details/gt2fommskmz.html

JS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yqzptvhb.html

TS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gt2mapcmesk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlkfoddp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuanzhike.top/Article/details/gt2ufnekkyc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.haohaochexian.top/Article/details/gt2brxvojcy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jwwmymfo.html

[O03] 加锁保护共享数据
来源：http://dali.zhongyouzk.top/Article/details/gt2yoisnmzs.html

Py:   with lock: shared += 1
来源：http://dali.9152youxi.cn/Article/details/gt2phcvqduw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pvmwnbkt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ybcxt.top/Article/details/gt2urgwdcal.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gt2vawfairh.html

Java: synchronized (this) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gt2zyuzoske.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iehprxcs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.quarkkingdee.top/Article/details/gt2amuvzgcp.html

C#:   lock (gate) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gt2zrwavuuq.html

[O04] 定义异步函数并等待
来源：http://dali.zdqjudy.top/Article/details/gt2elxvgpdy.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wkzqfrpv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenzaomai.com/Article/details/gt2yyzbpjyu.html

JS:   async function f() { await g(); }
来源：http://dali.hammf.cn/Article/details/gt2fwvjivic.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gt2ekwkuwyq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cdnleiting.top/Article/details/gt2wregnhif.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigfzy.top/Article/details/gt2rvekslvf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.0kj1m.cn/Article/details/gt2uisentbx.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2ufbmqvfo.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigfzy.top/Article/details/gt2jibdkuhd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.svipenyu.cn/Article/details/gt2wvevzydt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.birdmap.top/Article/details/gt2ieqkbpcu.html

JS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gt2nmquteaq.html

TS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gt2tugdelck.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.bjfxy.top/Article/details/gt2tehqxqeb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ehwqpu.com/Article/details/gt2bmyptreq.html

Ruby: threads.map(&:join)
来源：http://dali.fengsongda.top/Article/details/gt2ntdyoqdh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.iojbl.cn/Article/details/gt2qlydbbed.html

[O06] 使用进程池
来源：http://dali.xziqi.cn/Article/details/gt2kqomeaif.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sufxvd.cn/Article/details/gt2dvuzonwa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zycfv.cn/Article/details/gt2chhfjqjg.html

JS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gt2aiqwzisl.html

TS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gt2jsygxlzc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.snrcjt.cn/Article/details/gt2vjrtlumn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.vqdsnc.cn/Article/details/gt2ahvpfejn.html

Ruby: // fork 块
来源：http://dali.cheryme.top/Article/details/gt2tqbchsnr.html

C#:   Parallel.For
来源：http://dali.hfpthk.cn/Article/details/gt2zzicuhtr.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2jxrsnceb.html

P. 常用工具函数
来源：http://dali.chenzaomai.com/Article/details/gt2pvepvmun.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhurtyyy.html

[P01] 生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fdqwxlbc.html

Py:   str(uuid.uuid4())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xcgdpvih.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daria6918.cn/Article/details/gt2dzogktyi.html

JS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gt2twkazqyl.html

TS:   crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gt2eelarpzy.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgufenzy.top/Article/details/gt2yzrhieih.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hammf.cn/Article/details/gt2hixxxunl.html

Ruby: SecureRandom.uuid
来源：http://dali.dashuyun.cn/Article/details/gt2hckbgmtt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhongyouzk.top/Article/details/gt2ndwysgdm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhongyouzk.top/Article/details/gt2wtnntpmu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.c1oappe.top/Article/details/gt2koqbuvnt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zrjcbrsq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.kuanghao11.cn/Article/details/gt2zwbekwog.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hysaishi.cn/Article/details/gt2tfabansp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gogol.net.cn/Article/details/gt2wawycobp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2kjpruemr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.meibo888.top/Article/details/gt2twqlzrlb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dashuyun.cn/Article/details/gt2izznezsy.html

[P03] 生成短随机字符串
来源：http://dali.sweek.top/Article/details/gt2tvjyawyt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nwbrower.top/Article/details/gt2blhqvfkr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hongshengwenyu.top/Article/details/gt2atjltdrq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2evfzboio.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gt2euzhkmgu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gt2pusqvebq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jlsjyb.cn/Article/details/gt2wiitdtsi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhongyouzk.top/Article/details/gt2vnmhpfoe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cqqwz.cn/Article/details/gt2bzpjwqxj.html

[P04] 求长度
来源：http://dali.cucudq.cn/Article/details/gt2glxmfnse.html


<!-- 参考信息 -->