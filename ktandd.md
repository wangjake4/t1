代发 wailian999

Py:   resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gt2kwmxenso.html

PHP:  json_decode($body, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2lqprqzuk.html

JS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cjwkgwlb.html

TS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2jahmebbi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuanzx.com/Article/details/gt2kxdxtibm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ehwqpu.com/Article/details/gt2yminkvdz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbjwhspe.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gt2jdlwwmaf.html

[L07] 处理 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gt2onxzgexf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yanxiufei.cn/Article/details/gt2hlficocx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258.top/Article/details/gt2dftxpoxs.html

JS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gt2pvbouvuk.html

TS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gt2jpirjmse.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gt2hyplxxuw.html

Go:   resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gt2djdtvhrg.html

Ruby: resp.code.to_i
来源：http://dali.gzhubu.top/Article/details/gt2zoblhayt.html

C#:   (int)resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gt2xvdscljc.html

[L08] 并发请求多个地址
来源：http://dali.cheryme.top/Article/details/gt2xreozwgq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aibaodan.cn/Article/details/gt2blyepney.html

PHP:  curl_multi_init() 系列
来源：http://dali.9152youxi.cn/Article/details/gt2npzvsvfh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gt2kevssqeo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2pbbmcozp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jlsjyb.cn/Article/details/gt2ywgeuuvj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhongyouzk.top/Article/details/gt2zzereeme.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daria6918.cn/Article/details/gt2iifrsaax.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2umqnbfaz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2rmdmwfei.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangdashe.top/Article/details/gt2dtriifky.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ndxneeem.html

[M01] 读取命令行参数
来源：http://dali.cashguo.top/Article/details/gt2ghltdrrg.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gt2ujbopihc.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gt2gueydejx.html

JS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gt2hndmlqfo.html

TS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gt2yokbcptw.html

Java: args 数组（main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gt2tsaukupf.html

Go:   os.Args[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mklyfyiy.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gt2ytgersio.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gt2htqndxac.html

[M02] 读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gt2hdbuznug.html

Py:   os.environ.get("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2qdebfsdw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gt2cekksquq.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gt2hsmxssha.html

TS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gt2htrjdpau.html

Java: System.getenv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2tzzyhztg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2qsvlmbaz.html

Ruby: ENV["HOME"]
来源：http://dali.jqgufenzy.top/Article/details/gt2hnueamdl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2vfzulvam.html

[M03] 执行外部命令
来源：http://dali.jyoumei.cn/Article/details/gt2vbjglteg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cdnleiting.top/Article/details/gt2nkxyqyit.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zdqjudy.top/Article/details/gt2jthuuarn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gt2hoxmbqyy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2mziovazy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yangfankeji.com/Article/details/gt2nqumfeuf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.0kj1m.cn/Article/details/gt2ojevakit.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guowangkeji.top/Article/details/gt2gqzwigjc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gt2tcrcbjuf.html

[M04] 获取当前工作目录
来源：http://dali.xuanzx.com/Article/details/gt2enqnrwcp.html

Py:   os.getcwd()
来源：http://dali.0kj1m.cn/Article/details/gt2aqwnnbkn.html

PHP:  getcwd();
来源：http://dali.dianchejie.cn/Article/details/gt2yvkuxebb.html

JS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2isxzrgiy.html

TS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gt2iqrayias.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kkiuohou.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ukprpcfk.html

Ruby: Dir.pwd
来源：http://dali.snrcjt.cn/Article/details/gt2jlpgxkmp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ehwqpu.com/Article/details/gt2wttsjbmh.html

[M05] 设置退出码
来源：http://dali.cucudq.cn/Article/details/gt2ocrxpclg.html

Py:   sys.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2tnvpbhfm.html

PHP:  exit(1);
来源：http://dali.guannengcc.top/Article/details/gt2ohskrwwr.html

JS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2logtdbug.html

TS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gt2oxikvpii.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2vmhsxjzq.html

Go:   os.Exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2yqqnyroh.html

Ruby: exit 1
来源：http://dali.nanxuanxn.top/Article/details/gt2dnqjzhyy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aizwys.cn/Article/details/gt2owzfxzzx.html

[M06] 向标准错误输出
来源：http://dali.0kj1m.cn/Article/details/gt2mhqtwzjh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gt2khqgfcyz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenlongwang.top/Article/details/gt2zbcnphmc.html

JS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gt2emovmtej.html

TS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gt2vulmszkh.html

Java: System.err.println("err")
来源：http://dali.gogol.net.cn/Article/details/gt2hxysuuto.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gt2wpjnjmyp.html

Ruby: warn "err"
来源：http://dali.tianlin.xyz/Article/details/gt2iviqixxq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gt2bfqrfelw.html

[M07] 判断是否为主入口
来源：http://dali.ybcxt.top/Article/details/gt2neegtdaj.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigufen.top/Article/details/gt2ocwyfnlt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qnqjytku.html

JS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gt2jqiwqgda.html

TS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gt2pngppsst.html

Java: public static void main(String[] args)
来源：http://dali.ppjwa.cn/Article/details/gt2erxgyqan.html

Go:   func main()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nfslussd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gt2garhepfb.html

C#:   static void Main(string[] args)
来源：http://dali.sweek.top/Article/details/gt2ynkyfpnx.html

[M08] 获取系统与运行时信息
来源：http://dali.snrcjt.cn/Article/details/gt2qabaxmre.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuetiantiany.cn/Article/details/gt2brgmruqn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hywenlv.cn/Article/details/gt2gtcbhqgr.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gt2ahzyqnnh.html

TS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gt2wrabzoov.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ehwqpu.com/Article/details/gt2eisbngxb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzysijct.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.vqdsnc.cn/Article/details/gt2ohsoxyhf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.svipenyu.cn/Article/details/gt2tnceldrv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2rxybmyfx.html

N. 数据结构与算法
来源：http://dali.nanxinkj.top/Article/details/gt2awsxvmci.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2xkuxhuhx.html

[N01] 二分查找（有序数组）
来源：http://dali.kuanghao11.cn/Article/details/gt2ahqogibx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2snhqbzzp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2atvotmhl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gt2hturbyih.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gt2eaiwaerq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2mxjfcvms.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2nncpwnqj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.haohaochexian.top/Article/details/gt2zzhtjpit.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2zjcozllw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lsqhpqyh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kujflhmk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.kuanghao11.cn/Article/details/gt2tpydblbp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gt2xwggooty.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gt2fobirzqw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gt2spuombhp.html

Go:   slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gt2vckceyhb.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gt2muldactz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ivvv.top/Article/details/gt2apexcnpk.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigfzy.top/Article/details/gt2frwohvbs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenlongwang.top/Article/details/gt2ywtsochf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.meibo888.top/Article/details/gt2tardlgvz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gt2ktdrcrtz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gt2svvtqetw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.316326.xyz/Article/details/gt2gmkgxobu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guowangkeji.top/Article/details/gt2nozpbqxy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gotoacloud.top/Article/details/gt2nmqqxxur.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj202588.top/Article/details/gt2xranqbqg.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gt2zmgwnilg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gt2roggfqda.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xziqi.cn/Article/details/gt2atsifsio.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gt2dltkjzmi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gt2gkxjzqgd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gt2uequrqag.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daxiang520.top/Article/details/gt2kzbjkqyp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gt2yjcstipw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gt2rapslkhn.html

[N05] 最大公约数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xrcoieqe.html

Py:   math.gcd(a, b)
来源：http://dali.316326.xyz/Article/details/gt2qxxlujzl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yueranfly.top/Article/details/gt2jyskkvif.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gt2ljcqjmbi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gt2afknrkwu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gt2ohgvjjhi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnxiangtu.top/Article/details/gt2rduahsuw.html

Ruby: a.gcd(b)
来源：http://dali.jiagoushi.top/Article/details/gt2azuagmbb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vcamumnh.html

[N06] 判断回文字符串
来源：http://dali.tianlin.xyz/Article/details/gt2ojnwaplt.html

Py:   s == s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2tzcyjwtl.html

PHP:  $s === strrev($s);
来源：http://dali.cqqwz.cn/Article/details/gt2unsnczfm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gt2eiqlhbti.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gt2kwyafkgo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cashguo.top/Article/details/gt2liedcrdc.html

Go:   // 双指针从两端比较
来源：http://dali.yangfankeji.com/Article/details/gt2zemqcrro.html

Ruby: s == s.reverse
来源：http://dali.fzhhl.top/Article/details/gt2twqlucat.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gt2ttziutyn.html

[N07] 两数之和（返回下标）
来源：http://dali.gaohongyu789.top/Article/details/gt2otbpjxeo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigfzy.top/Article/details/gt2trrxmxnf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258.top/Article/details/gt2fxsyigkm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ydzc1.top/Article/details/gt2efhrjeci.html

TS:   // 手写 Map<string, number>
来源：http://dali.sweek.top/Article/details/gt2nnmgwkrq.html

Java: // 手写 HashMap
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lemfewnm.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gt2mrzqiczt.html

Ruby: // 手写 Hash
来源：http://dali.sysykeji.top/Article/details/gt2cbqohlah.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jiagoushi.top/Article/details/gt2fkoayana.html

[N08] 生成全排列
来源：http://dali.quarkkingdee.top/Article/details/gt2cqpmemxb.html

Py:   itertools.permutations(arr)
来源：http://dali.yongpay.top/Article/details/gt2miwyxrxe.html

PHP:  // 手写递归交换
来源：http://dali.quarkkingdee.top/Article/details/gt2fpslkvxq.html

JS:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gt2vehpubam.html

TS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2yvhvxszr.html

Java: // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2qswyrhhq.html

Go:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2pazecxir.html

Ruby: arr.permutation.to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gsayvavw.html

C#:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2ghgqvnul.html

[N09] 栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ghaoxynk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guowangkeji.top/Article/details/gt2iffbfgtg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gt2ygjjvvtg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2iuwalhrg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uprqdmrq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ivvv.top/Article/details/gt2gnugivyh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuanzx.com/Article/details/gt2idgmfprj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gt2tlurwtlm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gt2ycgcrial.html

[N10] 链表节点定义
来源：http://dali.sufxvd.cn/Article/details/gt2jqbercfc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nwbrower.top/Article/details/gt2wrbrkccb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ydzc1.top/Article/details/gt2jkmiszmh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yanxiufei.cn/Article/details/gt2kiyzntpb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tanke756.top/Article/details/gt2lierbnrx.html

Java: class Node { int v; Node next; }
来源：http://dali.zhengqikj.top/Article/details/gt2rgzuifrh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2siuzhjwy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigfzy.top/Article/details/gt2rgrdsbme.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.iojbl.cn/Article/details/gt2anxuyehx.html

[N11] 二叉树中序遍历
来源：http://dali.tian-w.cn/Article/details/gt2hmyzaviu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hywenlv.cn/Article/details/gt2gugeixoe.html

PHP:  // 手写递归函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cuscqxlk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gt2shfkmhvc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xuxpamca.html

Java: // 手写递归
来源：http://dali.guannengcc.top/Article/details/gt2tqympsoh.html

Go:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gt2skuayoue.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sweek.top/Article/details/gt2ogaavyzg.html

C#:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gt2yeadsujp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fzhhl.top/Article/details/gt2ywodnubu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhongyouzk.top/Article/details/gt2gaxwznut.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cashguo.top/Article/details/gt2trkfpcmx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gt2euxbhxku.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gt2khdaivyl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gt2wtexfdkd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cucudq.cn/Article/details/gt2tgqqmrjk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2taugtexj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gt2wpoverhb.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2wcdpkkrm.html

O. 并发与异步
来源：http://dali.fengsongda.top/Article/details/gt2xkcrqtrq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2cwzhucjc.html

[O01] 启动一个线程
来源：http://dali.daria6918.cn/Article/details/gt2aadmdptz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ogjprwbb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdwonpac.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shuidangran.top/Article/details/gt2yenynanj.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gt2yftgyovo.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihmyzhot.html

Go:   go f()
来源：http://dali.zhongyouzk.top/Article/details/gt2qalczwlg.html

Ruby: Thread.new { f }
来源：http://dali.xinyue.icu/Article/details/gt2turtpiyw.html

C#:   Task.Run(() => F());
来源：http://dali.tianlin.xyz/Article/details/gt2fqqgoxal.html

[O02] 使用线程池
来源：http://dali.redwolf501.top/Article/details/gt2atsjjfbo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hfpthk.cn/Article/details/gt2lsfnmstz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.havefunace.top/Article/details/gt2jorwvrfj.html

JS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gt2phoceznc.html

TS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gt2zxjtzsjs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yvedp.cn/Article/details/gt2nispzqjd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwkjsztk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pengpengdd.cyou/Article/details/gt2lzqawdir.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhixingplan.top/Article/details/gt2hthwopoz.html

[O03] 加锁保护共享数据
来源：http://dali.hnqzz.top/Article/details/gt2hkzrsesf.html

Py:   with lock: shared += 1
来源：http://dali.ppjwa.cn/Article/details/gt2zddqgbty.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvhcznr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhoulong.xyz/Article/details/gt2xwaoygok.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gt2yxbwpowr.html

Java: synchronized (this) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gt2rxkpykpo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.316326.xyz/Article/details/gt2ckhkzlsu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.0kj1m.cn/Article/details/gt2wrpbuncx.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfluzhzr.html

[O04] 定义异步函数并等待
来源：http://dali.ydzc1.top/Article/details/gt2jserwahi.html

Py:   async def f():⏎    await g()
来源：http://dali.jlsjyb.cn/Article/details/gt2wtopmnmk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenlongwang.top/Article/details/gt2pznpiipv.html

JS:   async function f() { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xzcmrazj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.smart0.xyz/Article/details/gt2jnouxlug.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuanzhike.top/Article/details/gt2okfcfksv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ydzc1.top/Article/details/gt2pteayunb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhbjofvg.html

C#:   async Task F() { await G(); }
来源：http://dali.zhengqikj.top/Article/details/gt2uobzaxms.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenlongwang.top/Article/details/gt2agvyvkrw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ydzc1.top/Article/details/gt2jtrodswc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgufenzy.top/Article/details/gt2kgrktzjy.html

JS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gt2vzqpauez.html

TS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gt2nccaches.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jlsjyb.cn/Article/details/gt2dcitasdp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guowangkeji.top/Article/details/gt2dqjskmop.html

Ruby: threads.map(&:join)
来源：http://dali.0kj1m.cn/Article/details/gt2lgyenywe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ivvv.top/Article/details/gt2zydeengy.html

[O06] 使用进程池
来源：http://dali.jianghu66.top/Article/details/gt2pomuktah.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yueranfly.top/Article/details/gt2khacuhjn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ehwqpu.com/Article/details/gt2qnmwkcsa.html

JS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gt2vcqezfnb.html

TS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gt2bhcmdugb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tianlin.xyz/Article/details/gt2wndapnsx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lngeeygv.html

Ruby: // fork 块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hjzhohgw.html

C#:   Parallel.For
来源：http://dali.haohaochexian.top/Article/details/gt2tqmtgeqw.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ovyfcoxz.html

P. 常用工具函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2haccrpqk.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2scffrxbv.html

[P01] 生成 UUID
来源：http://dali.fzhhl.top/Article/details/gt2hbjlvmpt.html

Py:   str(uuid.uuid4())
来源：http://dali.yongpay.top/Article/details/gt2xthkqvbh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jiagoushi.top/Article/details/gt2jnjrtmjj.html

JS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gt2nomtvdqu.html

TS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gt2ydokumoq.html

Java: UUID.randomUUID().toString()
来源：http://dali.dashuyun.cn/Article/details/gt2zsfojzlj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2emgvpfbr.html

Ruby: SecureRandom.uuid
来源：http://dali.yuxming.cn/Article/details/gt2rdlojhwq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jianghu66.top/Article/details/gt2cezanhrw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgufenzy.top/Article/details/gt2yzzibtpj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.kuanghao11.cn/Article/details/gt2smxjnwpd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbkgnea.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cheryme.top/Article/details/gt2bknozrnw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fengsongda.top/Article/details/gt2javkdsem.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2bhooflpj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tian-w.cn/Article/details/gt2itvabnwj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2awxmsieo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258888.top/Article/details/gt2gfhvussr.html

[P03] 生成短随机字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewxsayub.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tanke756.top/Article/details/gt2mgcvqylp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gt2iuyobenx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2wwypwibb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gt2fjmjdmwc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guannengcc.top/Article/details/gt2nxgyszol.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jianghu66.top/Article/details/gt2ozxtzrnc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.snrcjt.cn/Article/details/gt2gzibvvex.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shuidangran.top/Article/details/gt2dzjmvtox.html

[P04] 求长度
来源：http://dali.vqdsnc.cn/Article/details/gt2xagcrfkc.html


<!-- 参考信息 -->