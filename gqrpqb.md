代发 wailian999

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gtmbkafrnf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.birdmap.top/Article/details/gtlekxwrcm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtfqlqkdyx.html

[K05] 深拷贝对象
来源：http://dali.dianchejie.cn/Article/details/gtbfjhieot.html

Py:   copy.deepcopy(obj)
来源：http://dali.aibaodan.cn/Article/details/gtpelxktjy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.haohaochexian.top/Article/details/gtffhrmoiy.html

JS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gtmqhhckep.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtawtihoxn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xylfe.cn/Article/details/gtmlkxckza.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nwbrower.top/Article/details/gtdhaijwvk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gtqwnidbmh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gtnvorggpr.html

[K06] 解析 URL 查询串
来源：http://dali.nwbrower.top/Article/details/gtbqjcdcyv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gtsyftywkz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gtlcueerms.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gtaleoygfv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtuvewxmfl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yueranfly.top/Article/details/gtpxqdvrze.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtyosetzkv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtfaajnzop.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtqxcztimd.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gtvswawikf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtksnbvheo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zdqjudy.top/Article/details/gtrwkjkibv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtzzxvdpza.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtcpdtocrk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtsbabakda.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gtvtsjarrr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cdnleiting.top/Article/details/gtdwdweitx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtnlhngtsf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cucudq.cn/Article/details/gtysouuiee.html

Py:   pickle.dumps(obj)
来源：http://dali.tianlin.xyz/Article/details/gtydmgeqiy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yonumen.top/Article/details/gteyxfuteg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtcvyrctvz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gteeupwzty.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hammf.cn/Article/details/gtzlgipndl.html

Go:   encoding/gob
来源：http://dali.cashguo.top/Article/details/gtrfrnyslh.html

Ruby: Marshal.dump(obj)
来源：http://dali.xylfe.cn/Article/details/gtdrwwakvv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gtlfatjyaz.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtzmhtwklm.html

L. 网络请求
来源：http://dali.snrcjt.cn/Article/details/gtbcgiauxd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtesmsegtn.html

[L01] 发送 GET 请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvujuxtt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.havefunace.top/Article/details/gtkhhqjqze.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhiwuduotai.top/Article/details/gtdtmknvwv.html

JS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gttxedohhw.html

TS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtqlaltxac.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sweek.top/Article/details/gtfjyghcje.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhongyouzk.top/Article/details/gthdfwicsa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuanzx.com/Article/details/gtjmlkcidk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqyqvjduh.html

[L02] 发送 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gtobriudlo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cashguo.top/Article/details/gtubgftpyz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gtgwsvathv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aizwys.cn/Article/details/gtjxmnjhyc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gtqbpkcepj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shzxlz.cn/Article/details/gtkglcenav.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jlsjyb.cn/Article/details/gtrvdnisek.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gtvorwxtal.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ydzc1.top/Article/details/gteompgnli.html

[L03] 设置自定义请求头
来源：http://dali.havefunace.top/Article/details/gttdjxygbt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shzxlz.cn/Article/details/gtvncwvdfd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jiagoushi.top/Article/details/gtbljjlztd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gtodkworqe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gtznorghqu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtiocyirzz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gttgphdkrf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.kuanghao11.cn/Article/details/gtkcbxnkoq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gtstshnfdy.html

[L04] 设置超时
来源：http://dali.sysykeji.top/Article/details/gtohqfpknm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.quarkkingdee.top/Article/details/gttqaqaysh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gtnaxacddj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gtyhwjokbs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gtkxkxfllo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tian-w.cn/Article/details/gtbgflavxn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fengsongda.top/Article/details/gtnonwilwh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sysykeji.top/Article/details/gtviwyszul.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jianghu66.top/Article/details/gtztshemcd.html

[L05] 上传文件（multipart）
来源：http://dali.yueranfly.top/Article/details/gtnqhszzsu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xylfe.cn/Article/details/gtrdbjeqdg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangdashe.top/Article/details/gtnwzlqzgu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gtsrqhecya.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gtnasxzpyh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgufenzy.top/Article/details/gtepcbufim.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangshuangyany.cn/Article/details/gtdzhmaixh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgfzy.top/Article/details/gtigbhgauz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aizwys.cn/Article/details/gtqvslehtz.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gthqfxnlkn.html

Py:   resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgsjwinn.html

PHP:  json_decode($body, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtioyuergv.html

JS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtdietqbcn.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gttivabvjn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtalumgcpu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gtxhbkvxlq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuanzx.com/Article/details/gtkxywmswq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtakgmegcy.html

[L07] 处理 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gtdtrsfgdw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhengqikj.top/Article/details/gtnoxokzzv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gttgnlofqr.html

JS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gtalqymajb.html

TS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtrpobreqe.html

Java: resp.statusCode()
来源：http://dali.guowangkeji.top/Article/details/gtjuryjtmt.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtzmnnqeve.html

Ruby: resp.code.to_i
来源：http://dali.havefunace.top/Article/details/gtxzaudafe.html

C#:   (int)resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gthjniyjsk.html

[L08] 并发请求多个地址
来源：http://dali.wangshuangyany.cn/Article/details/gtcsxzlgnf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sweek.top/Article/details/gtdbmdphtj.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhengqikj.top/Article/details/gtqwiyvqie.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtutfnxfds.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gtivuuixuj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gtuinuvrkh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gtfetfucbu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.bjfxy.top/Article/details/gtnbfrndox.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtqkcmaz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtiywqfilq.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcdncehf.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtnpxmyjtd.html

[M01] 读取命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gthzlpcvjl.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gtdamrmlcy.html

PHP:  $argv;  $argc;
来源：http://dali.zhiwuduotai.top/Article/details/gtoeoxgwzl.html

JS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtmgtqvwjp.html

TS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtzugrhbvg.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gtvpctcpvf.html

Go:   os.Args[1:]
来源：http://dali.cdnleiting.top/Article/details/gtwhknpthp.html

Ruby: ARGV
来源：http://dali.yuxming.cn/Article/details/gtszwwmixf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtktguipkg.html

[M02] 读取环境变量
来源：http://dali.ivvv.top/Article/details/gtyegktegk.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtzhagdfds.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtjyeyydpl.html

JS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gtosrjwkpx.html

TS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtnblmmckw.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gtekjtilwa.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gthyhjcjks.html

Ruby: ENV["HOME"]
来源：http://dali.dashuyun.cn/Article/details/gtbggivvqb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gtciizrkuh.html

[M03] 执行外部命令
来源：http://dali.jqgfzy.top/Article/details/gtwpnnruwr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtwcnwqozz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dianchejie.cn/Article/details/gtphvneyns.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtrlajihiw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gtwcniwewg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pycfn.com/Article/details/gtkoogkgjc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tanke756.top/Article/details/gtmeacmfbo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shangyingyoupin.top/Article/details/gtuwkgnopf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gzhubu.top/Article/details/gtokoeteax.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gtpsayvtis.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gtpwdjsdxa.html

PHP:  getcwd();
来源：http://dali.svipenyu.cn/Article/details/gtjserifrw.html

JS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gttslngnah.html

TS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gtwbayakex.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guannengcc.top/Article/details/gthwhghnbj.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gtqgygxhqg.html

Ruby: Dir.pwd
来源：http://dali.quarkkingdee.top/Article/details/gtwxjyzxas.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuejxazzf.html

[M05] 设置退出码
来源：http://dali.shangyingyoupin.top/Article/details/gtcwbubwua.html

Py:   sys.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtrhxccpcg.html

PHP:  exit(1);
来源：http://dali.mhx1999.top/Article/details/gtmetobgkk.html

JS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtjgojrmvw.html

TS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtwmjoprfg.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtuiowltcw.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtyukacsca.html

Ruby: exit 1
来源：http://dali.shzxlz.cn/Article/details/gtsdknhlhm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigufen.top/Article/details/gtagosvcls.html

[M06] 向标准错误输出
来源：http://dali.wangdashe.top/Article/details/gtcvknraau.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gtzcienpep.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenzaomai.com/Article/details/gtiucebnaq.html

JS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrbtnwgq.html

TS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gtzymypetn.html

Java: System.err.println("err")
来源：http://dali.aizwys.cn/Article/details/gtlukxibbc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigufen.top/Article/details/gtfhizjowt.html

Ruby: warn "err"
来源：http://dali.smart0.xyz/Article/details/gtntbgrver.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuanzhike.top/Article/details/gtzyuyshvo.html

[M07] 判断是否为主入口
来源：http://dali.cashguo.top/Article/details/gttpwofkhz.html

Py:   if __name__ == "__main__":
来源：http://dali.cashguo.top/Article/details/gtnhblbdwm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tanke756.top/Article/details/gtevpjwzww.html

JS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtrkdwofxo.html

TS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtjikhrzac.html

Java: public static void main(String[] args)
来源：http://dali.zhoulong.xyz/Article/details/gtsxcqhuhr.html

Go:   func main()
来源：http://dali.yueranfly.top/Article/details/gtjrtfprzv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.kuanghao11.cn/Article/details/gtpntmbdhi.html

C#:   static void Main(string[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstyngpfg.html

[M08] 获取系统与运行时信息
来源：http://dali.yanxiufei.cn/Article/details/gtssgmauwl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigfzy.top/Article/details/gtqzetjmgz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyibdbsm.html

JS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gtcrmafkiz.html

TS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gtwfeocbww.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftraayty.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.kuanghao11.cn/Article/details/gtdyojnwju.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtziwyxb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gtjzamwqqr.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtotggrmhs.html

N. 数据结构与算法
来源：http://dali.guowangkeji.top/Article/details/gtsogvuikp.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqumwowut.html

[N01] 二分查找（有序数组）
来源：http://dali.bjfxy.top/Article/details/gtsnfaowsu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtoocknatz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gtagznorch.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtdcxledkj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gtkrjktldo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtqfdongep.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtxodothto.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guowangkeji.top/Article/details/gtwrknxezf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gthtdhhdzk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yanxiufei.cn/Article/details/gtrshjabvk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckkahcvw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajzxbdhx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtlqscemnw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtczxtagjt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cheryme.top/Article/details/gtotgrvcho.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gtxfjceoss.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gtdthcwhji.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gtlojgenpi.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangtech.top/Article/details/gtowimrhmj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhixingplan.top/Article/details/gtihsbupzj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hongshengwenyu.top/Article/details/gtynhvmveg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gtoyyvtppq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gtbaiexgvp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258888.top/Article/details/gtgiigjvou.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ydzc1.top/Article/details/gtdqdbyeue.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daxiang520.top/Article/details/gtlalupmdk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangdashe.top/Article/details/gtopdxzyex.html

[N04] 斐波那契数列
来源：http://dali.yvedp.cn/Article/details/gtkgoewxcv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtquaiyflv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqaafajbk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtqphmgpmn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gtuakzztco.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258.top/Article/details/gtdudwutxn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yvedp.cn/Article/details/gtwkxhnzzf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gtfxnkyxuu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtnwecyykg.html

[N05] 最大公约数
来源：http://dali.zhoulong.xyz/Article/details/gtdmkjwnjq.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gtdeatbnay.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.9152youxi.cn/Article/details/gtdtrsqmvc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyxknise.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtuykwzbvx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.feifeiyinyue.top/Article/details/gtglvuluzi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aibaodan.cn/Article/details/gtlmvibjqd.html

Ruby: a.gcd(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcupifqfh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.birdmap.top/Article/details/gtcspqknnr.html

[N06] 判断回文字符串
来源：http://dali.hnqzz.top/Article/details/gtlvfxccxp.html

Py:   s == s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluazbmfr.html

PHP:  $s === strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gtkhxliknw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtfzqkwzqb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtlnlgazqh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.9152youxi.cn/Article/details/gtgzjrmpat.html

Go:   // 双指针从两端比较
来源：http://dali.cashguo.top/Article/details/gtikbnubez.html

Ruby: s == s.reverse
来源：http://dali.nanxinkj.top/Article/details/gtlarmxrgj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtmmvabyfw.html

[N07] 两数之和（返回下标）
来源：http://dali.zhiwuduotai.top/Article/details/gtzqjehylx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhengqikj.top/Article/details/gtpjqtjfsy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cheryme.top/Article/details/gtdthpiubr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guannengcc.top/Article/details/gtlvferkeb.html

TS:   // 手写 Map<string, number>
来源：http://dali.yongpay.top/Article/details/gticvpcdcl.html

Java: // 手写 HashMap
来源：http://dali.jiagoushi.top/Article/details/gthrkjbbcl.html

Go:   // 手写 map[int]int
来源：http://dali.yj202588.top/Article/details/gtxkbjetjj.html

Ruby: // 手写 Hash
来源：http://dali.quarkkingdee.top/Article/details/gtivvvsfgg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jyoumei.cn/Article/details/gtwdqwkppf.html

[N08] 生成全排列
来源：http://dali.ybcxt.top/Article/details/gtfvjxrwro.html

Py:   itertools.permutations(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtiswlqrut.html

PHP:  // 手写递归交换
来源：http://dali.ybcxt.top/Article/details/gtxolmpiyt.html

JS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgathyhaj.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtsbjnaqof.html

Java: // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtskimwjlt.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtndmzokyy.html

Ruby: arr.permutation.to_a
来源：http://dali.xylfe.cn/Article/details/gtgytrvnqh.html

C#:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtrtdhpmsm.html

[N09] 栈与队列
来源：http://dali.cucudq.cn/Article/details/gtqzawzldf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftkybjyj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtaeyjkhvg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtmglphtof.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fengsongda.top/Article/details/gtmgkjxgjm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.meibo888.top/Article/details/gtozghbugp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.andypj.xyz/Article/details/gteiypespk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtthcirsgh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gturrwjane.html

[N10] 链表节点定义
来源：http://dali.ehwqpu.com/Article/details/gtmfwtlydk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigfzy.top/Article/details/gtriqcogkg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jiagoushi.top/Article/details/gtehaknvht.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sufxvd.cn/Article/details/gtbzugssty.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jlsjyb.cn/Article/details/gtbxlbqsud.html

Java: class Node { int v; Node next; }
来源：http://dali.zhongyouzk.top/Article/details/gtpicawoor.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlyaydbhk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ybcxt.top/Article/details/gtovkylrpm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmcxxozfl.html

[N11] 二叉树中序遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtcosyesbm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangshuangyany.cn/Article/details/gtqabwkmal.html

PHP:  // 手写递归函数
来源：http://dali.chenjidiqi.icu/Article/details/gtsoxmvfvr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gtutdqopel.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gtdiobtrjh.html

Java: // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtjhshimgq.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtvnjchxqe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jiagoushi.top/Article/details/gttaxotkyw.html

C#:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtfjbltqok.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hfpthk.cn/Article/details/gtqohguxgf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aizwys.cn/Article/details/gtkbmrceer.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.birdmap.top/Article/details/gtudyrlkfa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gtmiecjxfw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gtmmmnwfay.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxuanxn.top/Article/details/gtucpcgmiy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.birdmap.top/Article/details/gtbqzquuxm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtdzhveuqu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gtamoqtzlv.html


<!-- 参考信息 -->