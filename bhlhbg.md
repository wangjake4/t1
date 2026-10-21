代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.nanxinkj.top/Article/details/gtmwnnaipy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shangyingyoupin.top/Article/details/gtydyzmfvq.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtawzjehpk.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtjjemjxhm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gtfihugpdm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sysykeji.top/Article/details/gtozjwcxii.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sxryk.cn/Article/details/gtginharma.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xinyue.icu/Article/details/gtvrjpcanc.html

[K06] 解析 URL 查询串
来源：http://dali.chenzaomai.com/Article/details/gtpkagxeej.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guannengcc.top/Article/details/gthnqtfigu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenjidiqi.icu/Article/details/gtkdfeijke.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gtqwrvnbie.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gtpfwbmswi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.meibo888.top/Article/details/gtjxdwspvn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtajqycumo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtdvzdiilr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtiqghcolp.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmdukhhn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtlqfattjf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sxryk.cn/Article/details/gtcjlwnqal.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtdztsgqop.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtinmquewp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtjbywukhq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhengqikj.top/Article/details/gtuxflmyog.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ydzc1.top/Article/details/gtlgxeomdx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtyvgifdha.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gtirvwtrux.html

Py:   pickle.dumps(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtstxwlwqz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.snrcjt.cn/Article/details/gtjrexyiaw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiaygdiyk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gtxhlwvpcz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pycfn.com/Article/details/gtmacytyhp.html

Go:   encoding/gob
来源：http://dali.kuanghao11.cn/Article/details/gtvozdfoyx.html

Ruby: Marshal.dump(obj)
来源：http://dali.havefunace.top/Article/details/gtkzbjulcq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gtdfshtghx.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttgwnesft.html

L. 网络请求
来源：http://dali.yanxiufei.cn/Article/details/gtqqgzmfcz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtaaawwqfp.html

[L01] 发送 GET 请求
来源：http://dali.havefunace.top/Article/details/gtgqfdgmoq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yvedp.cn/Article/details/gtuiufsotj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxinkj.top/Article/details/gtppwwgmxe.html

JS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gtfkcusiri.html

TS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtealdlbjq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fengsongda.top/Article/details/gtcnpvqqvw.html

Go:   resp, err := http.Get(url)
来源：http://dali.aizwys.cn/Article/details/gttzwlltga.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnqzz.top/Article/details/gtoqqsppng.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ybcxt.top/Article/details/gtkbvvqmxh.html

[L02] 发送 POST JSON
来源：http://dali.yj202588.top/Article/details/gtssyhejty.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtywbywrkt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jiagoushi.top/Article/details/gtnxuylqzk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gtxvidepti.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gtzofdhknb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gzhubu.top/Article/details/gtyqmychqa.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daria6918.cn/Article/details/gtdyiroiay.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvreheqd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhongyouzk.top/Article/details/gtnftxtuqt.html

[L03] 设置自定义请求头
来源：http://dali.hammf.cn/Article/details/gtupdnwddr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ppjwa.cn/Article/details/gtjqallvmj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gtmokyudkg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtixskoxgs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gtrzgraabo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cqqwz.cn/Article/details/gthcbslsju.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtwjfrmbif.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guannengcc.top/Article/details/gtwhcukhox.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gttarfoqoy.html

[L04] 设置超时
来源：http://dali.fengsongda.top/Article/details/gtxdlyfnnt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jiagoushi.top/Article/details/gtglskythw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigufen.top/Article/details/gtmuplttqn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gtjouecuif.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gtthrhojrb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hywenlv.cn/Article/details/gtpgjoovqb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sweek.top/Article/details/gtucgsgbkp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjeftxxu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jlsjyb.cn/Article/details/gtvkdzelao.html

[L05] 上传文件（multipart）
来源：http://dali.jyoumei.cn/Article/details/gtrryvvtmv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.redwolf501.top/Article/details/gtjzqmpgfh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cqqwz.cn/Article/details/gtjyomlvmi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gtkwkcpqub.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtvpfjsiit.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xylfe.cn/Article/details/gtwovxvwgk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pengpengdd.cyou/Article/details/gtwlmnycvn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zycfv.cn/Article/details/gtspupwlxf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yueranfly.top/Article/details/gtodmuwjio.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gtqjkjzyec.html

Py:   resp.json()
来源：http://dali.cucudq.cn/Article/details/gtioofndnf.html

PHP:  json_decode($body, true);
来源：http://dali.daria6918.cn/Article/details/gteqzwinew.html

JS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtioupwgih.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtniwigdkm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daria6918.cn/Article/details/gtkastqbgf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.quarkkingdee.top/Article/details/gtajrlkvlr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yvedp.cn/Article/details/gtanfcrboc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtlqttkzcz.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtcwcqklht.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zycfv.cn/Article/details/gtbyfegxuj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gtkdlninzn.html

JS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gthznphmor.html

TS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gtobderakp.html

Java: resp.statusCode()
来源：http://dali.yanxiufei.cn/Article/details/gterwkmczh.html

Go:   resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtqtxqxzbu.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gtudwlxdqs.html

C#:   (int)resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtijmrqyny.html

[L08] 并发请求多个地址
来源：http://dali.cdnleiting.top/Article/details/gtmeyefasn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shangyingyoupin.top/Article/details/gtzjejskac.html

PHP:  curl_multi_init() 系列
来源：http://dali.jlsjyb.cn/Article/details/gtuarvnnfo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtoshertcs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtiayxrtkw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhoulong.xyz/Article/details/gtdusvrubm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ivvv.top/Article/details/gtuszurveu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gtlqyrbbir.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fzhhl.top/Article/details/gtlttzugbp.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthjbofcyq.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gtyetwrwyc.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtavazzvpu.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtshoeqywj.html

Py:   sys.argv[1:]
来源：http://dali.chenzaomai.com/Article/details/gthgayozzp.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gtssjseqhu.html

JS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gtghyutekm.html

TS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtbxhxqynh.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtzvhtxrpf.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gtxhjaeddb.html

Ruby: ARGV
来源：http://dali.wangdashe.top/Article/details/gtwypxetav.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gtztprqria.html

[M02] 读取环境变量
来源：http://dali.sxryk.cn/Article/details/gtavmnnacu.html

Py:   os.environ.get("HOME")
来源：http://dali.tian-w.cn/Article/details/gtthiymcgj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gtjekdmide.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtikxgsqtn.html

TS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtmvejaklo.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtoobfuylm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zycfv.cn/Article/details/gtfygwbanf.html

Ruby: ENV["HOME"]
来源：http://dali.gaohongyu789.top/Article/details/gtwxyipupt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gtrcrewxnf.html

[M03] 执行外部命令
来源：http://dali.cdnleiting.top/Article/details/gtxflqwndc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gteiqqwqwc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tianlin.xyz/Article/details/gtvfxjhqig.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtrxeghcft.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtasljddph.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gaohongyu789.top/Article/details/gtdwfijwcz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guannengcc.top/Article/details/gtrauqwadg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gtijqtimfx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258888.top/Article/details/gtozajuuiq.html

[M04] 获取当前工作目录
来源：http://dali.bjfxy.top/Article/details/gtyetcniux.html

Py:   os.getcwd()
来源：http://dali.xuanzx.com/Article/details/gtbohkonxp.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gtiniburyv.html

JS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gtyooqiwzs.html

TS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gtyzxvnyvg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fzhhl.top/Article/details/gtsiqrhbbd.html

Go:   os.Getwd()
来源：http://dali.hnqzz.top/Article/details/gtsslqdmtn.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gtiupqohwp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gtgevvulqc.html

[M05] 设置退出码
来源：http://dali.gotoacloud.top/Article/details/gtdisljwlr.html

Py:   sys.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtainqcwvw.html

PHP:  exit(1);
来源：http://dali.ydzc1.top/Article/details/gtdiupwnql.html

JS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gttpbxzhyj.html

TS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtbdozlgcm.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtvidfbkzw.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtjvajihar.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtothxbbih.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ivvv.top/Article/details/gtikthryrm.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gtovnpyzlv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gtujyfaknh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ydzc1.top/Article/details/gtkcyahmgz.html

JS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gtadzcmbdj.html

TS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gtnimevgvv.html

Java: System.err.println("err")
来源：http://dali.yuxming.cn/Article/details/gtmootcfzr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gtomrowuwj.html

Ruby: warn "err"
来源：http://dali.hammf.cn/Article/details/gtfzeodjpr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangdashe.top/Article/details/gtgkgbldqe.html

[M07] 判断是否为主入口
来源：http://dali.iojbl.cn/Article/details/gtwqcaaubn.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258.top/Article/details/gttarrygdq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gtylsfpcbc.html

JS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gtjrrfazxo.html

TS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gtrnyjsbba.html

Java: public static void main(String[] args)
来源：http://dali.9152youxi.cn/Article/details/gttjuykfjo.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gtlrcvhyuv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gttjwmdlhv.html

C#:   static void Main(string[] args)
来源：http://dali.chenzaomai.com/Article/details/gtinsqvfnj.html

[M08] 获取系统与运行时信息
来源：http://dali.wangshuangyany.cn/Article/details/gtzrlsmomx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigufen.top/Article/details/gtkfjkdnyl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangshuangyany.cn/Article/details/gtkyqufepb.html

JS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gtkkphnsgw.html

TS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gtehmpsizk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.snrcjt.cn/Article/details/gtvctfipnq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cdnleiting.top/Article/details/gtsbrywwst.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gtukawppfb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.quarkkingdee.top/Article/details/gtqcmhlywm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gteuarjdag.html

N. 数据结构与算法
来源：http://dali.0kj1m.cn/Article/details/gtvpgnsctl.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtcwpmpqpk.html

[N01] 二分查找（有序数组）
来源：http://dali.hongshengwenyu.top/Article/details/gtxdpbdpsm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtzgtkdmgd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhengqikj.top/Article/details/gthavtcuwb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gtgdatoljl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtptqaqavh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtckkbdeyc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtlcoenmta.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhoulong.xyz/Article/details/gtabpmysvz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtvoctvdvi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shuidangran.top/Article/details/gtmcglostl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtxyeqtwcb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtkykllcfv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtjqruqgxm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtpdyisgbe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgfzy.top/Article/details/gtgpwecyye.html

Go:   slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gtnjnfbhxx.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gtcziirvvc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ehwqpu.com/Article/details/gttugwhpjd.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gtvzeiljdh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.birdmap.top/Article/details/gtfkeuruae.html

PHP:  // 递归实现，或用 usort
来源：http://dali.andypj.xyz/Article/details/gtfyqkmqym.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gtbhibzttc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gtqzogpkqn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yvedp.cn/Article/details/gtfwtaruwe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xylfe.cn/Article/details/gteqlyqncj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhixingplan.top/Article/details/gtrdujrfcy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gtbahwurqj.html

[N04] 斐波那契数列
来源：http://dali.jqgfzy.top/Article/details/gtxtivyhqw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkemwxmkj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.meibo888.top/Article/details/gtwpgzxppo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtiringbmj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtxpbqhcbc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cucudq.cn/Article/details/gtdkarsxpw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hfpthk.cn/Article/details/gtanezgpyr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnuscyuh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtcaivpjhd.html

[N05] 最大公约数
来源：http://dali.quarkkingdee.top/Article/details/gtjzttbusf.html

Py:   math.gcd(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtinxjfcem.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jlsjyb.cn/Article/details/gtgqrthsib.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gtvipbwcpg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtzwywklrp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gtricrrysm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmaqxkfb.html

Ruby: a.gcd(b)
来源：http://dali.jianghu66.top/Article/details/gtmmxqfzla.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigufen.top/Article/details/gtgibfxdgf.html

[N06] 判断回文字符串
来源：http://dali.birdmap.top/Article/details/gtidwzuhve.html

Py:   s == s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gtldwzusqm.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gtdranrxbq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gttmiwxuxp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtaykopaxq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtishndpsb.html

Go:   // 双指针从两端比较
来源：http://dali.chenjidiqi.icu/Article/details/gtpdvafadx.html

Ruby: s == s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewzyvwcn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gtmueluoer.html

[N07] 两数之和（返回下标）
来源：http://dali.haohaochexian.top/Article/details/gtwdyitwwl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gtduqdzpfj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hysaishi.cn/Article/details/gtaawhlarn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangshuangyany.cn/Article/details/gtwrdawlki.html

TS:   // 手写 Map<string, number>
来源：http://dali.ydzc1.top/Article/details/gtquwqjzyb.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbtunrmb.html

Go:   // 手写 map[int]int
来源：http://dali.tanke756.top/Article/details/gtzyviclna.html

Ruby: // 手写 Hash
来源：http://dali.tianlin.xyz/Article/details/gtafesmcpe.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yangfankeji.com/Article/details/gtqobrvyyf.html

[N08] 生成全排列
来源：http://dali.xziqi.cn/Article/details/gtxuejfrgk.html

Py:   itertools.permutations(arr)
来源：http://dali.gogol.net.cn/Article/details/gtihduqzws.html

PHP:  // 手写递归交换
来源：http://dali.yongpay.top/Article/details/gtkknchalw.html

JS:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtkbrfzdgh.html

TS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtcavettbk.html

Java: // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtznujlvxl.html

Go:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtdooctwtk.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gtcpcbkjji.html

C#:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtzgqvsvor.html

[N09] 栈与队列
来源：http://dali.yj20258888.top/Article/details/gtcopeodpi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtyttxlj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuanzx.com/Article/details/gttgiyxhws.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtwussegal.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gzhubu.top/Article/details/gtmipjrisq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shuidangran.top/Article/details/gtotqwhrud.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jlsjyb.cn/Article/details/gtocgztqen.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtavlmycqf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ivvv.top/Article/details/gtawdqieif.html

[N10] 链表节点定义
来源：http://dali.tianlin.xyz/Article/details/gtljeqypba.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jianghu66.top/Article/details/gtlwzqfmdt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pycfn.com/Article/details/gtkgrxkfjb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guannengcc.top/Article/details/gtltsmbcpb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gtjeqhbruv.html

Java: class Node { int v; Node next; }
来源：http://dali.cqqwz.cn/Article/details/gtjmvtyoha.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigufen.top/Article/details/gtkjknxqlf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pengpengdd.cyou/Article/details/gtlloferry.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnqzz.top/Article/details/gtdogpblgw.html

[N11] 二叉树中序遍历
来源：http://dali.316326.xyz/Article/details/gtnnzlkoor.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.svipenyu.cn/Article/details/gtqbgnraqf.html

PHP:  // 手写递归函数
来源：http://dali.dianchejie.cn/Article/details/gtfbqzaxlc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gtbrrjtxvd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gtvgwkeebq.html

Java: // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtmfflzmmi.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtnvoqdxbo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangdashe.top/Article/details/gtgrsbpfis.html

C#:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtfnixuvkv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yongpay.top/Article/details/gtkbiplsej.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgfzy.top/Article/details/gtpanwwswf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuanzhike.top/Article/details/gtxdpeaanw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzsaybpl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gtmlfeccml.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gtrfngqcgb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dashuyun.cn/Article/details/gtuyhpgylw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.iojbl.cn/Article/details/gtqvulufjw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gtdimrvtxp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtpemqtxsu.html

O. 并发与异步
来源：http://dali.nanxinkj.top/Article/details/gtlwqluhos.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkqafmut.html

[O01] 启动一个线程
来源：http://dali.yj202588.top/Article/details/gtwcjqdjej.html


<!-- 参考信息 -->