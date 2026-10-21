代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.yj20258888.top/Article/details/gtryfexzhn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.svipenyu.cn/Article/details/gtmhdqeofj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwfxjhuc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtgyfzuapp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtmitwyuvb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.snrcjt.cn/Article/details/gtbajeutrn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gtnqtmvxhx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sufxvd.cn/Article/details/gtslnbonxd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gthvysuutl.html

[L04] 设置超时
来源：http://dali.dashuyun.cn/Article/details/gtusmgddun.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guowangkeji.top/Article/details/gtggduuywo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.mhx1999.top/Article/details/gtzmupksmf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtbcwzkdup.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtvmpluaaj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtehwpunmg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sxryk.cn/Article/details/gtwmprzhpq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.redwolf501.top/Article/details/gtffhdjuck.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tianlin.xyz/Article/details/gtdxoccclq.html

[L05] 上传文件（multipart）
来源：http://dali.daria6918.cn/Article/details/gtulntzibg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigufen.top/Article/details/gtivkfpqph.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gtbhciwgjn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtkvtxvnnv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtwaetzbhy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zycfv.cn/Article/details/gtoiphkixd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.iojbl.cn/Article/details/gtlotzwoqi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhixingplan.top/Article/details/gtfpmjkjdh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daria6918.cn/Article/details/gtqliluxlp.html

[L06] 解析响应为 JSON
来源：http://dali.yj202588.top/Article/details/gttesvssdc.html

Py:   resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtfqnjyscc.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258.top/Article/details/gtmgmzpsol.html

JS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gtjzwgston.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtylofqssw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtpjqxqkcg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ppjwa.cn/Article/details/gtszkciejt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gtzxmipypq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.bjfxy.top/Article/details/gtusbrnvyx.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtmnypifnj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gtmaptjosc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yangfankeji.com/Article/details/gtmbbuwoax.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtbmgvsntf.html

TS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gtcyxohyon.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcehiljlw.html

Go:   resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtmgtmxcdp.html

Ruby: resp.code.to_i
来源：http://dali.daxiang520.top/Article/details/gtjjykxufh.html

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gttbfqjouu.html

[L08] 并发请求多个地址
来源：http://dali.hnqzz.top/Article/details/gtaabelbyp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hammf.cn/Article/details/gtbmsgcbzp.html

PHP:  curl_multi_init() 系列
来源：http://dali.gaohongyu789.top/Article/details/gtgxodfftd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtyroppeoc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtlfycvsgo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hywenlv.cn/Article/details/gtfglfriuw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gtctgqfsqr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gtmuirvgdu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gtomgmdutf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtyjuqszjr.html

M. 命令行 / 进程 / 环境
来源：http://dali.zycfv.cn/Article/details/gtdvcxwxil.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmfylmqct.html

[M01] 读取命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtnektvtmo.html

Py:   sys.argv[1:]
来源：http://dali.zdqjudy.top/Article/details/gtlkvomjzr.html

PHP:  $argv;  $argc;
来源：http://dali.haohaochexian.top/Article/details/gtznqnoemn.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtulpvlkjo.html

TS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtlczbgozs.html

Java: args 数组（main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gtliumwwum.html

Go:   os.Args[1:]
来源：http://dali.bjfxy.top/Article/details/gtybdvngef.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesehxvdl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtygapzmxx.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtirdnwmmw.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gtjspjfpel.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtfrkqybnp.html

JS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtnbakztfi.html

TS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtboerthlp.html

Java: System.getenv("HOME")
来源：http://dali.mhx1999.top/Article/details/gtiliqjlri.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hammf.cn/Article/details/gtsxuiwtld.html

Ruby: ENV["HOME"]
来源：http://dali.ywan-chungtsiang.top/Article/details/gterbsupyf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zycfv.cn/Article/details/gtnzudqvnj.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gtcwfwttcr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gtoavgyfcq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.316326.xyz/Article/details/gtgjzsrefq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtuexyamyg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gtwvehcrsj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangshuangyany.cn/Article/details/gtqgdcsudx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258.top/Article/details/gtnxbsznyf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.316326.xyz/Article/details/gtpmwftcnx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gtzosqggmm.html

[M04] 获取当前工作目录
来源：http://dali.andypj.xyz/Article/details/gthsqdviww.html

Py:   os.getcwd()
来源：http://dali.zhongyouzk.top/Article/details/gtazplinyj.html

PHP:  getcwd();
来源：http://dali.jlsjyb.cn/Article/details/gtzxvehonb.html

JS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gtrdyhtwaf.html

TS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtmlmsasyw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cdnleiting.top/Article/details/gtgwkadsfw.html

Go:   os.Getwd()
来源：http://dali.nanxuanxn.top/Article/details/gtqjzxrpli.html

Ruby: Dir.pwd
来源：http://dali.zhoulong.xyz/Article/details/gtvqhhmngo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.meibo888.top/Article/details/gtropzedsi.html

[M05] 设置退出码
来源：http://dali.9152youxi.cn/Article/details/gtszxlvvxi.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtoxesvuna.html

PHP:  exit(1);
来源：http://dali.hnqzz.top/Article/details/gtocvhphey.html

JS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtetkmbgtg.html

TS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtwwwfuway.html

Java: System.exit(1)
来源：http://dali.tanke756.top/Article/details/gtphfkafne.html

Go:   os.Exit(1)
来源：http://dali.xuanzx.com/Article/details/gtkwcoxmcb.html

Ruby: exit 1
来源：http://dali.tian-w.cn/Article/details/gtpztpxhkp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhongyouzk.top/Article/details/gtqxqiypvu.html

[M06] 向标准错误输出
来源：http://dali.hnqzz.top/Article/details/gtftykkqal.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gtgkqjwegw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhixingplan.top/Article/details/gthepiyojg.html

JS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gtvsxsxzas.html

TS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtxwuporpq.html

Java: System.err.println("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnduzsbr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gogol.net.cn/Article/details/gtboegxcfs.html

Ruby: warn "err"
来源：http://dali.sysykeji.top/Article/details/gtgdlogjcu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tanke756.top/Article/details/gtqsizsjkp.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gtspwgxfbk.html

Py:   if __name__ == "__main__":
来源：http://dali.cheryme.top/Article/details/gthxmudhxu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aizwys.cn/Article/details/gtsylmyxyp.html

JS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gtsznxihjl.html

TS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtlkpeuzyg.html

Java: public static void main(String[] args)
来源：http://dali.hywenlv.cn/Article/details/gtxoqftzyo.html

Go:   func main()
来源：http://dali.xziqi.cn/Article/details/gtvtllptqg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gtmqjpqbzh.html

C#:   static void Main(string[] args)
来源：http://dali.snrcjt.cn/Article/details/gtvpzwbodk.html

[M08] 获取系统与运行时信息
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrjaopns.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hammf.cn/Article/details/gtfmqwupby.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxvffpzk.html

JS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gtubuosvxs.html

TS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gtjvrfjlud.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jianghu66.top/Article/details/gtqlzidwhr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gtpwkkdusr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ivvv.top/Article/details/gtvsjdrgva.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gtxbnjxsdd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtipzvowut.html

N. 数据结构与算法
来源：http://dali.cucudq.cn/Article/details/gtyhxuobvr.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtgadhdcwo.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gtygndnloi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtgltdrjvu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqbqnken.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtnolngbtc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtlkcnoaac.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtnetxlnxx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtpxqurhow.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hfpthk.cn/Article/details/gtihipoxog.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtzcrtmiwo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hammf.cn/Article/details/gtiaporbzc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gtmqkiwlkc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guannengcc.top/Article/details/gtbrfrazoz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtfazyyyud.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfcdklbt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.vqdsnc.cn/Article/details/gthectnusk.html

Go:   slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtajzwbcsp.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gteegzzxll.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xinyue.icu/Article/details/gtajchqlim.html

[N03] 快速排序（分治示例）
来源：http://dali.xuetiantiany.cn/Article/details/gtelmrcroq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj202588.top/Article/details/gtcrlxrzfh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cheryme.top/Article/details/gtjsnffbwl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gtxxnsyzhf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtiwevmxmy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangdashe.top/Article/details/gtakalkogx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jiagoushi.top/Article/details/gtyuhvboaj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gtpzbsgjwk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dashuyun.cn/Article/details/gtrjocmkgz.html

[N04] 斐波那契数列
来源：http://dali.shangyingyoupin.top/Article/details/gtpbsyckxv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gtifcxkxyn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtnivffjac.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtwwxczsdb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtstloqxsh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gtaelonnvd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shzxlz.cn/Article/details/gtkrptpctt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gtkvpszexz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtihnfbwds.html

[N05] 最大公约数
来源：http://dali.cqqwz.cn/Article/details/gtqsfxwapt.html

Py:   math.gcd(a, b)
来源：http://dali.pycfn.com/Article/details/gtrhqdxfqr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.quarkkingdee.top/Article/details/gthmhwkrct.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gtqugtjmuz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtcxjfybvv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuanzhike.top/Article/details/gteewwczha.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtexlwmnes.html

Ruby: a.gcd(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtxlytmkdc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daria6918.cn/Article/details/gtydgpesrl.html

[N06] 判断回文字符串
来源：http://dali.jinqigufen.top/Article/details/gtcmvnurnl.html

Py:   s == s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gttdfuiszr.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckiqfekf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtazzirsit.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtcbpqgkus.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cashguo.top/Article/details/gtkzoivtnh.html

Go:   // 双指针从两端比较
来源：http://dali.zhoulong.xyz/Article/details/gteopkdlao.html

Ruby: s == s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtiutztrek.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gtdkckpnko.html

[N07] 两数之和（返回下标）
来源：http://dali.aizwys.cn/Article/details/gtrdauzdqj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxinkj.top/Article/details/gttgphyphy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pengpengdd.cyou/Article/details/gtucmspcaq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hongshengwenyu.top/Article/details/gtjqiciiek.html

TS:   // 手写 Map<string, number>
来源：http://dali.andypj.xyz/Article/details/gtpplaphew.html

Java: // 手写 HashMap
来源：http://dali.hysaishi.cn/Article/details/gtziwjutjb.html

Go:   // 手写 map[int]int
来源：http://dali.meibo888.top/Article/details/gtfgulwucd.html

Ruby: // 手写 Hash
来源：http://dali.zhiwuduotai.top/Article/details/gtcfdlvrkh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolaimjlc.html

[N08] 生成全排列
来源：http://dali.andypj.xyz/Article/details/gttqxeihop.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtfjzqegqc.html

PHP:  // 手写递归交换
来源：http://dali.cdnleiting.top/Article/details/gtictrekwi.html

JS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtvkmueegp.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtxgiqocut.html

Java: // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtbhfxnyfh.html

Go:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtikvwrlti.html

Ruby: arr.permutation.to_a
来源：http://dali.fengsongda.top/Article/details/gtwlfzgdcu.html

C#:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtkveceefl.html

[N09] 栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gtoqynqqdh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangdashe.top/Article/details/gtgnrcqdba.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gtdjjouamm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gtqwrmczoe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cheryme.top/Article/details/gtzfosrajx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.snrcjt.cn/Article/details/gtpmayyfha.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gtvptlbfbd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtxgazrnzn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnonnbkx.html

[N10] 链表节点定义
来源：http://dali.xinyue.icu/Article/details/gtufqgmtsz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.andypj.xyz/Article/details/gtranwocbs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsmhxfuuu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hnxiangtu.top/Article/details/gtnbsgutzx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gtmqnyjqsb.html

Java: class Node { int v; Node next; }
来源：http://dali.sxryk.cn/Article/details/gtfhufmsge.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cdnleiting.top/Article/details/gtmmdtapbb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258.top/Article/details/gthovolopz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxuanxn.top/Article/details/gtdisluqns.html

[N11] 二叉树中序遍历
来源：http://dali.tian-w.cn/Article/details/gtpqhqrlmh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnxiangtu.top/Article/details/gtbuicvlqx.html

PHP:  // 手写递归函数
来源：http://dali.zhiwuduotai.top/Article/details/gtvinivdna.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtmdlxsnvr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gtujxbozab.html

Java: // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtcdzbpjmu.html

Go:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gtpmcemebt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sysykeji.top/Article/details/gtmpcfroyl.html

C#:   // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gteznyuqow.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.svipenyu.cn/Article/details/gtlvimjooy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yangfankeji.com/Article/details/gtfzbjdeim.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.0kj1m.cn/Article/details/gtqzhspcym.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gtmafgtcde.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gtqrtpzmja.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtbyzqlgiw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jyoumei.cn/Article/details/gtdnclfspk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxinkj.top/Article/details/gtwizsnxqm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gtcjtipgpk.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtarghuqns.html

O. 并发与异步
来源：http://dali.smart0.xyz/Article/details/gthmgasmrg.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtsbuopotb.html

[O01] 启动一个线程
来源：http://dali.cucudq.cn/Article/details/gtereokkml.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtjqmpubtd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fzhhl.top/Article/details/gthirnlvni.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj202588.top/Article/details/gthebxodwe.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtmwxqtdzt.html

Java: new Thread(() -> f()).start()
来源：http://dali.xylfe.cn/Article/details/gtoiabryin.html

Go:   go f()
来源：http://dali.zhixingplan.top/Article/details/gtubjjlwxp.html

Ruby: Thread.new { f }
来源：http://dali.smart0.xyz/Article/details/gthfxwjdun.html

C#:   Task.Run(() => F());
来源：http://dali.svipenyu.cn/Article/details/gtysdfeumu.html

[O02] 使用线程池
来源：http://dali.zhoulong.xyz/Article/details/gtnduoxmbr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.vqdsnc.cn/Article/details/gtxeltkiic.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.feifeiyinyue.top/Article/details/gtcjiwexek.html

JS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gtfcriqyzw.html

TS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gtnfygbboh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gogol.net.cn/Article/details/gtiicnnnfs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xylfe.cn/Article/details/gtnhgknrpk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.birdmap.top/Article/details/gtowqmkyuf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.c1oappe.top/Article/details/gtuhwgokjk.html

[O03] 加锁保护共享数据
来源：http://dali.zhiwuduotai.top/Article/details/gtfqeosqwp.html

Py:   with lock: shared += 1
来源：http://dali.pycfn.com/Article/details/gtsajtpjsa.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenlongwang.top/Article/details/gtzuvvnbrc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daria6918.cn/Article/details/gtjndntvaq.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtcyetwbzk.html

Java: synchronized (this) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gtwpccktbd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dianchejie.cn/Article/details/gtwhimjznp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gtggzonbgr.html

C#:   lock (gate) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gtynevavqu.html

[O04] 定义异步函数并等待
来源：http://dali.yueranfly.top/Article/details/gtgicrvhxq.html

Py:   async def f():⏎    await g()
来源：http://dali.yvedp.cn/Article/details/gtsjndugao.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shuidangran.top/Article/details/gtwwhhxcpf.html

JS:   async function f() { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtghfaujuk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkwmkosc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gotoacloud.top/Article/details/gtocwyacld.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258.top/Article/details/gtldqoaixr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jlsjyb.cn/Article/details/gtcexfznjo.html

C#:   async Task F() { await G(); }
来源：http://dali.ybcxt.top/Article/details/gtgizohcmq.html

[O05] 并发执行并等待全部完成
来源：http://dali.cashguo.top/Article/details/gtfzofmrmx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtdhboswzs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hnqzz.top/Article/details/gthvkpfeey.html

JS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gtxmzcvigc.html

TS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gtmddavldc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ybcxt.top/Article/details/gtwqabvbfc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gtrxfwprrn.html

Ruby: threads.map(&:join)
来源：http://dali.yvedp.cn/Article/details/gtcguixhjq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gtfafdbfec.html

[O06] 使用进程池
来源：http://dali.nanxinkj.top/Article/details/gtyuxeylnw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258.top/Article/details/gtmvahzsyb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuxming.cn/Article/details/gttlmrdnpt.html

JS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gthspcvnaa.html

TS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gthsjnifxm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.mhx1999.top/Article/details/gtnknakjtu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xinyue.icu/Article/details/gtvfczfiao.html

Ruby: // fork 块
来源：http://dali.0kj1m.cn/Article/details/gtewzzztxu.html

C#:   Parallel.For
来源：http://dali.chenlongwang.top/Article/details/gtxudqlhnh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtgyhiphul.html

P. 常用工具函数
来源：http://dali.zhengqikj.top/Article/details/gtrgkuhyuv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtrvspkuaw.html


<!-- 参考信息 -->