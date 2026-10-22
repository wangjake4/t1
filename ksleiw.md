代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shuidangran.top/Article/details/gt2tkyfuaoq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxinkj.top/Article/details/gt2pelmjuxz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2jxtyoetm.html

[L06] 解析响应为 JSON
来源：http://dali.cheryme.top/Article/details/gt2safzzdgy.html

Py:   resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gt2pfvgcmnx.html

PHP:  json_decode($body, true);
来源：http://dali.0kj1m.cn/Article/details/gt2opylfdlq.html

JS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gt2cevztmuf.html

TS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gt2frlansja.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gt2hkkuemay.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenlongwang.top/Article/details/gt2sxigxndu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daxiang520.top/Article/details/gt2bswzxuik.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.birdmap.top/Article/details/gt2sjwxxexp.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gt2scylxgwk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gt2nmiljeto.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gzhubu.top/Article/details/gt2vaucblya.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gt2vdmrttix.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gt2yxomtdwm.html

Java: resp.statusCode()
来源：http://dali.jlsjyb.cn/Article/details/gt2lcaehoib.html

Go:   resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gt2lqmabzqa.html

Ruby: resp.code.to_i
来源：http://dali.dashuyun.cn/Article/details/gt2ytucygca.html

C#:   (int)resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gt2uhsnltdp.html

[L08] 并发请求多个地址
来源：http://dali.snrcjt.cn/Article/details/gt2fwuhkagp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tianlin.xyz/Article/details/gt2qbrqompx.html

PHP:  curl_multi_init() 系列
来源：http://dali.pycfn.com/Article/details/gt2rgkkxxoe.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2ppyjeqxd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2kfdjysml.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gogol.net.cn/Article/details/gt2dncpzeol.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aizwys.cn/Article/details/gt2rkfzjnpa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gt2azevmfts.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2scdgrcjn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2wctyslvr.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gt2phkwwotb.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2zjpaqruf.html

[M01] 读取命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gt2rilklgzf.html

Py:   sys.argv[1:]
来源：http://dali.dianchejie.cn/Article/details/gt2lvaxdqxf.html

PHP:  $argv;  $argc;
来源：http://dali.shzxlz.cn/Article/details/gt2hbobzbgi.html

JS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gt2cksxtwwo.html

TS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xarexhrc.html

Java: args 数组（main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gt2yihpvvlg.html

Go:   os.Args[1:]
来源：http://dali.snrcjt.cn/Article/details/gt2ueipesef.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gt2cqczgjsp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gt2oyxultvu.html

[M02] 读取环境变量
来源：http://dali.zycfv.cn/Article/details/gt2ojlotzje.html

Py:   os.environ.get("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2rfknjpie.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gt2gjvrbdjr.html

JS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gt2ihkujdmy.html

TS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gt2sjiwctua.html

Java: System.getenv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2aapgizyg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2orrufnrh.html

Ruby: ENV["HOME"]
来源：http://dali.fengsongda.top/Article/details/gt2guboyhhv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2uzzgnxzz.html

[M03] 执行外部命令
来源：http://dali.kuanghao11.cn/Article/details/gt2bvndtpjx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gt2pymiokxm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aibaodan.cn/Article/details/gt2zkifjbym.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2giknvtbn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gt2rxisirkx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gt2lzrczgwi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxinkj.top/Article/details/gt2ypoceljx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pengpengdd.cyou/Article/details/gt2bvmhyvun.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhongyouzk.top/Article/details/gt2efowvwld.html

[M04] 获取当前工作目录
来源：http://dali.shzxlz.cn/Article/details/gt2crmvmsek.html

Py:   os.getcwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2igitpeop.html

PHP:  getcwd();
来源：http://dali.jiagoushi.top/Article/details/gt2vrtvwpqa.html

JS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gt2daepnvlp.html

TS:   process.cwd()
来源：http://dali.jiagoushi.top/Article/details/gt2rwmxmusa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenlongwang.top/Article/details/gt2xttdnhwh.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gt2zudnolmq.html

Ruby: Dir.pwd
来源：http://dali.tanke756.top/Article/details/gt2jyiceuuy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgfzy.top/Article/details/gt2fupsludr.html

[M05] 设置退出码
来源：http://dali.guannengcc.top/Article/details/gt2novwkdou.html

Py:   sys.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2zwmjvkuy.html

PHP:  exit(1);
来源：http://dali.tanke756.top/Article/details/gt2vuzurtbg.html

JS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2pntnmsgs.html

TS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2ibkyzkmk.html

Java: System.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2rqnfuyfx.html

Go:   os.Exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pzazvkhw.html

Ruby: exit 1
来源：http://dali.hysaishi.cn/Article/details/gt2msrntgvo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.redwolf501.top/Article/details/gt2fejepnwo.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ztoypwjq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gt2pjnqvebs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cqqwz.cn/Article/details/gt2bmjcofno.html

JS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gt2aojevthc.html

TS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gt2tmkytdpi.html

Java: System.err.println("err")
来源：http://dali.nwbrower.top/Article/details/gt2duetynyf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jianghu66.top/Article/details/gt2ubqxydey.html

Ruby: warn "err"
来源：http://dali.0kj1m.cn/Article/details/gt2zbbfxnpd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hywenlv.cn/Article/details/gt2drqdbzye.html

[M07] 判断是否为主入口
来源：http://dali.sysykeji.top/Article/details/gt2spmyghkl.html

Py:   if __name__ == "__main__":
来源：http://dali.zycfv.cn/Article/details/gt2nprbyyqd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.316326.xyz/Article/details/gt2eovtmcsf.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ymenajuc.html

TS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gt2lzaeplsv.html

Java: public static void main(String[] args)
来源：http://dali.daria6918.cn/Article/details/gt2jkfblrcb.html

Go:   func main()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qlrkozxb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.snrcjt.cn/Article/details/gt2lfrantid.html

C#:   static void Main(string[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqgwxfwt.html

[M08] 获取系统与运行时信息
来源：http://dali.ppjwa.cn/Article/details/gt2tyijxtqq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yangfankeji.com/Article/details/gt2ievkbzgg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yueranfly.top/Article/details/gt2wagknhcu.html

JS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gt2lfkabrbx.html

TS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gt2nwrapzho.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daxiang520.top/Article/details/gt2vckkinyk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ukcxwzzx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ybcxt.top/Article/details/gt2xvqhhpdw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tian-w.cn/Article/details/gt2jvztihxj.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2yosjtgsn.html

N. 数据结构与算法
来源：http://dali.chenzaomai.com/Article/details/gt2hdxhbjtp.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ftetgyiz.html

[N01] 二分查找（有序数组）
来源：http://dali.chenlongwang.top/Article/details/gt2ygrhfvgd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2fygwrcmn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gt2zjikuikz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gt2dnobgbdf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xiofcmrc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2fechjqfw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2lmjakxke.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sysykeji.top/Article/details/gt2acpeowlf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2anvyuzmy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gt2yssshljb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gt2varkuoim.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.birdmap.top/Article/details/gt2uqrpdyxo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gt2eyhjzwqu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gt2msyuruqo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hysaishi.cn/Article/details/gt2wvxsrbzk.html

Go:   slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2ijjvojjp.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vjvslbti.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuxming.cn/Article/details/gt2rwngmbol.html

[N03] 快速排序（分治示例）
来源：http://dali.yongpay.top/Article/details/gt2oxlmpnis.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.vqdsnc.cn/Article/details/gt2typfwdhb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.iojbl.cn/Article/details/gt2qhabvpgx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gt2rlpyjdwp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gt2dlliaxcg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxuanxn.top/Article/details/gt2zsyhlsiv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.havefunace.top/Article/details/gt2tbjiwfdl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gt2qnxlyvuz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gt2owecetjn.html

[N04] 斐波那契数列
来源：http://dali.dianchejie.cn/Article/details/gt2rhmretod.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2blobeeqy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gt2xskwltcr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gt2cqegkemx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gt2bxkanlss.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gt2sswxvqmh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xinyue.icu/Article/details/gt2oeefwtrb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nginnkid.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gt2rcwfyvgi.html

[N05] 最大公约数
来源：http://dali.jinqigfzy.top/Article/details/gt2pquqaoyz.html

Py:   math.gcd(a, b)
来源：http://dali.9152youxi.cn/Article/details/gt2cljewjit.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gt2upfskuic.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gt2qffgpthg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gt2wcovpnmb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hefcmfap.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jiagoushi.top/Article/details/gt2hoqutelx.html

Ruby: a.gcd(b)
来源：http://dali.zhoulong.xyz/Article/details/gt2cbqnhheg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuanzx.com/Article/details/gt2fxhidbfk.html

[N06] 判断回文字符串
来源：http://dali.daxiang520.top/Article/details/gt2rlcltqhb.html

Py:   s == s[::-1]
来源：http://dali.fzhhl.top/Article/details/gt2wupnovcf.html

PHP:  $s === strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2prccifgi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gt2wzvetzxa.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gt2rvaqznoh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxuanxn.top/Article/details/gt2cgqmiyyw.html

Go:   // 双指针从两端比较
来源：http://dali.zhixingplan.top/Article/details/gt2adayohnt.html

Ruby: s == s.reverse
来源：http://dali.yongpay.top/Article/details/gt2adjvihsv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gt2phobzjbu.html

[N07] 两数之和（返回下标）
来源：http://dali.jiagoushi.top/Article/details/gt2zbifwqdc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hywenlv.cn/Article/details/gt2mfzkwnbn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guowangkeji.top/Article/details/gt2jouvcbtj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hfpthk.cn/Article/details/gt2hjjysfdf.html

TS:   // 手写 Map<string, number>
来源：http://dali.dianchejie.cn/Article/details/gt2hgptakcf.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhqsctlv.html

Go:   // 手写 map[int]int
来源：http://dali.hnqzz.top/Article/details/gt2raqecsmj.html

Ruby: // 手写 Hash
来源：http://dali.jyoumei.cn/Article/details/gt2qazixwko.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.feifeiyinyue.top/Article/details/gt2hpcfzrnb.html

[N08] 生成全排列
来源：http://dali.cucudq.cn/Article/details/gt2aukdiqox.html

Py:   itertools.permutations(arr)
来源：http://dali.cucudq.cn/Article/details/gt2bmjsrekx.html

PHP:  // 手写递归交换
来源：http://dali.zdqjudy.top/Article/details/gt2vsiuvkbb.html

JS:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2xyyluoqx.html

TS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gt2bkjclvzp.html

Java: // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2chhgqjam.html

Go:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2oorqiqdn.html

Ruby: arr.permutation.to_a
来源：http://dali.c1oappe.top/Article/details/gt2yrklmilf.html

C#:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2andqbamb.html

[N09] 栈与队列
来源：http://dali.daria6918.cn/Article/details/gt2vqwlcehj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gt2tteaacwz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tian-w.cn/Article/details/gt2fxdfrydm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gt2elvvrxec.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nwbrower.top/Article/details/gt2oawppvin.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xylfe.cn/Article/details/gt2wkxoudns.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhengqikj.top/Article/details/gt2jsjfjzmw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gt2oxwuaheu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hammf.cn/Article/details/gt2kwksykay.html

[N10] 链表节点定义
来源：http://dali.wangshuangyany.cn/Article/details/gt2junrjjzw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pengpengdd.cyou/Article/details/gt2anhwlvqj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sysykeji.top/Article/details/gt2fnsgmril.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guowangkeji.top/Article/details/gt2nhyntjkn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.meibo888.top/Article/details/gt2xtecpwqp.html

Java: class Node { int v; Node next; }
来源：http://dali.cqqwz.cn/Article/details/gt2ngesrlwm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.316326.xyz/Article/details/gt2mjiblemo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2kirywxog.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.andypj.xyz/Article/details/gt2ncslqzgv.html

[N11] 二叉树中序遍历
来源：http://dali.sweek.top/Article/details/gt2habdnsbm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mmdhfdco.html

PHP:  // 手写递归函数
来源：http://dali.redwolf501.top/Article/details/gt2jzvflqwo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gt2vilzyhqf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gt2wrsynlkp.html

Java: // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gt2thteoumm.html

Go:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wrtpyzci.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxuanxn.top/Article/details/gt2lxdclenv.html

C#:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gt2brzixcex.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhongyouzk.top/Article/details/gt2qscyqkhb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.bjfxy.top/Article/details/gt2bnxhklvg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gt2qyomrhbb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gt2ipkwrdmr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gt2kmikqfqr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gt2yskrxpjf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258888.top/Article/details/gt2zofvahbf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dashuyun.cn/Article/details/gt2uosrrgyy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gt2hbpcelal.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2yfohdhfk.html

O. 并发与异步
来源：http://dali.guowangkeji.top/Article/details/gt2jbttbmdw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2rdhbkhnw.html

[O01] 启动一个线程
来源：http://dali.sxryk.cn/Article/details/gt2akpkztuv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxinkj.top/Article/details/gt2yphrfbxc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.9152youxi.cn/Article/details/gt2ruyigknb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hammf.cn/Article/details/gt2bfwadmqf.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gt2ksvquwig.html

Java: new Thread(() -> f()).start()
来源：http://dali.quarkkingdee.top/Article/details/gt2okkdhdys.html

Go:   go f()
来源：http://dali.jqgufenzy.top/Article/details/gt2nijsrioj.html

Ruby: Thread.new { f }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2imgurnjb.html

C#:   Task.Run(() => F());
来源：http://dali.ivvv.top/Article/details/gt2zufwqzcy.html

[O02] 使用线程池
来源：http://dali.zhoulong.xyz/Article/details/gt2sqkhmjox.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.316326.xyz/Article/details/gt2vasuitis.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xylfe.cn/Article/details/gt2uheqwbvs.html

JS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2gnpjqmaa.html

TS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gt2jdppbbmy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.redwolf501.top/Article/details/gt2nmskcxfb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxuanxn.top/Article/details/gt2amokwyqu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jlsjyb.cn/Article/details/gt2vrogbpvb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gt2mmsynbph.html

[O03] 加锁保护共享数据
来源：http://dali.hnxiangtu.top/Article/details/gt2imbwipkv.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2onjanhwo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.vqdsnc.cn/Article/details/gt2wkartwgi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cheryme.top/Article/details/gt2jrsnnvnf.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jgecpazp.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gt2sxptdxbr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daria6918.cn/Article/details/gt2yoizusov.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tnhsndum.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258.top/Article/details/gt2ywpclnwy.html

[O04] 定义异步函数并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vkfejfaa.html

Py:   async def f():⏎    await g()
来源：http://dali.havefunace.top/Article/details/gt2jydmbotr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258888.top/Article/details/gt2oeguqkhd.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hedcscza.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2ufbufsup.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shuidangran.top/Article/details/gt2gshufmwl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gt2nvwttkfw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gaohongyu789.top/Article/details/gt2hrcjwesv.html

C#:   async Task F() { await G(); }
来源：http://dali.cdnleiting.top/Article/details/gt2ouffjuux.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenzaomai.com/Article/details/gt2lbwuurbf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hfpthk.cn/Article/details/gt2qlqvjbcf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.0kj1m.cn/Article/details/gt2efrqddzd.html

JS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gt2kquospce.html

TS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gt2lqaaygud.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj202588.top/Article/details/gt2dceobkhd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.vqdsnc.cn/Article/details/gt2oolhrigd.html

Ruby: threads.map(&:join)
来源：http://dali.mhx1999.top/Article/details/gt2bqtmfgpg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258.top/Article/details/gt2ctpgtcms.html

[O06] 使用进程池
来源：http://dali.jiagoushi.top/Article/details/gt2lrvontqm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.andypj.xyz/Article/details/gt2trpobehf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guowangkeji.top/Article/details/gt2gedgobvl.html

JS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ojkifqel.html

TS:   // child_process / cluster 模块
来源：http://dali.tian-w.cn/Article/details/gt2odrzhuka.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhoulong.xyz/Article/details/gt2dlixdyad.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.bjfxy.top/Article/details/gt2auabkqxv.html

Ruby: // fork 块
来源：http://dali.ybcxt.top/Article/details/gt2sgxtxoxy.html

C#:   Parallel.For
来源：http://dali.316326.xyz/Article/details/gt2cbdnpewp.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2znyznlpi.html

P. 常用工具函数
来源：http://dali.cqqwz.cn/Article/details/gt2rskdalvc.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsjvuzpu.html

[P01] 生成 UUID
来源：http://dali.guannengcc.top/Article/details/gt2lutmrtfz.html

Py:   str(uuid.uuid4())
来源：http://dali.yuxming.cn/Article/details/gt2vohiyela.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.0kj1m.cn/Article/details/gt2sawvmhva.html

JS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gbibblea.html

TS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gt2hqzfovmn.html

Java: UUID.randomUUID().toString()
来源：http://dali.iojbl.cn/Article/details/gt2ongchxaa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vchrxebg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhiwuduotai.top/Article/details/gt2jtyjawvx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2cjdiwfmi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xuanzx.com/Article/details/gt2wlbemgkv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxuanxn.top/Article/details/gt2iiszlgvh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxinkj.top/Article/details/gt2krxskkvg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cheryme.top/Article/details/gt2wuftelbx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rgobjhsv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gt2jibnbghj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gt2rgcpcbll.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cqqwz.cn/Article/details/gt2yogagtic.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxinkj.top/Article/details/gt2wxlxqqkj.html

[P03] 生成短随机字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2vtzhpfzo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258.top/Article/details/gt2qrzwqorb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cheryme.top/Article/details/gt2qyjdtoiv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gt2xcjxdbhy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gt2coulicac.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2otbkfyvi.html


<!-- 参考信息 -->