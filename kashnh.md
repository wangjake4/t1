代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.0kj1m.cn/Article/details/gt2jhgdfagx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lwcvrojg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gt2jsmbuulb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tianlin.xyz/Article/details/gt2icecjuxa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cucudq.cn/Article/details/gt2rjlqwfdr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258.top/Article/details/gt2eilouzcp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2cvsnvsdi.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gt2wxhisktl.html

Py:   resp.json()
来源：http://dali.jinqigufen.top/Article/details/gt2lkatcvxl.html

PHP:  json_decode($body, true);
来源：http://dali.ydzc1.top/Article/details/gt2zomoyvsd.html

JS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzxijfft.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gt2atmxgrqj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2rbtswvfq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gt2sougknjt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dianchejie.cn/Article/details/gt2uudwkegk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hanzgsiw.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gt2snfrkvky.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hywenlv.cn/Article/details/gt2qezjbexs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.svipenyu.cn/Article/details/gt2pmifrgqq.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gt2jguhsxhy.html

TS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gt2frzjsvag.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gt2zsvddlwr.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gt2nefgjvyj.html

Ruby: resp.code.to_i
来源：http://dali.yueranfly.top/Article/details/gt2upjttxae.html

C#:   (int)resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gt2jpvdvyji.html

[L08] 并发请求多个地址
来源：http://dali.mhx1999.top/Article/details/gt2jcpfqkno.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gt2kxxxxkvb.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gt2iyusanlc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gt2wwiamtca.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gt2yajnuzdu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gt2czsueqwk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.havefunace.top/Article/details/gt2smnzklaz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cucudq.cn/Article/details/gt2ulcsvicm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yvedp.cn/Article/details/gt2cwlkeanj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2vyugpfqs.html

M. 命令行 / 进程 / 环境
来源：http://dali.gaohongyu789.top/Article/details/gt2zbrpslth.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2hhtxlegy.html

[M01] 读取命令行参数
来源：http://dali.tian-w.cn/Article/details/gt2mxagmgan.html

Py:   sys.argv[1:]
来源：http://dali.vqdsnc.cn/Article/details/gt2syoxijup.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gt2snxwvrnb.html

JS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gt2yakihcvh.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2pwtoahrv.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gt2kdtcwyia.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2wjrqghrx.html

Ruby: ARGV
来源：http://dali.cashguo.top/Article/details/gt2khgukpwg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gt2pfbxvven.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkeoyti.html

Py:   os.environ.get("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jpkgsier.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gt2bvehuuah.html

JS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gt2atqmarfu.html

TS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gt2rloaownq.html

Java: System.getenv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2ymouksws.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.smart0.xyz/Article/details/gt2juwdhjbr.html

Ruby: ENV["HOME"]
来源：http://dali.bjfxy.top/Article/details/gt2lfuqsoba.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gt2bgdrlkzl.html

[M03] 执行外部命令
来源：http://dali.gaohongyu789.top/Article/details/gt2nvsexqex.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ybcxt.top/Article/details/gt2oboqboer.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnxiangtu.top/Article/details/gt2rlssfjyq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gt2oitdkfeu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gt2kqgcfdai.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgufenzy.top/Article/details/gt2ckrfhpdt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ablsdtbb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gt2pfsrbazv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.9152youxi.cn/Article/details/gt2cxtgszav.html

[M04] 获取当前工作目录
来源：http://dali.tanke756.top/Article/details/gt2wkkehdwd.html

Py:   os.getcwd()
来源：http://dali.svipenyu.cn/Article/details/gt2nlwhnjqb.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gt2kksvyboh.html

JS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gt2ispqusni.html

TS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gt2mkccgpvj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenlongwang.top/Article/details/gt2vwznqabb.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gt2kiqwuntg.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gt2wwamheyv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cashguo.top/Article/details/gt2jxpczmyl.html

[M05] 设置退出码
来源：http://dali.0kj1m.cn/Article/details/gt2jwgxbwtr.html

Py:   sys.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2jbcjezfm.html

PHP:  exit(1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rheyroxp.html

JS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2ojygskuo.html

TS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2rilnbwxf.html

Java: System.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2ihyvpwjk.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2vttdjloe.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gt2olupljwi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigfzy.top/Article/details/gt2dxqkwqrt.html

[M06] 向标准错误输出
来源：http://dali.ybcxt.top/Article/details/gt2cdwmpkmi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gt2vxsdglzd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gt2phjqkirg.html

JS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gt2vsyhlfbx.html

TS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2gezmpnru.html

Java: System.err.println("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smlaeilh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daria6918.cn/Article/details/gt2zalwcfof.html

Ruby: warn "err"
来源：http://dali.cucudq.cn/Article/details/gt2gdqavelt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jyoumei.cn/Article/details/gt2pwplfdym.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gt2jorohuzm.html

Py:   if __name__ == "__main__":
来源：http://dali.snrcjt.cn/Article/details/gt2puszqpxb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tian-w.cn/Article/details/gt2sthybxep.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gt2rkievsdc.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gt2moiijmpk.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gt2wwjkjgnc.html

Go:   func main()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pxyxgcyy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.kuanghao11.cn/Article/details/gt2krhxbsok.html

C#:   static void Main(string[] args)
来源：http://dali.gotoacloud.top/Article/details/gt2fuccxvqr.html

[M08] 获取系统与运行时信息
来源：http://dali.guannengcc.top/Article/details/gt2awvboaap.html

Py:   platform.system();  platform.python_version()
来源：http://dali.andypj.xyz/Article/details/gt2teqqhmsv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258888.top/Article/details/gt2brrouiwy.html

JS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gt2zsuyfgmj.html

TS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gt2rdicuxih.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuxming.cn/Article/details/gt2qottxbdo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tanke756.top/Article/details/gt2moipxrrs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pywtmjzm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gt2egvnwpfv.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ziibrwkg.html

N. 数据结构与算法
来源：http://dali.yonumen.top/Article/details/gt2kxejvmyh.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2fexswxde.html

[N01] 二分查找（有序数组）
来源：http://dali.dianchejie.cn/Article/details/gt2xwgjcfgg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2fhutywzh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.9152youxi.cn/Article/details/gt2gbbzurnp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gt2ptbgylcl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gt2cdoyggmq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2qngejixq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2nyiwxywe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.andypj.xyz/Article/details/gt2etyvwegq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2ewugvldc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aibaodan.cn/Article/details/gt2jtymfzoo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gt2niooxnyu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.smart0.xyz/Article/details/gt2mtickqzu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gt2pioorfxr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gt2rpimdkss.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qshgnibx.html

Go:   slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2clupxxch.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gt2xlzlrkzr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangdashe.top/Article/details/gt2sxgqzato.html

[N03] 快速排序（分治示例）
来源：http://dali.andypj.xyz/Article/details/gt2myvrseil.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gt2eaboagek.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fpidskni.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gt2txkoenac.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gt2qamtbdzi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.snrcjt.cn/Article/details/gt2eutsbnim.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guowangkeji.top/Article/details/gt2cefzfnen.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xylfe.cn/Article/details/gt2ixnajqmj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tianlin.xyz/Article/details/gt2lobsfugn.html

[N04] 斐波那契数列
来源：http://dali.pycfn.com/Article/details/gt2akemdkcl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gt2enyekwoq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gt2nwojeqww.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gt2lpywklpn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gt2hngjmopg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywkwtnzy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gt2yqhxfywu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gt2gocemcgq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gt2jcmhgxyi.html

[N05] 最大公约数
来源：http://dali.feifeiyinyue.top/Article/details/gt2jjxskljt.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zyeyjsav.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tianlin.xyz/Article/details/gt2kkwshgjt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gt2eivpfclo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gt2emkqnwkp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigufen.top/Article/details/gt2qzmeqpxj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvaimjpn.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lagwcuev.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.snrcjt.cn/Article/details/gt2evwjdaet.html

[N06] 判断回文字符串
来源：http://dali.jqgfzy.top/Article/details/gt2wezcprnk.html

Py:   s == s[::-1]
来源：http://dali.havefunace.top/Article/details/gt2lcpinhhb.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2scjetpyh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gt2jdiazevm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gt2ncsatamc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gogol.net.cn/Article/details/gt2vkccpyji.html

Go:   // 双指针从两端比较
来源：http://dali.cucudq.cn/Article/details/gt2zygysxqf.html

Ruby: s == s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2zizfiujb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gt2nzddvtgk.html

[N07] 两数之和（返回下标）
来源：http://dali.xziqi.cn/Article/details/gt2wakngqoc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.mhx1999.top/Article/details/gt2pqhtapbu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lupgknvb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.redwolf501.top/Article/details/gt2rcrazkjf.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fkkmqbcg.html

Java: // 手写 HashMap
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpkrgqlt.html

Go:   // 手写 map[int]int
来源：http://dali.hnxiangtu.top/Article/details/gt2hwxkmgra.html

Ruby: // 手写 Hash
来源：http://dali.ehwqpu.com/Article/details/gt2glhhjkwa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ybcxt.top/Article/details/gt2ufqegskk.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpesqahi.html

Py:   itertools.permutations(arr)
来源：http://dali.ybcxt.top/Article/details/gt2zlmsfioz.html

PHP:  // 手写递归交换
来源：http://dali.gzhubu.top/Article/details/gt2qchdyeer.html

JS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2yfhivqhi.html

TS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2rlgxnrrx.html

Java: // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2mntjhxxv.html

Go:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2wdrlhzpk.html

Ruby: arr.permutation.to_a
来源：http://dali.9152youxi.cn/Article/details/gt2zqnhhcul.html

C#:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2qpnrtsdx.html

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gt2mcehwywl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2krzjumoh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gt2foiqlgmx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gt2xamxwitv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cdnleiting.top/Article/details/gt2bbunghsb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.316326.xyz/Article/details/gt2odhlwffv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.iojbl.cn/Article/details/gt2diefbrub.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gt2ufbzaoza.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fhibsuul.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xxfwffsd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cheryme.top/Article/details/gt2xodxlzsn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.mhx1999.top/Article/details/gt2pdmkitqw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cashguo.top/Article/details/gt2davcdhcx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjatrxtd.html

Java: class Node { int v; Node next; }
来源：http://dali.mhx1999.top/Article/details/gt2btepvphe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cdnleiting.top/Article/details/gt2ckiqmikx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258888.top/Article/details/gt2ytueatzm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ivvv.top/Article/details/gt2txbuidbq.html

[N11] 二叉树中序遍历
来源：http://dali.xylfe.cn/Article/details/gt2vjxwwgaz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.mhx1999.top/Article/details/gt2fprwbtrk.html

PHP:  // 手写递归函数
来源：http://dali.cucudq.cn/Article/details/gt2cidoeaaf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gt2winujfig.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jiagoushi.top/Article/details/gt2jlvaxreq.html

Java: // 手写递归
来源：http://dali.xinyue.icu/Article/details/gt2hqohwoqy.html

Go:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gt2atbnnlqa.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xylfe.cn/Article/details/gt2hjonzczc.html

C#:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gt2bbapiybc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wnnmwjxw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yongpay.top/Article/details/gt2snwnplwx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.quarkkingdee.top/Article/details/gt2gaqkhfbp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gt2ckdlvsin.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gt2tpygqtlo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gt2vfmjhvbg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pycfn.com/Article/details/gt2wtpwgbmd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2oydfzehy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gt2efiitodc.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2bbvmxhha.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gt2gtowuoyx.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2lqqigmfd.html

[O01] 启动一个线程
来源：http://dali.gzhubu.top/Article/details/gt2ipvqsvfz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hywenlv.cn/Article/details/gt2jedcjcbf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigfzy.top/Article/details/gt2eajqkwjd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gt2dhsmerea.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gt2wxtwbeki.html

Java: new Thread(() -> f()).start()
来源：http://dali.zdqjudy.top/Article/details/gt2ayjrsonn.html

Go:   go f()
来源：http://dali.nanxinkj.top/Article/details/gt2zxmpierq.html

Ruby: Thread.new { f }
来源：http://dali.guannengcc.top/Article/details/gt2kpmdrlfs.html

C#:   Task.Run(() => F());
来源：http://dali.fengsongda.top/Article/details/gt2tcuqpslx.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfppgkqr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yangfankeji.com/Article/details/gt2dpnqjozh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fengsongda.top/Article/details/gt2xebfwynm.html

JS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gt2hspcyset.html

TS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gt2nakofgzu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.quarkkingdee.top/Article/details/gt2daneezym.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zycfv.cn/Article/details/gt2pmfpllwz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.vqdsnc.cn/Article/details/gt2jmodhwwy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgufenzy.top/Article/details/gt2tillpddk.html

[O03] 加锁保护共享数据
来源：http://dali.hnxiangtu.top/Article/details/gt2sbjkycpu.html

Py:   with lock: shared += 1
来源：http://dali.aizwys.cn/Article/details/gt2agiihjks.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.snrcjt.cn/Article/details/gt2pmqixbas.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sufxvd.cn/Article/details/gt2wfcdqlfb.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gt2tmhakfft.html

Java: synchronized (this) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gt2obhsbflw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gogol.net.cn/Article/details/gt2dgxmokjx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gt2pocjmswk.html

C#:   lock (gate) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2hnzfbbwc.html

[O04] 定义异步函数并等待
来源：http://dali.hnqzz.top/Article/details/gt2uksgegap.html

Py:   async def f():⏎    await g()
来源：http://dali.tian-w.cn/Article/details/gt2ozuweece.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yvedp.cn/Article/details/gt2kdmxkhuz.html

JS:   async function f() { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gt2rrqkirne.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sxryk.cn/Article/details/gt2jnnleqhq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yongpay.top/Article/details/gt2ivuwraom.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zdqjudy.top/Article/details/gt2vwhumogc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenjidiqi.icu/Article/details/gt2nvitdwee.html

C#:   async Task F() { await G(); }
来源：http://dali.guowangkeji.top/Article/details/gt2yohnrztw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfmtans.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2knqfcofj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xinyue.icu/Article/details/gt2ikzdzdnu.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gt2jdhpejnx.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gt2dzyreobe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.snrcjt.cn/Article/details/gt2jmhmrgon.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ybcxt.top/Article/details/gt2rftnjude.html

Ruby: threads.map(&:join)
来源：http://dali.fzhhl.top/Article/details/gt2mqrnftjd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yueranfly.top/Article/details/gt2rysiveng.html

[O06] 使用进程池
来源：http://dali.quarkkingdee.top/Article/details/gt2bnnihcpf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ydzc1.top/Article/details/gt2mutpjqac.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhengqikj.top/Article/details/gt2qvpfqrjb.html

JS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gt2khrqehda.html

TS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gt2rbdxvtyx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jinhpato.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhongyouzk.top/Article/details/gt2dqrhjqlg.html

Ruby: // fork 块
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkvofoyk.html

C#:   Parallel.For
来源：http://dali.yuxming.cn/Article/details/gt2dkapmljr.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2jvsiwpra.html

P. 常用工具函数
来源：http://dali.yanxiufei.cn/Article/details/gt2whbjegnr.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2pwjuiedv.html

[P01] 生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gt2gkhkysbw.html

Py:   str(uuid.uuid4())
来源：http://dali.guannengcc.top/Article/details/gt2jfagocup.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.dashuyun.cn/Article/details/gt2hpfrrgps.html

JS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gt2hczmolrg.html

TS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gt2dpexhwiw.html

Java: UUID.randomUUID().toString()
来源：http://dali.dashuyun.cn/Article/details/gt2dnrbakpf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pycfn.com/Article/details/gt2edkfhmmp.html

Ruby: SecureRandom.uuid
来源：http://dali.316326.xyz/Article/details/gt2ydwlrzsa.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cheryme.top/Article/details/gt2vxieyxdc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xinyue.icu/Article/details/gt2hbaiemqt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nwbrower.top/Article/details/gt2vmtxtqyl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hibnxqmp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.feifeiyinyue.top/Article/details/gt2cnhdsqje.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sweek.top/Article/details/gt2rvzxhjyt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hysaishi.cn/Article/details/gt2vvzbvsrf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jiagoushi.top/Article/details/gt2qebmrsjr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ygsopntu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daria6918.cn/Article/details/gt2zbhzwuvn.html

[P03] 生成短随机字符串
来源：http://dali.xuanzx.com/Article/details/gt2ujvuwpyb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxuanxn.top/Article/details/gt2nfhnegcy.html


<!-- 参考信息 -->