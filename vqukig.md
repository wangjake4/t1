代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtjckfumtt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtgayvhvnt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtkjbhwtqc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.birdmap.top/Article/details/gtapgmaspz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gtqoduqkik.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtjrikquiw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.bjfxy.top/Article/details/gtqproakmy.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gtcxiqoxry.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhsyvrag.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gttdirgxha.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gtqueubcuc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tanke756.top/Article/details/gtlphdflny.html

Go:   encoding/gob
来源：http://dali.aibaodan.cn/Article/details/gtqlhakofx.html

Ruby: Marshal.dump(obj)
来源：http://dali.hammf.cn/Article/details/gtgjftrpru.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtxtiesppc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gthnwsouov.html

L. 网络请求
来源：http://dali.bjfxy.top/Article/details/gtplcwpajt.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtekejvhjv.html

[L01] 发送 GET 请求
来源：http://dali.gzhubu.top/Article/details/gtixawettb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hongshengwenyu.top/Article/details/gtkixhhgbw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnvsxlvt.html

JS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gtosdamocn.html

TS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtypiiwopc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cashguo.top/Article/details/gtztbnshrm.html

Go:   resp, err := http.Get(url)
来源：http://dali.yongpay.top/Article/details/gtqhejtwvz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gtzpukjhun.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtfazvhhvq.html

[L02] 发送 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtrkaoqvua.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hammf.cn/Article/details/gtuuslgbjn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yonumen.top/Article/details/gtqyxldjlg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtelirwkry.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtryxacjnh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgfzy.top/Article/details/gtchzgfipw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnxiangtu.top/Article/details/gtqqadptwy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhoulong.xyz/Article/details/gtmcoovpqw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.quarkkingdee.top/Article/details/gtwryfjtkh.html

[L03] 设置自定义请求头
来源：http://dali.shangyingyoupin.top/Article/details/gtydquoqwq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigufen.top/Article/details/gtlzzuynny.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtygocklzp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gtqkrbbgmt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gtgyyptsto.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gaohongyu789.top/Article/details/gtrqfwjoic.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtqdsrtjub.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ydzc1.top/Article/details/gtsnvwjkpw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gtogrmrddm.html

[L04] 设置超时
来源：http://dali.yangfankeji.com/Article/details/gtgctokobi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daxiang520.top/Article/details/gtnozetpbw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigufen.top/Article/details/gtwajbltog.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfylbkwuu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gtfwdyxshj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.vqdsnc.cn/Article/details/gtizczkuxf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuanzhike.top/Article/details/gtncwovoao.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sufxvd.cn/Article/details/gtphoxumzz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hongshengwenyu.top/Article/details/gtawvwnadb.html

[L05] 上传文件（multipart）
来源：http://dali.chenlongwang.top/Article/details/gtcovvcrnr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gtgrkwfgsz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gttyejsxgk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gtnslaavcf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gthtihymsp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.bjfxy.top/Article/details/gtzuwkiuot.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daria6918.cn/Article/details/gtxviuqfaa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xinyue.icu/Article/details/gtpvhsrvpr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yueranfly.top/Article/details/gtwpinlwey.html

[L06] 解析响应为 JSON
来源：http://dali.mhx1999.top/Article/details/gtpqtewret.html

Py:   resp.json()
来源：http://dali.daria6918.cn/Article/details/gtmiveatnp.html

PHP:  json_decode($body, true);
来源：http://dali.tian-w.cn/Article/details/gteqgwrnpf.html

JS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtwvrnlsfk.html

TS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtiwcaexfs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtxzgmcsyr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xinyue.icu/Article/details/gtwnnzdfpc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sysykeji.top/Article/details/gtdfvbuwwu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.quarkkingdee.top/Article/details/gtenfosuqr.html

[L07] 处理 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtabyeaeyv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigufen.top/Article/details/gtjjipmpkv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dianchejie.cn/Article/details/gtoyanqylp.html

JS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gtsqzijalq.html

TS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gtlhvjepib.html

Java: resp.statusCode()
来源：http://dali.kuanghao11.cn/Article/details/gtnvjqmvcy.html

Go:   resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gtiqwcfmcr.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gtcuibcxek.html

C#:   (int)resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gttvttdage.html

[L08] 并发请求多个地址
来源：http://dali.fzhhl.top/Article/details/gtawgnrpyk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gtygkuxqbn.html

PHP:  curl_multi_init() 系列
来源：http://dali.aizwys.cn/Article/details/gttshxoucq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtjwsjzvjd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtgilsmpzl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tian-w.cn/Article/details/gtbnxdmdio.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sufxvd.cn/Article/details/gtgcpibyph.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xinyue.icu/Article/details/gtcspqcqup.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.9152youxi.cn/Article/details/gtakfirhkn.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtgzpsyndg.html

M. 命令行 / 进程 / 环境
来源：http://dali.jianghu66.top/Article/details/gtmpydhstq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchkkispk.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gttylqwrxa.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gtufrwkedc.html

PHP:  $argv;  $argc;
来源：http://dali.ivvv.top/Article/details/gtjkbsjsrh.html

JS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtcjifnagi.html

TS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gthlabmqif.html

Java: args 数组（main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtgbjpeefp.html

Go:   os.Args[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtsnlfxpgj.html

Ruby: ARGV
来源：http://dali.sweek.top/Article/details/gtjllukaci.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtdoxqhxyg.html

[M02] 读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gtkbfzfsqc.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtonhbfbbs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gtnprubrls.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtkypjyimx.html

TS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gtfgcpezie.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtczyfdaqq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtxgtdqsld.html

Ruby: ENV["HOME"]
来源：http://dali.redwolf501.top/Article/details/gtxhoedhdo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtygdggvbr.html

[M03] 执行外部命令
来源：http://dali.nwbrower.top/Article/details/gtggxqqsyq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.iojbl.cn/Article/details/gtntvtifsz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gtctlemqqi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtyncdnhyt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtgfodakbk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.316326.xyz/Article/details/gtwdpttyfb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuanzx.com/Article/details/gtwethxanh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxinkj.top/Article/details/gtjklmnxcp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zycfv.cn/Article/details/gtpvvmhmpv.html

[M04] 获取当前工作目录
来源：http://dali.jlsjyb.cn/Article/details/gtsaseclqe.html

Py:   os.getcwd()
来源：http://dali.smart0.xyz/Article/details/gtowjhieug.html

PHP:  getcwd();
来源：http://dali.yonumen.top/Article/details/gtrxddkmcp.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtogjcjyyr.html

TS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtyrscauhj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hammf.cn/Article/details/gtgcmoadij.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gtenuwgpgk.html

Ruby: Dir.pwd
来源：http://dali.jiagoushi.top/Article/details/gtcftaqudt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daria6918.cn/Article/details/gtmnwsdehc.html

[M05] 设置退出码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdemmhrnj.html

Py:   sys.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtgldudvvy.html

PHP:  exit(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrtccuvc.html

JS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtmcjnhjbo.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtvdwygsvn.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtxasjgpyo.html

Go:   os.Exit(1)
来源：http://dali.pycfn.com/Article/details/gthnwdazbt.html

Ruby: exit 1
来源：http://dali.havefunace.top/Article/details/gtmwqbxwhz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.birdmap.top/Article/details/gtdnoldqpc.html

[M06] 向标准错误输出
来源：http://dali.gogol.net.cn/Article/details/gtqmmmnmmp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gtznybkcqx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhixingplan.top/Article/details/gtwomuadnz.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtqrunwmrq.html

TS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gtjsogueer.html

Java: System.err.println("err")
来源：http://dali.daxiang520.top/Article/details/gtizrokdwz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.vqdsnc.cn/Article/details/gttccqixmn.html

Ruby: warn "err"
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpghdakm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.meibo888.top/Article/details/gtvgwkedvn.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gtgjxwyjfc.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gtyretjevp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenlongwang.top/Article/details/gtdbhtaext.html

JS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gtrjjexije.html

TS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtyrhabthk.html

Java: public static void main(String[] args)
来源：http://dali.nanxuanxn.top/Article/details/gtermrtyqc.html

Go:   func main()
来源：http://dali.hnxiangtu.top/Article/details/gtmccykzel.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tian-w.cn/Article/details/gtyuhnmsnn.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtwcrajkfa.html

[M08] 获取系统与运行时信息
来源：http://dali.yuanzhike.top/Article/details/gtmcwrqspf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqgwqmpd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gtnmutruhj.html

JS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gttpsetplx.html

TS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtbokrbwzn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tian-w.cn/Article/details/gtcedliqyi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gtkaalrznz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258.top/Article/details/gtjjulqsku.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.andypj.xyz/Article/details/gtcudnqrvw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtirjyrpjr.html

N. 数据结构与算法
来源：http://dali.aizwys.cn/Article/details/gtsveyuauq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtdhdpnjkb.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gtzhlqjfsk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtdpzpriee.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtgiynzfce.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gtxvpurbys.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gtrzhdcqdb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtpjynmuzn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtonjwlinp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xylfe.cn/Article/details/gtkhmfyhnn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtyteqocnr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhixingplan.top/Article/details/gtucocpnhf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gtrszhlvrh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtsbbyscsy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfuybzxj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgawahnbk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gtiqthrpgk.html

Go:   slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtypqikglf.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gtuhxxkmyi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yanxiufei.cn/Article/details/gtehrarviy.html

[N03] 快速排序（分治示例）
来源：http://dali.kuanghao11.cn/Article/details/gteifurnqv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgfzy.top/Article/details/gtggtfypul.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gogol.net.cn/Article/details/gtknmqcgrk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gtcuhhovrw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gtyavuhyss.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gttmzmawop.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtauthtuiq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtachlsjyd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daria6918.cn/Article/details/gtjzokkmng.html

[N04] 斐波那契数列
来源：http://dali.smart0.xyz/Article/details/gtwmxoimvq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gtprwuppfh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gtxbifaehw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtagoluiao.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtccruwyne.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.iojbl.cn/Article/details/gtfwczbici.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tanke756.top/Article/details/gtnfrbkked.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gtvfchbwqx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gthyhnnygh.html

[N05] 最大公约数
来源：http://dali.gaohongyu789.top/Article/details/gtlpfvknuy.html

Py:   math.gcd(a, b)
来源：http://dali.cashguo.top/Article/details/gtynuvgppk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sysykeji.top/Article/details/gttefdubyv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gtogzrsdhq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtlhnumhyg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hfpthk.cn/Article/details/gtqmgzvggr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fzhhl.top/Article/details/gttgxmopha.html

Ruby: a.gcd(b)
来源：http://dali.guannengcc.top/Article/details/gtrcwvaegt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.quarkkingdee.top/Article/details/gtbtpbhqdj.html

[N06] 判断回文字符串
来源：http://dali.ehwqpu.com/Article/details/gtvradmwfo.html

Py:   s == s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gttufjjxcs.html

PHP:  $s === strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtnkrfxuxg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtqvjhufzb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtpmobodqn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.9152youxi.cn/Article/details/gtfegsezwm.html

Go:   // 双指针从两端比较
来源：http://dali.yanxiufei.cn/Article/details/gtqwxqidfr.html

Ruby: s == s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtdhftpfsi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gtgjbcnjjb.html

[N07] 两数之和（返回下标）
来源：http://dali.iojbl.cn/Article/details/gtjluswbfj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhengqikj.top/Article/details/gtxrvgxgdv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sufxvd.cn/Article/details/gtfnouildg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.vqdsnc.cn/Article/details/gttgwrghil.html

TS:   // 手写 Map<string, number>
来源：http://dali.fengsongda.top/Article/details/gtvamsbtuw.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gtebdkgnon.html

Go:   // 手写 map[int]int
来源：http://dali.bjfxy.top/Article/details/gtohmrodmd.html

Ruby: // 手写 Hash
来源：http://dali.cashguo.top/Article/details/gtewdujgvu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hfpthk.cn/Article/details/gterrijmhq.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gttosdmerq.html

Py:   itertools.permutations(arr)
来源：http://dali.hfpthk.cn/Article/details/gtoqekcrcx.html

PHP:  // 手写递归交换
来源：http://dali.sufxvd.cn/Article/details/gtjktsftoo.html

JS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtajyqthyh.html

TS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtyjqprovy.html

Java: // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtpoxrbyqz.html

Go:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtynngfrxj.html

Ruby: arr.permutation.to_a
来源：http://dali.yueranfly.top/Article/details/gtokgsjkoj.html

C#:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gttmegqxte.html

[N09] 栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gtshyxcxxn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cucudq.cn/Article/details/gtaxxkwrll.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gtstewmyzi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtnpoxkrms.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nwbrower.top/Article/details/gttmzucqpu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gtpxefsqwd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj202588.top/Article/details/gtsoyuwvtq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtwoyyzzww.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sxryk.cn/Article/details/gtqsjzyhlz.html

[N10] 链表节点定义
来源：http://dali.hnxiangtu.top/Article/details/gtmzxvqopq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvnaezqx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gtrwamturh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.andypj.xyz/Article/details/gtoqngkeyo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcksirug.html

Java: class Node { int v; Node next; }
来源：http://dali.cashguo.top/Article/details/gtuajoclwt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangdashe.top/Article/details/gtokedjezf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jiagoushi.top/Article/details/gtdgghwzak.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhengqikj.top/Article/details/gtthfwcetj.html

[N11] 二叉树中序遍历
来源：http://dali.yangfankeji.com/Article/details/gttlyexols.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fengsongda.top/Article/details/gtrhyluaec.html

PHP:  // 手写递归函数
来源：http://dali.cucudq.cn/Article/details/gtihoqqaqc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gtzpqfopey.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gtqwtvhniv.html

Java: // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtvhvetiwm.html

Go:   // 手写递归
来源：http://dali.sweek.top/Article/details/gtmxpfqfqe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangdashe.top/Article/details/gtfecevmka.html

C#:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtqptgiqjp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangshuangyany.cn/Article/details/gtqhnfliri.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtxoadlbdx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yonumen.top/Article/details/gtjkmgpics.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gttipkiadk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gtykmbiqph.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gtmfyzvxoh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbjnjmcq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtxigekjwt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gttrhqkekb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtfsusogox.html

O. 并发与异步
来源：http://dali.tian-w.cn/Article/details/gtxujnciab.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtqokbrdiu.html

[O01] 启动一个线程
来源：http://dali.vqdsnc.cn/Article/details/gtkwatafcx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nwbrower.top/Article/details/gturjxcbly.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gtcotjlnrr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.0kj1m.cn/Article/details/gtanazvolh.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gtvngdsxjf.html

Java: new Thread(() -> f()).start()
来源：http://dali.aizwys.cn/Article/details/gtktjhzzmv.html

Go:   go f()
来源：http://dali.yj20258888.top/Article/details/gtanxdtwpw.html

Ruby: Thread.new { f }
来源：http://dali.xuetiantiany.cn/Article/details/gthuryenhq.html

C#:   Task.Run(() => F());
来源：http://dali.chenlongwang.top/Article/details/gtmxocdtrl.html

[O02] 使用线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtldjolcur.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.andypj.xyz/Article/details/gtmcbqptoy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.iojbl.cn/Article/details/gtlcqzszkb.html

JS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gtfbeenvln.html

TS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gtmhdckvig.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gogol.net.cn/Article/details/gtzxhxobss.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuanzx.com/Article/details/gtjtqasekc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ydzc1.top/Article/details/gtqtfzoqjx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hfpthk.cn/Article/details/gtwhcypyqg.html

[O03] 加锁保护共享数据
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmhtqfuz.html

Py:   with lock: shared += 1
来源：http://dali.tian-w.cn/Article/details/gtlsgznmqs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cashguo.top/Article/details/gtsepflmhz.html


<!-- 参考信息 -->