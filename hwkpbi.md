代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.redwolf501.top/Article/details/gtoopxfybt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hfpthk.cn/Article/details/gtjvcaswoy.html

[L05] 上传文件（multipart）
来源：http://dali.gaohongyu789.top/Article/details/gtqabkptzt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gtljlopwet.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecbwlgzo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtryoawrgc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclxatghc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tian-w.cn/Article/details/gtdhellyoh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenlongwang.top/Article/details/gtjefkmupr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenlongwang.top/Article/details/gtggmwxvyh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ivvv.top/Article/details/gtoanqpecl.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gtforrdnbg.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gtvchoagnj.html

PHP:  json_decode($body, true);
来源：http://dali.gogol.net.cn/Article/details/gtacrtxybp.html

JS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtqwkzqelo.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtvkjsbqxu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.bjfxy.top/Article/details/gtonvzrevq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tanke756.top/Article/details/gtcpfemwcz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gtypdzpwim.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258888.top/Article/details/gtxrelujtw.html

[L07] 处理 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gtmasnfvpb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gthzydubsm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258.top/Article/details/gtzffecwxk.html

JS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtmlyeyquf.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknzdofph.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gtezofzgpl.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtephhcquz.html

Ruby: resp.code.to_i
来源：http://dali.yj202588.top/Article/details/gtgmjivmvf.html

C#:   (int)resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtvdlzsuzn.html

[L08] 并发请求多个地址
来源：http://dali.zhongyouzk.top/Article/details/gtxnztlavb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.birdmap.top/Article/details/gtcuexmfeq.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsangdkga.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtddabewqw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtcssybybm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuetiantiany.cn/Article/details/gttcglyeva.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shuidangran.top/Article/details/gtclelbzel.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenlongwang.top/Article/details/gtwisqzgsa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtgpwiqlbp.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtoxiykquj.html

M. 命令行 / 进程 / 环境
来源：http://dali.yvedp.cn/Article/details/gtdkkcvysb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgijhryme.html

[M01] 读取命令行参数
来源：http://dali.nwbrower.top/Article/details/gtvbykrbvf.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gtczplghex.html

PHP:  $argv;  $argc;
来源：http://dali.sysykeji.top/Article/details/gtaohqdzdf.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gttspjmvcy.html

TS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtckjcldfn.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdhebqzy.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gtkgtgggsb.html

Ruby: ARGV
来源：http://dali.zycfv.cn/Article/details/gtxpgnnczo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtayuchjcj.html

[M02] 读取环境变量
来源：http://dali.yuxming.cn/Article/details/gtmrdqhvin.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwhsnyrx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtzzpihjmi.html

JS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gtadnbvzpa.html

TS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gtcxxikccz.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtfoqusrgx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gthxamjcii.html

Ruby: ENV["HOME"]
来源：http://dali.kuanghao11.cn/Article/details/gtdhxlkswm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtgsslshoj.html

[M03] 执行外部命令
来源：http://dali.hfpthk.cn/Article/details/gtavynqxoo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenlongwang.top/Article/details/gtjhbadxct.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.0kj1m.cn/Article/details/gtdevkpinn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtmuxeaesf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gtastxgajb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gtjnpcsvod.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuanzhike.top/Article/details/gtkutgmohe.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.svipenyu.cn/Article/details/gthusicjwn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmoqbwjyv.html

[M04] 获取当前工作目录
来源：http://dali.feifeiyinyue.top/Article/details/gtwlhueclr.html

Py:   os.getcwd()
来源：http://dali.c1oappe.top/Article/details/gtxnjyiakw.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gtvzunxpqp.html

JS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtkwaewoyu.html

TS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gtzdpbljci.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hywenlv.cn/Article/details/gtajamimtu.html

Go:   os.Getwd()
来源：http://dali.tanke756.top/Article/details/gttgwobgum.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gtiikdnohg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zdqjudy.top/Article/details/gtwhhqnjqd.html

[M05] 设置退出码
来源：http://dali.316326.xyz/Article/details/gttdtjlojq.html

Py:   sys.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtpuavgbdg.html

PHP:  exit(1);
来源：http://dali.nwbrower.top/Article/details/gtgkozuwcl.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtltmjlumg.html

TS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtvggcrzla.html

Java: System.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtalsenjcm.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gtqkscetqr.html

Ruby: exit 1
来源：http://dali.svipenyu.cn/Article/details/gtgscgdpmd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenlongwang.top/Article/details/gtjzhkbzwu.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gtvulgimem.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gtslzphvrr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gtttexipzs.html

JS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtrbefjalk.html

TS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtilborpgi.html

Java: System.err.println("err")
来源：http://dali.smart0.xyz/Article/details/gtxwtopozt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuanzhike.top/Article/details/gtepaekjmv.html

Ruby: warn "err"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrafkueds.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guannengcc.top/Article/details/gtlihymcii.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gtpyseucjm.html

Py:   if __name__ == "__main__":
来源：http://dali.shzxlz.cn/Article/details/gtmbipxnil.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jianghu66.top/Article/details/gtkqgewsys.html

JS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gtckjqiuih.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtzdtkyjvd.html

Java: public static void main(String[] args)
来源：http://dali.jqgufenzy.top/Article/details/gtuksudloi.html

Go:   func main()
来源：http://dali.cucudq.cn/Article/details/gtvkxyxwhg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangtech.top/Article/details/gtutdcigny.html

C#:   static void Main(string[] args)
来源：http://dali.jianghu66.top/Article/details/gtoiprbtki.html

[M08] 获取系统与运行时信息
来源：http://dali.tian-w.cn/Article/details/gtukobjtxi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jlsjyb.cn/Article/details/gtusxyrzqt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guowangkeji.top/Article/details/gtbklngyar.html

JS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gtvsmgzktf.html

TS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gttlwivgsc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gzhubu.top/Article/details/gtcuivbrjs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gtrjvwqrpu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnxiangtu.top/Article/details/gtmmhvhcsu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ybcxt.top/Article/details/gtcnozjewn.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gttpuxhlgo.html

N. 数据结构与算法
来源：http://dali.sufxvd.cn/Article/details/gtbuhsmozx.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtvsgcoiqq.html

[N01] 二分查找（有序数组）
来源：http://dali.xziqi.cn/Article/details/gtbbifgyzu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtuuiprmvh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tian-w.cn/Article/details/gtaltogdnw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gtmjikowqw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gtjltpjurs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gthffpfdsz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtkbsozfet.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gttxhrchlp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtmdgfndgz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gtsqueaiah.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gthcnjlzzo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.snrcjt.cn/Article/details/gthpvndpiy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtfbmtszjn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtpftpepof.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sufxvd.cn/Article/details/gtkxrkdpqn.html

Go:   slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gtckiiuxac.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtemdmpukz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guannengcc.top/Article/details/gtrdzrpyuq.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gtxxutjbor.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gotoacloud.top/Article/details/gtouyqwvfl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jyoumei.cn/Article/details/gturqlrgdd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gtebjdlyok.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gtzuefvdka.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shzxlz.cn/Article/details/gtdpatiuyo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yonumen.top/Article/details/gtoywqtvor.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hnqzz.top/Article/details/gtkuhbzuqr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cqqwz.cn/Article/details/gtrfkvmtwd.html

[N04] 斐波那契数列
来源：http://dali.guannengcc.top/Article/details/gtfafiyphb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gtonjltjzz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gtymslqkag.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtqnttssvq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtpxoxqqmv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gzhubu.top/Article/details/gtqzafzkqi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuanzx.com/Article/details/gtoofopvni.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gtexrzdnwf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtwgkdepcc.html

[N05] 最大公约数
来源：http://dali.chenjidiqi.icu/Article/details/gtopefuvzn.html

Py:   math.gcd(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtlgzdunct.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xylfe.cn/Article/details/gthkekpgjl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gtmhrnufuq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtgulxeqxb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gtvfkbtghl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgufenzy.top/Article/details/gthpsextbb.html

Ruby: a.gcd(b)
来源：http://dali.pengpengdd.cyou/Article/details/gttrplswxe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gttvpwszqs.html

[N06] 判断回文字符串
来源：http://dali.aibaodan.cn/Article/details/gtuxutaomb.html

Py:   s == s[::-1]
来源：http://dali.xziqi.cn/Article/details/gtycrpzeeb.html

PHP:  $s === strrev($s);
来源：http://dali.shuidangran.top/Article/details/gtlzdpdson.html

JS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtlifevuth.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gthwrnyjai.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gtwsnbnyuv.html

Go:   // 双指针从两端比较
来源：http://dali.hnqzz.top/Article/details/gtetyxfrry.html

Ruby: s == s.reverse
来源：http://dali.bjfxy.top/Article/details/gtzumuvumz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gtbionzvcm.html

[N07] 两数之和（返回下标）
来源：http://dali.fengsongda.top/Article/details/gtvlyzlayb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.svipenyu.cn/Article/details/gtajlptlvs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gtsodwycxl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.316326.xyz/Article/details/gtmchkklvw.html

TS:   // 手写 Map<string, number>
来源：http://dali.meibo888.top/Article/details/gtrtcfcjqj.html

Java: // 手写 HashMap
来源：http://dali.jiagoushi.top/Article/details/gtcbuzyzev.html

Go:   // 手写 map[int]int
来源：http://dali.daria6918.cn/Article/details/gtwvyuilks.html

Ruby: // 手写 Hash
来源：http://dali.svipenyu.cn/Article/details/gtvxinmoay.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xylfe.cn/Article/details/gtfmmtigcb.html

[N08] 生成全排列
来源：http://dali.sufxvd.cn/Article/details/gtloklldrq.html

Py:   itertools.permutations(arr)
来源：http://dali.tanke756.top/Article/details/gtqoeeujgq.html

PHP:  // 手写递归交换
来源：http://dali.iojbl.cn/Article/details/gteefkyqgf.html

JS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtgdfkgjhz.html

TS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtjqlgsjcy.html

Java: // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtelblulyn.html

Go:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtkkmdctpf.html

Ruby: arr.permutation.to_a
来源：http://dali.pycfn.com/Article/details/gtokdumdoh.html

C#:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtfpgienjl.html

[N09] 栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtddtwfzfm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ydzc1.top/Article/details/gthxrwyxvm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtxgrblucc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtsrsdfhxn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhongyouzk.top/Article/details/gtkquaogfo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258888.top/Article/details/gtjcydumdp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxinkj.top/Article/details/gtcibdrdem.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtbdkfddmi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fengsongda.top/Article/details/gtcmxozdnn.html

[N10] 链表节点定义
来源：http://dali.jinghuilouyu.cn/Article/details/gthvoeckox.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hongshengwenyu.top/Article/details/gtkepbtovl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnyhfqdb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gtbyfcwlyr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shzxlz.cn/Article/details/gtqrburdkw.html

Java: class Node { int v; Node next; }
来源：http://dali.iojbl.cn/Article/details/gtdjvfvmxx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhongyouzk.top/Article/details/gtedksvkwr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zycfv.cn/Article/details/gtjfqnbcdq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jlsjyb.cn/Article/details/gtjmqqumez.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gtyltlyypg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xziqi.cn/Article/details/gtoqgzzaqj.html

PHP:  // 手写递归函数
来源：http://dali.xuanzx.com/Article/details/gtcxmxjjvx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gtkhltfruq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gtfsrrvocz.html

Java: // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtyxtjbacd.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojxbfrsv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gtimnsmtke.html

C#:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtyhzsdlkb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yangfankeji.com/Article/details/gtcbnaqggu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.dashuyun.cn/Article/details/gtshzhwjtl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgfzy.top/Article/details/gtzhiytcdk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gtuuwyeaue.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gtbjiqfyap.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gthaejnvti.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cashguo.top/Article/details/gtkfmpwpeg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tian-w.cn/Article/details/gtcahxdxcu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gtbyemdcwp.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdjtqzfu.html

O. 并发与异步
来源：http://dali.havefunace.top/Article/details/gtqjrbqvoi.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtedxmioxa.html

[O01] 启动一个线程
来源：http://dali.redwolf501.top/Article/details/gtytzgeoox.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.feifeiyinyue.top/Article/details/gtctdrijqp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sxryk.cn/Article/details/gteskcyclv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.havefunace.top/Article/details/gtqiyikdjt.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gtbrhzrscw.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigfzy.top/Article/details/gtjozvxglu.html

Go:   go f()
来源：http://dali.cqqwz.cn/Article/details/gtknmynubq.html

Ruby: Thread.new { f }
来源：http://dali.chenjidiqi.icu/Article/details/gtwnqpdewl.html

C#:   Task.Run(() => F());
来源：http://dali.c1oappe.top/Article/details/gtwpkkhrgd.html

[O02] 使用线程池
来源：http://dali.meibo888.top/Article/details/gtvkewbdpv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.svipenyu.cn/Article/details/gtxarssjuj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shangyingyoupin.top/Article/details/gtmreuqctp.html

JS:   // worker_threads 线程池
来源：http://dali.jlsjyb.cn/Article/details/gtoswmzfds.html

TS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gtaopzufvf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hywenlv.cn/Article/details/gtytwkutno.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhiwuduotai.top/Article/details/gtfwszyzyu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxuanxn.top/Article/details/gtwtgpgdvf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigfzy.top/Article/details/gtokmsjxrh.html

[O03] 加锁保护共享数据
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomcnqbfs.html

Py:   with lock: shared += 1
来源：http://dali.chenlongwang.top/Article/details/gtuijkshfz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cdnleiting.top/Article/details/gtcwhyncwt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.smart0.xyz/Article/details/gtxdfpbiee.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtbhbrvvqn.html

Java: synchronized (this) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gtazflgwsm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ybcxt.top/Article/details/gtggkdoyzd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pycfn.com/Article/details/gttgvrhkqv.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gtrcioglsp.html

[O04] 定义异步函数并等待
来源：http://dali.sysykeji.top/Article/details/gtfdfcsiiw.html

Py:   async def f():⏎    await g()
来源：http://dali.cqqwz.cn/Article/details/gtrletlpci.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cheryme.top/Article/details/gtjalytvyp.html

JS:   async function f() { await g(); }
来源：http://dali.iojbl.cn/Article/details/gtqmqygjth.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gtmzsvtecv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxuanxn.top/Article/details/gtzjnvcjge.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cucudq.cn/Article/details/gtwmhfrtyg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fzhhl.top/Article/details/gtddyaqkky.html

C#:   async Task F() { await G(); }
来源：http://dali.tianlin.xyz/Article/details/gtgtdzhhgq.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gtkilkcpon.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dianchejie.cn/Article/details/gtgkxzzdvj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yvedp.cn/Article/details/gtsrxcagfy.html

JS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtycxazqjg.html

TS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtxlsodcda.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.andypj.xyz/Article/details/gtfognxzvo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.aizwys.cn/Article/details/gtfburxxfe.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtnmdbeork.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tianlin.xyz/Article/details/gtzgswgytc.html

[O06] 使用进程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybfrekka.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cqqwz.cn/Article/details/gtqxmafban.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.0kj1m.cn/Article/details/gtaxsfsunt.html

JS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtnzzvwyyx.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gtaklrbqez.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hywenlv.cn/Article/details/gtasyvalbr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.316326.xyz/Article/details/gtpzhaxzsw.html

Ruby: // fork 块
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzerxtfc.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gtaninlqbe.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtshuqioyd.html

P. 常用工具函数
来源：http://dali.daxiang520.top/Article/details/gtpivoakmn.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtzpjznwla.html

[P01] 生成 UUID
来源：http://dali.shzxlz.cn/Article/details/gtmliegjgw.html

Py:   str(uuid.uuid4())
来源：http://dali.aibaodan.cn/Article/details/gtnggoaqco.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shuidangran.top/Article/details/gtwqnhmqqi.html

JS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gtnjntuzhv.html

TS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtrzmikvsb.html

Java: UUID.randomUUID().toString()
来源：http://dali.redwolf501.top/Article/details/gtzsiqcfhy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenzaomai.com/Article/details/gtctnzwyns.html

Ruby: SecureRandom.uuid
来源：http://dali.jianghu66.top/Article/details/gtikbjcghy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigufen.top/Article/details/gtilqrirki.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnanxdalu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shangyingyoupin.top/Article/details/gtmgdihjvx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shzxlz.cn/Article/details/gtfvswobbe.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258888.top/Article/details/gthjxfwnuc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.316326.xyz/Article/details/gthqmicptb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtfiidlhxm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhongyouzk.top/Article/details/gtxsfygsbl.html


<!-- 参考信息 -->