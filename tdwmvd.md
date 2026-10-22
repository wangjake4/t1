代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnxiangtu.top/Article/details/gt2bjrcmpmz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vymuywbs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gt2kfutefit.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.bjfxy.top/Article/details/gt2mdpeqocv.html

[L03] 设置自定义请求头
来源：http://dali.zhengqikj.top/Article/details/gt2qnusszhb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigufen.top/Article/details/gt2nevgzhmj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuanzhike.top/Article/details/gt2alvwgfbt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gt2odtykgde.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gt2vrntwidl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yvedp.cn/Article/details/gt2bhpfsznn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gt2scfripcz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnxiangtu.top/Article/details/gt2nfbucjzg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gt2unvuqruz.html

[L04] 设置超时
来源：http://dali.xuanzx.com/Article/details/gt2ofynmbsn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zycfv.cn/Article/details/gt2piytsswk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2omtzvcic.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2poipfhxx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gt2ioamwtiu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xylfe.cn/Article/details/gt2couqbobf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cheryme.top/Article/details/gt2qdupnpgf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aibaodan.cn/Article/details/gt2qvujjnuq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dianchejie.cn/Article/details/gt2kcgdneju.html

[L05] 上传文件（multipart）
来源：http://dali.xziqi.cn/Article/details/gt2sptydres.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigfzy.top/Article/details/gt2svffuyaz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jyoumei.cn/Article/details/gt2irfzfzzg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gt2xshhzdhz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gt2jvgsurem.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jyoumei.cn/Article/details/gt2koqhtcwq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guannengcc.top/Article/details/gt2zeberhbi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhongyouzk.top/Article/details/gt2eqjzofqo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2amuzmnsj.html

[L06] 解析响应为 JSON
来源：http://dali.wangshuangyany.cn/Article/details/gt2xrfyejmg.html

Py:   resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2npzzvvjb.html

PHP:  json_decode($body, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2axnabozy.html

JS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gt2ogssquun.html

TS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gt2jgzkyrrn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2isrydnmf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuanzhike.top/Article/details/gt2bbyrhvyz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xziqi.cn/Article/details/gt2wcpzdtpl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xinyue.icu/Article/details/gt2phfsytiy.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gt2rykgwxau.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxinkj.top/Article/details/gt2fijhzvrn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.wangdashe.top/Article/details/gt2bllyjbzh.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gt2awetvdst.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gt2qovixldh.html

Java: resp.statusCode()
来源：http://dali.jyoumei.cn/Article/details/gt2scqkmgio.html

Go:   resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gt2lwstmkht.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgioodz.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gt2ijcvzqew.html

[L08] 并发请求多个地址
来源：http://dali.fzhhl.top/Article/details/gt2vvmgyubu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxuanxn.top/Article/details/gt2kbuwlkmw.html

PHP:  curl_multi_init() 系列
来源：http://dali.iojbl.cn/Article/details/gt2xakyyxav.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gt2tezatalr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gt2rsnmlfko.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenzaomai.com/Article/details/gt2vbwryeyk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gt2gllncsap.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gt2uzckdvys.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pycfn.com/Article/details/gt2mbvxbfim.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2iwfcbtjs.html

M. 命令行 / 进程 / 环境
来源：http://dali.vqdsnc.cn/Article/details/gt2wswfhpla.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2cmdaxkab.html

[M01] 读取命令行参数
来源：http://dali.haohaochexian.top/Article/details/gt2euqiltlf.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gt2dgmjlhap.html

PHP:  $argv;  $argc;
来源：http://dali.hammf.cn/Article/details/gt2klrhzqos.html

JS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gt2vqzslvsv.html

TS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jzedmeno.html

Java: args 数组（main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjwzgdmw.html

Go:   os.Args[1:]
来源：http://dali.quarkkingdee.top/Article/details/gt2cqtdvzar.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2brromkzw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gt2uhbjxnwr.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ykckjgru.html

Py:   os.environ.get("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2yvnbuhkp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gt2cbtvniad.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gt2homuzwfb.html

TS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gt2eatnlmev.html

Java: System.getenv("HOME")
来源：http://dali.sweek.top/Article/details/gt2iwaztkvv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yvedp.cn/Article/details/gt2brwpouil.html

Ruby: ENV["HOME"]
来源：http://dali.jianghu66.top/Article/details/gt2oxipftmx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2dwqjmipp.html

[M03] 执行外部命令
来源：http://dali.sufxvd.cn/Article/details/gt2twdrxfom.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.316326.xyz/Article/details/gt2mzdbdxyv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gt2dlzfbjut.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gt2hzehrbgj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gt2kojluqbw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gt2sqsspjfh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.mhx1999.top/Article/details/gt2szssflqu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jlsjyb.cn/Article/details/gt2kpqliwfz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenlongwang.top/Article/details/gt2oxjkbksc.html

[M04] 获取当前工作目录
来源：http://dali.dashuyun.cn/Article/details/gt2rlsbuwru.html

Py:   os.getcwd()
来源：http://dali.cheryme.top/Article/details/gt2alrrbrdx.html

PHP:  getcwd();
来源：http://dali.xylfe.cn/Article/details/gt2wapbgalt.html

JS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gt2madqigfn.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gt2nrdcgpmm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guowangkeji.top/Article/details/gt2ilcakqki.html

Go:   os.Getwd()
来源：http://dali.tian-w.cn/Article/details/gt2qtyypizb.html

Ruby: Dir.pwd
来源：http://dali.quarkkingdee.top/Article/details/gt2ykgicbqv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shuidangran.top/Article/details/gt2zhmxfmvh.html

[M05] 设置退出码
来源：http://dali.ybcxt.top/Article/details/gt2rtfyzkdh.html

Py:   sys.exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2csjgphqy.html

PHP:  exit(1);
来源：http://dali.tianlin.xyz/Article/details/gt2lefznnhp.html

JS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2tijjbxnq.html

TS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2mqjqwzdw.html

Java: System.exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2jnfpasdw.html

Go:   os.Exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2tzdyidlv.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gt2agomyswq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gogol.net.cn/Article/details/gt2hkdjlxtv.html

[M06] 向标准错误输出
来源：http://dali.hnxiangtu.top/Article/details/gt2sclhspva.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gt2wptiwvkl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gaohongyu789.top/Article/details/gt2jvvzhcfr.html

JS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gt2vxrvfbuh.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gt2ajlixtth.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gt2gezblinr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jiagoushi.top/Article/details/gt2lxviqzfp.html

Ruby: warn "err"
来源：http://dali.jianghu66.top/Article/details/gt2xaesfzxt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cdnleiting.top/Article/details/gt2dpttwnmg.html

[M07] 判断是否为主入口
来源：http://dali.birdmap.top/Article/details/gt2qwhuqyti.html

Py:   if __name__ == "__main__":
来源：http://dali.dianchejie.cn/Article/details/gt2huiwiigy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xziqi.cn/Article/details/gt2vqzasvnz.html

JS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gt2qrjybgxt.html

TS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gt2qwvofdfy.html

Java: public static void main(String[] args)
来源：http://dali.havefunace.top/Article/details/gt2lslcmdvi.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gt2sxmkbghi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenlongwang.top/Article/details/gt2duqsomow.html

C#:   static void Main(string[] args)
来源：http://dali.zdqjudy.top/Article/details/gt2qlmdzagk.html

[M08] 获取系统与运行时信息
来源：http://dali.xuanzx.com/Article/details/gt2okubayqk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.snrcjt.cn/Article/details/gt2korplhgl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ivvv.top/Article/details/gt2minkyszr.html

JS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gt2cozkaofj.html

TS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gt2jgvddmeg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yonumen.top/Article/details/gt2zdyanstv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pengpengdd.cyou/Article/details/gt2adegomhi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zdqjudy.top/Article/details/gt2ktabryuy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yueranfly.top/Article/details/gt2mjvsfhzk.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2oaimeokn.html

N. 数据结构与算法
来源：http://dali.0kj1m.cn/Article/details/gt2jndwlune.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2vbrevxqh.html

[N01] 二分查找（有序数组）
来源：http://dali.hysaishi.cn/Article/details/gt2fchzgfvs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2imnklxne.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hysaishi.cn/Article/details/gt2mzvvwqpf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gt2xyfyuapb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gt2leknjaif.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2ngylwakq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2tlrokpds.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.0kj1m.cn/Article/details/gt2iyrgszzu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2xdwwilmg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangdashe.top/Article/details/gt2zwffhcij.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gt2hcxczova.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigufen.top/Article/details/gt2kwepwzzg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gt2ruhqvjua.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gt2mixgcqew.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gt2mnesngnp.html

Go:   slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2zrvkoqsv.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gt2xxfbgink.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ivvv.top/Article/details/gt2bqjvjkpj.html

[N03] 快速排序（分治示例）
来源：http://dali.yueranfly.top/Article/details/gt2xdlfsxne.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigfzy.top/Article/details/gt2zypwahlz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhongyouzk.top/Article/details/gt2yrydmehq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gt2yejwkpph.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gt2ewlayfwo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yvedp.cn/Article/details/gt2nhftrqud.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xziqi.cn/Article/details/gt2jmnoltby.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuanzhike.top/Article/details/gt2knrotofn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daria6918.cn/Article/details/gt2mkupuqbx.html

[N04] 斐波那契数列
来源：http://dali.xziqi.cn/Article/details/gt2lgzifvbt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gt2dnevcxeg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cvcvlyzh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gt2fidmvlpz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gt2ztvdgeel.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gt2qhtovbsr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhengqikj.top/Article/details/gt2kmmnpqou.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2mdjwnwkk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2xvehzfmv.html

[N05] 最大公约数
来源：http://dali.tianlin.xyz/Article/details/gt2igakhjns.html

Py:   math.gcd(a, b)
来源：http://dali.cdnleiting.top/Article/details/gt2rdaaewhb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sweek.top/Article/details/gt2yqfkxfzc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gt2zctimwxe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gt2wnzbqife.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yueranfly.top/Article/details/gt2vocaigtb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnxiangtu.top/Article/details/gt2aieiupdk.html

Ruby: a.gcd(b)
来源：http://dali.ivvv.top/Article/details/gt2izcopoof.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.iojbl.cn/Article/details/gt2rxjamfxv.html

[N06] 判断回文字符串
来源：http://dali.cqqwz.cn/Article/details/gt2mcdoxqfh.html

Py:   s == s[::-1]
来源：http://dali.iojbl.cn/Article/details/gt2jmtfgbiy.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bstmkdps.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2fyilrtlh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gt2kkrceaap.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jlsjyb.cn/Article/details/gt2lbfhovsu.html

Go:   // 双指针从两端比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ruhujmzm.html

Ruby: s == s.reverse
来源：http://dali.tianlin.xyz/Article/details/gt2rfcgmkdv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gt2euyxznog.html

[N07] 两数之和（返回下标）
来源：http://dali.ivvv.top/Article/details/gt2winxgmyk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.andypj.xyz/Article/details/gt2pnfevltg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jyoumei.cn/Article/details/gt2esvuxjdw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2krkolpao.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangdashe.top/Article/details/gt2svqanjrl.html

Java: // 手写 HashMap
来源：http://dali.cqqwz.cn/Article/details/gt2hitlplel.html

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gt2ruhuhscw.html

Ruby: // 手写 Hash
来源：http://dali.hywenlv.cn/Article/details/gt2fcsfhlhg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.bjfxy.top/Article/details/gt2jsdbphdz.html

[N08] 生成全排列
来源：http://dali.cdnleiting.top/Article/details/gt2ezqdporp.html

Py:   itertools.permutations(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2dvwwnnvn.html

PHP:  // 手写递归交换
来源：http://dali.yangfankeji.com/Article/details/gt2zfkrugju.html

JS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2sstggpuf.html

TS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2ihxfjyrq.html

Java: // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2dphdfdrc.html

Go:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2cpgwcoqn.html

Ruby: arr.permutation.to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qhkdjwqh.html

C#:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2ebanortp.html

[N09] 栈与队列
来源：http://dali.xinyue.icu/Article/details/gt2vpsuoshy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gt2gdyofvoz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fengsongda.top/Article/details/gt2wrfrumwn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2jjpxiwoh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgufenzy.top/Article/details/gt2xpobxyij.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.birdmap.top/Article/details/gt2xknscdze.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jianghu66.top/Article/details/gt2tllunpyl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2glsjfsrd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sxryk.cn/Article/details/gt2xwrhadhi.html

[N10] 链表节点定义
来源：http://dali.hysaishi.cn/Article/details/gt2gljmpldy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gt2xbtvsabs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenlongwang.top/Article/details/gt2xyvxgtoq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tanke756.top/Article/details/gt2anfmjvqj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guowangkeji.top/Article/details/gt2ewzaoxhg.html

Java: class Node { int v; Node next; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kviskmnw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gt2kmcmpacf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xinyue.icu/Article/details/gt2ufzpkfzx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gndlldzp.html

[N11] 二叉树中序遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qhapoqjv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fzhhl.top/Article/details/gt2rnchvmdm.html

PHP:  // 手写递归函数
来源：http://dali.sxryk.cn/Article/details/gt2hzomfeil.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zijiihdn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2fngbxcxt.html

Java: // 手写递归
来源：http://dali.havefunace.top/Article/details/gt2qvttxphg.html

Go:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gt2rajlddhe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shangyingyoupin.top/Article/details/gt2qefmkjvi.html

C#:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gt2xjeqznss.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yanxiufei.cn/Article/details/gt2eoexkjra.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sxryk.cn/Article/details/gt2hzzyfcpr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yonumen.top/Article/details/gt2pulqqihm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gt2tlxafhck.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gt2qyzwxaka.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gbhkinek.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pycfn.com/Article/details/gt2advrlvxn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pycfn.com/Article/details/gt2xgdfkqbr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gt2nsqngbnn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdhkiwrn.html

O. 并发与异步
来源：http://dali.birdmap.top/Article/details/gt2qotnwcev.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2hgeydjbj.html

[O01] 启动一个线程
来源：http://dali.dianchejie.cn/Article/details/gt2hwhphcaj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tian-w.cn/Article/details/gt2sjiywnyo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yangfankeji.com/Article/details/gt2xcdydakh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shangyingyoupin.top/Article/details/gt2dqupupxa.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gt2ernianxv.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgfzy.top/Article/details/gt2qwnzeksb.html

Go:   go f()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhcmjtie.html

Ruby: Thread.new { f }
来源：http://dali.hywenlv.cn/Article/details/gt2fgkghjlm.html

C#:   Task.Run(() => F());
来源：http://dali.zdqjudy.top/Article/details/gt2xtvrbkfm.html

[O02] 使用线程池
来源：http://dali.xuanzx.com/Article/details/gt2uhrhvolm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnwbvqlw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigfzy.top/Article/details/gt2acijhspm.html

JS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gt2exzzfvnp.html

TS:   // worker_threads 线程池
来源：http://dali.chenjidiqi.icu/Article/details/gt2daypopej.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fzhhl.top/Article/details/gt2jqxsfbdo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.havefunace.top/Article/details/gt2fogluedm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pycfn.com/Article/details/gt2ssaavzcf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tian-w.cn/Article/details/gt2sqpxzvfl.html

[O03] 加锁保护共享数据
来源：http://dali.xuanzx.com/Article/details/gt2exnhzszs.html

Py:   with lock: shared += 1
来源：http://dali.nwbrower.top/Article/details/gt2xeyqzyhb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.9152youxi.cn/Article/details/gt2nyfswjcy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.vqdsnc.cn/Article/details/gt2yincgbgh.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thjcvlpw.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258.top/Article/details/gt2dwyytagl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuxming.cn/Article/details/gt2rpagkhrf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.smart0.xyz/Article/details/gt2oogpbbbi.html

C#:   lock (gate) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2slpnjwmu.html

[O04] 定义异步函数并等待
来源：http://dali.zycfv.cn/Article/details/gt2njarpvze.html

Py:   async def f():⏎    await g()
来源：http://dali.yj202588.top/Article/details/gt2uyrcnaqy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daria6918.cn/Article/details/gt2vaqdjxjh.html

JS:   async function f() { await g(); }
来源：http://dali.yj202588.top/Article/details/gt2drmhdfni.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2yzvrlvxv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yangfankeji.com/Article/details/gt2vstghpgd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.316326.xyz/Article/details/gt2ikdjxpmg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.aibaodan.cn/Article/details/gt2ouruaaxt.html

C#:   async Task F() { await G(); }
来源：http://dali.hysaishi.cn/Article/details/gt2zkyivxhy.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgufenzy.top/Article/details/gt2fusybugf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2wonxozfk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenjidiqi.icu/Article/details/gt2imoyxnxt.html

JS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gt2skhyvxqm.html

TS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gt2ffufcoqz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zycfv.cn/Article/details/gt2dmrpyesx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jianghu66.top/Article/details/gt2yibtbfjh.html

Ruby: threads.map(&:join)
来源：http://dali.jyoumei.cn/Article/details/gt2xjqwhapk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.smart0.xyz/Article/details/gt2wdhqzwtv.html

[O06] 使用进程池
来源：http://dali.hammf.cn/Article/details/gt2fmdvttfe.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ppjwa.cn/Article/details/gt2cmxlxdxd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jzofwkaz.html

JS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gt2omgudmoj.html

TS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gt2ossaffav.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hysaishi.cn/Article/details/gt2xkrxevlt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gaohongyu789.top/Article/details/gt2irktaswm.html

Ruby: // fork 块
来源：http://dali.gzhubu.top/Article/details/gt2dexlmbnb.html


<!-- 参考信息 -->