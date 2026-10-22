代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hywenlv.cn/Article/details/gt2iaploybu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkizogfz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cashguo.top/Article/details/gt2arqqxoqh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pycfn.com/Article/details/gt2mhlwxnjc.html

[K06] 解析 URL 查询串
来源：http://dali.iojbl.cn/Article/details/gt2eenslwer.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iywalxxi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gt2snxpooag.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gt2pgjfjakm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gt2symjvbgv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258.top/Article/details/gt2grczdfrd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gt2zaolgcab.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gt2mkwgjyix.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krpojgvv.html

[K07] 进制转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2crcoidmb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2etoynwuu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rlerbzun.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2geqprwzf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2eihtetea.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2zifxofkm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.mhx1999.top/Article/details/gt2yrducurl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jiagoushi.top/Article/details/gt2oltyrsoc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2henrbrlj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zdqjudy.top/Article/details/gt2kunvaosq.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2llsxejyy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxxveyxt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gt2otgtmeje.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gt2fmqbdigz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hfpthk.cn/Article/details/gt2ckeyohlf.html

Go:   encoding/gob
来源：http://dali.kuanghao11.cn/Article/details/gt2qbiszbwo.html

Ruby: Marshal.dump(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2eufykbgk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gt2owocjftt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2beybaowk.html

L. 网络请求
来源：http://dali.xuanzx.com/Article/details/gt2kdreintx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2tgcyfnvu.html

[L01] 发送 GET 请求
来源：http://dali.hywenlv.cn/Article/details/gt2jqpogxan.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dianchejie.cn/Article/details/gt2ssffhwvf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ynqsyukn.html

JS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gt2ceamjiox.html

TS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gt2ibuuatwy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gt2xsamwdbq.html

Go:   resp, err := http.Get(url)
来源：http://dali.jianghu66.top/Article/details/gt2prelgseg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xylfe.cn/Article/details/gt2ojotibch.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigufen.top/Article/details/gt2yaeqelwm.html

[L02] 发送 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gt2douxgtjf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gt2fcadvxcf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aizwys.cn/Article/details/gt2nmbywdsw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gt2ctgrwsjd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gt2calzspee.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yvedp.cn/Article/details/gt2qyuefzcy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.snrcjt.cn/Article/details/gt2euzrxtlp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sufxvd.cn/Article/details/gt2wtgxzbua.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuanzhike.top/Article/details/gt2tidtbakq.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gt2ovsxapge.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gt2vxcokxdf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gt2hvzloalp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ikpfippi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gt2jpywgfio.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yueranfly.top/Article/details/gt2xbzfbhex.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gt2jiyfsxxq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zpwlfvlz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ogglvaub.html

[L04] 设置超时
来源：http://dali.jyoumei.cn/Article/details/gt2zsofytgl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cqqwz.cn/Article/details/gt2ygcyfmox.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yueranfly.top/Article/details/gt2pvnjfffr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phrpbijg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gt2pmwdurqf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.redwolf501.top/Article/details/gt2tnflgmmw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnealxop.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2afetazmd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tian-w.cn/Article/details/gt2gyesloeh.html

[L05] 上传文件（multipart）
来源：http://dali.mhx1999.top/Article/details/gt2kplzprxt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gt2nmagtrhy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenlongwang.top/Article/details/gt2ygtroxmv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gt2vbaprkcm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gt2uvwvlavs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cucudq.cn/Article/details/gt2fendqutp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.c1oappe.top/Article/details/gt2olkxszks.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hfpthk.cn/Article/details/gt2vajvyvrt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2ysqzhktx.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gt2kwfejhez.html

Py:   resp.json()
来源：http://dali.gotoacloud.top/Article/details/gt2wlobxoif.html

PHP:  json_decode($body, true);
来源：http://dali.yongpay.top/Article/details/gt2txtoizkn.html

JS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2dbhmorbe.html

TS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gt2dagudhdz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yueranfly.top/Article/details/gt2xhqnrbev.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuanzhike.top/Article/details/gt2ubqrpzbl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.quarkkingdee.top/Article/details/gt2szyvemoi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aizwys.cn/Article/details/gt2usvsjkyr.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gt2kgsarnqm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gt2vkulqdeg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hammf.cn/Article/details/gt2hikbrtzd.html

JS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gt2amigxhec.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gt2efvlelou.html

Java: resp.statusCode()
来源：http://dali.jqgufenzy.top/Article/details/gt2uucekgmn.html

Go:   resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gt2vqawyvuq.html

Ruby: resp.code.to_i
来源：http://dali.wangshuangyany.cn/Article/details/gt2cuqwvefk.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gt2bgfwqoha.html

[L08] 并发请求多个地址
来源：http://dali.jianghu66.top/Article/details/gt2kshboajw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hongshengwenyu.top/Article/details/gt2rkxwhqrp.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gt2beiwzkgq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2ppwecogu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gt2txulcfyp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yanxiufei.cn/Article/details/gt2fhfrdpym.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gt2tpiejvii.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hammf.cn/Article/details/gt2ljbawjub.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2dqtrgtqc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2pejlsibf.html

M. 命令行 / 进程 / 环境
来源：http://dali.hfpthk.cn/Article/details/gt2ippzofff.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2perwshnu.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gt2bbsxaszp.html

Py:   sys.argv[1:]
来源：http://dali.fengsongda.top/Article/details/gt2zwixpfiz.html

PHP:  $argv;  $argc;
来源：http://dali.daxiang520.top/Article/details/gt2xxfdwmlu.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gt2vryohdkw.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gt2pxlmgzyb.html

Java: args 数组（main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gt2cctfrrih.html

Go:   os.Args[1:]
来源：http://dali.cucudq.cn/Article/details/gt2hvhcjbqo.html

Ruby: ARGV
来源：http://dali.tian-w.cn/Article/details/gt2spgjsypc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jydfbsus.html

[M02] 读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gt2jcropexd.html

Py:   os.environ.get("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yviafxva.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gt2bknikdwj.html

JS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gt2nxewtqld.html

TS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gt2wiyvlkqh.html

Java: System.getenv("HOME")
来源：http://dali.fengsongda.top/Article/details/gt2evuqldpn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2csyfqtoz.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iidlctne.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2ejmvkyzh.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gt2mevvryrn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zycfv.cn/Article/details/gt2havmduzu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gt2mzvgaqrg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gt2qvkozwrb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gt2ugyjnqmo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gt2llzpildd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgufenzy.top/Article/details/gt2oothevmp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gt2dtdqkmkp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhixingplan.top/Article/details/gt2tokvokne.html

[M04] 获取当前工作目录
来源：http://dali.mhx1999.top/Article/details/gt2hvhoaqut.html

Py:   os.getcwd()
来源：http://dali.yonumen.top/Article/details/gt2bllybzon.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gt2wwtivmmf.html

JS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gt2eivsaqhy.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tfxnkokp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.mhx1999.top/Article/details/gt2ywkmtvdg.html

Go:   os.Getwd()
来源：http://dali.vqdsnc.cn/Article/details/gt2pefiozzy.html

Ruby: Dir.pwd
来源：http://dali.yueranfly.top/Article/details/gt2mzpyhxlb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.meibo888.top/Article/details/gt2ajwzwcys.html

[M05] 设置退出码
来源：http://dali.yangfankeji.com/Article/details/gt2mrofdatr.html

Py:   sys.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2uujpyejl.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gt2wqqenmzi.html

JS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2upnoemjy.html

TS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2rmtnedwo.html

Java: System.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewmjjyul.html

Go:   os.Exit(1)
来源：http://dali.yj20258.top/Article/details/gt2ljihvoww.html

Ruby: exit 1
来源：http://dali.tian-w.cn/Article/details/gt2udlvapem.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.havefunace.top/Article/details/gt2dwpreidk.html

[M06] 向标准错误输出
来源：http://dali.yangfankeji.com/Article/details/gt2bmyyqait.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yzjtjytc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gt2uejpcuhy.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gt2finhuknv.html

TS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gt2laejaglp.html

Java: System.err.println("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wuixgdpq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nwbrower.top/Article/details/gt2nuydwoie.html

Ruby: warn "err"
来源：http://dali.sxryk.cn/Article/details/gt2jxjycqjl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuanzhike.top/Article/details/gt2bzqlxckz.html

[M07] 判断是否为主入口
来源：http://dali.yvedp.cn/Article/details/gt2svkizuqr.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gt2xopyrgad.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gt2dxovsull.html

JS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gt2yspvkqii.html

TS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gt2vfttmqxf.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pgrteyhw.html

Go:   func main()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdasagny.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gt2gghxzrsj.html

C#:   static void Main(string[] args)
来源：http://dali.snrcjt.cn/Article/details/gt2eghqplpo.html

[M08] 获取系统与运行时信息
来源：http://dali.chenlongwang.top/Article/details/gt2fucdyvze.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gt2edmymkor.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangshuangyany.cn/Article/details/gt2oocisqcp.html

JS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gt2vbhezoik.html

TS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gt2hdlfvtyq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guannengcc.top/Article/details/gt2yjcvoixs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ehwqpu.com/Article/details/gt2lxkmfdhn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gotoacloud.top/Article/details/gt2klzvzlki.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgfzy.top/Article/details/gt2utpgkssf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2aumtowbb.html

N. 数据结构与算法
来源：http://dali.gaohongyu789.top/Article/details/gt2ffkntzad.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2zdgxtnda.html

[N01] 二分查找（有序数组）
来源：http://dali.yvedp.cn/Article/details/gt2shlentst.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2sxrjrnij.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xziqi.cn/Article/details/gt2jgetmlgu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gt2udovxwxl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nuebqvdu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2bqgkajjr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2kqfkdhcj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dianchejie.cn/Article/details/gt2rxxfqqqi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2adlrfvtm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtovgixc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gt2xvbqwbaw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.kuanghao11.cn/Article/details/gt2hdensuib.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gt2qhknguuy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gt2utskpbfl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgfzy.top/Article/details/gt2csngqabe.html

Go:   slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gt2nwesgfls.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gt2lqvdkrxg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ppjwa.cn/Article/details/gt2sewttdkj.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvwgfay.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sysykeji.top/Article/details/gt2vrbktcnc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxuanxn.top/Article/details/gt2mxecytgv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gt2tcaxkzhc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gt2nitiusam.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zycfv.cn/Article/details/gt2nhuigunz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hammf.cn/Article/details/gt2ojjjrnxu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxuanxn.top/Article/details/gt2eewanami.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shzxlz.cn/Article/details/gt2svpzryza.html

[N04] 斐波那契数列
来源：http://dali.daxiang520.top/Article/details/gt2kzwkqqsp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gt2bnacxfun.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cashguo.top/Article/details/gt2pvhdalzr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gt2epozoyev.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gt2vpcgijfi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2njatwhim.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zdqjudy.top/Article/details/gt2jhdgdlzr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gt2erkrizwv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2hqkwtspi.html

[N05] 最大公约数
来源：http://dali.9152youxi.cn/Article/details/gt2jccckrhp.html

Py:   math.gcd(a, b)
来源：http://dali.tanke756.top/Article/details/gt2otlnfhrw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenlongwang.top/Article/details/gt2bldhqrzf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gt2yzsjjcvc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gt2tcikzacg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxinkj.top/Article/details/gt2chwpwffo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gt2meluiypb.html

Ruby: a.gcd(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yzgptxod.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hysaishi.cn/Article/details/gt2kgwsnvkd.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gt2ezhwwsqk.html

Py:   s == s[::-1]
来源：http://dali.wangdashe.top/Article/details/gt2uucmdvhg.html

PHP:  $s === strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2bvblrmqy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2thzayzdb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2eyrjhbex.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jyoumei.cn/Article/details/gt2lrllyvwb.html

Go:   // 双指针从两端比较
来源：http://dali.nanxinkj.top/Article/details/gt2dusnwzjk.html

Ruby: s == s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2ntuhsjtq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gt2ikcgbeml.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhuxnoz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.0kj1m.cn/Article/details/gt2jhssgqhf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jnftnwth.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sysykeji.top/Article/details/gt2zzjengzk.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gt2ltmzyznt.html

Java: // 手写 HashMap
来源：http://dali.quarkkingdee.top/Article/details/gt2gcysmaul.html

Go:   // 手写 map[int]int
来源：http://dali.fengsongda.top/Article/details/gt2eqfbyxss.html

Ruby: // 手写 Hash
来源：http://dali.yangfankeji.com/Article/details/gt2eheonfay.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.quarkkingdee.top/Article/details/gt2avkyncli.html

[N08] 生成全排列
来源：http://dali.hongshengwenyu.top/Article/details/gt2xsxvxara.html

Py:   itertools.permutations(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2xcoghngc.html

PHP:  // 手写递归交换
来源：http://dali.nanxuanxn.top/Article/details/gt2jvyzeavs.html

JS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2tdvcxgyz.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ajhwausn.html

Java: // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gt2rbwsftid.html

Go:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2jjugtxjj.html

Ruby: arr.permutation.to_a
来源：http://dali.jiagoushi.top/Article/details/gt2qeekrnoq.html

C#:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2nsqmthhh.html

[N09] 栈与队列
来源：http://dali.jiagoushi.top/Article/details/gt2lkccrvzu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aizwys.cn/Article/details/gt2zmutlzha.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gt2rojskfxe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gt2irtvjhkm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ehwqpu.com/Article/details/gt2pjniloce.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nwbrower.top/Article/details/gt2nnischsw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ehwqpu.com/Article/details/gt2zadtegih.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2ponenhbr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gt2wmztyciw.html

[N10] 链表节点定义
来源：http://dali.aibaodan.cn/Article/details/gt2mbkhctod.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhiwuduotai.top/Article/details/gt2ugujyltq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuanzhike.top/Article/details/gt2tixmshtv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guannengcc.top/Article/details/gt2gqlhdxrz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnxiangtu.top/Article/details/gt2brwoipwc.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gt2xtwyepjn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdosadkk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uezwlwdz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ybcxt.top/Article/details/gt2nvlwytdq.html

[N11] 二叉树中序遍历
来源：http://dali.cdnleiting.top/Article/details/gt2lwuyowry.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhoulong.xyz/Article/details/gt2cllibrcg.html

PHP:  // 手写递归函数
来源：http://dali.cqqwz.cn/Article/details/gt2cnivvfgg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gt2ixcheypc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gt2svjdsgnm.html

Java: // 手写递归
来源：http://dali.xuanzx.com/Article/details/gt2dqvfwdtu.html

Go:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gt2cmwhybci.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.daxiang520.top/Article/details/gt2dcqharze.html

C#:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gt2qzxgifgl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2alumfzfd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gaohongyu789.top/Article/details/gt2nyqwwpvo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hysaishi.cn/Article/details/gt2dpzuwozt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gt2rfsnqfga.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gt2fpqjqunz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yangfankeji.com/Article/details/gt2hrctmmmh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uojinfex.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jianghu66.top/Article/details/gt2brejukzo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gt2miaobmdb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2taafggez.html

O. 并发与异步
来源：http://dali.nwbrower.top/Article/details/gt2lzqczzfi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2tmnisvos.html

[O01] 启动一个线程
来源：http://dali.jqgfzy.top/Article/details/gt2edxjsmyd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fzhhl.top/Article/details/gt2zukvpwqr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uunimluj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenlongwang.top/Article/details/gt2znaybejo.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymcrmzbl.html


<!-- 参考信息 -->