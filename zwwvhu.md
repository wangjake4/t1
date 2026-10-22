代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.smart0.xyz/Article/details/gtelljqyel.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gttsqrchog.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gtxdbllxcg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.vqdsnc.cn/Article/details/gtaafimcof.html

Go:   encoding/gob
来源：http://dali.quarkkingdee.top/Article/details/gtkdmkblpw.html

Ruby: Marshal.dump(obj)
来源：http://dali.yangfankeji.com/Article/details/gtfiitreer.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gttaztemux.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcnvhtcz.html

L. 网络请求
来源：http://dali.jinqigufen.top/Article/details/gtbuivplno.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtuchmoazo.html

[L01] 发送 GET 请求
来源：http://dali.hammf.cn/Article/details/gtlxojsxbx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.bjfxy.top/Article/details/gtqbuycqta.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jlsjyb.cn/Article/details/gtsfazfuhv.html

JS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtwnwiwpjm.html

TS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gthxmvrttk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuanzx.com/Article/details/gtyfvaxamq.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gtfydwjtsv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuanzx.com/Article/details/gthefnogvk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ybcxt.top/Article/details/gtsutaxdtn.html

[L02] 发送 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gtgkbadfmt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gtysqrsbxu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuxming.cn/Article/details/gtntuwwgum.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gtxbvdnqwr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gtoeqzpjyt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hammf.cn/Article/details/gtueugyrxr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yangfankeji.com/Article/details/gtwhrpjnnk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhixingplan.top/Article/details/gtjsyprhqb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gaohongyu789.top/Article/details/gtpxmexlzz.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gtcqerizkq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gtcdceyskq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnqzz.top/Article/details/gtqwqseovd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gtmisglvhs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gtbrhmuxce.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gthoiinzxr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gttxgznqpy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xylfe.cn/Article/details/gthydhyaiw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gtdlyjdrtr.html

[L04] 设置超时
来源：http://dali.feifeiyinyue.top/Article/details/gtkcbegmbe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.andypj.xyz/Article/details/gtqweoaslv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gtrtvjavzz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gtyhhsbmiu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gtawzrvykw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnqzz.top/Article/details/gtlnzumgfd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hfpthk.cn/Article/details/gtcdpqzjql.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangdashe.top/Article/details/gtsithmtmo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xinyue.icu/Article/details/gtjofhplhp.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gtyxrliilz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gthpxddgso.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dashuyun.cn/Article/details/gtwyvnjeab.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gtgodaysgp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gtsxvdpiai.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gtkikdptlx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gtkpebpvly.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sysykeji.top/Article/details/gtvrzdmhvi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtcnimnmxd.html

[L06] 解析响应为 JSON
来源：http://dali.ivvv.top/Article/details/gtrwluaeje.html

Py:   resp.json()
来源：http://dali.redwolf501.top/Article/details/gtkchpubyo.html

PHP:  json_decode($body, true);
来源：http://dali.gotoacloud.top/Article/details/gtmztirghc.html

JS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gttmyudikc.html

TS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtwspiphbs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtveqfyngp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yangfankeji.com/Article/details/gtsitiiidr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ehwqpu.com/Article/details/gtjmhkprcq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.kuanghao11.cn/Article/details/gtlntoyqku.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpovmyypi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhixingplan.top/Article/details/gtnbtnusqq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dashuyun.cn/Article/details/gtabelrfsz.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvzcrdpq.html

TS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gtumaerpag.html

Java: resp.statusCode()
来源：http://dali.haohaochexian.top/Article/details/gtkpbfadau.html

Go:   resp.StatusCode
来源：http://dali.fengsongda.top/Article/details/gtpvgegamy.html

Ruby: resp.code.to_i
来源：http://dali.tanke756.top/Article/details/gtsydycznw.html

C#:   (int)resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gtjxgomwio.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gtotpnxiyo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aizwys.cn/Article/details/gtufvncktu.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258888.top/Article/details/gtailxtsnf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtcqojlpfr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtgvhsseen.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gtserxctiy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cucudq.cn/Article/details/gtdzxtufrr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tanke756.top/Article/details/gtdzmmiiny.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtpfdhnlcg.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtnigzdmpr.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gtmwizgptf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtkeuvlelu.html

[M01] 读取命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtsimtmock.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtoeugqbtu.html

PHP:  $argv;  $argc;
来源：http://dali.hfpthk.cn/Article/details/gtiejogiqh.html

JS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtberxdujw.html

TS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gtfdefwtrq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtemkblpgl.html

Go:   os.Args[1:]
来源：http://dali.cqqwz.cn/Article/details/gtcaliklpi.html

Ruby: ARGV
来源：http://dali.jqgfzy.top/Article/details/gtaufezgxk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtbzpubkjk.html

[M02] 读取环境变量
来源：http://dali.yj20258888.top/Article/details/gtybmgivqq.html

Py:   os.environ.get("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtsmaeetgz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtdaiegcop.html

JS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gtadrrfaqr.html

TS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtypjefuzy.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtbzhpavls.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtgtnfsnrl.html

Ruby: ENV["HOME"]
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqijgoqt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbchnejfh.html

[M03] 执行外部命令
来源：http://dali.hongshengwenyu.top/Article/details/gthfsptymt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aibaodan.cn/Article/details/gtzltpahgx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gtkqrqhxbw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmdteeid.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gtglachosf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gtupclipsm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnqzz.top/Article/details/gtnwmravrl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sxryk.cn/Article/details/gtmltzsdip.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gtjumozccr.html

[M04] 获取当前工作目录
来源：http://dali.jiagoushi.top/Article/details/gtmxtoyxvm.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gtkktmwcmp.html

PHP:  getcwd();
来源：http://dali.nanxuanxn.top/Article/details/gtskmovpid.html

JS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtinacpvwq.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gtzrudfrzj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yueranfly.top/Article/details/gtearzdiin.html

Go:   os.Getwd()
来源：http://dali.cdnleiting.top/Article/details/gtotzfepls.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gtmiztqzhl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tianlin.xyz/Article/details/gtjumwouly.html

[M05] 设置退出码
来源：http://dali.nanxuanxn.top/Article/details/gthwpoekbz.html

Py:   sys.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtkggrdvnq.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gthbhfcacv.html

JS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtffmqcvoz.html

TS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtoodahggw.html

Java: System.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtootsqbou.html

Go:   os.Exit(1)
来源：http://dali.c1oappe.top/Article/details/gtzqemqdrh.html

Ruby: exit 1
来源：http://dali.guannengcc.top/Article/details/gtjtdknjxm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zdqjudy.top/Article/details/gtpkzrfewh.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gtpixghhlx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gtmnqkhygf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gtplzwuygk.html

JS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gtbxkhqzky.html

TS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gtezggoiiu.html

Java: System.err.println("err")
来源：http://dali.jianghu66.top/Article/details/gtprqwsohj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gtfbethcib.html

Ruby: warn "err"
来源：http://dali.sysykeji.top/Article/details/gttkfvbxxu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cqqwz.cn/Article/details/gtthmnzhxr.html

[M07] 判断是否为主入口
来源：http://dali.guowangkeji.top/Article/details/gtsevtezlb.html

Py:   if __name__ == "__main__":
来源：http://dali.zhongyouzk.top/Article/details/gtcexoxgzo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gtvcpgqyyb.html

JS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gttpzzswye.html

TS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gtukhqkcpf.html

Java: public static void main(String[] args)
来源：http://dali.fengsongda.top/Article/details/gtkosemzfn.html

Go:   func main()
来源：http://dali.meibo888.top/Article/details/gtfgbehsch.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.kuanghao11.cn/Article/details/gtmaxgqlpt.html

C#:   static void Main(string[] args)
来源：http://dali.hammf.cn/Article/details/gtkhmrwffk.html

[M08] 获取系统与运行时信息
来源：http://dali.jiagoushi.top/Article/details/gtwgpxdhlm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.kuanghao11.cn/Article/details/gtlxqbczsd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijqcxzyw.html

JS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gtaujxusry.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtdukumcrz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxumslxk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjtjsuai.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gaohongyu789.top/Article/details/gtzmomfubt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cucudq.cn/Article/details/gtgbnnslbh.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtugymxvwt.html

N. 数据结构与算法
来源：http://dali.xylfe.cn/Article/details/gtdefhuxmp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtltlzfvvu.html

[N01] 二分查找（有序数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnmtbjtd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtcljjarep.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtiuckxcml.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gthzisrmmc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtvpcnshsy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtbiiyadcy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtafdbqwdk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cucudq.cn/Article/details/gtvadrstxl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtbxymsstx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gttzgwsnjv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtcridcuat.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xylfe.cn/Article/details/gtiqpujtos.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtovnvokmf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtluwtcmhu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cheryme.top/Article/details/gttyjznine.html

Go:   slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gtzqileiqt.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gtxrcgkses.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cdnleiting.top/Article/details/gtpfhfjfgg.html

[N03] 快速排序（分治示例）
来源：http://dali.daria6918.cn/Article/details/gtjlexlhog.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.kuanghao11.cn/Article/details/gtriazvebt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yueranfly.top/Article/details/gtfzraasrq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gtasjktkez.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gttdupplur.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gotoacloud.top/Article/details/gtykerkfyq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.andypj.xyz/Article/details/gtxiqelobt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dashuyun.cn/Article/details/gtbrqkcwjq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.c1oappe.top/Article/details/gtjnzthgau.html

[N04] 斐波那契数列
来源：http://dali.shuidangran.top/Article/details/gtxnnivzdz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gtzuofkxyg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtemhxkusr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gthdyrhaft.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtbnowfgvr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtbzsnxcdf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sxryk.cn/Article/details/gtwonfqqia.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gthbmssxjk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtlcuqzmzt.html

[N05] 最大公约数
来源：http://dali.nanxinkj.top/Article/details/gtzuwuukhr.html

Py:   math.gcd(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtjiaesnxj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.316326.xyz/Article/details/gtvqqkxcck.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gtoxmslxyf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gtsvlhipwd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gtpmkpysnw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hongshengwenyu.top/Article/details/gtovsnnzjv.html

Ruby: a.gcd(b)
来源：http://dali.yj20258.top/Article/details/gtqipstdfb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ybcxt.top/Article/details/gtldluuzij.html

[N06] 判断回文字符串
来源：http://dali.c1oappe.top/Article/details/gtsgzszcfw.html

Py:   s == s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gtiretnhds.html

PHP:  $s === strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzdudesg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtgqfsiaha.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtwsdejaui.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.316326.xyz/Article/details/gtahazejmp.html

Go:   // 双指针从两端比较
来源：http://dali.redwolf501.top/Article/details/gtxxdezidh.html

Ruby: s == s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtyosyxttw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtnikfsgzg.html

[N07] 两数之和（返回下标）
来源：http://dali.kuanghao11.cn/Article/details/gtfxxcvbpv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xinyue.icu/Article/details/gtogdgliik.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgufenzy.top/Article/details/gtviqfjzlo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gtirxztkvt.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gtmhoouzdl.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gtpmzedjcl.html

Go:   // 手写 map[int]int
来源：http://dali.ehwqpu.com/Article/details/gtatsffsio.html

Ruby: // 手写 Hash
来源：http://dali.hnxiangtu.top/Article/details/gtiwomenlm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ybcxt.top/Article/details/gtgncdlror.html

[N08] 生成全排列
来源：http://dali.wangshuangyany.cn/Article/details/gtyyalrmpn.html

Py:   itertools.permutations(arr)
来源：http://dali.dianchejie.cn/Article/details/gtbrgjated.html

PHP:  // 手写递归交换
来源：http://dali.zhengqikj.top/Article/details/gttzmkiinf.html

JS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtnhuvxgoq.html

TS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtkdmjkdba.html

Java: // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtotahhlsm.html

Go:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtcxugtkhd.html

Ruby: arr.permutation.to_a
来源：http://dali.havefunace.top/Article/details/gtizxhcure.html

C#:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtcaxhqzhn.html

[N09] 栈与队列
来源：http://dali.yongpay.top/Article/details/gtjpoitkdk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuksieita.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtaxlzfgno.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtmgemhmzy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yangfankeji.com/Article/details/gtadbxizqy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ppjwa.cn/Article/details/gttbiicgwl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yonumen.top/Article/details/gtwdzsgooe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtpbyxizic.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuanzx.com/Article/details/gtnvrdjsag.html

[N10] 链表节点定义
来源：http://dali.hnqzz.top/Article/details/gtdqrlxegg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.9152youxi.cn/Article/details/gtrdsdjzho.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tianlin.xyz/Article/details/gtqmoleyju.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhengqikj.top/Article/details/gtrabcyobk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigfzy.top/Article/details/gtpbcfcefp.html

Java: class Node { int v; Node next; }
来源：http://dali.redwolf501.top/Article/details/gtswfnmkxy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zdqjudy.top/Article/details/gtqpneczxl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevwpwuog.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gotoacloud.top/Article/details/gtoefihwbj.html

[N11] 二叉树中序遍历
来源：http://dali.ehwqpu.com/Article/details/gtjriutoha.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pengpengdd.cyou/Article/details/gtdcmfavij.html

PHP:  // 手写递归函数
来源：http://dali.sufxvd.cn/Article/details/gtwqtcngdn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gtthkqcfwv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gtqpydobbt.html

Java: // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtfuidqubr.html

Go:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gthdzjombm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ybcxt.top/Article/details/gtuzzcvpci.html

C#:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtteygnkiy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fzhhl.top/Article/details/gtlixydfuf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cucudq.cn/Article/details/gtxnqunzre.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cashguo.top/Article/details/gtglmsipli.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtkhbipwns.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjhwbyda.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gtbrpyzkjr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzjixpch.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gogol.net.cn/Article/details/gtfgpgmctq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtjrsoeabp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtozsjkpjw.html

O. 并发与异步
来源：http://dali.gotoacloud.top/Article/details/gtzlkfmipm.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtqdczyuyj.html

[O01] 启动一个线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtlspklaio.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gaohongyu789.top/Article/details/gtzgorirpt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.snrcjt.cn/Article/details/gtvywezoao.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hfpthk.cn/Article/details/gtqjmsmawy.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtsqvwbmcx.html

Java: new Thread(() -> f()).start()
来源：http://dali.ehwqpu.com/Article/details/gthxhpljbd.html

Go:   go f()
来源：http://dali.xuanzx.com/Article/details/gtuixoyqgl.html

Ruby: Thread.new { f }
来源：http://dali.xuanzx.com/Article/details/gtahlwwkxy.html

C#:   Task.Run(() => F());
来源：http://dali.nanxuanxn.top/Article/details/gtrajxmunm.html

[O02] 使用线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtmiygwcto.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinghuilouyu.cn/Article/details/gttqakdzif.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhixingplan.top/Article/details/gtvjnjnhan.html

JS:   // worker_threads 线程池
来源：http://dali.gotoacloud.top/Article/details/gtigmouzpy.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gtjwkrsuyz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jiagoushi.top/Article/details/gtafmprpfc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.meibo888.top/Article/details/gtctwylpmn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cashguo.top/Article/details/gtwcirvmzn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tianlin.xyz/Article/details/gtgfirrtsh.html

[O03] 加锁保护共享数据
来源：http://dali.nanxinkj.top/Article/details/gtkbuovena.html

Py:   with lock: shared += 1
来源：http://dali.shuidangran.top/Article/details/gtmrptmzgw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cheryme.top/Article/details/gthhmlohyc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangshuangyany.cn/Article/details/gtjvcrsgfq.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtpffuudmb.html

Java: synchronized (this) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gtpakpjsim.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sysykeji.top/Article/details/gtlmijzqor.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.smart0.xyz/Article/details/gtlzuqpcmb.html

C#:   lock (gate) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gtatozvork.html

[O04] 定义异步函数并等待
来源：http://dali.mhx1999.top/Article/details/gthixesjgg.html

Py:   async def f():⏎    await g()
来源：http://dali.mhx1999.top/Article/details/gtnenvvulo.html


<!-- 参考信息 -->