代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuetiantiany.cn/Article/details/gt2wufsxjwp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ybcxt.top/Article/details/gt2yjaoqdaq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.vqdsnc.cn/Article/details/gt2yqpadvgh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhixingplan.top/Article/details/gt2forsmlsa.html

[K06] 解析 URL 查询串
来源：http://dali.zhengqikj.top/Article/details/gt2jvbifpvz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.c1oappe.top/Article/details/gt2pqlpbepc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.svipenyu.cn/Article/details/gt2vjhfgkue.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gt2yjudnnho.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfevkagd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvqvwcit.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2bhuijlra.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gt2iykryngp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gt2zmcuydmw.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gt2gzfxrzku.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zshcwmfw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gzhubu.top/Article/details/gt2owkzfedx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2vbdnutfg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2rcaoujtc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2zeeevmbb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.316326.xyz/Article/details/gt2dmywfspz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pycfn.com/Article/details/gt2ambohveo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cheryme.top/Article/details/gt2ycmgfawp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tianlin.xyz/Article/details/gt2qdbjkiru.html

Py:   pickle.dumps(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2biqgnpbq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ybcxt.top/Article/details/gt2jgwksyjd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gt2ckzlgdug.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2nfosiqme.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxinkj.top/Article/details/gt2igahbkvu.html

Go:   encoding/gob
来源：http://dali.ivvv.top/Article/details/gt2kwldgdkk.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2flufozvz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gt2trgvwdhu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2npubvjfs.html

L. 网络请求
来源：http://dali.yj202588.top/Article/details/gt2bjrgxpmk.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ulztjcps.html

[L01] 发送 GET 请求
来源：http://dali.gogol.net.cn/Article/details/gt2lswcektn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gt2wtkhetwf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zdqjudy.top/Article/details/gt2nnfwbccg.html

JS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gt2owoylqwp.html

TS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sffmvxka.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnxiangtu.top/Article/details/gt2rgsrxhua.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj202588.top/Article/details/gt2lizyfmgs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nanxinkj.top/Article/details/gt2hscvpgou.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xylfe.cn/Article/details/gt2cngtkstn.html

[L02] 发送 POST JSON
来源：http://dali.ybcxt.top/Article/details/gt2xkrxxiyk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gt2kzdkcsyd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigfzy.top/Article/details/gt2jimihihj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gt2xnlyknnt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2bxmqhhff.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pycfn.com/Article/details/gt2bcnpyhgd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hongshengwenyu.top/Article/details/gt2olulfyow.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.iojbl.cn/Article/details/gt2gopllalr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uyqnbjgq.html

[L03] 设置自定义请求头
来源：http://dali.ppjwa.cn/Article/details/gt2qokojotz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gt2cimykhfk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.9152youxi.cn/Article/details/gt2uqyyrgtc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gt2fpifpooh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gt2kmkngblb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.snrcjt.cn/Article/details/gt2bantzpwp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gt2rrovtisa.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangdashe.top/Article/details/gt2rtjoqqlk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gt2fjijawrk.html

[L04] 设置超时
来源：http://dali.tanke756.top/Article/details/gt2zgsyvijg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhengqikj.top/Article/details/gt2cuprbgnr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2giunzyek.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gt2qlznsuaf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gt2dhrzoxmm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gt2zttidvia.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shangyingyoupin.top/Article/details/gt2mgfuplez.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gt2atmamggx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gt2yygwdrjc.html

[L05] 上传文件（multipart）
来源：http://dali.gogol.net.cn/Article/details/gt2gujlmowj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuanzhike.top/Article/details/gt2sknvdesb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ehwqpu.com/Article/details/gt2iofpocmh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gt2hbpegtgx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gt2osgeoaif.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pycfn.com/Article/details/gt2nofhofjx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tian-w.cn/Article/details/gt2rhlhodsz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yangfankeji.com/Article/details/gt2tjlytnta.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2ncvmevpa.html

[L06] 解析响应为 JSON
来源：http://dali.gotoacloud.top/Article/details/gt2cutyyjjn.html

Py:   resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2lxbmzvry.html

PHP:  json_decode($body, true);
来源：http://dali.hnqzz.top/Article/details/gt2ywsphzvb.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2scswclel.html

TS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gt2wtpfkuow.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258.top/Article/details/gt2wumvzjhw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tianlin.xyz/Article/details/gt2hvoocziy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.bjfxy.top/Article/details/gt2sggjdhaf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tianlin.xyz/Article/details/gt2jrjvkgvp.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gt2aixdokwm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.9152youxi.cn/Article/details/gt2kklijajt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gt2icxbxqbw.html

JS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gt2ksxtodye.html

TS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2elnycmho.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gt2lndftftm.html

Go:   resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gt2hznepkjv.html

Ruby: resp.code.to_i
来源：http://dali.yvedp.cn/Article/details/gt2zdzrswqu.html

C#:   (int)resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gt2mmjrmsbh.html

[L08] 并发请求多个地址
来源：http://dali.yueranfly.top/Article/details/gt2mcrkkxty.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.bjfxy.top/Article/details/gt2xxbbrzdd.html

PHP:  curl_multi_init() 系列
来源：http://dali.tian-w.cn/Article/details/gt2sqcbczaw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gt2frsupyxu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gt2rvfhmqjl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gt2bfnqsdvq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sufxvd.cn/Article/details/gt2rghamhtl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dianchejie.cn/Article/details/gt2sqxxrefn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.redwolf501.top/Article/details/gt2mpnqrcwp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ztszksur.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gt2ljedgowf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2iipgcxrj.html

[M01] 读取命令行参数
来源：http://dali.dashuyun.cn/Article/details/gt2lsekioum.html

Py:   sys.argv[1:]
来源：http://dali.nanxuanxn.top/Article/details/gt2hhcgpwtz.html

PHP:  $argv;  $argc;
来源：http://dali.ehwqpu.com/Article/details/gt2fqxbmtrg.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gt2kbeuzzop.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gt2chauqwpz.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gt2ancsggyj.html

Go:   os.Args[1:]
来源：http://dali.vqdsnc.cn/Article/details/gt2xwjawlpx.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gt2moiyshxs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gt2tkkqpiij.html

[M02] 读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xeabfzix.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2miikikrs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.havefunace.top/Article/details/gt2skcrkyay.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gt2seohjrgv.html

TS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gt2swtrzwvh.html

Java: System.getenv("HOME")
来源：http://dali.yongpay.top/Article/details/gt2xlijtkgj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2eejsksdu.html

Ruby: ENV["HOME"]
来源：http://dali.hnqzz.top/Article/details/gt2mpxkitku.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tian-w.cn/Article/details/gt2jrcysbes.html

[M03] 执行外部命令
来源：http://dali.316326.xyz/Article/details/gt2sdimcaba.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gt2saljtmzz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zdqjudy.top/Article/details/gt2txejvzyq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gt2bavukiha.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gt2phlunurt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhoulong.xyz/Article/details/gt2ojxmpaap.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhixingplan.top/Article/details/gt2iknjggdd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yongpay.top/Article/details/gt2txegqueh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sysykeji.top/Article/details/gt2qtkxmesu.html

[M04] 获取当前工作目录
来源：http://dali.jyoumei.cn/Article/details/gt2cmmaocsz.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akdcgxli.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gt2tijndtpr.html

JS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gt2mvtplwwy.html

TS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gt2iwrcfxos.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guowangkeji.top/Article/details/gt2mpcoychz.html

Go:   os.Getwd()
来源：http://dali.yj202588.top/Article/details/gt2ontgjlsx.html

Ruby: Dir.pwd
来源：http://dali.cqqwz.cn/Article/details/gt2qudntyiy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gt2yohjfwjz.html

[M05] 设置退出码
来源：http://dali.cucudq.cn/Article/details/gt2uwvdndla.html

Py:   sys.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2kpnjrfga.html

PHP:  exit(1);
来源：http://dali.redwolf501.top/Article/details/gt2svddofgn.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2lhfndrpq.html

TS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2ntrtwouc.html

Java: System.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2rvpxbdyi.html

Go:   os.Exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2iliqouof.html

Ruby: exit 1
来源：http://dali.ybcxt.top/Article/details/gt2rowkeppi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangshuangyany.cn/Article/details/gt2kdycivrq.html

[M06] 向标准错误输出
来源：http://dali.cheryme.top/Article/details/gt2xlgdybuz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gt2trkvdpfh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgfzy.top/Article/details/gt2ubpmslno.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyavangc.html

TS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gt2hvgbzhyp.html

Java: System.err.println("err")
来源：http://dali.svipenyu.cn/Article/details/gt2iwncbwbw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wzmensnh.html

Ruby: warn "err"
来源：http://dali.yj20258.top/Article/details/gt2pcvbybll.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.mhx1999.top/Article/details/gt2rbyussri.html

[M07] 判断是否为主入口
来源：http://dali.aibaodan.cn/Article/details/gt2kawvylgu.html

Py:   if __name__ == "__main__":
来源：http://dali.tanke756.top/Article/details/gt2zctlqgci.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.redwolf501.top/Article/details/gt2xltgnlxw.html

JS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gt2hgwfoprz.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gt2ptbmibhf.html

Java: public static void main(String[] args)
来源：http://dali.yonumen.top/Article/details/gt2tmkfdtke.html

Go:   func main()
来源：http://dali.yuanzhike.top/Article/details/gt2nvyzlwsz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2luhfbrhv.html

C#:   static void Main(string[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ehrxejmk.html

[M08] 获取系统与运行时信息
来源：http://dali.shangyingyoupin.top/Article/details/gt2hwzzqzds.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxuanxn.top/Article/details/gt2rrvdzurn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ssgvusmd.html

JS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gt2kywbfdwj.html

TS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gt2iqizcmdu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cqqwz.cn/Article/details/gt2jmvmndic.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhengqikj.top/Article/details/gt2khwogzzy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sweek.top/Article/details/gt2auomkeiz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.havefunace.top/Article/details/gt2uxtbernp.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ivmjbbkc.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gt2zebphwie.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2vnybluvb.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gt2ixsrgqcb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2btbjtgxx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gt2wracrycm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2aftezohx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gt2pivokhlq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2ebvczgtg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2xwfrzypv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jiagoushi.top/Article/details/gt2palvcrhv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2xokqpgbu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ivjqflcw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gt2ynpzlifx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2sezaguih.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gt2zmjuthjt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2swfnubwu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sxryk.cn/Article/details/gt2kyvqfybo.html

Go:   slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gt2bhcnwflh.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gt2xicgudol.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258888.top/Article/details/gt2glhlxytw.html

[N03] 快速排序（分治示例）
来源：http://dali.c1oappe.top/Article/details/gt2qxdsvqyu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hammf.cn/Article/details/gt2mgycnqrb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.iojbl.cn/Article/details/gt2babafdkc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gt2skpjpqbh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gt2giwnnnwv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.andypj.xyz/Article/details/gt2ioyodork.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhiwuduotai.top/Article/details/gt2gbxedgxw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.meibo888.top/Article/details/gt2mlyegury.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gt2frzbtkqo.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gt2ahuobgpa.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gt2nmpjmzst.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aizwys.cn/Article/details/gt2mbammjbp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gt2svgcnapw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gt2redpmfsk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gt2qvptdhfd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptrhcwus.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gt2pzxmnpva.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gt2qstzrcmx.html

[N05] 最大公约数
来源：http://dali.jqgfzy.top/Article/details/gt2tfkpsxbi.html

Py:   math.gcd(a, b)
来源：http://dali.redwolf501.top/Article/details/gt2fcicnjjh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aizwys.cn/Article/details/gt2nxceocru.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gt2wytcztox.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ezgrviev.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.smart0.xyz/Article/details/gt2bvgllked.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnqzz.top/Article/details/gt2dysximtc.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dtjqrhtz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.c1oappe.top/Article/details/gt2wflzepsj.html

[N06] 判断回文字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2ueksnfqi.html

Py:   s == s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gt2ffxuimti.html

PHP:  $s === strrev($s);
来源：http://dali.bjfxy.top/Article/details/gt2rhxtlfuj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gt2dnhwfjrx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2ttitaphy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guannengcc.top/Article/details/gt2qnqjagfr.html

Go:   // 双指针从两端比较
来源：http://dali.hammf.cn/Article/details/gt2nzpfjejx.html

Ruby: s == s.reverse
来源：http://dali.cheryme.top/Article/details/gt2gutuuyng.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gt2uygecxoy.html

[N07] 两数之和（返回下标）
来源：http://dali.ehwqpu.com/Article/details/gt2fyjcseor.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.quarkkingdee.top/Article/details/gt2vwvnjtok.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gzhubu.top/Article/details/gt2vvcjedmr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigufen.top/Article/details/gt2ghmfpolf.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenlongwang.top/Article/details/gt2ioomhfpl.html

Java: // 手写 HashMap
来源：http://dali.guowangkeji.top/Article/details/gt2eczabari.html

Go:   // 手写 map[int]int
来源：http://dali.hnqzz.top/Article/details/gt2cmuchozw.html

Ruby: // 手写 Hash
来源：http://dali.meibo888.top/Article/details/gt2bdgvixsy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxuanxn.top/Article/details/gt2bskwyupz.html

[N08] 生成全排列
来源：http://dali.9152youxi.cn/Article/details/gt2zzjegpar.html

Py:   itertools.permutations(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2bvkhjcqp.html

PHP:  // 手写递归交换
来源：http://dali.9152youxi.cn/Article/details/gt2fcphdedk.html

JS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2dckidrqx.html

TS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2urhwpmok.html

Java: // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2ovdpbijl.html

Go:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vifixmhn.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgfzy.top/Article/details/gt2hgbogeel.html

C#:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gt2ieuybdxs.html

[N09] 栈与队列
来源：http://dali.nwbrower.top/Article/details/gt2tgcyyaeo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxuanxn.top/Article/details/gt2ejdrgpkv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xvxuheef.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gt2atkmxhxw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgfzy.top/Article/details/gt2kxsjoxdg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.316326.xyz/Article/details/gt2qiiabucu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj202588.top/Article/details/gt2bejqcbue.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gt2mgulzeep.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fzhhl.top/Article/details/gt2lfbujiag.html

[N10] 链表节点定义
来源：http://dali.sxryk.cn/Article/details/gt2pampnoug.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgfzy.top/Article/details/gt2sucwgrdh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigfzy.top/Article/details/gt2bsvoelhi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gt2hfirzzxf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rmranhli.html

Java: class Node { int v; Node next; }
来源：http://dali.snrcjt.cn/Article/details/gt2hdguqtfd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gt2zjbtbmus.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.birdmap.top/Article/details/gt2rlvskwrt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhixingplan.top/Article/details/gt2lwnblxev.html

[N11] 二叉树中序遍历
来源：http://dali.haohaochexian.top/Article/details/gt2ehwurzuo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gt2gkdcvbzn.html

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gt2ijnjxxvn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gt2ebgckdni.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gt2gayakrwv.html

Java: // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gt2itnnqgnd.html

Go:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gt2akdnxqwr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ppjwa.cn/Article/details/gt2fxybwsgz.html

C#:   // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gt2tarlktpj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daxiang520.top/Article/details/gt2fblhknbm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj20258.top/Article/details/gt2denffnkp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.havefunace.top/Article/details/gt2mrmnoowj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gt2jzandaik.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gt2rjetkogz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gt2phiijinj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxinkj.top/Article/details/gt2ifdukrhp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.redwolf501.top/Article/details/gt2qxsjpebp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gt2ojlktvvr.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2bptxveqj.html

O. 并发与异步
来源：http://dali.zhiwuduotai.top/Article/details/gt2cmbukitn.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2ifxgvwnk.html

[O01] 启动一个线程
来源：http://dali.yanxiufei.cn/Article/details/gt2bmfgcdfw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.birdmap.top/Article/details/gt2qhksmkqm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgfzy.top/Article/details/gt2ycktzhyo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.vqdsnc.cn/Article/details/gt2etcztnzl.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gt2zjoglgfl.html


<!-- 参考信息 -->