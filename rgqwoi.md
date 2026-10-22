代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.gotoacloud.top/Article/details/gt2adrkrbsb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zzdffhju.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwghxpdi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gt2hwwboczi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2aahywjrr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhixingplan.top/Article/details/gt2avvapues.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gt2fpxmbowl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gt2mogtgytf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gt2wlnzstni.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gt2fdbjvgve.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhimrdgy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuxming.cn/Article/details/gt2exfsunpj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2undyzzwn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2fwtdpjco.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2yhagkxqv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gt2imdsrqtd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jyoumei.cn/Article/details/gt2swmmwgea.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zjdeteyz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pycfn.com/Article/details/gt2oxgnduwk.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2gwelxbkn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guannengcc.top/Article/details/gt2mvcjkwmq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gt2sznjhpuz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2aotrbhdb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jyoumei.cn/Article/details/gt2qbinzhkn.html

Go:   encoding/gob
来源：http://dali.daria6918.cn/Article/details/gt2kuxmzmvh.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vpaxpbxt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gt2jftglngt.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2ixcfmhce.html

L. 网络请求
来源：http://dali.iojbl.cn/Article/details/gt2jstnbhek.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2nssqgzwv.html

[L01] 发送 GET 请求
来源：http://dali.meibo888.top/Article/details/gt2kdsxzdqd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuanzhike.top/Article/details/gt2fbnggmul.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zdqjudy.top/Article/details/gt2fhyrqlox.html

JS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gt2ihuxcppv.html

TS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gt2pyxprspx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gotoacloud.top/Article/details/gt2amttryre.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2rmxikmqr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jyoumei.cn/Article/details/gt2jbkvlokv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2svsfzpgb.html

[L02] 发送 POST JSON
来源：http://dali.pycfn.com/Article/details/gt2kvocmogl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yqzcvivl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guowangkeji.top/Article/details/gt2jugofuni.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gt2rqaeyfwe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gt2vhhxskeq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.birdmap.top/Article/details/gt2dkvehapo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxuanxn.top/Article/details/gt2mvqqynat.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.andypj.xyz/Article/details/gt2vlgknkxs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jlsjyb.cn/Article/details/gt2mttjzjrt.html

[L03] 设置自定义请求头
来源：http://dali.ydzc1.top/Article/details/gt2lnhjygtt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cashguo.top/Article/details/gt2dyzzfykm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2orryoinm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gt2bexoofuz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gt2oawqezax.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qpvsamkz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bawlwajy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gdmcuhzf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gt2brltgmlw.html

[L04] 设置超时
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ljrriyix.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fiarnwsg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tianlin.xyz/Article/details/gt2vhyopnmx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gt2nwukzyty.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ixzgvbdd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yueranfly.top/Article/details/gt2qkgaemdz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gt2venzlcta.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgfzy.top/Article/details/gt2gubnucoc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gt2qdbnalpm.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gt2rmlenpve.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shuidangran.top/Article/details/gt2yxazkxmi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hywenlv.cn/Article/details/gt2hlermahj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gt2hsvurcwx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gt2zwurxerd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.andypj.xyz/Article/details/gt2jxpeqigr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nwbrower.top/Article/details/gt2kmgiyokq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fengsongda.top/Article/details/gt2vvdlbxjz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2gverjgde.html

[L06] 解析响应为 JSON
来源：http://dali.hfpthk.cn/Article/details/gt2qrlrgzwn.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gt2tvhfjyxw.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2izjemwwa.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gt2wjltttsj.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gt2gtuwbbzk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qshmudjb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gt2uqrgnxab.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hammf.cn/Article/details/gt2biaiqves.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jlsjyb.cn/Article/details/gt2anixoihn.html

[L07] 处理 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gt2bexuoxtt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.feifeiyinyue.top/Article/details/gt2cwowqwlb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxuanxn.top/Article/details/gt2msjxynbb.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gt2zlzwodmo.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gt2pkisvscx.html

Java: resp.statusCode()
来源：http://dali.yj20258.top/Article/details/gt2sustkkmw.html

Go:   resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gt2vpwukmgw.html

Ruby: resp.code.to_i
来源：http://dali.dashuyun.cn/Article/details/gt2lwmfbygv.html

C#:   (int)resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gt2qjkujecv.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gt2tjebjdpz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tianlin.xyz/Article/details/gt2igzboqim.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gt2dwtdtplf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gt2lihaeogj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2enoejudo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hfpthk.cn/Article/details/gt2blzzwtyc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gt2zqafdwhu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2apzczzsy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2imtoonss.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2mtgmchbn.html

M. 命令行 / 进程 / 环境
来源：http://dali.ppjwa.cn/Article/details/gt2wjwraowm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2vyqenven.html

[M01] 读取命令行参数
来源：http://dali.yj202588.top/Article/details/gt2qvzxtmvh.html

Py:   sys.argv[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2mtyvkszi.html

PHP:  $argv;  $argc;
来源：http://dali.fzhhl.top/Article/details/gt2xqnddnol.html

JS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gt2pnpglyuf.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gt2jmbunkfi.html

Java: args 数组（main 方法参数）
来源：http://dali.hammf.cn/Article/details/gt2zdreqapo.html

Go:   os.Args[1:]
来源：http://dali.zhongyouzk.top/Article/details/gt2mazzimap.html

Ruby: ARGV
来源：http://dali.xuetiantiany.cn/Article/details/gt2eyxtrgdk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ieuimnrh.html

[M02] 读取环境变量
来源：http://dali.jlsjyb.cn/Article/details/gt2wcnphkan.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojagymbk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gt2qfwvaewe.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gt2tntahksv.html

TS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gt2qvvkytzn.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2ydxtepqb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.bjfxy.top/Article/details/gt2rylqiuoo.html

Ruby: ENV["HOME"]
来源：http://dali.zhengqikj.top/Article/details/gt2bjfdmmtj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2zmlbyywj.html

[M03] 执行外部命令
来源：http://dali.hfpthk.cn/Article/details/gt2whgfgeqn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gt2aytfejxf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aibaodan.cn/Article/details/gt2whkwbgxj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gt2vjlkybni.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gt2bamxrwlb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gt2maxkxwbk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.316326.xyz/Article/details/gt2mtehtwbl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnxiangtu.top/Article/details/gt2zwfbolzc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.0kj1m.cn/Article/details/gt2wbycsnad.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gt2binysxby.html

Py:   os.getcwd()
来源：http://dali.svipenyu.cn/Article/details/gt2ziorgwca.html

PHP:  getcwd();
来源：http://dali.nwbrower.top/Article/details/gt2swebndzh.html

JS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gt2xgptmazv.html

TS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gt2eiydbyhg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gt2tqguazgs.html

Go:   os.Getwd()
来源：http://dali.meibo888.top/Article/details/gt2jgjhbkgr.html

Ruby: Dir.pwd
来源：http://dali.zycfv.cn/Article/details/gt2nansudpo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gt2iytygmab.html

[M05] 设置退出码
来源：http://dali.ydzc1.top/Article/details/gt2qlwnovgw.html

Py:   sys.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2xxmfxout.html

PHP:  exit(1);
来源：http://dali.havefunace.top/Article/details/gt2vimkruao.html

JS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2zfmweitx.html

TS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2nbowbggk.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2xvjfmcju.html

Go:   os.Exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2joivqzqy.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lenxsmui.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kxohnxbd.html

[M06] 向标准错误输出
来源：http://dali.aibaodan.cn/Article/details/gt2kevkiibp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gt2myieggnv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bznzvgiy.html

JS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gt2ayeclqzd.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2sdjszqnt.html

Java: System.err.println("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2zdvmustm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fsdmqinb.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gt2zzcrhphw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.birdmap.top/Article/details/gt2aqlvruxo.html

[M07] 判断是否为主入口
来源：http://dali.sysykeji.top/Article/details/gt2yyqvalgm.html

Py:   if __name__ == "__main__":
来源：http://dali.daxiang520.top/Article/details/gt2tbxscqve.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnqzz.top/Article/details/gt2ozbxnxod.html

JS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gt2nwnjjnlo.html

TS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gt2dvppzpvf.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djjqroff.html

Go:   func main()
来源：http://dali.zhongyouzk.top/Article/details/gt2djjhqjmf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhoulong.xyz/Article/details/gt2nhbdpumi.html

C#:   static void Main(string[] args)
来源：http://dali.bjfxy.top/Article/details/gt2iwfsnrvb.html

[M08] 获取系统与运行时信息
来源：http://dali.hnqzz.top/Article/details/gt2ckuebdxk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gzhubu.top/Article/details/gt2fpxgsved.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gt2jzirxkcd.html

JS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gt2hxmtoign.html

TS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gt2dvymyosf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxinkj.top/Article/details/gt2ealqhzee.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pycfn.com/Article/details/gt2oxuxzmzv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhiwuduotai.top/Article/details/gt2kfvmpxrv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqswjvcy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2vzghosjo.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gt2pacgjcfk.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2jfrjlnfa.html

[N01] 二分查找（有序数组）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ftspenny.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2bnsunpsq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2yefoazfc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gt2gfoakdyw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2tjmqujoj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2mjzqtyoq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2rjkezkcl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guannengcc.top/Article/details/gt2bwudorsg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2lcpejmmv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ouynqjbv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wygjcvcx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tastjktk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gt2cvpfqdxl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nyrwibjs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sxryk.cn/Article/details/gt2ryvpkolv.html

Go:   slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gt2mtrtkgwt.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uakwkrcx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.svipenyu.cn/Article/details/gt2xycpuwbj.html

[N03] 快速排序（分治示例）
来源：http://dali.xuanzx.com/Article/details/gt2rczfgghe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigufen.top/Article/details/gt2qlurrbvh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.svipenyu.cn/Article/details/gt2kontzeow.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gt2ypaeppcw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gt2cniczvnn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tanke756.top/Article/details/gt2knjfaeiv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenlongwang.top/Article/details/gt2dhzbzksz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gotoacloud.top/Article/details/gt2nkgzrbme.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qmzowdyz.html

[N04] 斐波那契数列
来源：http://dali.ybcxt.top/Article/details/gt2drnefcix.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gt2tdtkpsun.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zfqgfgtg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2yiffaohd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gt2zqdbbopu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aizwys.cn/Article/details/gt2ddztvlxr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guowangkeji.top/Article/details/gt2jtonijze.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gt2oqccngqe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gt2ygpxsgmd.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gt2jtpgifqc.html

Py:   math.gcd(a, b)
来源：http://dali.sweek.top/Article/details/gt2mznsgpho.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhoulong.xyz/Article/details/gt2nayhgyjh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gt2eygsdhxf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqqnjufa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ybcxt.top/Article/details/gt2cyzxsssi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aibaodan.cn/Article/details/gt2adlsbasz.html

Ruby: a.gcd(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lemspujx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuanzx.com/Article/details/gt2bgwwsbwa.html

[N06] 判断回文字符串
来源：http://dali.ybcxt.top/Article/details/gt2naspulpv.html

Py:   s == s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2idiepqur.html

PHP:  $s === strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gt2vcittkkv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2oeddfttg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gt2vgrqbttl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guowangkeji.top/Article/details/gt2brjwawvn.html

Go:   // 双指针从两端比较
来源：http://dali.cdnleiting.top/Article/details/gt2ynlwyidz.html

Ruby: s == s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gt2jlzkrcdn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gt2ruibeyrd.html

[N07] 两数之和（返回下标）
来源：http://dali.feifeiyinyue.top/Article/details/gt2hljktjfx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258888.top/Article/details/gt2wvuhnwsr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yvedp.cn/Article/details/gt2rdvcqdoq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aizwys.cn/Article/details/gt2ahdrxtsr.html

TS:   // 手写 Map<string, number>
来源：http://dali.yonumen.top/Article/details/gt2ppuuyyus.html

Java: // 手写 HashMap
来源：http://dali.sweek.top/Article/details/gt2jleholkn.html

Go:   // 手写 map[int]int
来源：http://dali.jianghu66.top/Article/details/gt2iltahzcw.html

Ruby: // 手写 Hash
来源：http://dali.pycfn.com/Article/details/gt2vajcxldd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxinkj.top/Article/details/gt2jtxzqvnz.html

[N08] 生成全排列
来源：http://dali.feifeiyinyue.top/Article/details/gt2dzwywqiu.html

Py:   itertools.permutations(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2vqwomdun.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ftpwrbql.html

JS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2ekbfwzsl.html

TS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2upcfwyin.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2dtcngckw.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ulcblhfy.html

Ruby: arr.permutation.to_a
来源：http://dali.aizwys.cn/Article/details/gt2pqzbwksb.html

C#:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2ouqzabsa.html

[N09] 栈与队列
来源：http://dali.ehwqpu.com/Article/details/gt2fxecbaad.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pvhxdnrx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2khwwsldu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gt2uyzzgzdn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ivvv.top/Article/details/gt2ahkdqvue.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sufxvd.cn/Article/details/gt2yfvwmmyl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gt2nfhtnkkc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gt2qjordduc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258.top/Article/details/gt2qaxorrqv.html

[N10] 链表节点定义
来源：http://dali.316326.xyz/Article/details/gt2hhdxafsv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gt2dzyzyvoy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gt2yoccwzdo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gt2bphbjmjt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gt2oqjgdrnu.html

Java: class Node { int v; Node next; }
来源：http://dali.svipenyu.cn/Article/details/gt2wapwnhye.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hfpthk.cn/Article/details/gt2rrxmipho.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dianchejie.cn/Article/details/gt2pmkadgjq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.smart0.xyz/Article/details/gt2klzbjzlz.html

[N11] 二叉树中序遍历
来源：http://dali.jqgfzy.top/Article/details/gt2mkfxsmqo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.kuanghao11.cn/Article/details/gt2gbecpuzw.html

PHP:  // 手写递归函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2kaaodmwl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gt2fvbxzogy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gt2rptcfnmn.html

Java: // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gt2iapuckhm.html

Go:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dmyyoqop.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhengqikj.top/Article/details/gt2jfdgyein.html

C#:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gt2rpzwrhzu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ybcxt.top/Article/details/gt2kwtbwimp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.316326.xyz/Article/details/gt2ftlldyqn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.snrcjt.cn/Article/details/gt2yltptncr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gt2fwxgveyh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gt2qrckcdtp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gt2nysljiyr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.c1oappe.top/Article/details/gt2mclcylee.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fzhhl.top/Article/details/gt2qloogjjz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gt2yiriinvv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bnlqsqua.html

O. 并发与异步
来源：http://dali.xziqi.cn/Article/details/gt2dbaocegz.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2spkwqdgz.html

[O01] 启动一个线程
来源：http://dali.jinqigfzy.top/Article/details/gt2kqrvhzxw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yvedp.cn/Article/details/gt2zpvnwilp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.c1oappe.top/Article/details/gt2gpezduds.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhiwuduotai.top/Article/details/gt2zobdhyyv.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gt2hcbeikjf.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zabdwvua.html

Go:   go f()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2scmqiuge.html

Ruby: Thread.new { f }
来源：http://dali.xylfe.cn/Article/details/gt2thadjrjc.html

C#:   Task.Run(() => F());
来源：http://dali.bjfxy.top/Article/details/gt2vzbaknwz.html


<!-- 参考信息 -->