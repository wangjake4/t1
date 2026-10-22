代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.dashuyun.cn/Article/details/gtleeadghs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gtjsebhuaw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.birdmap.top/Article/details/gtbyaxhqoq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtcqcigoii.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gthuvnmemu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sufxvd.cn/Article/details/gtqrabamkl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtaxgpisky.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtvpaswctn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtorimyfhn.html

[K07] 进制转换
来源：http://dali.redwolf501.top/Article/details/gttkpsmjea.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtiishxavs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258888.top/Article/details/gtcblxuykq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtrxiscyut.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtbispersq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtnbeepxmf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenzaomai.com/Article/details/gtdsujkqrq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ehwqpu.com/Article/details/gtfylfrssc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtjoqnhbbr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guowangkeji.top/Article/details/gtdenxunva.html

Py:   pickle.dumps(obj)
来源：http://dali.jiagoushi.top/Article/details/gtryhumqae.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.smart0.xyz/Article/details/gtmnnvkxpy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtaddswyyp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gtygdeywgr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gtkewjypza.html

Go:   encoding/gob
来源：http://dali.feifeiyinyue.top/Article/details/gtgoppujox.html

Ruby: Marshal.dump(obj)
来源：http://dali.hywenlv.cn/Article/details/gtzcarsskj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gtntispvhm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gthsgqbitp.html

L. 网络请求
来源：http://dali.zhongyouzk.top/Article/details/gtqwptqjim.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtimbgxuty.html

[L01] 发送 GET 请求
来源：http://dali.aizwys.cn/Article/details/gtpaylquxn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gtsumlgxqn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ppjwa.cn/Article/details/gtovrxsims.html

JS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gtdhviieab.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrvqdpqz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenjidiqi.icu/Article/details/gtbmltpmrk.html

Go:   resp, err := http.Get(url)
来源：http://dali.0kj1m.cn/Article/details/gtusulytjj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.9152youxi.cn/Article/details/gtupfmgvfc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daxiang520.top/Article/details/gtyoumagkz.html

[L02] 发送 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtsknrhapk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fengsongda.top/Article/details/gtdsyhtmtx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangdashe.top/Article/details/gtgutbfaxc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtebphwhmi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtdynizwuz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.andypj.xyz/Article/details/gtlbvfvuyk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aizwys.cn/Article/details/gtnkaqrkju.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yongpay.top/Article/details/gtnwbrzfwt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xziqi.cn/Article/details/gtcwgblyvm.html

[L03] 设置自定义请求头
来源：http://dali.jqgufenzy.top/Article/details/gtkmuiydbn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnqzz.top/Article/details/gtawoalqon.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jiagoushi.top/Article/details/gtskxahdmp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gtxtvgtlsv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtkxjseady.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fengsongda.top/Article/details/gtacgquctt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwphdfxq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.smart0.xyz/Article/details/gtjyeimzfo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gthdrvvyyj.html

[L04] 设置超时
来源：http://dali.guannengcc.top/Article/details/gtzonhmlhn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xinyue.icu/Article/details/gtfyghukze.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenjidiqi.icu/Article/details/gtstlabquw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtmepaqvsm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gtchplvdwo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hysaishi.cn/Article/details/gtikhuqmxv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sxryk.cn/Article/details/gtvksjhwpx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daria6918.cn/Article/details/gttdowogpu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.meibo888.top/Article/details/gtwvzjpiyh.html

[L05] 上传文件（multipart）
来源：http://dali.jianghu66.top/Article/details/gtiiuuzmzr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ybcxt.top/Article/details/gtohuuuztf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqimzesss.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtsfqzjqjp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gtllcrtbss.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gtqhitthwe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hfpthk.cn/Article/details/gtnxsrawns.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnqzz.top/Article/details/gtglrghphr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zycfv.cn/Article/details/gtvtnxyyls.html

[L06] 解析响应为 JSON
来源：http://dali.pycfn.com/Article/details/gtexqrqyil.html

Py:   resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxlcdutx.html

PHP:  json_decode($body, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtthiztqwj.html

JS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtisvdpnft.html

TS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gttombipws.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.meibo888.top/Article/details/gtgmubvzdc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nwbrower.top/Article/details/gtoiswyvxr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aizwys.cn/Article/details/gtdvutqzxv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ivvv.top/Article/details/gtkemmvzxi.html

[L07] 处理 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gttuxhohev.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gtatnfikqn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guowangkeji.top/Article/details/gtgrhfgtpz.html

JS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtiroysglm.html

TS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gtzofuhodg.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gtbyvmowqb.html

Go:   resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnowsscvl.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gtiyzzislt.html

C#:   (int)resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gtzxfchwlc.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzykbkvf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shzxlz.cn/Article/details/gtjkxwzyfn.html

PHP:  curl_multi_init() 系列
来源：http://dali.gotoacloud.top/Article/details/gtdclxdyku.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gtusqedmxt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtesrekloo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shuidangran.top/Article/details/gtkahevxek.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gtczxbztbq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gtgduzaihz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gthhrdlyvg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqjuitkqr.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gtqplmhdbn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtvgdjwvmv.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gtktzweygr.html

Py:   sys.argv[1:]
来源：http://dali.shzxlz.cn/Article/details/gtogtvkdqw.html

PHP:  $argv;  $argc;
来源：http://dali.9152youxi.cn/Article/details/gtppmjnskf.html

JS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtfkidztzo.html

TS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gtswqnjukq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gthzklopzs.html

Go:   os.Args[1:]
来源：http://dali.gotoacloud.top/Article/details/gtstjgdgwr.html

Ruby: ARGV
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnihgqabn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtetyfrmnp.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtryrnbxuw.html

Py:   os.environ.get("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtvyxaipbh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtknewtwqm.html

JS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gtuptrschk.html

TS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gtlorxvdcv.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtmdxihaui.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtrhzzrklj.html

Ruby: ENV["HOME"]
来源：http://dali.tianlin.xyz/Article/details/gtldlmozgj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gtfykmswxv.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqebkumy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cashguo.top/Article/details/gtkmcmbqcw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuanzx.com/Article/details/gtdguqbyuc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtmbfiytnf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtolyobomu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrfsilag.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.9152youxi.cn/Article/details/gtwjhtudhn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258.top/Article/details/gtggtiujuf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gtrjabcokt.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gtvozbwkto.html

Py:   os.getcwd()
来源：http://dali.jqgufenzy.top/Article/details/gteztyixll.html

PHP:  getcwd();
来源：http://dali.yj20258888.top/Article/details/gtuzryxznp.html

JS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtwpphdbfq.html

TS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gtqgzcmcyt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.316326.xyz/Article/details/gtzbnltcps.html

Go:   os.Getwd()
来源：http://dali.nwbrower.top/Article/details/gtkvyflflv.html

Ruby: Dir.pwd
来源：http://dali.zhixingplan.top/Article/details/gtjzdteudn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jianghu66.top/Article/details/gtzlxzpadn.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gteigcinhe.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gthotzdmvd.html

PHP:  exit(1);
来源：http://dali.shuidangran.top/Article/details/gtxavghplm.html

JS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gtnnqxglal.html

TS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtbzlifcmq.html

Java: System.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtqwvzmkbk.html

Go:   os.Exit(1)
来源：http://dali.xuanzx.com/Article/details/gtbvrcbssc.html

Ruby: exit 1
来源：http://dali.xylfe.cn/Article/details/gtvdbwwdtq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nwbrower.top/Article/details/gthzpmftsa.html

[M06] 向标准错误输出
来源：http://dali.fengsongda.top/Article/details/gtkeeokvct.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gtpsdemmnk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hysaishi.cn/Article/details/gttjtsahfw.html

JS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtwazfshyt.html

TS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtzbqbiifi.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gtdyevlzay.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gtnoljufsr.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gttmwwwtcs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtwzzjltwi.html

[M07] 判断是否为主入口
来源：http://dali.ydzc1.top/Article/details/gtwacevjtv.html

Py:   if __name__ == "__main__":
来源：http://dali.feifeiyinyue.top/Article/details/gtkphyirhp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jlsjyb.cn/Article/details/gtruwisaql.html

JS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gtnepvhmvt.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gtszudbsir.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtiojndmlg.html

Go:   func main()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfgbcbws.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.quarkkingdee.top/Article/details/gtsxstecnw.html

C#:   static void Main(string[] args)
来源：http://dali.cucudq.cn/Article/details/gtkomjjcvh.html

[M08] 获取系统与运行时信息
来源：http://dali.jianghu66.top/Article/details/gtslpgmhnz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.quarkkingdee.top/Article/details/gtjhwnttkp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fengsongda.top/Article/details/gthsmqwbea.html

JS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtxyungjgp.html

TS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtkogjkgkm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hfpthk.cn/Article/details/gtyzeeolwn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gtmtjfcqhg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guannengcc.top/Article/details/gtedjxfzzq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gtozfalcvk.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtkdaigvgi.html

N. 数据结构与算法
来源：http://dali.ppjwa.cn/Article/details/gtuylswxkd.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtoslgungt.html

[N01] 二分查找（有序数组）
来源：http://dali.gaohongyu789.top/Article/details/gtcyhnfqhu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtjkwcaqqg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtjmveurdw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtcfbneqbj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gtldbfphfg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtchtzrxgw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtfjjsypng.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gtusqsgkeh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtizmpoinh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjuyignot.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzafhwmw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtyiiwgzxv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtolcirbjk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gteifizjvl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhoulong.xyz/Article/details/gteqmslhud.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gtgjnxhhys.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gttbcdjpax.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cashguo.top/Article/details/gtkcugkgtk.html

[N03] 快速排序（分治示例）
来源：http://dali.aibaodan.cn/Article/details/gtzqbcasxn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.9152youxi.cn/Article/details/gtyvijklpm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.meibo888.top/Article/details/gtcyiplkdp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtqrvanjet.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gthkawqizj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guowangkeji.top/Article/details/gtvrbbwyya.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yonumen.top/Article/details/gtzuojkbsd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yvedp.cn/Article/details/gtwtttxapb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnxiangtu.top/Article/details/gtpeganhze.html

[N04] 斐波那契数列
来源：http://dali.jinqigufen.top/Article/details/gtqeszxdcu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gtdvynmaxl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.iojbl.cn/Article/details/gtssymnysb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtipnkbwzt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gtiaokpygp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthaiqgaom.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenzaomai.com/Article/details/gtswztiwfl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gtjvsxxqdb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gttpfyqzij.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gtbuwxxmwu.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gthzkhxjzy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tian-w.cn/Article/details/gtfqztjmvb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gtfkpjftvn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gtbxvwhbhg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sxryk.cn/Article/details/gtsaugbghr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.mhx1999.top/Article/details/gtmchljdxw.html

Ruby: a.gcd(b)
来源：http://dali.jqgfzy.top/Article/details/gtrunxnkou.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gtrdflgojy.html

[N06] 判断回文字符串
来源：http://dali.yongpay.top/Article/details/gtmvfmnmuf.html

Py:   s == s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gtboljiyuz.html

PHP:  $s === strrev($s);
来源：http://dali.andypj.xyz/Article/details/gtbngworul.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtyamekypn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtmlmzzsvm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pengpengdd.cyou/Article/details/gtmscerzdj.html

Go:   // 双指针从两端比较
来源：http://dali.yonumen.top/Article/details/gtywdsjaec.html

Ruby: s == s.reverse
来源：http://dali.haohaochexian.top/Article/details/gtazeuwydm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gtwrcrxgzd.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigfzy.top/Article/details/gtfflwbxkf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.svipenyu.cn/Article/details/gtkfauegim.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cdnleiting.top/Article/details/gtfredcmbw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gtqzxsgoxw.html

TS:   // 手写 Map<string, number>
来源：http://dali.yanxiufei.cn/Article/details/gtdqzgezlh.html

Java: // 手写 HashMap
来源：http://dali.ydzc1.top/Article/details/gtxynyurwa.html

Go:   // 手写 map[int]int
来源：http://dali.pengpengdd.cyou/Article/details/gtkdyulyjz.html

Ruby: // 手写 Hash
来源：http://dali.hammf.cn/Article/details/gtuzzofzft.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zycfv.cn/Article/details/gtjjmedhcj.html

[N08] 生成全排列
来源：http://dali.shzxlz.cn/Article/details/gtmzmvattv.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtlyihovgz.html

PHP:  // 手写递归交换
来源：http://dali.sxryk.cn/Article/details/gtiokiwptv.html

JS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtuvjdhlvf.html

TS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtxoegpbok.html

Java: // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtvvcubepl.html

Go:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtjlixluef.html

Ruby: arr.permutation.to_a
来源：http://dali.ybcxt.top/Article/details/gthsaguquo.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtgbnvmohr.html

[N09] 栈与队列
来源：http://dali.chenlongwang.top/Article/details/gtrfyfwpia.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.iojbl.cn/Article/details/gtjihhvcnt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtdzovggbm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gtjtgwzwxr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daxiang520.top/Article/details/gtkuaofqvu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gzhubu.top/Article/details/gtzirrwdvt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gtqvwnwyvi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtqdxfnqdo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gzhubu.top/Article/details/gtiqxdmpkv.html

[N10] 链表节点定义
来源：http://dali.havefunace.top/Article/details/gtmdwxjcih.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cheryme.top/Article/details/gteldajmfn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yonumen.top/Article/details/gtjwjeeiit.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtecjpkezn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuxming.cn/Article/details/gtqimhsmpa.html

Java: class Node { int v; Node next; }
来源：http://dali.zycfv.cn/Article/details/gtmzupjwmh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.meibo888.top/Article/details/gttbueejul.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnxiangtu.top/Article/details/gtgfiumdja.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aibaodan.cn/Article/details/gtdxmsbsrf.html

[N11] 二叉树中序遍历
来源：http://dali.ybcxt.top/Article/details/gtxkeustom.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hywenlv.cn/Article/details/gtyyfhdabz.html

PHP:  // 手写递归函数
来源：http://dali.tanke756.top/Article/details/gtjsagqliz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tian-w.cn/Article/details/gtmnrgwprg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gtrbxmccdy.html

Java: // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtikmftjva.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtlaupjpun.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenlongwang.top/Article/details/gtjtzseaok.html

C#:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtopoumzhb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.redwolf501.top/Article/details/gtozzhdqaj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.svipenyu.cn/Article/details/gtjgbksrke.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gtrewlhzsf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtuamhllav.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigfzy.top/Article/details/gthgvkwjsd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gtocgaesfm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cheryme.top/Article/details/gtuukuakpq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuanzhike.top/Article/details/gtiwaehwyf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtabtovnag.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gthzhjtkno.html

O. 并发与异步
来源：http://dali.haohaochexian.top/Article/details/gtgzmlhlre.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtmcqpmcfe.html

[O01] 启动一个线程
来源：http://dali.hywenlv.cn/Article/details/gtkhlssfnt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgfzy.top/Article/details/gttihsojjz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhixingplan.top/Article/details/gtuspslgfh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jlsjyb.cn/Article/details/gtytvqrmhi.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gtftaeumme.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclqyfhoc.html

Go:   go f()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrbzxlrp.html

Ruby: Thread.new { f }
来源：http://dali.yonumen.top/Article/details/gtooryibll.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gtujnaqaos.html


<!-- 参考信息 -->