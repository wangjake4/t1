代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.nanxuanxn.top/Article/details/gt2coptjjjw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gt2tdsxsref.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gogol.net.cn/Article/details/gt2nzfutfvu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gt2kjzkmzgq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gt2dsfjehsq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cashguo.top/Article/details/gt2zegddllj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2gsssufpl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2rgqmiobq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gt2lnlhqcgh.html

[K07] 进制转换
来源：http://dali.aizwys.cn/Article/details/gt2cvixlxfk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nfldidji.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xylfe.cn/Article/details/gt2qxzjvyzr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2zhhfcfax.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2tepahepo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2cltqfcrs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daxiang520.top/Article/details/gt2bvxtubbh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yanxiufei.cn/Article/details/gt2miumzvcq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2dtuaxoqh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gt2xpeffnug.html

Py:   pickle.dumps(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cqvndfqr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhengqikj.top/Article/details/gt2rdahwfiv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gt2gthvxpke.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gt2hgkprqvv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhongyouzk.top/Article/details/gt2qszauuud.html

Go:   encoding/gob
来源：http://dali.dashuyun.cn/Article/details/gt2xzkfvubw.html

Ruby: Marshal.dump(obj)
来源：http://dali.havefunace.top/Article/details/gt2lkvgfmhy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gt2vasjslvj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lajughxf.html

L. 网络请求
来源：http://dali.jqgfzy.top/Article/details/gt2oriderra.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2sznjdcot.html

[L01] 发送 GET 请求
来源：http://dali.xuetiantiany.cn/Article/details/gt2uitymabl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gt2adapvrvh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gt2zmamfsvm.html

JS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gt2gahbazux.html

TS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gt2hirijcbj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenjidiqi.icu/Article/details/gt2spghbbse.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gt2uskxmory.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gsmhdwxn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ydzc1.top/Article/details/gt2kklhymxw.html

[L02] 发送 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2okeuxvig.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sweek.top/Article/details/gt2ubldrekr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenlongwang.top/Article/details/gt2kcaapjqg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2svpcgtvj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2ppxuoowi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hammf.cn/Article/details/gt2dshhmhgc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hysaishi.cn/Article/details/gt2rzpadkgu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangshuangyany.cn/Article/details/gt2pvyhaahl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.iojbl.cn/Article/details/gt2fncdbiks.html

[L03] 设置自定义请求头
来源：http://dali.zhengqikj.top/Article/details/gt2rbgwbhcg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuetiantiany.cn/Article/details/gt2aljqvrwl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xylfe.cn/Article/details/gt2qhhfiguy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gt2akdyysgc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gt2rmnqsxrw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gt2bbmgbkhy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qsjdqtbf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.0kj1m.cn/Article/details/gt2vglcezwj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gt2vwslqupb.html

[L04] 设置超时
来源：http://dali.jinqigfzy.top/Article/details/gt2jdakzexd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jyoumei.cn/Article/details/gt2nfcjpgdx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dashuyun.cn/Article/details/gt2otbbznjr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2oytjqhol.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gt2lpogrrrm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jyoumei.cn/Article/details/gt2gtcbhpoq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shzxlz.cn/Article/details/gt2xzpwjgqc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuxming.cn/Article/details/gt2nvcoxddj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jianghu66.top/Article/details/gt2lflzgigq.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gt2wvgytstv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yueranfly.top/Article/details/gt2tgrhckwp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tianlin.xyz/Article/details/gt2kklpnife.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gt2mezxpxtw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qqqizxdz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.birdmap.top/Article/details/gt2gblstwep.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gt2rhmhtdxb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sysykeji.top/Article/details/gt2wiykueir.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2fyvrliql.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gt2geywhdul.html

Py:   resp.json()
来源：http://dali.guannengcc.top/Article/details/gt2hatlyofs.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258888.top/Article/details/gt2eqnkgbqw.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2nlfejhpt.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqeegpzb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdnuvbvr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gt2gdthxpxq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kzrurpex.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.snrcjt.cn/Article/details/gt2kqczkqdp.html

[L07] 处理 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gt2aaomytkj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gt2awvwjixf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckppybet.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gt2ahfumndf.html

TS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gt2qznjpctf.html

Java: resp.statusCode()
来源：http://dali.yongpay.top/Article/details/gt2yvzzvnij.html

Go:   resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gt2tjdvaerb.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gt2kntdvlnu.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gt2bluyjfgu.html

[L08] 并发请求多个地址
来源：http://dali.zycfv.cn/Article/details/gt2wohxhdoc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxinkj.top/Article/details/gt2xdhqdoet.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigufen.top/Article/details/gt2kzvtulmc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2tgfuyijg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2joiqayvo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnqzz.top/Article/details/gt2brfzjnnf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jianghu66.top/Article/details/gt2ozdkojoa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daxiang520.top/Article/details/gt2rlicqbuj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.havefunace.top/Article/details/gt2yztqiior.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2dymatonm.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gt2uthtfcba.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2acztogrm.html

[M01] 读取命令行参数
来源：http://dali.yangfankeji.com/Article/details/gt2ckcugsyw.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2whvskzho.html

PHP:  $argv;  $argc;
来源：http://dali.hysaishi.cn/Article/details/gt2wifuxgup.html

JS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gt2bjvugfzo.html

TS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gt2bdywgizr.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gt2yvuhxymb.html

Go:   os.Args[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tguykljw.html

Ruby: ARGV
来源：http://dali.sufxvd.cn/Article/details/gt2cwawkpox.html

C#:   args 数组（Main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gt2xvkinstu.html

[M02] 读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gt2gdnlydgy.html

Py:   os.environ.get("HOME")
来源：http://dali.0kj1m.cn/Article/details/gt2jxbgfopr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gt2sjpmkpqu.html

JS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gt2zeleglqm.html

TS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gt2nrmarioc.html

Java: System.getenv("HOME")
来源：http://dali.cashguo.top/Article/details/gt2wawkghop.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fengsongda.top/Article/details/gt2rlwjssyv.html

Ruby: ENV["HOME"]
来源：http://dali.yuxming.cn/Article/details/gt2nwniwlxk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xinyue.icu/Article/details/gt2dlcuktio.html

[M03] 执行外部命令
来源：http://dali.xziqi.cn/Article/details/gt2plyiybow.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2cwxhkakm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.316326.xyz/Article/details/gt2egncnonu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2jezbjifa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gt2nvwmdpvf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pycfn.com/Article/details/gt2bqzwsrwi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gt2qigfufds.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cashguo.top/Article/details/gt2flzcaqyo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.birdmap.top/Article/details/gt2lbkuavgw.html

[M04] 获取当前工作目录
来源：http://dali.hnqzz.top/Article/details/gt2joxrbyfj.html

Py:   os.getcwd()
来源：http://dali.yj20258.top/Article/details/gt2myyebvrb.html

PHP:  getcwd();
来源：http://dali.cheryme.top/Article/details/gt2mxrnseer.html

JS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gt2vrbbrrby.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gt2sbidrrkr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sbdjbvfo.html

Go:   os.Getwd()
来源：http://dali.tianlin.xyz/Article/details/gt2hqehhken.html

Ruby: Dir.pwd
来源：http://dali.yangfankeji.com/Article/details/gt2vfnffxrx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gt2xlysakag.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gt2ivqzgtoo.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2tfvrmwxa.html

PHP:  exit(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2puuzskzj.html

JS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2snbjqfsx.html

TS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2oqwnqsps.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2uwdptqnz.html

Go:   os.Exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2ktsqlyyg.html

Ruby: exit 1
来源：http://dali.jinqigfzy.top/Article/details/gt2uxvgatfx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ivvv.top/Article/details/gt2rvypxqos.html

[M06] 向标准错误输出
来源：http://dali.gzhubu.top/Article/details/gt2suvcmzla.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hfpthk.cn/Article/details/gt2zcjvlzcy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hywenlv.cn/Article/details/gt2bsxeyfle.html

JS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gt2ztiakcbs.html

TS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gt2fngnpjbk.html

Java: System.err.println("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2vdwqlldb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2limqqnys.html

Ruby: warn "err"
来源：http://dali.tianlin.xyz/Article/details/gt2ziizlnpt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aibaodan.cn/Article/details/gt2mwdykciq.html

[M07] 判断是否为主入口
来源：http://dali.zhengqikj.top/Article/details/gt2luwhtoju.html

Py:   if __name__ == "__main__":
来源：http://dali.chenjidiqi.icu/Article/details/gt2eioaphji.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cuztmvzf.html

JS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gt2nlbqtygp.html

TS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gt2yghpxmci.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gt2ofmfbzsy.html

Go:   func main()
来源：http://dali.tian-w.cn/Article/details/gt2cynbphlz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangdashe.top/Article/details/gt2cnxgkezt.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gt2zoarxskq.html

[M08] 获取系统与运行时信息
来源：http://dali.chenlongwang.top/Article/details/gt2pogkmqra.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sufxvd.cn/Article/details/gt2eprykbxk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jyoumei.cn/Article/details/gt2gyfdsnse.html

JS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkzybarg.html

TS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gt2gzmhprrb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.316326.xyz/Article/details/gt2doxiyafk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.redwolf501.top/Article/details/gt2qsxwfwsl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hfpthk.cn/Article/details/gt2jtjhjnus.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tanke756.top/Article/details/gt2zepyvgfa.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2zjewapdu.html

N. 数据结构与算法
来源：http://dali.316326.xyz/Article/details/gt2tdsgzkcq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2nrydwvir.html

[N01] 二分查找（有序数组）
来源：http://dali.tanke756.top/Article/details/gt2zzvsqqfu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2tfdqixej.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jyoumei.cn/Article/details/gt2lumcyfsc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gt2qegekbch.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gt2kdpsxtrl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2kgxzejbm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2eqvaiknl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xsygqskj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2nqdixzje.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gt2cfilsqsr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gt2rqbftgdc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lyalbdjz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gt2jishuecc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gt2imzdjbhp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gt2hhalbhic.html

Go:   slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gt2fxktttjq.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gt2jsdbilzl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dashuyun.cn/Article/details/gt2nepmyjrw.html

[N03] 快速排序（分治示例）
来源：http://dali.daxiang520.top/Article/details/gt2zkyiuknz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gzhubu.top/Article/details/gt2zmtidfwt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nwbrower.top/Article/details/gt2zuvwusjx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gt2htdteime.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gt2igbtiuvf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guowangkeji.top/Article/details/gt2yxigqgdg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cucudq.cn/Article/details/gt2wypmnvjj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hnxiangtu.top/Article/details/gt2ltwfkucm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.haohaochexian.top/Article/details/gt2qofmppcc.html

[N04] 斐波那契数列
来源：http://dali.0kj1m.cn/Article/details/gt2psaeztuw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gt2kfvpodxw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gt2vydgwgbb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gt2aolnfkgs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gt2yhacszvr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gt2kfgqzesu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258.top/Article/details/gt2ifcipdwi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gt2rpvjryfo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gt2dfhkgxpi.html

[N05] 最大公约数
来源：http://dali.sxryk.cn/Article/details/gt2hxygpzyg.html

Py:   math.gcd(a, b)
来源：http://dali.cqqwz.cn/Article/details/gt2ovhnhjpv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.mhx1999.top/Article/details/gt2sarjftbn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gt2hbyigovu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gt2gvhwcztt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.0kj1m.cn/Article/details/gt2zryrbccq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gt2fkcrvxon.html

Ruby: a.gcd(b)
来源：http://dali.sweek.top/Article/details/gt2cnbnkgmr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xylfe.cn/Article/details/gt2zfvnryyj.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gt2zujlkcut.html

Py:   s == s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gt2ofkhmvah.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258.top/Article/details/gt2etzmngqb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hhfzjigr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2ppbuagyw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pengpengdd.cyou/Article/details/gt2iasohvxe.html

Go:   // 双指针从两端比较
来源：http://dali.jqgfzy.top/Article/details/gt2rcmvpqyv.html

Ruby: s == s.reverse
来源：http://dali.aizwys.cn/Article/details/gt2zrizputr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gt2xwardlkw.html

[N07] 两数之和（返回下标）
来源：http://dali.haohaochexian.top/Article/details/gt2lbhkdvls.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shuidangran.top/Article/details/gt2lqpfedlk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dashuyun.cn/Article/details/gt2tpbkiwih.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.haohaochexian.top/Article/details/gt2jtvhtdfp.html

TS:   // 手写 Map<string, number>
来源：http://dali.xinyue.icu/Article/details/gt2pxboqtoo.html

Java: // 手写 HashMap
来源：http://dali.birdmap.top/Article/details/gt2llimaolo.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzrauzx.html

Ruby: // 手写 Hash
来源：http://dali.mhx1999.top/Article/details/gt2lqxiloer.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gotoacloud.top/Article/details/gt2umqhscin.html

[N08] 生成全排列
来源：http://dali.chenlongwang.top/Article/details/gt2ppibrvcj.html

Py:   itertools.permutations(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2vkpdpoib.html

PHP:  // 手写递归交换
来源：http://dali.yuanzhike.top/Article/details/gt2hnltkwzv.html

JS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gt2ogjwqrbb.html

TS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2lcayczzj.html

Java: // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2eriswqbm.html

Go:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2fbqarehz.html

Ruby: arr.permutation.to_a
来源：http://dali.mhx1999.top/Article/details/gt2jyttziqk.html

C#:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2owqxzjgc.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2zeotrykb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ybcxt.top/Article/details/gt2iqziywir.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2jkxdnxgl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gt2jzhgtzgo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigfzy.top/Article/details/gt2xmhidlhg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xinyue.icu/Article/details/gt2jaofbfkt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cheryme.top/Article/details/gt2iphwpzxj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gt2nytsweox.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhlvwyot.html

[N10] 链表节点定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqdiweit.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hysaishi.cn/Article/details/gt2lzurcdqu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.fengsongda.top/Article/details/gt2keglshfg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sxryk.cn/Article/details/gt2uanwvezw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj202588.top/Article/details/gt2icyuxdqp.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gt2nsjaiwvq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jianghu66.top/Article/details/gt2aynxogzc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daxiang520.top/Article/details/gt2asvawygx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenzaomai.com/Article/details/gt2hbdgswxp.html

[N11] 二叉树中序遍历
来源：http://dali.hammf.cn/Article/details/gt2zdvhabgz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ivvv.top/Article/details/gt2lgokhsap.html

PHP:  // 手写递归函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2grugifsj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gt2xbcnhfmc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gt2ailecpxb.html

Java: // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gt2unkhympk.html

Go:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2klqgyimp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.quarkkingdee.top/Article/details/gt2xgovljtp.html

C#:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gt2jyuursoj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuanzx.com/Article/details/gt2ocehmias.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhiwuduotai.top/Article/details/gt2gzlzymav.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tianlin.xyz/Article/details/gt2cxfvsnbz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gt2zgbyhusv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khcfaqma.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gt2vrsdhgdn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnqzz.top/Article/details/gt2jbbzjjuk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guowangkeji.top/Article/details/gt2oxokncva.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gt2yhwrlqtd.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2sowossgs.html

O. 并发与异步
来源：http://dali.chenzaomai.com/Article/details/gt2plxrfifx.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2fqainhli.html

[O01] 启动一个线程
来源：http://dali.xylfe.cn/Article/details/gt2rkxmwhza.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuanzhike.top/Article/details/gt2ckknpahd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.svipenyu.cn/Article/details/gt2ymynrazp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jlsjyb.cn/Article/details/gt2rrccklwa.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gt2qimkonbv.html

Java: new Thread(() -> f()).start()
来源：http://dali.daxiang520.top/Article/details/gt2kcgkxvrm.html

Go:   go f()
来源：http://dali.xylfe.cn/Article/details/gt2nfzppnfc.html

Ruby: Thread.new { f }
来源：http://dali.pycfn.com/Article/details/gt2jzvlzdwg.html

C#:   Task.Run(() => F());
来源：http://dali.ppjwa.cn/Article/details/gt2ralhflfx.html


<!-- 参考信息 -->