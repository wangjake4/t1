代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhixingplan.top/Article/details/gt2nbyynwce.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhiwuduotai.top/Article/details/gt2jsrrxwzv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigufen.top/Article/details/gt2txxknazf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258.top/Article/details/gt2qbwbsege.html

[L03] 设置自定义请求头
来源：http://dali.sufxvd.cn/Article/details/gt2ysiyglka.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenlongwang.top/Article/details/gt2vdsvdqey.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yonumen.top/Article/details/gt2bsaptlbz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gt2qdcsdfni.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gt2ijiinaht.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigufen.top/Article/details/gt2tszyqlnv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmovfbhk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhengqikj.top/Article/details/gt2qigxqcti.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gt2jblrqksg.html

[L04] 设置超时
来源：http://dali.redwolf501.top/Article/details/gt2quvablnw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cheryme.top/Article/details/gt2pgpkjbka.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cdnleiting.top/Article/details/gt2kvffvovg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gt2stspabmc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gt2bxsizarb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yangfankeji.com/Article/details/gt2qijmdrxl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gt2kdrpytsz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hammf.cn/Article/details/gt2nacvasya.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.smart0.xyz/Article/details/gt2acrmiing.html

[L05] 上传文件（multipart）
来源：http://dali.fengsongda.top/Article/details/gt2tfjaihwf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gt2xqcsiszl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jyoumei.cn/Article/details/gt2rfxhiecu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2cstqzdqc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gt2mrrdmuvl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pengpengdd.cyou/Article/details/gt2ccrtxrql.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yanxiufei.cn/Article/details/gt2dtmecgzr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pengpengdd.cyou/Article/details/gt2pplsydfn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2sbmndzxf.html

[L06] 解析响应为 JSON
来源：http://dali.sufxvd.cn/Article/details/gt2zrgjswfy.html

Py:   resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2vqleoekz.html

PHP:  json_decode($body, true);
来源：http://dali.yj202588.top/Article/details/gt2hfeavuzs.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2vdqayfmu.html

TS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gt2uwlwtnzv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2afpqhsne.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gaohongyu789.top/Article/details/gt2xxaggfyr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gogol.net.cn/Article/details/gt2kiemekgy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yangfankeji.com/Article/details/gt2yhdrdial.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gt2xxvgqczt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gzhubu.top/Article/details/gt2gedzsbub.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj202588.top/Article/details/gt2uubqubfo.html

JS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gt2brwosknz.html

TS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gt2tsbekmxf.html

Java: resp.statusCode()
来源：http://dali.cqqwz.cn/Article/details/gt2fxymayff.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gt2qlrjdtoa.html

Ruby: resp.code.to_i
来源：http://dali.daxiang520.top/Article/details/gt2osuznxno.html

C#:   (int)resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gt2gwimddfi.html

[L08] 并发请求多个地址
来源：http://dali.xinyue.icu/Article/details/gt2yfwvincs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shzxlz.cn/Article/details/gt2vmvemznk.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xwpzrxxt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gt2fyraedos.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gt2psnlmogr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yangfankeji.com/Article/details/gt2sugxcrqj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgfzy.top/Article/details/gt2hkyvpiiu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zeqhiaex.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gt2lshthhog.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2nbuvlqaa.html

M. 命令行 / 进程 / 环境
来源：http://dali.ivvv.top/Article/details/gt2pufftxaa.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2dyyvqjvh.html

[M01] 读取命令行参数
来源：http://dali.yj202588.top/Article/details/gt2tqsgvkik.html

Py:   sys.argv[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2onsbfkin.html

PHP:  $argv;  $argc;
来源：http://dali.kuanghao11.cn/Article/details/gt2jovcgfyh.html

JS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gt2reaaascf.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gt2nlamvnmz.html

Java: args 数组（main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gt2htwdatak.html

Go:   os.Args[1:]
来源：http://dali.jianghu66.top/Article/details/gt2oxiisxeq.html

Ruby: ARGV
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awmdzkjj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gt2ucwudnme.html

[M02] 读取环境变量
来源：http://dali.redwolf501.top/Article/details/gt2rhhragbq.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2gshsuvmi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gt2gfbjoipx.html

JS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gt2rmnzmzzc.html

TS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gt2bduswzmi.html

Java: System.getenv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2uxcbrlty.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2xmbawtwf.html

Ruby: ENV["HOME"]
来源：http://dali.fengsongda.top/Article/details/gt2idmybvtq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gt2gcejwrov.html

[M03] 执行外部命令
来源：http://dali.cashguo.top/Article/details/gt2dckxnyoc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xinyue.icu/Article/details/gt2albwbplr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2byvgdqtb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gt2ijmzqedl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2eszflbjw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yvedp.cn/Article/details/gt2pusdqxrm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fengsongda.top/Article/details/gt2ghgkujww.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenlongwang.top/Article/details/gt2ivshincw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pengpengdd.cyou/Article/details/gt2nlyymgpn.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gt2gprlosgw.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2pfyvxvhm.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2rebsxcel.html

JS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjkzyauf.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2twtymciv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yonumen.top/Article/details/gt2ahmypiox.html

Go:   os.Getwd()
来源：http://dali.jyoumei.cn/Article/details/gt2rykgmlyd.html

Ruby: Dir.pwd
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbcimojx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ydzc1.top/Article/details/gt2yrpgziyz.html

[M05] 设置退出码
来源：http://dali.dashuyun.cn/Article/details/gt2pnovagfh.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2pijklyyy.html

PHP:  exit(1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpuybsgd.html

JS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2ehdcklfl.html

TS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2rwsegbjp.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2zxokesxo.html

Go:   os.Exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2pjekzxmy.html

Ruby: exit 1
来源：http://dali.cashguo.top/Article/details/gt2qguyobko.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hongshengwenyu.top/Article/details/gt2szsilwpp.html

[M06] 向标准错误输出
来源：http://dali.zhongyouzk.top/Article/details/gt2rgdhtyuo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gt2vlkjrqun.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmvmpkil.html

JS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gt2vkumfabn.html

TS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gt2ahvfbqze.html

Java: System.err.println("err")
来源：http://dali.yj202588.top/Article/details/gt2fmvtekck.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhengqikj.top/Article/details/gt2pncdlyee.html

Ruby: warn "err"
来源：http://dali.ybcxt.top/Article/details/gt2owcokjgh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gt2xcvkdlvf.html

[M07] 判断是否为主入口
来源：http://dali.yanxiufei.cn/Article/details/gt2qqfnoiff.html

Py:   if __name__ == "__main__":
来源：http://dali.birdmap.top/Article/details/gt2horiptib.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zycfv.cn/Article/details/gt2ivwesljk.html

JS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gt2xnbttddo.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2uqiyugsf.html

Java: public static void main(String[] args)
来源：http://dali.xziqi.cn/Article/details/gt2qountjve.html

Go:   func main()
来源：http://dali.yvedp.cn/Article/details/gt2rycpiesj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daria6918.cn/Article/details/gt2ryswkisa.html

C#:   static void Main(string[] args)
来源：http://dali.daxiang520.top/Article/details/gt2eklrscii.html

[M08] 获取系统与运行时信息
来源：http://dali.tanke756.top/Article/details/gt2unfuzmqr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hammf.cn/Article/details/gt2aoamzzfv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenlongwang.top/Article/details/gt2ilqgzmun.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gt2xlyhjwya.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gt2wijapoxv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aibaodan.cn/Article/details/gt2noianzao.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gt2gjhtghfo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gt2zgwhvwur.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yanxiufei.cn/Article/details/gt2dupxrrry.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2qxbvjxzw.html

N. 数据结构与算法
来源：http://dali.xuetiantiany.cn/Article/details/gt2trgjstst.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2tuuprmgw.html

[N01] 二分查找（有序数组）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybsacvnw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2jxiwhyzh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zdqjudy.top/Article/details/gt2uricrueu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gt2xobzaiff.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gt2kdorbvol.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2ydqoudnb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2udhoxftk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gt2slxwiaoe.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2latvtwey.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.0kj1m.cn/Article/details/gt2xrqqpdmj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gt2kjrpigwn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hammf.cn/Article/details/gt2afhjfzgq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gt2uxnzzsmi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gt2ylfalikz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ppjwa.cn/Article/details/gt2sotkbrwg.html

Go:   slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gt2ozynrbtm.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gt2ybktexor.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xcuscfrw.html

[N03] 快速排序（分治示例）
来源：http://dali.jyoumei.cn/Article/details/gt2ktsqhpsj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjjavvcb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shzxlz.cn/Article/details/gt2naqeahru.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gt2xxdnxism.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gt2jbzevvhp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhengqikj.top/Article/details/gt2lixmppcz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnxiangtu.top/Article/details/gt2erbaqtkj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.meibo888.top/Article/details/gt2hdbckenf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gt2hmthlgmb.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gt2smfbwwfk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gt2dysgrerz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gt2rswzjwkb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gt2myzedeiz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gt2qawqownx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nefjazii.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gt2awxxhial.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gt2scekspqc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2uatuojre.html

[N05] 最大公约数
来源：http://dali.chenjidiqi.icu/Article/details/gt2kiucunwh.html

Py:   math.gcd(a, b)
来源：http://dali.yangfankeji.com/Article/details/gt2dfvtvhxf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sxryk.cn/Article/details/gt2dlearfdn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gt2rjakhoql.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gt2xauwuhcc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sufxvd.cn/Article/details/gt2nneecept.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.316326.xyz/Article/details/gt2aqwbngha.html

Ruby: a.gcd(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2knsffgvb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.mhx1999.top/Article/details/gt2migosofl.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gt2ynwwsjma.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gt2fhdllugb.html

PHP:  $s === strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2claozhyh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gt2lxrkbiqb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxaeprir.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cashguo.top/Article/details/gt2agepwsif.html

Go:   // 双指针从两端比较
来源：http://dali.xziqi.cn/Article/details/gt2cbfchuaw.html

Ruby: s == s.reverse
来源：http://dali.cdnleiting.top/Article/details/gt2fooautym.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yefqxuob.html

[N07] 两数之和（返回下标）
来源：http://dali.cheryme.top/Article/details/gt2ybaviodh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daxiang520.top/Article/details/gt2lfbsrdye.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj202588.top/Article/details/gt2ibtyojby.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sxryk.cn/Article/details/gt2wjrxmmop.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenlongwang.top/Article/details/gt2pmeqkrdy.html

Java: // 手写 HashMap
来源：http://dali.fengsongda.top/Article/details/gt2lgmtmkku.html

Go:   // 手写 map[int]int
来源：http://dali.nanxuanxn.top/Article/details/gt2kbhoznty.html

Ruby: // 手写 Hash
来源：http://dali.hnxiangtu.top/Article/details/gt2qoppckgn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj202588.top/Article/details/gt2itcuyvau.html

[N08] 生成全排列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aplazckh.html

Py:   itertools.permutations(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2lukwxcuw.html

PHP:  // 手写递归交换
来源：http://dali.shangyingyoupin.top/Article/details/gt2hzvqlwog.html

JS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2bsqknyxt.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2qctxofzs.html

Java: // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gt2opzbsowd.html

Go:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gt2tshwjiqo.html

Ruby: arr.permutation.to_a
来源：http://dali.wangdashe.top/Article/details/gt2cqpykndl.html

C#:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2ujbdnffj.html

[N09] 栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gt2scjjzyak.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sweek.top/Article/details/gt2gpftlmlm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gt2nvzftvaf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gt2ysvewone.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhengqikj.top/Article/details/gt2temywrxt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.redwolf501.top/Article/details/gt2zmcbsxup.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gt2bnjwfrbs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gt2nfxbmyfh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigufen.top/Article/details/gt2trgelplh.html

[N10] 链表节点定义
来源：http://dali.jqgufenzy.top/Article/details/gt2gwutbhrf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hysaishi.cn/Article/details/gt2piurhqdh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbvwgaxy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aibaodan.cn/Article/details/gt2lzhmfnah.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhoulong.xyz/Article/details/gt2reqwbkub.html

Java: class Node { int v; Node next; }
来源：http://dali.tianlin.xyz/Article/details/gt2notqrgfw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.vqdsnc.cn/Article/details/gt2hnqkpcjf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sysykeji.top/Article/details/gt2hcbhqadc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2amhmrvhp.html

[N11] 二叉树中序遍历
来源：http://dali.iojbl.cn/Article/details/gt2nuuvdxqm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yanxiufei.cn/Article/details/gt2uawngsyj.html

PHP:  // 手写递归函数
来源：http://dali.ppjwa.cn/Article/details/gt2cfzrumyq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gt2mmjcwjmn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gt2izfuyucr.html

Java: // 手写递归
来源：http://dali.yongpay.top/Article/details/gt2yaxvoayj.html

Go:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zpsnphnd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tanke756.top/Article/details/gt2ptzfekwx.html

C#:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gt2ghoqthmw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fengsongda.top/Article/details/gt2dbtmbdsn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daria6918.cn/Article/details/gt2lpwolbvv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xylfe.cn/Article/details/gt2mvwjrbiq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gt2mvadnoza.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gt2kcjctikp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gt2kapglaki.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangdashe.top/Article/details/gt2lzdeuttv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daria6918.cn/Article/details/gt2hwlkjlyj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gt2cddfispk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2mivncurx.html

O. 并发与异步
来源：http://dali.yj202588.top/Article/details/gt2potqjxbd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2jvkvlyau.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gt2xfpqhcjp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xinyue.icu/Article/details/gt2kndxqjcn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sxryk.cn/Article/details/gt2bogquesx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cucudq.cn/Article/details/gt2obtfslpa.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gt2ztkexlxe.html

Java: new Thread(() -> f()).start()
来源：http://dali.ydzc1.top/Article/details/gt2myfqkdfd.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gt2hlowvtlv.html

Ruby: Thread.new { f }
来源：http://dali.316326.xyz/Article/details/gt2hiaxvfmd.html

C#:   Task.Run(() => F());
来源：http://dali.birdmap.top/Article/details/gt2iatrnfea.html

[O02] 使用线程池
来源：http://dali.wangshuangyany.cn/Article/details/gt2dyfvunfc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rcathlxq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbnascev.html

JS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gt2cbpyffjc.html

TS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gt2bygqavjs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fengsongda.top/Article/details/gt2tqyfhaxx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.quarkkingdee.top/Article/details/gt2jxlusipu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daria6918.cn/Article/details/gt2xlimjyav.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhixingplan.top/Article/details/gt2cmzcmqrt.html

[O03] 加锁保护共享数据
来源：http://dali.dianchejie.cn/Article/details/gt2qlyujyxh.html

Py:   with lock: shared += 1
来源：http://dali.chenzaomai.com/Article/details/gt2byxqoyfh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.0kj1m.cn/Article/details/gt2uqltzbde.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gogol.net.cn/Article/details/gt2stedqjsk.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gt2jxuxnbhs.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gt2psowyaiq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gaohongyu789.top/Article/details/gt2rnvqlvyw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.smart0.xyz/Article/details/gt2bswthinq.html

C#:   lock (gate) { shared++; }
来源：http://dali.yongpay.top/Article/details/gt2pxgsyxrz.html

[O04] 定义异步函数并等待
来源：http://dali.shangyingyoupin.top/Article/details/gt2huemigxq.html

Py:   async def f():⏎    await g()
来源：http://dali.xziqi.cn/Article/details/gt2ldkxwnrk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinghuilouyu.cn/Article/details/gt2afbhiyvp.html

JS:   async function f() { await g(); }
来源：http://dali.ivvv.top/Article/details/gt2xgjmsiwz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gt2dfnnojgm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgfzy.top/Article/details/gt2ybeooqlo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aibaodan.cn/Article/details/gt2afzleipc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhixingplan.top/Article/details/gt2xcblnxnx.html

C#:   async Task F() { await G(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2dyzindkw.html

[O05] 并发执行并等待全部完成
来源：http://dali.dianchejie.cn/Article/details/gt2zhwoypih.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fengsongda.top/Article/details/gt2pqhekzek.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ybcxt.top/Article/details/gt2pyqauzqf.html

JS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gt2dszaeyfm.html

TS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gt2xpomsfva.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj202588.top/Article/details/gt2lrzhehay.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xziqi.cn/Article/details/gt2mnwlscit.html

Ruby: threads.map(&:join)
来源：http://dali.mhx1999.top/Article/details/gt2woaiohqz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hywenlv.cn/Article/details/gt2wotyynjp.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqwlkzec.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tian-w.cn/Article/details/gt2yucsytws.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ehwqpu.com/Article/details/gt2ormsluny.html

JS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gt2nxfdmtbt.html

TS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gt2jxstykbl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vhwwjcyp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gt2toxkgtte.html

Ruby: // fork 块
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfrohfmn.html


<!-- 参考信息 -->