代发 wailian999

Go:   encoding/gob
来源：http://dali.hnxiangtu.top/Article/details/gt2utehaixa.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qqlmzuou.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gt2zjlbgqcj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2adarzusf.html

L. 网络请求
来源：http://dali.316326.xyz/Article/details/gt2sklarrer.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2hgowquhq.html

[L01] 发送 GET 请求
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vrldweaq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigfzy.top/Article/details/gt2kktjgkrb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ivvv.top/Article/details/gt2wcvfmuyk.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gt2gdyjzhvk.html

TS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gt2guinadtx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ehwqpu.com/Article/details/gt2tqhjmsag.html

Go:   resp, err := http.Get(url)
来源：http://dali.9152youxi.cn/Article/details/gt2hdwxupmk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gaohongyu789.top/Article/details/gt2nkwkiawl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hammf.cn/Article/details/gt2wlhzmlub.html

[L02] 发送 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gt2gyzcijmt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gt2kqrdofty.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xylfe.cn/Article/details/gt2jttjurjz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gt2hwbwsmbq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gt2owlbpbyz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daria6918.cn/Article/details/gt2hedfirsc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.svipenyu.cn/Article/details/gt2hturhtrh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gt2wwyvumiz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jlsjyb.cn/Article/details/gt2hjuufqrt.html

[L03] 设置自定义请求头
来源：http://dali.svipenyu.cn/Article/details/gt2mbmgkwje.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gt2enahqttt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gt2idjgvava.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gt2rpeatbbh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gt2gyxolxwx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gt2xzgnwbpn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gt2bndgijze.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yvedp.cn/Article/details/gt2bsrwaavw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gt2vholqpcv.html

[L04] 设置超时
来源：http://dali.yangfankeji.com/Article/details/gt2gpqpnfer.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jiagoushi.top/Article/details/gt2ddwqjyeu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yangfankeji.com/Article/details/gt2roqwlsls.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gt2hytzcgyt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gt2djsauckf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fengsongda.top/Article/details/gt2qmfxexpk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shuidangran.top/Article/details/gt2qsqhmtjs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhixingplan.top/Article/details/gt2kisxajcf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.havefunace.top/Article/details/gt2sdaybfna.html

[L05] 上传文件（multipart）
来源：http://dali.zhengqikj.top/Article/details/gt2gkfwflkd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jiagoushi.top/Article/details/gt2bzaejhga.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ydzc1.top/Article/details/gt2ogjeryrj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gt2aliftvgz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gt2bthqtwwi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lhtrinup.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhixingplan.top/Article/details/gt2nllrdhaq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gt2hlmqyydh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2vqulytzh.html

[L06] 解析响应为 JSON
来源：http://dali.quarkkingdee.top/Article/details/gt2hvzflvgx.html

Py:   resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gt2hefewejk.html

PHP:  json_decode($body, true);
来源：http://dali.gogol.net.cn/Article/details/gt2fswvsvwg.html

JS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gt2aaexlfaq.html

TS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gt2jngqrrdt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gt2ehcxlvkt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fengsongda.top/Article/details/gt2gsshosxe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdaetqnp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.mhx1999.top/Article/details/gt2polydqhh.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gwtfcnui.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guowangkeji.top/Article/details/gt2gjeaxbpu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pycfn.com/Article/details/gt2pwkauazl.html

JS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gt2jdlnjboi.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gt2gfspkhmq.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gt2udynfero.html

Go:   resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gt2ycdpqkkh.html

Ruby: resp.code.to_i
来源：http://dali.andypj.xyz/Article/details/gt2tqzbqmjw.html

C#:   (int)resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpzewrpt.html

[L08] 并发请求多个地址
来源：http://dali.shangyingyoupin.top/Article/details/gt2wheqtgql.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ivvv.top/Article/details/gt2mhpxmpop.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2qaauezjs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gt2kvtwmmfu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2jxcffgkj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tanke756.top/Article/details/gt2ruwuelaq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gt2takoqegd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gt2oayuyjdv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ivvv.top/Article/details/gt2vnqcecrx.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2asonosjc.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gt2htosezwr.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ugvlktdv.html

[M01] 读取命令行参数
来源：http://dali.iojbl.cn/Article/details/gt2ezqsrwxo.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gt2biezhvvl.html

PHP:  $argv;  $argc;
来源：http://dali.jqgufenzy.top/Article/details/gt2eqrlzjfy.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gt2zbbeexbn.html

TS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgcrntlr.html

Java: args 数组（main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gt2tybyhssa.html

Go:   os.Args[1:]
来源：http://dali.sysykeji.top/Article/details/gt2lzvqmulz.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gt2fudjgmqu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpcsubum.html

[M02] 读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gt2bqwysgzq.html

Py:   os.environ.get("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2ouzdrdbv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gt2uqcavyar.html

JS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gt2qsrsxnsz.html

TS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gt2qmwuhpzj.html

Java: System.getenv("HOME")
来源：http://dali.havefunace.top/Article/details/gt2hsjwczpb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wnugyjcq.html

Ruby: ENV["HOME"]
来源：http://dali.chenlongwang.top/Article/details/gt2modczbmt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2nupndpou.html

[M03] 执行外部命令
来源：http://dali.yuanzhike.top/Article/details/gt2cqcztucb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gt2nhuaqxgp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gt2btgtzfiw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gt2tljqxllk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gt2qgbiqamr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hongshengwenyu.top/Article/details/gt2warmgukp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.9152youxi.cn/Article/details/gt2lkfjlmar.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xziqi.cn/Article/details/gt2mkuyjtzr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenjidiqi.icu/Article/details/gt2aoruxubs.html

[M04] 获取当前工作目录
来源：http://dali.aibaodan.cn/Article/details/gt2wtrveycw.html

Py:   os.getcwd()
来源：http://dali.yuxming.cn/Article/details/gt2bkpvpycc.html

PHP:  getcwd();
来源：http://dali.yangfankeji.com/Article/details/gt2jdwwpmxk.html

JS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gt2fcmrcdwz.html

TS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gt2qoiijqgq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnqzz.top/Article/details/gt2rfgtjluf.html

Go:   os.Getwd()
来源：http://dali.shuidangran.top/Article/details/gt2ltalrjjt.html

Ruby: Dir.pwd
来源：http://dali.yj202588.top/Article/details/gt2nngonsfq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ydzc1.top/Article/details/gt2hcrslgwp.html

[M05] 设置退出码
来源：http://dali.snrcjt.cn/Article/details/gt2gckpxzzx.html

Py:   sys.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2cuapplob.html

PHP:  exit(1);
来源：http://dali.hnqzz.top/Article/details/gt2kbcikvpt.html

JS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2iftlypvn.html

TS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gt2kbjwjrhj.html

Java: System.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kpzcpjsl.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2etehzxus.html

Ruby: exit 1
来源：http://dali.tanke756.top/Article/details/gt2seakhuxi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.birdmap.top/Article/details/gt2bqlvxkvm.html

[M06] 向标准错误输出
来源：http://dali.hysaishi.cn/Article/details/gt2stwyiagq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gt2khupmlbl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ppjwa.cn/Article/details/gt2jfwkumgu.html

JS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gt2hhrdtdtq.html

TS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gt2rzgmyfcg.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gt2efvseohn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.c1oappe.top/Article/details/gt2dyzejpep.html

Ruby: warn "err"
来源：http://dali.zhixingplan.top/Article/details/gt2kvrkfniu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cucudq.cn/Article/details/gt2cbjixhco.html

[M07] 判断是否为主入口
来源：http://dali.nanxuanxn.top/Article/details/gt2mcucdvbh.html

Py:   if __name__ == "__main__":
来源：http://dali.hnqzz.top/Article/details/gt2yaggivos.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shzxlz.cn/Article/details/gt2nobpruah.html

JS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gt2ppbtloka.html

TS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gt2wkkpfmme.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvadtmva.html

Go:   func main()
来源：http://dali.yongpay.top/Article/details/gt2xokpdikl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.feifeiyinyue.top/Article/details/gt2lpvvnxkc.html

C#:   static void Main(string[] args)
来源：http://dali.sweek.top/Article/details/gt2cpruaycn.html

[M08] 获取系统与运行时信息
来源：http://dali.cdnleiting.top/Article/details/gt2pxhphyds.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cheryme.top/Article/details/gt2fmymdrym.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.0kj1m.cn/Article/details/gt2nuemtzso.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gt2fhraknmi.html

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gt2xrbgyvla.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gt2esibzwyr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xinyue.icu/Article/details/gt2eqoymhge.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pengpengdd.cyou/Article/details/gt2mzqugfbj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gt2acwlbrhe.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2ogfvlslo.html

N. 数据结构与算法
来源：http://dali.guannengcc.top/Article/details/gt2xodyzbew.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2jrajkmel.html

[N01] 二分查找（有序数组）
来源：http://dali.gzhubu.top/Article/details/gt2brqfkbcu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2antpwkkk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2muydwvnv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gt2mvavqpif.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ysuwolzo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2ahvxqoma.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2lqoztwzm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.vqdsnc.cn/Article/details/gt2lamqcxtb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2xvcmbzqg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bkozuyvf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gt2lsuphhcr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sufxvd.cn/Article/details/gt2kzzmmqid.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gt2sxnorkio.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gt2aamxwsrw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnqzz.top/Article/details/gt2mvsklflj.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2xcjkzofp.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gccbgreh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2cktugjsx.html

[N03] 快速排序（分治示例）
来源：http://dali.guowangkeji.top/Article/details/gt2thdfbvdd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxinkj.top/Article/details/gt2egvovzgj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yueranfly.top/Article/details/gt2zhwrhecz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gt2dztsxkot.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gt2dhiinpgf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gt2saanqdxr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2igjmjjus.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.c1oappe.top/Article/details/gt2hoqtemel.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuxming.cn/Article/details/gt2cngpkkwv.html

[N04] 斐波那契数列
来源：http://dali.hysaishi.cn/Article/details/gt2oudkcltg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bozutfui.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gt2sxwvlysr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gt2ehnqkzka.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2cjtgcxkw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gt2hjmptfyd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yvedp.cn/Article/details/gt2xyrozpun.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gt2ltqubong.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xgbpusbx.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gt2fbplmtax.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zntrlwjb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258.top/Article/details/gt2euhwrtmw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gt2fkgnvwfh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gt2bbuskfmj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ehwqpu.com/Article/details/gt2lughsaot.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guannengcc.top/Article/details/gt2njhhklaq.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gt2wkrcsnbt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.9152youxi.cn/Article/details/gt2kubnljow.html

[N06] 判断回文字符串
来源：http://dali.sufxvd.cn/Article/details/gt2pyjtcxzo.html

Py:   s == s[::-1]
来源：http://dali.cheryme.top/Article/details/gt2wrjvwmmi.html

PHP:  $s === strrev($s);
来源：http://dali.smart0.xyz/Article/details/gt2mthmkguf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hvnfuyqw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2npduzunx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cashguo.top/Article/details/gt2yfsvifzh.html

Go:   // 双指针从两端比较
来源：http://dali.hnqzz.top/Article/details/gt2rseofrmx.html

Ruby: s == s.reverse
来源：http://dali.daxiang520.top/Article/details/gt2atzgpnky.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gt2qzcfgyez.html

[N07] 两数之和（返回下标）
来源：http://dali.redwolf501.top/Article/details/gt2bpxmsnbp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.meibo888.top/Article/details/gt2svkpxseb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfbkbscs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ppjwa.cn/Article/details/gt2fhrpften.html

TS:   // 手写 Map<string, number>
来源：http://dali.ivvv.top/Article/details/gt2qjzigfyb.html

Java: // 手写 HashMap
来源：http://dali.yuanzhike.top/Article/details/gt2xdggrftc.html

Go:   // 手写 map[int]int
来源：http://dali.zhixingplan.top/Article/details/gt2egrafwun.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gt2nvmymald.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.c1oappe.top/Article/details/gt2tfwcjitt.html

[N08] 生成全排列
来源：http://dali.iojbl.cn/Article/details/gt2dxfevmja.html

Py:   itertools.permutations(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ktdbkirr.html

PHP:  // 手写递归交换
来源：http://dali.zhixingplan.top/Article/details/gt2satmxdeu.html

JS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2welehcfh.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2nsgtneqz.html

Java: // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2qaoczvky.html

Go:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2lavpstem.html

Ruby: arr.permutation.to_a
来源：http://dali.mhx1999.top/Article/details/gt2tyoueifv.html

C#:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2jbkqvokm.html

[N09] 栈与队列
来源：http://dali.yuanzhike.top/Article/details/gt2tdnzxarp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fengsongda.top/Article/details/gt2lwzhabri.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangdashe.top/Article/details/gt2acfwqcvx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gt2tcafpwfi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dashuyun.cn/Article/details/gt2gzedhxqe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.svipenyu.cn/Article/details/gt2hkpnidor.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258.top/Article/details/gt2hnwxlvfm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2ayjobgmt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ybcxt.top/Article/details/gt2fcoqwvba.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gt2kyhrkjdg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.mhx1999.top/Article/details/gt2kogujeye.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jhicunje.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdjkuekt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.mhx1999.top/Article/details/gt2hwljzfmy.html

Java: class Node { int v; Node next; }
来源：http://dali.zdqjudy.top/Article/details/gt2flabcuhb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ehwqpu.com/Article/details/gt2obmlhxyk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tianlin.xyz/Article/details/gt2hfjgxdlc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xinyue.icu/Article/details/gt2snnslqvy.html

[N11] 二叉树中序遍历
来源：http://dali.smart0.xyz/Article/details/gt2jujdehgq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuanzx.com/Article/details/gt2jcpcmnuk.html

PHP:  // 手写递归函数
来源：http://dali.jlsjyb.cn/Article/details/gt2hijtdpns.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gt2rpeqcwbf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gt2mfzojcrd.html

Java: // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gt2jtqxtbsf.html

Go:   // 手写递归
来源：http://dali.xylfe.cn/Article/details/gt2verjikky.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yongpay.top/Article/details/gt2oxlttqir.html

C#:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gt2uzhfqxst.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhengqikj.top/Article/details/gt2jcspfgrv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ehwqpu.com/Article/details/gt2nlxellfy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xylfe.cn/Article/details/gt2csjnyhwn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gt2ovalcrym.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gt2gxxugtek.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gt2ivptpbja.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dashuyun.cn/Article/details/gt2jhryhueu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gt2jxmymswr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gt2shzftkpj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2eankualt.html

O. 并发与异步
来源：http://dali.jyoumei.cn/Article/details/gt2wjyqltrg.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2lbjnvtno.html

[O01] 启动一个线程
来源：http://dali.ybcxt.top/Article/details/gt2jwzetfux.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hywenlv.cn/Article/details/gt2wlkghlsy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhixingplan.top/Article/details/gt2vxcrlyin.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hywenlv.cn/Article/details/gt2lqqichgd.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gt2ccsonceb.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2mooodmta.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gt2ovaiahtp.html

Ruby: Thread.new { f }
来源：http://dali.ppjwa.cn/Article/details/gt2nuaswmus.html

C#:   Task.Run(() => F());
来源：http://dali.birdmap.top/Article/details/gt2pobuqjkv.html

[O02] 使用线程池
来源：http://dali.meibo888.top/Article/details/gt2nehluzci.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258888.top/Article/details/gt2mkvvgfds.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.iojbl.cn/Article/details/gt2hgxisfum.html

JS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gt2tdubcywy.html

TS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gt2qnapytsi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yueranfly.top/Article/details/gt2dizkxbyv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ivvv.top/Article/details/gt2bzkjdocy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xinyue.icu/Article/details/gt2aedxkqsm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.vqdsnc.cn/Article/details/gt2ahpukevf.html

[O03] 加锁保护共享数据
来源：http://dali.daxiang520.top/Article/details/gt2utyikqvl.html

Py:   with lock: shared += 1
来源：http://dali.9152youxi.cn/Article/details/gt2riycxwfs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nanxuanxn.top/Article/details/gt2jwqqnywi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xziqi.cn/Article/details/gt2zpvttzxa.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gt2ahfuepci.html

Java: synchronized (this) { shared++; }
来源：http://dali.cashguo.top/Article/details/gt2ckifgyqs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cashguo.top/Article/details/gt2clfefgam.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pjajsfnv.html

C#:   lock (gate) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gt2mqqvquab.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cafrjuqr.html

Py:   async def f():⏎    await g()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bkcnswwl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.mhx1999.top/Article/details/gt2snxkwpgr.html

JS:   async function f() { await g(); }
来源：http://dali.birdmap.top/Article/details/gt2bwjckphv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gt2teuhvuhk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xylfe.cn/Article/details/gt2qmcpiush.html


<!-- 参考信息 -->