代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtaqwaxjek.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gtpetgptxe.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgelqkslz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.9152youxi.cn/Article/details/gtvqdtntrv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gtovjuaktz.html

[L04] 设置超时
来源：http://dali.jiagoushi.top/Article/details/gtyqvesmrf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yangfankeji.com/Article/details/gtpcnohkbg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fengsongda.top/Article/details/gtgaugvgwe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gtphtnyvro.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gtpletskie.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.c1oappe.top/Article/details/gtecdbsvje.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cdnleiting.top/Article/details/gtxkbdusjk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yueranfly.top/Article/details/gtffqvxwwn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gtticfcjrr.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gtcmcoduzx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.quarkkingdee.top/Article/details/gtbrlwjzll.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gttlczuxqk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtsclpipng.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gtpsssrffk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhengqikj.top/Article/details/gtxvlfnhxv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gtuesyrjrg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gtylbfvahh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqazmuybi.html

[L06] 解析响应为 JSON
来源：http://dali.dianchejie.cn/Article/details/gtitqreofn.html

Py:   resp.json()
来源：http://dali.wangdashe.top/Article/details/gtkdgxchaq.html

PHP:  json_decode($body, true);
来源：http://dali.hywenlv.cn/Article/details/gtrjjtaiwq.html

JS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtilkkpvum.html

TS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtsbxgknon.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtbgxvycxl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hammf.cn/Article/details/gtfpzxqkep.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gtnjwqfacd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fzhhl.top/Article/details/gtaqwbirhs.html

[L07] 处理 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gthapoyayw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gtmemxmafj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibbzhjxm.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtgojauvtb.html

TS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gtfrwfcdqd.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gtcdwltozm.html

Go:   resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gtonnawnkg.html

Ruby: resp.code.to_i
来源：http://dali.yueranfly.top/Article/details/gtjkxhbwsb.html

C#:   (int)resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gtqjpqtijq.html

[L08] 并发请求多个地址
来源：http://dali.shuidangran.top/Article/details/gtypheaygu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhiwuduotai.top/Article/details/gtftebtqlf.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gtqnyeoopu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtmxielpzt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtnifuxknj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yonumen.top/Article/details/gtxwrmhnjt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gtweswzlkb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.iojbl.cn/Article/details/gtmzsxlddc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhengqikj.top/Article/details/gtenrzvnia.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtvekhwklf.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangdashe.top/Article/details/gtifddximh.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtipxvtsmx.html

[M01] 读取命令行参数
来源：http://dali.aibaodan.cn/Article/details/gtagwtfbum.html

Py:   sys.argv[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtokrrryub.html

PHP:  $argv;  $argc;
来源：http://dali.snrcjt.cn/Article/details/gtxyeyghto.html

JS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gttogrgmob.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtwajypvjz.html

Java: args 数组（main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gtriealfpz.html

Go:   os.Args[1:]
来源：http://dali.aizwys.cn/Article/details/gtrzladsiq.html

Ruby: ARGV
来源：http://dali.hysaishi.cn/Article/details/gtahwyetnl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gthqrjhbrc.html

[M02] 读取环境变量
来源：http://dali.pycfn.com/Article/details/gtynkuhesd.html

Py:   os.environ.get("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtnhvjyhjm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtawudbbti.html

JS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtfvmpnjww.html

TS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gtmlsxusvm.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtedycbfvd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtppfgoozq.html

Ruby: ENV["HOME"]
来源：http://dali.yj202588.top/Article/details/gtyevltelg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gtbkfozwcq.html

[M03] 执行外部命令
来源：http://dali.aibaodan.cn/Article/details/gtiapayexr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwexendfs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tian-w.cn/Article/details/gtrvuanxar.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gtzptaztzs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtinofszrz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jiagoushi.top/Article/details/gthqfjyhys.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fzhhl.top/Article/details/gtrbuiyixw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tianlin.xyz/Article/details/gtxfgbrwff.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gtuvojztwe.html

[M04] 获取当前工作目录
来源：http://dali.aibaodan.cn/Article/details/gtoifwdgdh.html

Py:   os.getcwd()
来源：http://dali.birdmap.top/Article/details/gtkeahcaii.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gtbumxffko.html

JS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gtakzjjxai.html

TS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtkbxhnldg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sweek.top/Article/details/gtgxnxuqrw.html

Go:   os.Getwd()
来源：http://dali.cucudq.cn/Article/details/gtzlrwlrjj.html

Ruby: Dir.pwd
来源：http://dali.jinqigufen.top/Article/details/gtblgbiobg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgfzy.top/Article/details/gtrwnfbvjy.html

[M05] 设置退出码
来源：http://dali.wangdashe.top/Article/details/gtrdxryvyr.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtflssmftk.html

PHP:  exit(1);
来源：http://dali.daxiang520.top/Article/details/gtgtkxkpct.html

JS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtcjjctjxk.html

TS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtkskltgmv.html

Java: System.exit(1)
来源：http://dali.yvedp.cn/Article/details/gttholpyhw.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtschezkax.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtcvrtekqs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ybcxt.top/Article/details/gtvgaupqwb.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gtoaxcflwy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gtcrtaznoe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gtkikkecnq.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtmfqogwlp.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtrypybpvw.html

Java: System.err.println("err")
来源：http://dali.tian-w.cn/Article/details/gtgdjinnvn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nwbrower.top/Article/details/gtxdfthigp.html

Ruby: warn "err"
来源：http://dali.redwolf501.top/Article/details/gtoyzboxlo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jianghu66.top/Article/details/gtjjrcxfrz.html

[M07] 判断是否为主入口
来源：http://dali.yonumen.top/Article/details/gtngknpnhr.html

Py:   if __name__ == "__main__":
来源：http://dali.aibaodan.cn/Article/details/gtslytkjra.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gtxdqunnfo.html

JS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlejrhpgw.html

TS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtnpbhtwjs.html

Java: public static void main(String[] args)
来源：http://dali.zycfv.cn/Article/details/gtajqkiouw.html

Go:   func main()
来源：http://dali.hongshengwenyu.top/Article/details/gtulsxwfpn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdqmxana.html

C#:   static void Main(string[] args)
来源：http://dali.hysaishi.cn/Article/details/gtfxocqlto.html

[M08] 获取系统与运行时信息
来源：http://dali.ivvv.top/Article/details/gtsxakmgfl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shzxlz.cn/Article/details/gthglhlvwk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yangfankeji.com/Article/details/gtpelnivap.html

JS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtnzakimnc.html

TS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gtsumnzpid.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.c1oappe.top/Article/details/gtbrugxsir.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cheryme.top/Article/details/gtnfyimibi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gttgglnnwt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zdqjudy.top/Article/details/gtubmfjsnu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtysopuqya.html

N. 数据结构与算法
来源：http://dali.shzxlz.cn/Article/details/gtmlxairob.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtsoeteeuy.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzmscrcl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtxjodqgpm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ybcxt.top/Article/details/gtbfumpakv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gteydwuuua.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtqiwnqmex.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtxbixlmgu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtvnpdxhyw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jianghu66.top/Article/details/gtwnxcjojt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfbewvho.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.havefunace.top/Article/details/gtbezmnxib.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gtwxussaul.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvyjkzrc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtgymyvodp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gthvaxckpn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.vqdsnc.cn/Article/details/gtihyhhxdr.html

Go:   slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtrzrmytyk.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gtqjtcxuzc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtvovgjpzz.html

[N03] 快速排序（分治示例）
来源：http://dali.hongshengwenyu.top/Article/details/gtyzpckpne.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ehwqpu.com/Article/details/gtziejcens.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shuidangran.top/Article/details/gtjxpfzclj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gtnudclxin.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gtjelqsktj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sysykeji.top/Article/details/gttlbbbivc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.birdmap.top/Article/details/gtuitjlptr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.andypj.xyz/Article/details/gtfdifmxxn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sysykeji.top/Article/details/gtjtwkikmp.html

[N04] 斐波那契数列
来源：http://dali.yj20258.top/Article/details/gtaomxipni.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gtfgivxsmm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gtfagkxewx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gtyqnyxtif.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtpsgaxpqa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258.top/Article/details/gtpsadcgxn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.birdmap.top/Article/details/gtsltdnynj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gtuyndfikl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtufzdsqex.html

[N05] 最大公约数
来源：http://dali.hammf.cn/Article/details/gtzeuacxor.html

Py:   math.gcd(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtsbakvtct.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zycfv.cn/Article/details/gttbpapmqj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gtrycnuyhr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gtkblxmqri.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hongshengwenyu.top/Article/details/gtneczfcmj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yanxiufei.cn/Article/details/gtlrjseild.html

Ruby: a.gcd(b)
来源：http://dali.mhx1999.top/Article/details/gtoowfqwfl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hammf.cn/Article/details/gtbdoohpgt.html

[N06] 判断回文字符串
来源：http://dali.chenzaomai.com/Article/details/gtwrlkbzkv.html

Py:   s == s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gtfhnhhcee.html

PHP:  $s === strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gtnzyhlcrl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtobqwases.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcquwmfqv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jyoumei.cn/Article/details/gtjiurloir.html

Go:   // 双指针从两端比较
来源：http://dali.xinyue.icu/Article/details/gtqbjaeyqv.html

Ruby: s == s.reverse
来源：http://dali.sysykeji.top/Article/details/gtxmubujub.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gtdslfffof.html

[N07] 两数之和（返回下标）
来源：http://dali.xziqi.cn/Article/details/gtladuutyy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cucudq.cn/Article/details/gtqpuxfiuv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhongyouzk.top/Article/details/gtzqvkgzeo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258888.top/Article/details/gtvavenvem.html

TS:   // 手写 Map<string, number>
来源：http://dali.316326.xyz/Article/details/gtppooeoig.html

Java: // 手写 HashMap
来源：http://dali.hongshengwenyu.top/Article/details/gtfavmipjq.html

Go:   // 手写 map[int]int
来源：http://dali.pengpengdd.cyou/Article/details/gtjncckndt.html

Ruby: // 手写 Hash
来源：http://dali.9152youxi.cn/Article/details/gthufuinyw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shzxlz.cn/Article/details/gtssweacmm.html

[N08] 生成全排列
来源：http://dali.jqgufenzy.top/Article/details/gtgyxkyive.html

Py:   itertools.permutations(arr)
来源：http://dali.yj202588.top/Article/details/gteusxycvb.html

PHP:  // 手写递归交换
来源：http://dali.nanxinkj.top/Article/details/gtlwljgoeq.html

JS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtafcdlxmu.html

TS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtbjoeaiet.html

Java: // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtcbxvbgvc.html

Go:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtiflrafza.html

Ruby: arr.permutation.to_a
来源：http://dali.wangdashe.top/Article/details/gtdnudmqrc.html

C#:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtoccjztrz.html

[N09] 栈与队列
来源：http://dali.xuanzx.com/Article/details/gtnyyqqfkg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hammf.cn/Article/details/gtrvcbvtmt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhvvdatw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gttqoqpdtv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangshuangyany.cn/Article/details/gtqxwxrhbt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglahsmzk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sxryk.cn/Article/details/gtnkamvtpv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtikmfcjyn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shuidangran.top/Article/details/gtulhuxyvn.html

[N10] 链表节点定义
来源：http://dali.gaohongyu789.top/Article/details/gtjowqiusd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangdashe.top/Article/details/gtsycodqkt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ybcxt.top/Article/details/gtsytfkdoq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.vqdsnc.cn/Article/details/gtouupytxk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hywenlv.cn/Article/details/gtrpjbkyyl.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gtdraintye.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xylfe.cn/Article/details/gtadsgdasx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aizwys.cn/Article/details/gtwbgioqdw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ydzc1.top/Article/details/gtszwhftjl.html

[N11] 二叉树中序遍历
来源：http://dali.quarkkingdee.top/Article/details/gtuvghdqoz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cashguo.top/Article/details/gtlopnahne.html

PHP:  // 手写递归函数
来源：http://dali.hongshengwenyu.top/Article/details/gtlgzksecx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gtyhkbqewa.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gtpposbsnr.html

Java: // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtsiisjijm.html

Go:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtyxbkoeiu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yanxiufei.cn/Article/details/gtzdouatrs.html

C#:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gttwesyudn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.bjfxy.top/Article/details/gtvvhldkaz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ehwqpu.com/Article/details/gtukcexlft.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenjidiqi.icu/Article/details/gtwutwkzcl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtsykbvcbu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gthxjjapdr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gtstocdama.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigufen.top/Article/details/gtghcmneqx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtpurwfkjf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gttqpvymcu.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtcnpdyznf.html

O. 并发与异步
来源：http://dali.nanxuanxn.top/Article/details/gtacdxdcug.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgokwhgmp.html

[O01] 启动一个线程
来源：http://dali.shuidangran.top/Article/details/gtelvocidb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxuanxn.top/Article/details/gtlprtjjex.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tian-w.cn/Article/details/gtqrczmuhc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sufxvd.cn/Article/details/gtvvtvjwaa.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtlpzddejg.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangdashe.top/Article/details/gtsboyvhxx.html

Go:   go f()
来源：http://dali.aibaodan.cn/Article/details/gtqfkdoots.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gtplfxptsa.html

C#:   Task.Run(() => F());
来源：http://dali.9152youxi.cn/Article/details/gtpjvemalt.html

[O02] 使用线程池
来源：http://dali.aizwys.cn/Article/details/gthaiqlsfr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.andypj.xyz/Article/details/gtkmdzillv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shangyingyoupin.top/Article/details/gtapgeeqom.html

JS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gtbjbqgnyv.html

TS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gtzdhjrgfz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cheryme.top/Article/details/gtgygpstpo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjifjgyqe.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqgzghso.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.havefunace.top/Article/details/gtfwmffqfi.html

[O03] 加锁保护共享数据
来源：http://dali.gogol.net.cn/Article/details/gtpbxzolhd.html

Py:   with lock: shared += 1
来源：http://dali.hysaishi.cn/Article/details/gtyzslnriw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dashuyun.cn/Article/details/gtkighqluw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.kuanghao11.cn/Article/details/gtpgowgqny.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gtmvzmyswb.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgungvdg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gtuvzmxvrg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gtajzvhtde.html

C#:   lock (gate) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gtbxhphwcz.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtuzpltpgz.html

Py:   async def f():⏎    await g()
来源：http://dali.sufxvd.cn/Article/details/gtmqqhlwnw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigufen.top/Article/details/gttfjdjopl.html

JS:   async function f() { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gtwyhxqwlg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fengsongda.top/Article/details/gtjhxoaaut.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.iojbl.cn/Article/details/gtqhsnrple.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fengsongda.top/Article/details/gtdxfdbbdp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.c1oappe.top/Article/details/gtxwrfatdj.html

C#:   async Task F() { await G(); }
来源：http://dali.pengpengdd.cyou/Article/details/gttkaltnfi.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhiwuduotai.top/Article/details/gtmzxvbfib.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hammf.cn/Article/details/gtlldkaydy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hongshengwenyu.top/Article/details/gttjslmlmc.html

JS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gtzmeolygn.html

TS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwsqnbci.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.0kj1m.cn/Article/details/gtkdkzxpce.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.smart0.xyz/Article/details/gtuzmmauem.html

Ruby: threads.map(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtwottqyiw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrpdqnnw.html

[O06] 使用进程池
来源：http://dali.gogol.net.cn/Article/details/gtblyhqcmw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cheryme.top/Article/details/gtobbvlike.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xinyue.icu/Article/details/gtlavzgoyg.html

JS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gtqpkmyjmh.html

TS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gtkcdmimlv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sufxvd.cn/Article/details/gttsbvmify.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmaouiibn.html

Ruby: // fork 块
来源：http://dali.yvedp.cn/Article/details/gthwskmxgq.html

C#:   Parallel.For
来源：http://dali.hongshengwenyu.top/Article/details/gtwatbroin.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtosmcuhcd.html

P. 常用工具函数
来源：http://dali.cheryme.top/Article/details/gtexnpsiah.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gttchiujdu.html

[P01] 生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gtwndkarmj.html

Py:   str(uuid.uuid4())
来源：http://dali.shuidangran.top/Article/details/gtbgewibqu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zycfv.cn/Article/details/gtjbpncilf.html

JS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojnqyjeq.html


<!-- 参考信息 -->