代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hfpthk.cn/Article/details/gthhgddeos.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sysykeji.top/Article/details/gtnmdnmjtl.html

[L05] 上传文件（multipart）
来源：http://dali.gzhubu.top/Article/details/gtqkzksvjd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhengqikj.top/Article/details/gtohdlsbjp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shangyingyoupin.top/Article/details/gtghfhciqf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gttzmgoeyn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gtdkuyzyxx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jyoumei.cn/Article/details/gtowjgqooz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hysaishi.cn/Article/details/gtfrrcneiw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gtdwihygtp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ydzc1.top/Article/details/gtdllarpre.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gtnqtkbkms.html

Py:   resp.json()
来源：http://dali.c1oappe.top/Article/details/gtjpxrvlpg.html

PHP:  json_decode($body, true);
来源：http://dali.ppjwa.cn/Article/details/gtltteoisf.html

JS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtoplialzi.html

TS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyvndpbk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cheryme.top/Article/details/gtpdimciyr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.smart0.xyz/Article/details/gtwlplgdpq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuxming.cn/Article/details/gtqwnrcreh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.316326.xyz/Article/details/gtpmfqqdwr.html

[L07] 处理 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gtizhtutmu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cdnleiting.top/Article/details/gtkjgreqso.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gtjdngdggs.html

JS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gtmfhdsstp.html

TS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtbobrdglr.html

Java: resp.statusCode()
来源：http://dali.jqgfzy.top/Article/details/gtrsqpgpvm.html

Go:   resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gtoxikcmkv.html

Ruby: resp.code.to_i
来源：http://dali.yj20258.top/Article/details/gtavsnhflg.html

C#:   (int)resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgidrnbpw.html

[L08] 并发请求多个地址
来源：http://dali.tanke756.top/Article/details/gtzamjizdh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywwwwfuf.html

PHP:  curl_multi_init() 系列
来源：http://dali.dashuyun.cn/Article/details/gthynhlmtz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gtqgtftpez.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtqcgjjzuj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinghuilouyu.cn/Article/details/gthjqskxcv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sweek.top/Article/details/gtgnfuwbgr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.c1oappe.top/Article/details/gtwzbvyqhx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sweek.top/Article/details/gtffjkrsxi.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtbjelnjqy.html

M. 命令行 / 进程 / 环境
来源：http://dali.sweek.top/Article/details/gteyxnfpbp.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtyzjwzcbr.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gtivfmkdry.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfiobmfr.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwivzhdjh.html

JS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gthzzfjebu.html

TS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtlpstwqjo.html

Java: args 数组（main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtogdjzksa.html

Go:   os.Args[1:]
来源：http://dali.nanxinkj.top/Article/details/gtqpnzqvms.html

Ruby: ARGV
来源：http://dali.gaohongyu789.top/Article/details/gteuasrtwl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gthpvmoqtq.html

[M02] 读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gtxmbiwqlf.html

Py:   os.environ.get("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtpxegvpzd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gteztrhfmx.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnzpnhkw.html

TS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtfguiicqt.html

Java: System.getenv("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtkfyeqgcq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guannengcc.top/Article/details/gtgpbrtomi.html

Ruby: ENV["HOME"]
来源：http://dali.xuetiantiany.cn/Article/details/gtrirblgms.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtvabfxfck.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gthzyufvgu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuetiantiany.cn/Article/details/gttsrnmtdc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jiagoushi.top/Article/details/gtnxzqfayr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtrrfedsvh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtgolsbbnz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jianghu66.top/Article/details/gtjydiwdeb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.c1oappe.top/Article/details/gtiemvmqde.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gzhubu.top/Article/details/gtjyzfnubb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xziqi.cn/Article/details/gtvxkpxvjz.html

[M04] 获取当前工作目录
来源：http://dali.ppjwa.cn/Article/details/gtmgojvhlf.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gtftmezyps.html

PHP:  getcwd();
来源：http://dali.dashuyun.cn/Article/details/gthjwpltba.html

JS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gtzgtvyhvf.html

TS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtxoyfnohx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dashuyun.cn/Article/details/gtbruhrgoe.html

Go:   os.Getwd()
来源：http://dali.redwolf501.top/Article/details/gtgrrarhyw.html

Ruby: Dir.pwd
来源：http://dali.zhengqikj.top/Article/details/gtjqisywan.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xinyue.icu/Article/details/gtwqrnmcqg.html

[M05] 设置退出码
来源：http://dali.feifeiyinyue.top/Article/details/gtgjbabevc.html

Py:   sys.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtomchuxvp.html

PHP:  exit(1);
来源：http://dali.cashguo.top/Article/details/gthzcmoxgf.html

JS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtbccwnvlk.html

TS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtpedidfkf.html

Java: System.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtrtrngbry.html

Go:   os.Exit(1)
来源：http://dali.guannengcc.top/Article/details/gtkpmlpkvz.html

Ruby: exit 1
来源：http://dali.iojbl.cn/Article/details/gtjyfqzovw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hfpthk.cn/Article/details/gtdvqvukqq.html

[M06] 向标准错误输出
来源：http://dali.fengsongda.top/Article/details/gtwgrwkhbn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtvvvmtqou.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gtzaiuzeav.html

JS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gtojxwwkng.html

TS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gttnyhvmjt.html

Java: System.err.println("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtxepjunzk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gotoacloud.top/Article/details/gtodyuqtuf.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gtagoranqs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtijyxowxn.html

[M07] 判断是否为主入口
来源：http://dali.ppjwa.cn/Article/details/gtbekrtdqd.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gtrbibkwtz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqjkhnxw.html

JS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtgsoeqxxe.html

TS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtkkeldwzg.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gtkxumkrun.html

Go:   func main()
来源：http://dali.haohaochexian.top/Article/details/gtulpdrnif.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zycfv.cn/Article/details/gtjwdyqqkh.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gtmucxtihn.html

[M08] 获取系统与运行时信息
来源：http://dali.jlsjyb.cn/Article/details/gtirrxkjeg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gtinqytzeg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgufenzy.top/Article/details/gtiyivsjar.html

JS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtayaoqfff.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtizsvamor.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cdnleiting.top/Article/details/gtgzcugcqq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhoulong.xyz/Article/details/gtcuhwtxnx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ivvv.top/Article/details/gtmsqszgvp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gtzitwywzy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtzaozgvis.html

N. 数据结构与算法
来源：http://dali.jlsjyb.cn/Article/details/gtzpqtvzty.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtamkwdkbm.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gtcsmslthm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtftzujwpn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtrbgwefpn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtriyqefjc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gtwumrdisw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtmxqvuzvp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtawuceoit.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.vqdsnc.cn/Article/details/gtdzpyllhz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtqbqzpztj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fengsongda.top/Article/details/gtidmtvpqe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gteiurbelp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hywenlv.cn/Article/details/gtuettezct.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtttqkprtp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gtgdxwyvbr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gtkuotbtet.html

Go:   slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gtshyzkfzv.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gtmnngdyhw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guannengcc.top/Article/details/gthwxmtdty.html

[N03] 快速排序（分治示例）
来源：http://dali.ppjwa.cn/Article/details/gtzhqentcb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ehwqpu.com/Article/details/gtmtcsfigb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gtncfpniov.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gtdycrbtkp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gtukimgrjq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gtjaqwngsg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nwbrower.top/Article/details/gtopmxczhg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gzhubu.top/Article/details/gtajbkxets.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.snrcjt.cn/Article/details/gtqahbxzme.html

[N04] 斐波那契数列
来源：http://dali.hnqzz.top/Article/details/gtvjxevjuj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gtfjjwvhpf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.andypj.xyz/Article/details/gtzmrkdbjd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gttcmjovvv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtdxppfnrk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daxiang520.top/Article/details/gtfkrhnvmx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dashuyun.cn/Article/details/gtxlfuhxmk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gtunxibhja.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtffxgzjcw.html

[N05] 最大公约数
来源：http://dali.wangshuangyany.cn/Article/details/gtdgrdxalw.html

Py:   math.gcd(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrgzaaib.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jiagoushi.top/Article/details/gtuaxaapsu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfuoghxpo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtuvuflszx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.meibo888.top/Article/details/gtfgrgqtjr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtveeigjmy.html

Ruby: a.gcd(b)
来源：http://dali.kuanghao11.cn/Article/details/gtuwdjbfnv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtruyzncio.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gtlgqoohwj.html

Py:   s == s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gtregavuyz.html

PHP:  $s === strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gtojhsdzbe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtlrbxgspc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtpjrlxegw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuxming.cn/Article/details/gtivfhndsm.html

Go:   // 双指针从两端比较
来源：http://dali.sxryk.cn/Article/details/gtiesoquvy.html

Ruby: s == s.reverse
来源：http://dali.zycfv.cn/Article/details/gttmhwslev.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gtpetsgusq.html

[N07] 两数之和（返回下标）
来源：http://dali.bjfxy.top/Article/details/gtmujhtkri.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gotoacloud.top/Article/details/gtxmvifowz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fengsongda.top/Article/details/gtymufamdf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sweek.top/Article/details/gtbgsupejv.html

TS:   // 手写 Map<string, number>
来源：http://dali.iojbl.cn/Article/details/gtvudriivi.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gtskjqdxsc.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258.top/Article/details/gtghclqslq.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gtoluhbcrf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yongpay.top/Article/details/gtwmacjqoj.html

[N08] 生成全排列
来源：http://dali.zhengqikj.top/Article/details/gtslysyzqw.html

Py:   itertools.permutations(arr)
来源：http://dali.dianchejie.cn/Article/details/gtxwitecyc.html

PHP:  // 手写递归交换
来源：http://dali.andypj.xyz/Article/details/gtkyqmywfv.html

JS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtojwyxsyd.html

TS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtlompdutx.html

Java: // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtebxmdneo.html

Go:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtnrklhvyf.html

Ruby: arr.permutation.to_a
来源：http://dali.dashuyun.cn/Article/details/gtprhfuzjg.html

C#:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuybwkzd.html

[N09] 栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtzsdiccnr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtchcmxryz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtbmvmozyy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtsskrnfms.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gtbiffknds.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.c1oappe.top/Article/details/gtdvydtqvs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuanzx.com/Article/details/gtxrkmehjs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtsbywelnw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.bjfxy.top/Article/details/gtevyyuixx.html

[N10] 链表节点定义
来源：http://dali.ybcxt.top/Article/details/gtlkjyxzup.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cashguo.top/Article/details/gttuvzpulv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsgkgbfsj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gteqzyrcdu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ivvv.top/Article/details/gttqdafylk.html

Java: class Node { int v; Node next; }
来源：http://dali.gzhubu.top/Article/details/gtvjjgyeza.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zdqjudy.top/Article/details/gtnyirbhxj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.snrcjt.cn/Article/details/gtvoaifpci.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgfzy.top/Article/details/gtigtpazvg.html

[N11] 二叉树中序遍历
来源：http://dali.dianchejie.cn/Article/details/gtvyeocfhv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cdnleiting.top/Article/details/gtdlgupntb.html

PHP:  // 手写递归函数
来源：http://dali.gaohongyu789.top/Article/details/gtkrkjtzyx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gttpeblduc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtzmkxsdyq.html

Java: // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtrupmlnwj.html

Go:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gttktpkyov.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jyoumei.cn/Article/details/gtyopibukx.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtccmksuaf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj202588.top/Article/details/gtwvdkdvyu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shuidangran.top/Article/details/gtgxovnhvz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gtwvtjbkkz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gthmmdzpdh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gtzetritar.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxinkj.top/Article/details/gtlkzdxeks.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgufenzy.top/Article/details/gtybacepal.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtemdtsioj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gtaajzkmzc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpzfpfzc.html

O. 并发与异步
来源：http://dali.tanke756.top/Article/details/gtznnblfdn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtmwbpspoy.html

[O01] 启动一个线程
来源：http://dali.nanxinkj.top/Article/details/gtvdpwqcur.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zycfv.cn/Article/details/gthoqnpuzl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.svipenyu.cn/Article/details/gtcnrqildf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gtvuayujed.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gtsgiijlas.html

Java: new Thread(() -> f()).start()
来源：http://dali.hammf.cn/Article/details/gtsyqfszfz.html

Go:   go f()
来源：http://dali.zhoulong.xyz/Article/details/gttzvspfud.html

Ruby: Thread.new { f }
来源：http://dali.dianchejie.cn/Article/details/gtcwnyozpw.html

C#:   Task.Run(() => F());
来源：http://dali.smart0.xyz/Article/details/gtvhskbnyo.html

[O02] 使用线程池
来源：http://dali.nwbrower.top/Article/details/gtcslmkcvn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ehwqpu.com/Article/details/gtgdlsequs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guowangkeji.top/Article/details/gttnyieryz.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gtracvhgws.html

TS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gtreoipito.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenlongwang.top/Article/details/gtzacwnspn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gtoobevwsq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.havefunace.top/Article/details/gtmhjmjnrw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tian-w.cn/Article/details/gtuhagscav.html

[O03] 加锁保护共享数据
来源：http://dali.hnxiangtu.top/Article/details/gtnedvtrea.html

Py:   with lock: shared += 1
来源：http://dali.zhiwuduotai.top/Article/details/gtekmujlan.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangshuangyany.cn/Article/details/gtntvcbwws.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenzaomai.com/Article/details/gtewdwxrlg.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gtedrwbygf.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtriialsss.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj202588.top/Article/details/gtfsbzzpjp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.0kj1m.cn/Article/details/gtqumdhxzm.html

C#:   lock (gate) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gtvdkqnzxq.html

[O04] 定义异步函数并等待
来源：http://dali.shzxlz.cn/Article/details/gtdirilmuf.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gtasyfjdxo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxinkj.top/Article/details/gtpulwwnlq.html

JS:   async function f() { await g(); }
来源：http://dali.gzhubu.top/Article/details/gtfcmuqhup.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nwbrower.top/Article/details/gtmtlpjmyu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sweek.top/Article/details/gtfbnklcnn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sxryk.cn/Article/details/gtvgoxqdnf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258888.top/Article/details/gtgiwjkdsj.html

C#:   async Task F() { await G(); }
来源：http://dali.xinyue.icu/Article/details/gtoinwldpy.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhixingplan.top/Article/details/gtwvlsqmmj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ydzc1.top/Article/details/gtybmlqdmh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhoulong.xyz/Article/details/gtpbgrcslw.html

JS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtorxskjim.html

TS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gtgtwzhqth.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cucudq.cn/Article/details/gtnvrcgmig.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yvedp.cn/Article/details/gtpkoqowvq.html

Ruby: threads.map(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gtapqyrxot.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hammf.cn/Article/details/gtfzeljxyc.html

[O06] 使用进程池
来源：http://dali.gotoacloud.top/Article/details/gtijlvcwvs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangshuangyany.cn/Article/details/gtcknjyctw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gtbepkwgqg.html

JS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gtsxlinbsu.html

TS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gtjzdmhztl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sxryk.cn/Article/details/gtppgbtwdp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.kuanghao11.cn/Article/details/gtpiacomam.html

Ruby: // fork 块
来源：http://dali.xuetiantiany.cn/Article/details/gtlcnzwzvi.html

C#:   Parallel.For
来源：http://dali.tanke756.top/Article/details/gtksqcxzhd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtqqlbiieu.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gttqtqrguy.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclxdfgte.html

[P01] 生成 UUID
来源：http://dali.tanke756.top/Article/details/gthbygdtkb.html

Py:   str(uuid.uuid4())
来源：http://dali.chenlongwang.top/Article/details/gtgsvbtsqg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xylfe.cn/Article/details/gtqtldegct.html

JS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtrlvabtho.html

TS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gtgglxvrev.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj202588.top/Article/details/gtckaxblob.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdxdgfzp.html

Ruby: SecureRandom.uuid
来源：http://dali.sysykeji.top/Article/details/gtxgahugxy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shuidangran.top/Article/details/gtinqxavmm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgufenzy.top/Article/details/gtjwjtisnh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258.top/Article/details/gtpyibwtdk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhixingplan.top/Article/details/gthjnvaajq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dashuyun.cn/Article/details/gtpmqmzafj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gtiqmpxuuj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.mhx1999.top/Article/details/gtxgxulkzd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yongpay.top/Article/details/gtwxfhbfqg.html


<!-- 参考信息 -->