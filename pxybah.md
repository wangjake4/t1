代发 wailian999

Go:   encoding/gob
来源：http://dali.nwbrower.top/Article/details/gtvfhfvpgy.html

Ruby: Marshal.dump(obj)
来源：http://dali.iojbl.cn/Article/details/gtqdrlxbdi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtvstimxvk.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjztyayxf.html

L. 网络请求
来源：http://dali.dashuyun.cn/Article/details/gtrzhtrltc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtcscokfus.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gtnctvwokn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.c1oappe.top/Article/details/gttzfbcytt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daria6918.cn/Article/details/gtuafzdnlu.html

JS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtahuqbcrd.html

TS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gtfpclhidz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daria6918.cn/Article/details/gtfgwgclii.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gtraxixciv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhongyouzk.top/Article/details/gtlzfemqzb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aizwys.cn/Article/details/gtuptsjejl.html

[L02] 发送 POST JSON
来源：http://dali.tanke756.top/Article/details/gtrkfluxqq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gtvnjlrryw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.andypj.xyz/Article/details/gtluwqiupn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtxnlydsdl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtzmtvxavr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fzhhl.top/Article/details/gtqruvnhbh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shzxlz.cn/Article/details/gtyvjcwgka.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.snrcjt.cn/Article/details/gtxlqnitpq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.haohaochexian.top/Article/details/gtczoyuqqe.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gtrnbagffm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guowangkeji.top/Article/details/gtueaooltg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhengqikj.top/Article/details/gtnrsqyojq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gtxhqhyxiw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtwxozxewp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shangyingyoupin.top/Article/details/gttnxcowyp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gtnhvaagfn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhixingplan.top/Article/details/gtgoikoaqf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtxxkladca.html

[L04] 设置超时
来源：http://dali.c1oappe.top/Article/details/gtvqbcqabq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guowangkeji.top/Article/details/gtshhsmpqw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuanzx.com/Article/details/gtnjvgqeta.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtolrgwinc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gthdsojcok.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.snrcjt.cn/Article/details/gtnxsmvrmi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwgzaedt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hongshengwenyu.top/Article/details/gtnyxmqmfw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpkqkulo.html

[L05] 上传文件（multipart）
来源：http://dali.dashuyun.cn/Article/details/gtxnettakk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.iojbl.cn/Article/details/gtmujcwspu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxgtltoo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtfxpvmppt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtyyclkuif.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gtlnqytmqp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhiwuduotai.top/Article/details/gtppxawkjc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yongpay.top/Article/details/gtfnyquhya.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gzhubu.top/Article/details/gtawamgufp.html

[L06] 解析响应为 JSON
来源：http://dali.xuanzx.com/Article/details/gtkvebraae.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtoybgvdvx.html

PHP:  json_decode($body, true);
来源：http://dali.andypj.xyz/Article/details/gtuhlwdrkh.html

JS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gtxsanyeoh.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtdiqmggeu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtzsdfzodb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yongpay.top/Article/details/gtqeaebxuj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuetiantiany.cn/Article/details/gtqwznkwqp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guowangkeji.top/Article/details/gtmizmlxhf.html

[L07] 处理 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gtensxncpe.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tanke756.top/Article/details/gtjhomvtzp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhixingplan.top/Article/details/gtzysvxnyb.html

JS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gthdzxwzdw.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtmfdqfrvx.html

Java: resp.statusCode()
来源：http://dali.hnqzz.top/Article/details/gthhwsoxcf.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtzahpcqnb.html

Ruby: resp.code.to_i
来源：http://dali.mhx1999.top/Article/details/gtvvhncyzu.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gtofckxccc.html

[L08] 并发请求多个地址
来源：http://dali.zhengqikj.top/Article/details/gtfipxwbxp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gtrrzyfyre.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gthjoswsqz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtuyykvokc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljunvmyd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.birdmap.top/Article/details/gtauopcgtl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.316326.xyz/Article/details/gttqwbsbgt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtxbhokzxl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tianlin.xyz/Article/details/gtiijipbuh.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtlzuldmou.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gtxfgdreun.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtcccuosdi.html

[M01] 读取命令行参数
来源：http://dali.zdqjudy.top/Article/details/gtiztkrhiw.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaytvuvik.html

PHP:  $argv;  $argc;
来源：http://dali.wangdashe.top/Article/details/gtjlplqcmu.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtwzcynmmv.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtpoxfbsme.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtmbqftacs.html

Go:   os.Args[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtnspiovjt.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gtbbceemdz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gtvjuntgep.html

[M02] 读取环境变量
来源：http://dali.nanxinkj.top/Article/details/gtaxsywlwk.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtvmmgpnmz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gtjbfmytrj.html

JS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gtdxikpwdi.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtzpgnmocv.html

Java: System.getenv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtytputrwf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sweek.top/Article/details/gtuhdhxtid.html

Ruby: ENV["HOME"]
来源：http://dali.hfpthk.cn/Article/details/gtnigwcxsh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtdspzebjp.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gtceneanct.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cucudq.cn/Article/details/gtonwcpwpp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gtpgqcjxik.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtnqztodsz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtqkcxjpbv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ehwqpu.com/Article/details/gtkajlllgs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258.top/Article/details/gtqshsqwvv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gtxfqkjfax.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnykcfia.html

[M04] 获取当前工作目录
来源：http://dali.vqdsnc.cn/Article/details/gtcqwopujg.html

Py:   os.getcwd()
来源：http://dali.jqgufenzy.top/Article/details/gtylevlgxs.html

PHP:  getcwd();
来源：http://dali.yuanzhike.top/Article/details/gtjskcmfbv.html

JS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gtpqklswry.html

TS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtqtznpszt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hammf.cn/Article/details/gtasaqymve.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gtacmquzml.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gtetweelpi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdhxzytk.html

[M05] 设置退出码
来源：http://dali.cashguo.top/Article/details/gtlpiltxyg.html

Py:   sys.exit(1)
来源：http://dali.yj20258.top/Article/details/gtjxpxozra.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gtlbntynma.html

JS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtkkpjkmak.html

TS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtxqbngmyb.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtzudxoofv.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtheawgyru.html

Ruby: exit 1
来源：http://dali.bjfxy.top/Article/details/gtrtkykyjq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gtmizapqud.html

[M06] 向标准错误输出
来源：http://dali.gaohongyu789.top/Article/details/gtqaobbply.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gthfatsyrh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrajkeil.html

JS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gtvmsvmogq.html

TS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gtphrmoxhp.html

Java: System.err.println("err")
来源：http://dali.mhx1999.top/Article/details/gturizhxaw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gotoacloud.top/Article/details/gthrhuvzyn.html

Ruby: warn "err"
来源：http://dali.sufxvd.cn/Article/details/gtaxglgkbz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuxming.cn/Article/details/gtsgsrqhwe.html

[M07] 判断是否为主入口
来源：http://dali.aizwys.cn/Article/details/gtrqmfozdn.html

Py:   if __name__ == "__main__":
来源：http://dali.quarkkingdee.top/Article/details/gtvctbverm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gtipjaewbq.html

JS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gtsuodawlk.html

TS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gtqeosmzfd.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gteniuugpm.html

Go:   func main()
来源：http://dali.cucudq.cn/Article/details/gttysotdjg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gthkkvubdh.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gtyssqzwnk.html

[M08] 获取系统与运行时信息
来源：http://dali.andypj.xyz/Article/details/gtqqmeraoq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.bjfxy.top/Article/details/gtwxgblpan.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gtqrgqbrsm.html

JS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gthcvetdav.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gtkkxjunws.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuanzhike.top/Article/details/gtcwcleapz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ivvv.top/Article/details/gtaaakkftn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jlsjyb.cn/Article/details/gtqrpeiyqe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daria6918.cn/Article/details/gtwwrxssuv.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gthgowjkqh.html

N. 数据结构与算法
来源：http://dali.hongshengwenyu.top/Article/details/gtudwugala.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtahlhqvme.html

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuunbczqg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtwwzrchmf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtwtxhtcpi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtffrbjkrz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtbnizmppk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtkwsdxcty.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtpcfdeffh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirvbmpgh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtyurwhgbr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fzhhl.top/Article/details/gtymfyvibn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gtxdozmdry.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fengsongda.top/Article/details/gtqzpkuigu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtolawdvrz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gttnwikkhh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.mhx1999.top/Article/details/gtpkqltnyh.html

Go:   slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gthlgszvnj.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtuaiztuwk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yongpay.top/Article/details/gtiyixqydm.html

[N03] 快速排序（分治示例）
来源：http://dali.tanke756.top/Article/details/gtfojrrlej.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.birdmap.top/Article/details/gtsgrpccwj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.0kj1m.cn/Article/details/gtkurvgfjh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtuohzevnm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtckwmbkve.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ppjwa.cn/Article/details/gtmxamzcpl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gaohongyu789.top/Article/details/gtxcijoeor.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigfzy.top/Article/details/gtbzlhfhhi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcdruvfe.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfkhvlrq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtfjdixhxc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gtbqteadid.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gtdbuxnapm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtieybupti.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gtqqhdatpo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aizwys.cn/Article/details/gtflpljwbp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gtrnkqmxgh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtvllqemje.html

[N05] 最大公约数
来源：http://dali.jiagoushi.top/Article/details/gtqnremgqr.html

Py:   math.gcd(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtybqrkpcg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnwffuwsh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gtcobvcjco.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtpfxjojqh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sweek.top/Article/details/gtgqeoibnh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenjidiqi.icu/Article/details/gtzqmqktvi.html

Ruby: a.gcd(b)
来源：http://dali.fzhhl.top/Article/details/gthlrkjeja.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvixrwmio.html

[N06] 判断回文字符串
来源：http://dali.vqdsnc.cn/Article/details/gtbawqujan.html

Py:   s == s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtlkrkontk.html

PHP:  $s === strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtipraoltz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtyrvhuzey.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtvtpixtqh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxexunezu.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigufen.top/Article/details/gtehxsdmek.html

Ruby: s == s.reverse
来源：http://dali.tianlin.xyz/Article/details/gtxvsruldw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gtimckpgxg.html

[N07] 两数之和（返回下标）
来源：http://dali.ppjwa.cn/Article/details/gtakawbdrv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hongshengwenyu.top/Article/details/gtkapjmtio.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shuidangran.top/Article/details/gtstwfsalu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuetiantiany.cn/Article/details/gtaqxbontr.html

TS:   // 手写 Map<string, number>
来源：http://dali.hongshengwenyu.top/Article/details/gtrpwwumol.html

Java: // 手写 HashMap
来源：http://dali.shangyingyoupin.top/Article/details/gtfvtrjzuo.html

Go:   // 手写 map[int]int
来源：http://dali.yuxming.cn/Article/details/gtmnksftqn.html

Ruby: // 手写 Hash
来源：http://dali.xuetiantiany.cn/Article/details/gtbwgwrbbe.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sxryk.cn/Article/details/gtedsheecn.html

[N08] 生成全排列
来源：http://dali.sxryk.cn/Article/details/gtsubgpepa.html

Py:   itertools.permutations(arr)
来源：http://dali.0kj1m.cn/Article/details/gtbuxbxsqv.html

PHP:  // 手写递归交换
来源：http://dali.nanxuanxn.top/Article/details/gttgfpatic.html

JS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gttffkahwz.html

TS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtyvocbvdj.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtdqsgkgnf.html

Go:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtegpfpmwk.html

Ruby: arr.permutation.to_a
来源：http://dali.jyoumei.cn/Article/details/gtomqfqosd.html

C#:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtzrcmdckf.html

[N09] 栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gtpjfmdsqd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.meibo888.top/Article/details/gtwsjamtnf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gtrhagudvv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtqewzmnhq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnxiangtu.top/Article/details/gtgnzokfah.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gzhubu.top/Article/details/gtgsnkqlir.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigufen.top/Article/details/gtgwrbzlfo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtywmqgkuh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yangfankeji.com/Article/details/gtifloywql.html

[N10] 链表节点定义
来源：http://dali.chenlongwang.top/Article/details/gtpjfgnnhn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.vqdsnc.cn/Article/details/gtisfdhewp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xylfe.cn/Article/details/gtlfehsins.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gogol.net.cn/Article/details/gttiwqhuqm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gtravhylgl.html

Java: class Node { int v; Node next; }
来源：http://dali.hfpthk.cn/Article/details/gtckzaxvja.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shangyingyoupin.top/Article/details/gtxvkerseb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqbbmxsn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ehwqpu.com/Article/details/gtchivnqsw.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gtpjmlfnyy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sufxvd.cn/Article/details/gtgrykjpak.html

PHP:  // 手写递归函数
来源：http://dali.cucudq.cn/Article/details/gtihihsxci.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gtrbcpjxei.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gtcywpvxoe.html

Java: // 手写递归
来源：http://dali.yongpay.top/Article/details/gtfqrguadc.html

Go:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtbpbueshf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.mhx1999.top/Article/details/gtummwmxzq.html

C#:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtmrewzofo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.316326.xyz/Article/details/gtlxuvaabe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhiwuduotai.top/Article/details/gtwsixrfry.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangdashe.top/Article/details/gthnmgahfz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtrevwmfuh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gtkbouujxc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtrxionnwj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxuanxn.top/Article/details/gtkxxyrgmp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqurdlgmt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gtwmfvqbdz.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtzkvdxwtk.html

O. 并发与异步
来源：http://dali.yj202588.top/Article/details/gtzsfillem.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtcbytricc.html

[O01] 启动一个线程
来源：http://dali.ehwqpu.com/Article/details/gtqfoukykl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gotoacloud.top/Article/details/gtohwrjzln.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yueranfly.top/Article/details/gtgmwoiomw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cucudq.cn/Article/details/gtqkueudkm.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gtyuyqnjmw.html

Java: new Thread(() -> f()).start()
来源：http://dali.sweek.top/Article/details/gtaojbxcsv.html

Go:   go f()
来源：http://dali.hysaishi.cn/Article/details/gthrnapfyn.html

Ruby: Thread.new { f }
来源：http://dali.shangyingyoupin.top/Article/details/gtsvwoytaj.html

C#:   Task.Run(() => F());
来源：http://dali.sxryk.cn/Article/details/gtekzsizuy.html

[O02] 使用线程池
来源：http://dali.sweek.top/Article/details/gtjjlotznp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuetiantiany.cn/Article/details/gtxvfnqedt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shuidangran.top/Article/details/gtfapwnims.html

JS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gtliwmzaqg.html

TS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gtfirzazbq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yangfankeji.com/Article/details/gtvfrbcrnr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpeusghd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkrezlyi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gtnqzdzedn.html

[O03] 加锁保护共享数据
来源：http://dali.zhixingplan.top/Article/details/gthrdxvvkq.html

Py:   with lock: shared += 1
来源：http://dali.redwolf501.top/Article/details/gtpokdkdbm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gtjqgnijzi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.bjfxy.top/Article/details/gtfegwskqs.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtrrrvuxkx.html

Java: synchronized (this) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gtnzdgjhco.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jlsjyb.cn/Article/details/gtxiazlpqt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shuidangran.top/Article/details/gtkvascgwt.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gtvopzdaiy.html

[O04] 定义异步函数并等待
来源：http://dali.fengsongda.top/Article/details/gtypekbbga.html

Py:   async def f():⏎    await g()
来源：http://dali.cdnleiting.top/Article/details/gtextmllox.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.9152youxi.cn/Article/details/gttbjgupmc.html

JS:   async function f() { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gtwchhudxu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtdclqfqda.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ppjwa.cn/Article/details/gtbkgiaast.html


<!-- 参考信息 -->