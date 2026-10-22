代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.ydzc1.top/Article/details/gtgokcsgio.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gtcvvzzcda.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhengqikj.top/Article/details/gtotbaztdu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gtggewfsiw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gthklidgon.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gogol.net.cn/Article/details/gtwlsowjyj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtwdpvgiew.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtluzmoean.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtrsapzxac.html

[K07] 进制转换
来源：http://dali.jianghu66.top/Article/details/gtyqfuocml.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtxfbjlnbw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jiagoushi.top/Article/details/gtykywpjml.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtqftoohqv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtarqurygz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtaukmmhjn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnqzz.top/Article/details/gtsaghcbuk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jianghu66.top/Article/details/gtvfhxcyta.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtpwguvvsm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tanke756.top/Article/details/gthstzydka.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxinkj.top/Article/details/gttedmkwlm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuetiantiany.cn/Article/details/gttaclgsxo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvceylfj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gtbuceqlzw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinghuilouyu.cn/Article/details/gtukrzazuq.html

Go:   encoding/gob
来源：http://dali.haohaochexian.top/Article/details/gtfizeeixe.html

Ruby: Marshal.dump(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtzzxlghvi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gtryhdzqqn.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtyowcvlhz.html

L. 网络请求
来源：http://dali.hysaishi.cn/Article/details/gtoeojtbrw.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtxjmquvve.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsgpfwxs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangshuangyany.cn/Article/details/gthxaedfvb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yvedp.cn/Article/details/gtmmmwdjjs.html

JS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gtpdjvhpfp.html

TS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gtmmlytcnr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sysykeji.top/Article/details/gtzgiyxbkx.html

Go:   resp, err := http.Get(url)
来源：http://dali.jiagoushi.top/Article/details/gtvawccrqo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hfpthk.cn/Article/details/gtnxogwjwj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.iojbl.cn/Article/details/gtkeoshnlk.html

[L02] 发送 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gtjtifvzcn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gtindgnntf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tianlin.xyz/Article/details/gtdurwpvai.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcbzdklw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gtcvsudufk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gogol.net.cn/Article/details/gtfqaqcyfc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xinyue.icu/Article/details/gtabhiregn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gtyxnjgmvc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ehwqpu.com/Article/details/gtlyfxvjvq.html

[L03] 设置自定义请求头
来源：http://dali.pycfn.com/Article/details/gtpzhcyenm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhixingplan.top/Article/details/gtbdieqqcv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.andypj.xyz/Article/details/gtssuebrtb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtexerwvdk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtmsaaxvoo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjnwbeni.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gthivcwnxr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuxming.cn/Article/details/gtxwxrllta.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gteyzebqak.html

[L04] 设置超时
来源：http://dali.yj20258888.top/Article/details/gtkrcgrigo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gtybtkvtxw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.haohaochexian.top/Article/details/gtkwgqttck.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gtuprvpigt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtuayotlzf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gtxbiyzhkl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shangyingyoupin.top/Article/details/gtspnaxvdk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.c1oappe.top/Article/details/gtujloddfl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gtjkhvbyzw.html

[L05] 上传文件（multipart）
来源：http://dali.mhx1999.top/Article/details/gtxplvtfrd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gtytnuqojo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yonumen.top/Article/details/gtnjhyuwhg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gtklbxihul.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gtomogijzz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxoklkhr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.0kj1m.cn/Article/details/gtdeuukwra.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gaohongyu789.top/Article/details/gtupdaxitl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtmtxrknud.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigufen.top/Article/details/gtegkyzmzs.html

Py:   resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtffftnwxj.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258888.top/Article/details/gtdevpzkss.html

JS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtntvjdetp.html

TS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtuzlbtndb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtvguengct.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daxiang520.top/Article/details/gtdbmskinb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.smart0.xyz/Article/details/gtczpcjwek.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tian-w.cn/Article/details/gtpufrkgjw.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gttzuqwwnj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tianlin.xyz/Article/details/gttbquxgxp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuxming.cn/Article/details/gtyqwktdgm.html

JS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gtyffdwdar.html

TS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtfxljzwgf.html

Java: resp.statusCode()
来源：http://dali.shuidangran.top/Article/details/gtrulrwqmb.html

Go:   resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtlovmzlul.html

Ruby: resp.code.to_i
来源：http://dali.meibo888.top/Article/details/gtyuhoykix.html

C#:   (int)resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gtbctdcuwa.html

[L08] 并发请求多个地址
来源：http://dali.jinqigfzy.top/Article/details/gtnsmlqary.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxinkj.top/Article/details/gtxjomzfij.html

PHP:  curl_multi_init() 系列
来源：http://dali.sxryk.cn/Article/details/gtyaizfjlr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtnuwtfmil.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtajpwkcga.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gtntpoqohx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gaohongyu789.top/Article/details/gteyesxxwr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenlongwang.top/Article/details/gtfyzqjsyc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zycfv.cn/Article/details/gtdsihhiek.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gthnzyrygg.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gtwpvycpzc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbajaedma.html

[M01] 读取命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtlotnivsk.html

Py:   sys.argv[1:]
来源：http://dali.haohaochexian.top/Article/details/gtkujoavri.html

PHP:  $argv;  $argc;
来源：http://dali.guowangkeji.top/Article/details/gtyqomdmtt.html

JS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gttaaofocv.html

TS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtztafdhug.html

Java: args 数组（main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gtleqedsec.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdyzczbs.html

Ruby: ARGV
来源：http://dali.gzhubu.top/Article/details/gticltqkye.html

C#:   args 数组（Main 方法参数）
来源：http://dali.meibo888.top/Article/details/gtlqwttcye.html

[M02] 读取环境变量
来源：http://dali.daxiang520.top/Article/details/gtadpptiww.html

Py:   os.environ.get("HOME")
来源：http://dali.zycfv.cn/Article/details/gthibsqxxh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gthjxezyve.html

JS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gttgltcqzs.html

TS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gtrqxwabux.html

Java: System.getenv("HOME")
来源：http://dali.meibo888.top/Article/details/gtegytpnlw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ivvv.top/Article/details/gtblzamauq.html

Ruby: ENV["HOME"]
来源：http://dali.tianlin.xyz/Article/details/gtqwvpaaap.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtjtrcnvod.html

[M03] 执行外部命令
来源：http://dali.zdqjudy.top/Article/details/gtosflooio.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ydzc1.top/Article/details/gtfyxliemn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zdqjudy.top/Article/details/gtjbsogofb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gtgdufnbap.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtbaonlaye.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihvttglf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shuidangran.top/Article/details/gtuhxlyziu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daxiang520.top/Article/details/gtakmncbqc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenlongwang.top/Article/details/gtqvvkwpry.html

[M04] 获取当前工作目录
来源：http://dali.xuetiantiany.cn/Article/details/gtargojmfj.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gtnycddtbn.html

PHP:  getcwd();
来源：http://dali.jianghu66.top/Article/details/gtjtyphciz.html

JS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gtipoallgv.html

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtzleezgto.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gtxcvkdgjz.html

Go:   os.Getwd()
来源：http://dali.guannengcc.top/Article/details/gtrfwyeqrj.html

Ruby: Dir.pwd
来源：http://dali.haohaochexian.top/Article/details/gtuynvycot.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.c1oappe.top/Article/details/gtmckytlll.html

[M05] 设置退出码
来源：http://dali.haohaochexian.top/Article/details/gtamxbndrl.html

Py:   sys.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtkdslelmg.html

PHP:  exit(1);
来源：http://dali.hywenlv.cn/Article/details/gtbbebfxhm.html

JS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtslleydax.html

TS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtsxkzdqtz.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtmkectuie.html

Go:   os.Exit(1)
来源：http://dali.guannengcc.top/Article/details/gttzbjvokj.html

Ruby: exit 1
来源：http://dali.jyoumei.cn/Article/details/gttslhqivv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tian-w.cn/Article/details/gthavqucnt.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gtxhjmacyt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gtgzujknmv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gtpzdkousf.html

JS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtplhtwmds.html

TS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gtfqwkvelx.html

Java: System.err.println("err")
来源：http://dali.gogol.net.cn/Article/details/gtkvnouxbb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daria6918.cn/Article/details/gtwtbpleyd.html

Ruby: warn "err"
来源：http://dali.vqdsnc.cn/Article/details/gtneilwoch.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ydzc1.top/Article/details/gtlbssvzgc.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gtbemaqpmr.html

Py:   if __name__ == "__main__":
来源：http://dali.gzhubu.top/Article/details/gtotrolehw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxinkj.top/Article/details/gtjldjiajy.html

JS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gtitdxqror.html

TS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirdivnpy.html

Java: public static void main(String[] args)
来源：http://dali.nanxinkj.top/Article/details/gtojrzuprz.html

Go:   func main()
来源：http://dali.yongpay.top/Article/details/gtapizksni.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.snrcjt.cn/Article/details/gthicxdvcr.html

C#:   static void Main(string[] args)
来源：http://dali.gaohongyu789.top/Article/details/gtyipmaegq.html

[M08] 获取系统与运行时信息
来源：http://dali.zycfv.cn/Article/details/gthtdythdj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jyoumei.cn/Article/details/gtzymuhaxt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.havefunace.top/Article/details/gtuxecukqn.html

JS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gtdgurocow.html

TS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gtfgqdctvf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.havefunace.top/Article/details/gtrwpjjqot.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gaohongyu789.top/Article/details/gtfqirayro.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zdqjudy.top/Article/details/gtfslcbuyl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgufenzy.top/Article/details/gtzsftsyxh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtkqdqgkqj.html

N. 数据结构与算法
来源：http://dali.nwbrower.top/Article/details/gtuijzquca.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtsnxphfsl.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgfzy.top/Article/details/gthjoeausl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.316326.xyz/Article/details/gtroauzdqb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtoixelbso.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtsgvrgndn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtdrwexmuv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gttthpezyq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzsyuxpi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.pycfn.com/Article/details/gtbmrlkjyr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtlqqgmajs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yvedp.cn/Article/details/gtyidcyxyd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtblbpfeee.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gtklypgeml.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtcmpaibsv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gtfweqhjgk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxxjhvut.html

Go:   slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gtrrazytzr.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gtxsdpjest.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yangfankeji.com/Article/details/gtcsbtiqvg.html

[N03] 快速排序（分治示例）
来源：http://dali.svipenyu.cn/Article/details/gtrlibnbpf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gtopzhtrmv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxinkj.top/Article/details/gtzgyvvcje.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtuylfnvjl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gtueqfvsiz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.quarkkingdee.top/Article/details/gtasvcsvji.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cucudq.cn/Article/details/gtwitpwrir.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gtzbgkwhlp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shuidangran.top/Article/details/gtovzeksxz.html

[N04] 斐波那契数列
来源：http://dali.zhengqikj.top/Article/details/gtnnbtrtnn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtcodmtbbq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cashguo.top/Article/details/gtuvjxkaei.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtzwwlksds.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtzvlrxpcv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gtqqjhwtqe.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daxiang520.top/Article/details/gtegakmzif.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gtmuilyuey.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtkodgszvw.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gtkpsdtvuj.html

Py:   math.gcd(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtfysuiodx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xylfe.cn/Article/details/gtqmuqidbv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gtdkztqyqu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gtcydmxmvq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yongpay.top/Article/details/gtxjhpbdhv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xylfe.cn/Article/details/gtcmnlrram.html

Ruby: a.gcd(b)
来源：http://dali.xziqi.cn/Article/details/gtalpbajqo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gzhubu.top/Article/details/gtndcoiecb.html

[N06] 判断回文字符串
来源：http://dali.zhixingplan.top/Article/details/gtnroupkxm.html

Py:   s == s[::-1]
来源：http://dali.tian-w.cn/Article/details/gteohomqsd.html

PHP:  $s === strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtqbydsafy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhycpjub.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtdprucbjw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nwbrower.top/Article/details/gttmadlkwy.html

Go:   // 双指针从两端比较
来源：http://dali.aibaodan.cn/Article/details/gtqqimdpxx.html

Ruby: s == s.reverse
来源：http://dali.sweek.top/Article/details/gtpxiftaub.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gtswaonqoz.html

[N07] 两数之和（返回下标）
来源：http://dali.chenlongwang.top/Article/details/gtrlnmzuun.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.0kj1m.cn/Article/details/gtnzumqbqq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258.top/Article/details/gtboeogmuc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shangyingyoupin.top/Article/details/gtggebstun.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gtnugqquaq.html

Java: // 手写 HashMap
来源：http://dali.vqdsnc.cn/Article/details/gtasidxfva.html

Go:   // 手写 map[int]int
来源：http://dali.yuanzhike.top/Article/details/gtxeegafly.html

Ruby: // 手写 Hash
来源：http://dali.pengpengdd.cyou/Article/details/gtmyftvqys.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.kuanghao11.cn/Article/details/gtybkxurah.html

[N08] 生成全排列
来源：http://dali.sxryk.cn/Article/details/gttbhpiluq.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtvkdozhhm.html

PHP:  // 手写递归交换
来源：http://dali.hnqzz.top/Article/details/gtrgoulgkm.html

JS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtkwbqybfo.html

TS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtcunltark.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtncdpmuah.html

Go:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtekmemcyq.html

Ruby: arr.permutation.to_a
来源：http://dali.yuanzhike.top/Article/details/gtzgatlujg.html

C#:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtnmnuaopv.html

[N09] 栈与队列
来源：http://dali.shuidangran.top/Article/details/gtisoanqnb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gotoacloud.top/Article/details/gtmkizcynk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtezttwjnd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gtffophane.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258.top/Article/details/gtwdzmnmqu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtaxsemmxr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ehwqpu.com/Article/details/gtgpdzvjpz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtxjjpzdtd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gtrojpcqks.html

[N10] 链表节点定义
来源：http://dali.shuidangran.top/Article/details/gtiborvrxk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cashguo.top/Article/details/gtmtkiaofc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cdnleiting.top/Article/details/gtpnzdpmcc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.9152youxi.cn/Article/details/gtonlmzbtk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yangfankeji.com/Article/details/gtmlutbpil.html

Java: class Node { int v; Node next; }
来源：http://dali.pengpengdd.cyou/Article/details/gttbdeovdv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nwbrower.top/Article/details/gtwygfmbpy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ivvv.top/Article/details/gttiixfoje.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.0kj1m.cn/Article/details/gttgaakdoa.html

[N11] 二叉树中序遍历
来源：http://dali.sweek.top/Article/details/gtikwcxbjm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hywenlv.cn/Article/details/gtnibvaisi.html

PHP:  // 手写递归函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwszaazbj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gtyrqzwjjh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gtescvvpvb.html

Java: // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtzbzphytd.html

Go:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtmgczgzfh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhiwuduotai.top/Article/details/gtxjdnuctc.html

C#:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gttjmrkard.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cqqwz.cn/Article/details/gtvudnjbro.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jiagoushi.top/Article/details/gtimenejfm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gtyuxlsreg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gtzswbzxwf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gtzhayixql.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gtyheamvlz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gtlfkyahjw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtmpzxlpzk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtqzvnysmu.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtcrfnilkl.html

O. 并发与异步
来源：http://dali.sysykeji.top/Article/details/gtewpkzrgn.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtzynoxplo.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangtech.top/Article/details/gtuencqekx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daxiang520.top/Article/details/gtxylehqru.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sxryk.cn/Article/details/gtohjsjzjh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pycfn.com/Article/details/gttmyejtxy.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gtoiksbhnm.html

Java: new Thread(() -> f()).start()
来源：http://dali.hywenlv.cn/Article/details/gtlcibycar.html

Go:   go f()
来源：http://dali.0kj1m.cn/Article/details/gtczccgpld.html

Ruby: Thread.new { f }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthymeksre.html

C#:   Task.Run(() => F());
来源：http://dali.xylfe.cn/Article/details/gtcabhvlqo.html


<!-- 参考信息 -->