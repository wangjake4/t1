代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hywenlv.cn/Article/details/gtsezrgsdz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hysaishi.cn/Article/details/gtazxjqvpr.html

[L05] 上传文件（multipart）
来源：http://dali.kuanghao11.cn/Article/details/gtcsmjhjrf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinghuilouyu.cn/Article/details/gtjotzhnga.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangshuangyany.cn/Article/details/gthkedmram.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gtwdydjrdv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gttdixbjch.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuetiantiany.cn/Article/details/gtswjueqax.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gzhubu.top/Article/details/gtkblbjrpz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gtqcjzkhvw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtencpcmoq.html

[L06] 解析响应为 JSON
来源：http://dali.0kj1m.cn/Article/details/gtrcidkqyo.html

Py:   resp.json()
来源：http://dali.tanke756.top/Article/details/gtlfoorrax.html

PHP:  json_decode($body, true);
来源：http://dali.yongpay.top/Article/details/gtmzqweefn.html

JS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtjtsiajvk.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtphzlwsiw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtigxzsqzm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hammf.cn/Article/details/gtyvokpasd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nwbrower.top/Article/details/gtcdhnudak.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gtvtjmacau.html

[L07] 处理 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gthlthbmxw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sufxvd.cn/Article/details/gtqodfuteo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gtumxmqwbr.html

JS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtxivpqktc.html

TS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtpctymlpk.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gtlmgnsgpt.html

Go:   resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gtuflfofyo.html

Ruby: resp.code.to_i
来源：http://dali.hammf.cn/Article/details/gtvwnnzzro.html

C#:   (int)resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtmtvlcybc.html

[L08] 并发请求多个地址
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvzgoeru.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwlmsvzf.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgfzy.top/Article/details/gttfatache.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtzudnlxtt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtqhhcbwgy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gtgdzhcmiz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenjidiqi.icu/Article/details/gtlwzuebka.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gtepdqjmue.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxrazdvp.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtkzxkflke.html

M. 命令行 / 进程 / 环境
来源：http://dali.shzxlz.cn/Article/details/gtndxhyxkd.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtlprjwhum.html

[M01] 读取命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtposjrpld.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gtzbinpxxn.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gtiqweaecz.html

JS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtenhjjbrt.html

TS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gtkpcdscyq.html

Java: args 数组（main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtjypizuot.html

Go:   os.Args[1:]
来源：http://dali.ybcxt.top/Article/details/gtydvrflaw.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gtompnhsme.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gttppjxbzp.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtbgmrbxxt.html

Py:   os.environ.get("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtgmemkzuk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtedjmanve.html

JS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtggeytedu.html

TS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gtsisxlmrz.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtcvwvbiek.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtdnayrysm.html

Ruby: ENV["HOME"]
来源：http://dali.chenzaomai.com/Article/details/gtxrzpfggw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtjsokolwu.html

[M03] 执行外部命令
来源：http://dali.zhengqikj.top/Article/details/gtcyoytzkl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gtmoqlssin.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hongshengwenyu.top/Article/details/gtwsnolyzt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gtpgxrmvpl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gthleaimrm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sxryk.cn/Article/details/gtfshxapjz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ydzc1.top/Article/details/gtcntomwpo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gtwdltmnzw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xinyue.icu/Article/details/gtzluqogpi.html

[M04] 获取当前工作目录
来源：http://dali.tanke756.top/Article/details/gtvuixdeze.html

Py:   os.getcwd()
来源：http://dali.ybcxt.top/Article/details/gtssgtpsml.html

PHP:  getcwd();
来源：http://dali.svipenyu.cn/Article/details/gthvvhxnrn.html

JS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtzztdwoyg.html

TS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gtjpnjvbvg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.haohaochexian.top/Article/details/gtetgimmid.html

Go:   os.Getwd()
来源：http://dali.redwolf501.top/Article/details/gtxbvbwdzj.html

Ruby: Dir.pwd
来源：http://dali.sysykeji.top/Article/details/gtdkiigdou.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gttavgznnn.html

[M05] 设置退出码
来源：http://dali.yvedp.cn/Article/details/gtipkjdjrb.html

Py:   sys.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gttltgcngu.html

PHP:  exit(1);
来源：http://dali.yanxiufei.cn/Article/details/gthqwldmer.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtgjfmnnwx.html

TS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtowgecicw.html

Java: System.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gttplxuckl.html

Go:   os.Exit(1)
来源：http://dali.yongpay.top/Article/details/gtbjimzrxo.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtsytlmsbl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gzhubu.top/Article/details/gtebcfjusa.html

[M06] 向标准错误输出
来源：http://dali.jianghu66.top/Article/details/gtdksotthw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gtisqijoxc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenjidiqi.icu/Article/details/gtnsccfcod.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtvuezcwpj.html

TS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gtenvziyyh.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gtqrhwfrkx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigfzy.top/Article/details/gtukqhetxr.html

Ruby: warn "err"
来源：http://dali.zhixingplan.top/Article/details/gtwcxsrvgf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgufenzy.top/Article/details/gtxraqeucu.html

[M07] 判断是否为主入口
来源：http://dali.cucudq.cn/Article/details/gtxhruwwjs.html

Py:   if __name__ == "__main__":
来源：http://dali.feifeiyinyue.top/Article/details/gtlgoxwsjo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cucudq.cn/Article/details/gtximqvppj.html

JS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtszxnbznl.html

TS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gtctresrwr.html

Java: public static void main(String[] args)
来源：http://dali.cheryme.top/Article/details/gtresqpfxd.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gtpysdiuvw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchvwhxfe.html

C#:   static void Main(string[] args)
来源：http://dali.yueranfly.top/Article/details/gtswmsezhg.html

[M08] 获取系统与运行时信息
来源：http://dali.chenjidiqi.icu/Article/details/gtbwdcevnm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gtjvqvfgnu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gtrckpyfar.html

JS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gterzwblun.html

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtfxcvkrxy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gtxjznngvm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sweek.top/Article/details/gtdadbrukb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hywenlv.cn/Article/details/gtmafemste.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gtuvooiryg.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmejlhsgg.html

N. 数据结构与算法
来源：http://dali.birdmap.top/Article/details/gtnncuqidj.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtfxxfawqt.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxuanxn.top/Article/details/gtdwzniocw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtgdlsumod.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fengsongda.top/Article/details/gttvignisr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gtzvfqzskw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gthwthslau.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtzzponrob.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtnccrwrmu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gtcemjkjbt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtqbwzgona.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sxryk.cn/Article/details/gtkxxovhjo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gtaunwsrlq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtjmhwbuba.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgkhpdyc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtlkpwcnsq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ivvv.top/Article/details/gtniblguoc.html

Go:   slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gtfnhedrbc.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvblrfzb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dashuyun.cn/Article/details/gtzsocslkf.html

[N03] 快速排序（分治示例）
来源：http://dali.ehwqpu.com/Article/details/gtqavllrgt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hongshengwenyu.top/Article/details/gtfzfnktux.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shangyingyoupin.top/Article/details/gtzxelhlar.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gtyjdrpphc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gtvtacphou.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.kuanghao11.cn/Article/details/gtwlkbicxk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gtvjrgripy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gttedzbjtb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dianchejie.cn/Article/details/gtpzqkymdx.html

[N04] 斐波那契数列
来源：http://dali.nanxinkj.top/Article/details/gtwfslolcr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gtbmnerpzu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtbsahalck.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipliopkn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtnqktiugq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.mhx1999.top/Article/details/gtluujxfek.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxuanxn.top/Article/details/gtojqflcyr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gtgqzvghzu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtzickiwgo.html

[N05] 最大公约数
来源：http://dali.wangshuangyany.cn/Article/details/gtesxfoanu.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258.top/Article/details/gtvzbcqhmj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.c1oappe.top/Article/details/gtwwbkcbpi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gtkpngympw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gtdqpttivv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shuidangran.top/Article/details/gtpfsdknxj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yonumen.top/Article/details/gthcnmltvy.html

Ruby: a.gcd(b)
来源：http://dali.nanxinkj.top/Article/details/gteudutpji.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.feifeiyinyue.top/Article/details/gtiujxzcad.html

[N06] 判断回文字符串
来源：http://dali.nanxinkj.top/Article/details/gtwrynnxzl.html

Py:   s == s[::-1]
来源：http://dali.xziqi.cn/Article/details/gtzoshlepq.html

PHP:  $s === strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gtvbvmgkkz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtkiotevge.html

TS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtyvwahyuo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258.top/Article/details/gtwczrvzli.html

Go:   // 双指针从两端比较
来源：http://dali.sweek.top/Article/details/gtrhzvwcuw.html

Ruby: s == s.reverse
来源：http://dali.iojbl.cn/Article/details/gtumeyrrds.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gtfjikzwly.html

[N07] 两数之和（返回下标）
来源：http://dali.cqqwz.cn/Article/details/gtdwnumhbs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yangfankeji.com/Article/details/gtflwofktd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.smart0.xyz/Article/details/gtdvbtlgkt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sweek.top/Article/details/gttcisnyao.html

TS:   // 手写 Map<string, number>
来源：http://dali.mhx1999.top/Article/details/gtzypaatzi.html

Java: // 手写 HashMap
来源：http://dali.jqgufenzy.top/Article/details/gtrutmrdez.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfooylux.html

Ruby: // 手写 Hash
来源：http://dali.shuidangran.top/Article/details/gtfdplyzgo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zycfv.cn/Article/details/gtyninyyxp.html

[N08] 生成全排列
来源：http://dali.jinghuilouyu.cn/Article/details/gtpuukmkbr.html

Py:   itertools.permutations(arr)
来源：http://dali.gzhubu.top/Article/details/gtzrhpywed.html

PHP:  // 手写递归交换
来源：http://dali.sysykeji.top/Article/details/gtscboriew.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gthwqpkxtg.html

TS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtixyfgins.html

Java: // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtguhczuza.html

Go:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtjglrwzhh.html

Ruby: arr.permutation.to_a
来源：http://dali.fengsongda.top/Article/details/gtlipznhkp.html

C#:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtvoqxlbuz.html

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gtgjqkweak.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtobpcbsku.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtiddsszts.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtjhovrwaa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnxiangtu.top/Article/details/gtaglpgcpi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aizwys.cn/Article/details/gtjmkizkmv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenjidiqi.icu/Article/details/gtanequfnk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtslhctbak.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnxiangtu.top/Article/details/gtdlnwuqxx.html

[N10] 链表节点定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmatqueso.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhongyouzk.top/Article/details/gtsxywvzww.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hywenlv.cn/Article/details/gtegjvxiwt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtptqcxjra.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gaohongyu789.top/Article/details/gtskdmogoi.html

Java: class Node { int v; Node next; }
来源：http://dali.zhoulong.xyz/Article/details/gtbizjgjul.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gtphvwmbhq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yanxiufei.cn/Article/details/gttjxwfqkg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnxiangtu.top/Article/details/gtibjntmyn.html

[N11] 二叉树中序遍历
来源：http://dali.gzhubu.top/Article/details/gtfbouiuie.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gtmgwhnrdk.html

PHP:  // 手写递归函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszhjxrlc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tanke756.top/Article/details/gtmftjdxgq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtjcnrrdkt.html

Java: // 手写递归
来源：http://dali.cashguo.top/Article/details/gttqbpqogl.html

Go:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtexqpxdgy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hfpthk.cn/Article/details/gtutszghud.html

C#:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtggthbzlm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.snrcjt.cn/Article/details/gtnvdtmkff.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtlawkckcr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.bjfxy.top/Article/details/gtywtnnosc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gtwfqwsskq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gtdalfgldy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezzqetey.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenjidiqi.icu/Article/details/gtpvbafmkf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daria6918.cn/Article/details/gtmgzciqro.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gtsosswyix.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtaeivkqnp.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gtgxhohzgp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtjnaxmqvi.html

[O01] 启动一个线程
来源：http://dali.hywenlv.cn/Article/details/gtdzffvvgi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hnxiangtu.top/Article/details/gtwrbvakuq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.quarkkingdee.top/Article/details/gtztdjwvdi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xinyue.icu/Article/details/gtkwycvwxz.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtxcvxvhps.html

Java: new Thread(() -> f()).start()
来源：http://dali.dashuyun.cn/Article/details/gtdildysam.html

Go:   go f()
来源：http://dali.yj202588.top/Article/details/gtiusamlmw.html

Ruby: Thread.new { f }
来源：http://dali.haohaochexian.top/Article/details/gtcloszyvq.html

C#:   Task.Run(() => F());
来源：http://dali.daxiang520.top/Article/details/gtmtixkszh.html

[O02] 使用线程池
来源：http://dali.yuanzhike.top/Article/details/gthpibvlzl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnxiangtu.top/Article/details/gtjkusakpc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.316326.xyz/Article/details/gtwcqhuqsg.html

JS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gthjyzypgd.html

TS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteblrojsb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.snrcjt.cn/Article/details/gttgudcbeh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.iojbl.cn/Article/details/gtdxedjlen.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.vqdsnc.cn/Article/details/gtlcexmjxf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhiwuduotai.top/Article/details/gttvqphlde.html

[O03] 加锁保护共享数据
来源：http://dali.jinghuilouyu.cn/Article/details/gtzitgtmlw.html

Py:   with lock: shared += 1
来源：http://dali.gogol.net.cn/Article/details/gtajmnctcv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yongpay.top/Article/details/gtbtyemuxx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gotoacloud.top/Article/details/gtlpiauors.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gtogllohxi.html

Java: synchronized (this) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtmdlwmisz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dianchejie.cn/Article/details/gtzndjdtyd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dianchejie.cn/Article/details/gtixicksjn.html

C#:   lock (gate) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtixaedvpc.html

[O04] 定义异步函数并等待
来源：http://dali.cucudq.cn/Article/details/gtgkwwwpqr.html

Py:   async def f():⏎    await g()
来源：http://dali.zhixingplan.top/Article/details/gtqjxklidk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.9152youxi.cn/Article/details/gtmexanbpw.html

JS:   async function f() { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gtueohbdfq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gtvpzxgmvt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shuidangran.top/Article/details/gtmywjezjv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangdashe.top/Article/details/gtnkprmrwx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuanzx.com/Article/details/gtpeaxquyl.html

C#:   async Task F() { await G(); }
来源：http://dali.aibaodan.cn/Article/details/gttnbodmzx.html

[O05] 并发执行并等待全部完成
来源：http://dali.c1oappe.top/Article/details/gtpsbndaed.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtkvdmhdqb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shuidangran.top/Article/details/gtfjugnhmx.html

JS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gtouzbwelb.html

TS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtuqldubke.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jlsjyb.cn/Article/details/gttwrxwysu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tian-w.cn/Article/details/gtsduexnkj.html

Ruby: threads.map(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gtibndcbce.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigfzy.top/Article/details/gtadhchzkn.html

[O06] 使用进程池
来源：http://dali.zhoulong.xyz/Article/details/gtsmlfdbyq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenzaomai.com/Article/details/gtihyknsig.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gtccixxwfh.html

JS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gtscqmelwk.html

TS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtjuxiashv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yonumen.top/Article/details/gtgxavfwer.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenzaomai.com/Article/details/gtfwktmcec.html

Ruby: // fork 块
来源：http://dali.snrcjt.cn/Article/details/gthsyaaoam.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gtmvagjyso.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtwbltimbj.html

P. 常用工具函数
来源：http://dali.feifeiyinyue.top/Article/details/gtlcqgzmnr.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtgpdpflcp.html

[P01] 生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gtjkruunwn.html

Py:   str(uuid.uuid4())
来源：http://dali.zhengqikj.top/Article/details/gtnlqikvoy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sweek.top/Article/details/gtdaqydpik.html

JS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtvuizowcz.html

TS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtkyztxhqn.html

Java: UUID.randomUUID().toString()
来源：http://dali.daria6918.cn/Article/details/gtsproyofa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jianghu66.top/Article/details/gtuudzvefz.html

Ruby: SecureRandom.uuid
来源：http://dali.jyoumei.cn/Article/details/gtemnhssfa.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gotoacloud.top/Article/details/gtuhmrbovl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.andypj.xyz/Article/details/gtamxbebpo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ivvv.top/Article/details/gtmaeutpli.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuanzhike.top/Article/details/gtnalutvwn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fengsongda.top/Article/details/gtzanmgqcm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj20258.top/Article/details/gtsxmfvofz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258.top/Article/details/gtuediqojx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zdqjudy.top/Article/details/gtrjmpwxmg.html


<!-- 参考信息 -->