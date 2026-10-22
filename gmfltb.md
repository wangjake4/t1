代发 wailian999

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtltbbldwe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtkvgvvfvv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtlaggqkok.html

[K05] 深拷贝对象
来源：http://dali.dashuyun.cn/Article/details/gtqadwdepi.html

Py:   copy.deepcopy(obj)
来源：http://dali.gogol.net.cn/Article/details/gtchhudqex.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cheryme.top/Article/details/gtdrvzmsbj.html

JS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtkdibndiv.html

TS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gtgvblvqnd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhengqikj.top/Article/details/gtvjkkqdkh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xylfe.cn/Article/details/gtwgezysjt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daxiang520.top/Article/details/gtqlylpqgh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aibaodan.cn/Article/details/gtqwuvecuk.html

[K06] 解析 URL 查询串
来源：http://dali.dianchejie.cn/Article/details/gtzyootozk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtglfustqr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdubaxjwp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gtypwfipiy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gttizoystw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shuidangran.top/Article/details/gthunhvrxn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtmskgiuak.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtpflaulyc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtcrvhpnvl.html

[K07] 进制转换
来源：http://dali.316326.xyz/Article/details/gtzgncuanq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtybisjsck.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dianchejie.cn/Article/details/gthtoknyig.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtymrmhzop.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtmldnhoat.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtgbuzjdct.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ydzc1.top/Article/details/gtnkluqkiw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gttajofyml.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtmqondqyy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangtech.top/Article/details/gtalanmvvv.html

Py:   pickle.dumps(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsmeadlz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shuidangran.top/Article/details/gtrtzovodm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gtghkbjfpe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gtsltprqkt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jlsjyb.cn/Article/details/gtlwpgskuw.html

Go:   encoding/gob
来源：http://dali.zdqjudy.top/Article/details/gtkasinrei.html

Ruby: Marshal.dump(obj)
来源：http://dali.gzhubu.top/Article/details/gtzstlcptc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtocmgqlak.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtufwhnlwr.html

L. 网络请求
来源：http://dali.fzhhl.top/Article/details/gtjrdualst.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtiulrjsqh.html

[L01] 发送 GET 请求
来源：http://dali.snrcjt.cn/Article/details/gtumxebpfk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gteyrmlvlq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zycfv.cn/Article/details/gttnapgakw.html

JS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtsjsvsncd.html

TS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gtskirqlae.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhoulong.xyz/Article/details/gtkjrrnhsp.html

Go:   resp, err := http.Get(url)
来源：http://dali.0kj1m.cn/Article/details/gtmnzfkkbj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.quarkkingdee.top/Article/details/gtaybvonbt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hysaishi.cn/Article/details/gtkiaoiysm.html

[L02] 发送 POST JSON
来源：http://dali.sweek.top/Article/details/gtcfcqwdol.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gtppymvgvk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigufen.top/Article/details/gtxxkablmo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtruxctrji.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gtjkesdsjd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jyoumei.cn/Article/details/gtiusugumo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guowangkeji.top/Article/details/gtbugsrxhz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gotoacloud.top/Article/details/gtofgbfbon.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtriphlsvj.html

[L03] 设置自定义请求头
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuupdrpe.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenzaomai.com/Article/details/gtsuygukmk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jlsjyb.cn/Article/details/gtstuybyha.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtyumkceui.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpeojrxb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.quarkkingdee.top/Article/details/gtvcxcpxma.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gtmghhkbpg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjcdrush.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gttalpbhqd.html

[L04] 设置超时
来源：http://dali.havefunace.top/Article/details/gtdpdidpry.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xylfe.cn/Article/details/gtqexirgxd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangdashe.top/Article/details/gtbzkyxmal.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gtqiqmhfgg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gtwoksmrlw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cqqwz.cn/Article/details/gtgnowxazt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gtsrrlutdi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangshuangyany.cn/Article/details/gtiockumdf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sysykeji.top/Article/details/gtabznkmbt.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigfzy.top/Article/details/gtsbpnpgxa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ybcxt.top/Article/details/gtuftrscnp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aizwys.cn/Article/details/gtfqfxqzzb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gtixgwiqhk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtrdspxrea.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnxiangtu.top/Article/details/gtpzrwpyhi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gtttziyhjz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guannengcc.top/Article/details/gtwwgmgkjh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tanke756.top/Article/details/gtrfsikkju.html

[L06] 解析响应为 JSON
来源：http://dali.gzhubu.top/Article/details/gtivlrdimj.html

Py:   resp.json()
来源：http://dali.zycfv.cn/Article/details/gtejrryafe.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258888.top/Article/details/gtlbwfpxep.html

JS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtlssmblaj.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtsvrzyssl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtcctvrbzu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yueranfly.top/Article/details/gtdyntbktf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hammf.cn/Article/details/gtrhtnvmno.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pycfn.com/Article/details/gtvxouzwyl.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtbmyfrkmg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ybcxt.top/Article/details/gthrolgihv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvocddxt.html

JS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gtcelqplhk.html

TS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gtabzagmbo.html

Java: resp.statusCode()
来源：http://dali.c1oappe.top/Article/details/gtraveoqta.html

Go:   resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtzbhasbsm.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gtykruzbzy.html

C#:   (int)resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gtqagckhxo.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gtrgygnslt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenlongwang.top/Article/details/gtsikzfmvi.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gtykbumqjg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtugwtypcz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtzrfbnvem.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.svipenyu.cn/Article/details/gtgfnoruhd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.316326.xyz/Article/details/gtqjqhhcwz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ybcxt.top/Article/details/gtzugslnsn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cqqwz.cn/Article/details/gtwjefwcyw.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtebkmbprh.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gthiexyvyt.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtgeomctng.html

[M01] 读取命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtmhghdktn.html

Py:   sys.argv[1:]
来源：http://dali.fengsongda.top/Article/details/gtsxnuwrau.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbqcikcu.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtuurjpvch.html

TS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtsjutqlgr.html

Java: args 数组（main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gtyyfrvjti.html

Go:   os.Args[1:]
来源：http://dali.mhx1999.top/Article/details/gtzuapzaaw.html

Ruby: ARGV
来源：http://dali.gogol.net.cn/Article/details/gtgvznwamg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258.top/Article/details/gtrliqaxbk.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtbhjydnvf.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gtcrxuiiwk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gttphafgkr.html

JS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gtpygfyxmf.html

TS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gttpiuomug.html

Java: System.getenv("HOME")
来源：http://dali.yongpay.top/Article/details/gtvorxinzh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gttejetulj.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gtadrkyksc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtsfwmalqt.html

[M03] 执行外部命令
来源：http://dali.hysaishi.cn/Article/details/gtreckmske.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ehwqpu.com/Article/details/gthfosetwg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuanzx.com/Article/details/gtcgaxbhif.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtbxgcqmls.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttukzcmpu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fzhhl.top/Article/details/gtsauyqfgq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangdashe.top/Article/details/gtcimynxri.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yongpay.top/Article/details/gtrwlebyzs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jyoumei.cn/Article/details/gtrwluoeqq.html

[M04] 获取当前工作目录
来源：http://dali.9152youxi.cn/Article/details/gtnlmqdtys.html

Py:   os.getcwd()
来源：http://dali.sufxvd.cn/Article/details/gtflypktpb.html

PHP:  getcwd();
来源：http://dali.vqdsnc.cn/Article/details/gtuflzfjcr.html

JS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtumbfihgt.html

TS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtvvsjqake.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gaohongyu789.top/Article/details/gtmmbtimwg.html

Go:   os.Getwd()
来源：http://dali.cheryme.top/Article/details/gtanajeobo.html

Ruby: Dir.pwd
来源：http://dali.nanxuanxn.top/Article/details/gtzelgmset.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangshuangyany.cn/Article/details/gtkdofgcra.html

[M05] 设置退出码
来源：http://dali.jlsjyb.cn/Article/details/gtnspuaxcz.html

Py:   sys.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtmyryrgrf.html

PHP:  exit(1);
来源：http://dali.yanxiufei.cn/Article/details/gtmqzjmipb.html

JS:   process.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtzcrbdizh.html

TS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtbsixldpp.html

Java: System.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtnnheizuk.html

Go:   os.Exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtqfhhnjbe.html

Ruby: exit 1
来源：http://dali.shzxlz.cn/Article/details/gtalexrviv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.bjfxy.top/Article/details/gtlygjxgck.html

[M06] 向标准错误输出
来源：http://dali.shzxlz.cn/Article/details/gtoaptnavf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gtgtgzhbgc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gthvwspfan.html

JS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gtuvwhlvnz.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtevchshjk.html

Java: System.err.println("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtsuxcinzj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xinyue.icu/Article/details/gtfqyzyynu.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gtzxdzljcn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ybcxt.top/Article/details/gtorcwniwu.html

[M07] 判断是否为主入口
来源：http://dali.redwolf501.top/Article/details/gtpvibfuwm.html

Py:   if __name__ == "__main__":
来源：http://dali.havefunace.top/Article/details/gtluzupvlo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfiueejn.html

JS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtieeaavjv.html

TS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gtzzkxsdoo.html

Java: public static void main(String[] args)
来源：http://dali.jqgfzy.top/Article/details/gtplrljwkf.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gtnrriiauj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.316326.xyz/Article/details/gtaoubwxfc.html

C#:   static void Main(string[] args)
来源：http://dali.yueranfly.top/Article/details/gtbmwxlpdv.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gtkomotqdh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhengqikj.top/Article/details/gtjyiqzjen.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fengsongda.top/Article/details/gtgegjozdt.html

JS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtnmzpixtd.html

TS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gtylvkskaj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hammf.cn/Article/details/gtyohyrezq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xziqi.cn/Article/details/gtnfptuqil.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gtinditwok.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.meibo888.top/Article/details/gtbiylebob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtanokafba.html

N. 数据结构与算法
来源：http://dali.sysykeji.top/Article/details/gtwupmdynr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtnaxffaai.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxndgwrmp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkljzyios.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.9152youxi.cn/Article/details/gttpxqtmer.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtoledtznw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtrrfkkgav.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtygpjggic.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtpufwcgmu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.vqdsnc.cn/Article/details/gtashcuexe.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtpirpqavr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.smart0.xyz/Article/details/gtrhvizxds.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesqtnydk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.bjfxy.top/Article/details/gtimugopis.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtawmhozxz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtxcqkppdw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ydzc1.top/Article/details/gtdvlpvlnm.html

Go:   slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtcjfdqgjq.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgyquurt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtcfnkmyne.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gttuootpxn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmuzyzbn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gtvmlpwxwk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gtjcltjfkc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gteqgiymvp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuanzx.com/Article/details/gtiiptxmeu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxuanxn.top/Article/details/gtoozeovim.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.feifeiyinyue.top/Article/details/gteveblwcl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sufxvd.cn/Article/details/gtvjmmatzp.html

[N04] 斐波那契数列
来源：http://dali.yuanzhike.top/Article/details/gtyhupszyx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtikkitjhu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sxryk.cn/Article/details/gtswumwogx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtmesvnzvz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtyywbvmkv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtxyktwite.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ppjwa.cn/Article/details/gtctvnfvev.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gtrcdkbuyo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtuudkruef.html

[N05] 最大公约数
来源：http://dali.ppjwa.cn/Article/details/gtkdkcgxcs.html

Py:   math.gcd(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfihcxibz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtkhelfgox.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtexycpypl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258888.top/Article/details/gtswmywxqu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenzaomai.com/Article/details/gtthjayepb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgfzy.top/Article/details/gtolrktgiq.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtenldbuwx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yueranfly.top/Article/details/gtvxzndzzq.html

[N06] 判断回文字符串
来源：http://dali.jianghu66.top/Article/details/gtlnngmbpn.html

Py:   s == s[::-1]
来源：http://dali.meibo888.top/Article/details/gtrcotbgtk.html

PHP:  $s === strrev($s);
来源：http://dali.redwolf501.top/Article/details/gtgqrgameh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtzikleiuo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtsstiuacq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jianghu66.top/Article/details/gtcftcofxf.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gtafwzmxdk.html

Ruby: s == s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvvqorit.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gtcbhgadbh.html

[N07] 两数之和（返回下标）
来源：http://dali.gogol.net.cn/Article/details/gtoevmgdqh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gthqigxdsa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuanzx.com/Article/details/gtvczxkjtk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xylfe.cn/Article/details/gtflprevcm.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gtxvcybjqm.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangtech.top/Article/details/gtifnurfyg.html

Go:   // 手写 map[int]int
来源：http://dali.guowangkeji.top/Article/details/gtaxjwakrm.html

Ruby: // 手写 Hash
来源：http://dali.fengsongda.top/Article/details/gtkudpqmss.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gzhubu.top/Article/details/gtfoprbncn.html

[N08] 生成全排列
来源：http://dali.jlsjyb.cn/Article/details/gtvdxahxit.html

Py:   itertools.permutations(arr)
来源：http://dali.dashuyun.cn/Article/details/gtlilwvuub.html

PHP:  // 手写递归交换
来源：http://dali.tian-w.cn/Article/details/gtqdjrdxab.html

JS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtlpbcqegs.html

TS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtvrxnazsw.html

Java: // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtipovqecd.html

Go:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtqjqqqehk.html

Ruby: arr.permutation.to_a
来源：http://dali.iojbl.cn/Article/details/gtgoqibpfv.html

C#:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtocszdesj.html

[N09] 栈与队列
来源：http://dali.ydzc1.top/Article/details/gtcvbqixiv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhixingplan.top/Article/details/gtcxuqdzjb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yonumen.top/Article/details/gtqxyttxlz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtczwxytdc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgufenzy.top/Article/details/gtgiswkmkc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yueranfly.top/Article/details/gtxpaoevdt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gtshvbfsip.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtzdpmetfc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.iojbl.cn/Article/details/gtbqwplomq.html

[N10] 链表节点定义
来源：http://dali.xylfe.cn/Article/details/gtkpwhjupw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangtech.top/Article/details/gtmffwergz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigufen.top/Article/details/gtfezqvbcn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ybcxt.top/Article/details/gtoopweajw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.mhx1999.top/Article/details/gtbpeguesg.html

Java: class Node { int v; Node next; }
来源：http://dali.gzhubu.top/Article/details/gtpptlmtoe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258.top/Article/details/gteutklggz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.svipenyu.cn/Article/details/gtlcbsqqit.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.iojbl.cn/Article/details/gtatauzpxv.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gtzkujpjkm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cqqwz.cn/Article/details/gtagganqku.html

PHP:  // 手写递归函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtuipdcztg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtqigfpyyc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gteuvitjep.html

Java: // 手写递归
来源：http://dali.birdmap.top/Article/details/gtyqgftqyt.html

Go:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtapkwrzpf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yvedp.cn/Article/details/gtjfnpwglc.html

C#:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gthlwyghvn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuxming.cn/Article/details/gtvjzskqro.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zdqjudy.top/Article/details/gtkyxwlxyf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnrmaedk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gtwwwomyqv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gtpsqxtyey.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gtatgudbkd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.mhx1999.top/Article/details/gtdvdbnnib.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinqigfzy.top/Article/details/gtvdfwwjdw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gtixlquxvf.html


<!-- 参考信息 -->