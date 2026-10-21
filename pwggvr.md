代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtouyoqkea.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigufen.top/Article/details/gtqideytwv.html

JS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtbmgesgln.html

TS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupsjrxaf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cheryme.top/Article/details/gtdkdestbw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhengqikj.top/Article/details/gtrljzgckn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnxiangtu.top/Article/details/gteegaxmyb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cashguo.top/Article/details/gtpoexorum.html

[K06] 解析 URL 查询串
来源：http://dali.pycfn.com/Article/details/gtcvzhyptg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtgntnxmmu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.0kj1m.cn/Article/details/gtmnzeugby.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gtnvouhpok.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gtwibepacb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.c1oappe.top/Article/details/gtigvwwvhh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gttktpriph.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtndajueoa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtclscspfs.html

[K07] 进制转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugftpfkc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtqprbgahi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gthunqirzq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtvyhytpsz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdegtmpa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuukirizm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuetiantiany.cn/Article/details/gtsofktrhd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jiagoushi.top/Article/details/gtokbrkhlf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gteuuuaauy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sweek.top/Article/details/gtulcucmym.html

Py:   pickle.dumps(obj)
来源：http://dali.guowangkeji.top/Article/details/gtoyoitzvt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sweek.top/Article/details/gtbhrcxpdw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gtcpcpyxhd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtakdbkkat.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xziqi.cn/Article/details/gtkhikcrke.html

Go:   encoding/gob
来源：http://dali.jiagoushi.top/Article/details/gtorrulgsy.html

Ruby: Marshal.dump(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtyjupfcwe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gtvcjmaedf.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtjdljgqvb.html

L. 网络请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcitqrysv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtqhukdmcn.html

[L01] 发送 GET 请求
来源：http://dali.jqgufenzy.top/Article/details/gtmdrjszlc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fzhhl.top/Article/details/gtgyszjoce.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhengqikj.top/Article/details/gtvxapiofs.html

JS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtmdqonjed.html

TS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtwdnqxhfl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.kuanghao11.cn/Article/details/gtmzetpetx.html

Go:   resp, err := http.Get(url)
来源：http://dali.nwbrower.top/Article/details/gtrnnnyzfh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgufenzy.top/Article/details/gteeucqvmz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhoulong.xyz/Article/details/gtuymvdjyp.html

[L02] 发送 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtmypcucfs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gtydsvfjzr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangtech.top/Article/details/gttwtvcnjs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gttpgrsfno.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtecwucchy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cheryme.top/Article/details/gtglumqoht.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrzlplfq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj202588.top/Article/details/gtrtrkrtsv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gtexlsxios.html

[L03] 设置自定义请求头
来源：http://dali.aizwys.cn/Article/details/gtenznuooa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hfpthk.cn/Article/details/gtqmkijvjh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hywenlv.cn/Article/details/gtpqkjxlhe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhiwkarh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gtmyfdfrwo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ydzc1.top/Article/details/gtfermwqix.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gtqtxcixff.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gtttkvcdnl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gtsvxlrulh.html

[L04] 设置超时
来源：http://dali.cheryme.top/Article/details/gtghxkjapt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcexfovk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daxiang520.top/Article/details/gtswtthxxa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gtmalrgnzp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrcdlxfi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gticnoabrc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shangyingyoupin.top/Article/details/gtbfldornx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jyoumei.cn/Article/details/gtdmzdzbuq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yangfankeji.com/Article/details/gtdtbbkcgx.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258.top/Article/details/gtkpbmczqm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gthlzfipne.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenlongwang.top/Article/details/gtczabhlkm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gtqvgknfqc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gtcqgdwyrz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aibaodan.cn/Article/details/gtkvbpphej.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gotoacloud.top/Article/details/gtvqasloif.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzqswlsm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtteveckfz.html

[L06] 解析响应为 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtlqcoxtqp.html

Py:   resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtemvcvwqj.html

PHP:  json_decode($body, true);
来源：http://dali.guannengcc.top/Article/details/gtqyucrfar.html

JS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gtlvxdljqv.html

TS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gtqpwbsygn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtkfforczz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gtmaoepejh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.0kj1m.cn/Article/details/gtsolfyypk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gtitbvvjyc.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtjcoyewsd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gtmvcalvbm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ivvv.top/Article/details/gtonomebxd.html

JS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtoingbhge.html

TS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gtozmknbzy.html

Java: resp.statusCode()
来源：http://dali.jinqigufen.top/Article/details/gtvzbmfncn.html

Go:   resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtthyjxrqn.html

Ruby: resp.code.to_i
来源：http://dali.yueranfly.top/Article/details/gtstwfhdfk.html

C#:   (int)resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gteztsxjuv.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gtigjyvipl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenzaomai.com/Article/details/gtagsdygji.html

PHP:  curl_multi_init() 系列
来源：http://dali.gzhubu.top/Article/details/gtekwxlmbs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtcivaewrw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtehbvmtmb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenlongwang.top/Article/details/gtjmgmxhti.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhongyouzk.top/Article/details/gtoqbtvqjs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.bjfxy.top/Article/details/gtzzfbrohf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yangfankeji.com/Article/details/gtqrnlprit.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtlbcilkzi.html

M. 命令行 / 进程 / 环境
来源：http://dali.guannengcc.top/Article/details/gtejpqbsgb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtaftvmaew.html

[M01] 读取命令行参数
来源：http://dali.daxiang520.top/Article/details/gtjjqptldh.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gtcwrflpmp.html

PHP:  $argv;  $argc;
来源：http://dali.vqdsnc.cn/Article/details/gtfwpeasfu.html

JS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gtqavuhhzt.html

TS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gtxepkiejm.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtcakrlnrv.html

Go:   os.Args[1:]
来源：http://dali.xylfe.cn/Article/details/gtlxxsldmi.html

Ruby: ARGV
来源：http://dali.ppjwa.cn/Article/details/gtetrgwsit.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtiqvinpbd.html

[M02] 读取环境变量
来源：http://dali.yj202588.top/Article/details/gtfwbeiwfh.html

Py:   os.environ.get("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtemuntpol.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gthmikdxdt.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtbnvuzeei.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtvzljhbcy.html

Java: System.getenv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtrgongvdv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtrqjirazv.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gtecprdwjr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdldasojx.html

[M03] 执行外部命令
来源：http://dali.xziqi.cn/Article/details/gtwtjgevyx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ybcxt.top/Article/details/gtpzgfxpfr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gtfihrjodp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtpnmutmke.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtjbkvgplx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tanke756.top/Article/details/gtwzvckggk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.smart0.xyz/Article/details/gtskqtrpdg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gtzibtvvgi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jiagoushi.top/Article/details/gtuhrrifvf.html

[M04] 获取当前工作目录
来源：http://dali.zhengqikj.top/Article/details/gtinqguiqa.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gteljzocbn.html

PHP:  getcwd();
来源：http://dali.birdmap.top/Article/details/gttstfzcqg.html

JS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gtthcfoldt.html

TS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gtdujqmozu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gtjgammnag.html

Go:   os.Getwd()
来源：http://dali.sufxvd.cn/Article/details/gtxgrsmwrt.html

Ruby: Dir.pwd
来源：http://dali.cqqwz.cn/Article/details/gtyamcwmxu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.0kj1m.cn/Article/details/gtzknyfkrf.html

[M05] 设置退出码
来源：http://dali.shzxlz.cn/Article/details/gtadpryyup.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtqzqunleg.html

PHP:  exit(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkyincph.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gtwjwtmafe.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtdoqcafnq.html

Java: System.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtzmqygfbn.html

Go:   os.Exit(1)
来源：http://dali.bjfxy.top/Article/details/gtzoyikbkg.html

Ruby: exit 1
来源：http://dali.pengpengdd.cyou/Article/details/gttwjvpcgq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangshuangyany.cn/Article/details/gtwhldbrka.html

[M06] 向标准错误输出
来源：http://dali.yueranfly.top/Article/details/gtxairneqc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gtmhsphcup.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jianghu66.top/Article/details/gtyejmmosv.html

JS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtooqlzspx.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtfhvgogwx.html

Java: System.err.println("err")
来源：http://dali.quarkkingdee.top/Article/details/gtrrbpdeyx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jiagoushi.top/Article/details/gtwsmthmpx.html

Ruby: warn "err"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjznwtaw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xylfe.cn/Article/details/gtihqqkprp.html

[M07] 判断是否为主入口
来源：http://dali.jyoumei.cn/Article/details/gtevlyyxhq.html

Py:   if __name__ == "__main__":
来源：http://dali.xuetiantiany.cn/Article/details/gtbdzkeuus.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hywenlv.cn/Article/details/gtuvaogsvd.html

JS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gtnoxzigea.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtilxxaxve.html

Java: public static void main(String[] args)
来源：http://dali.jinqigufen.top/Article/details/gtqjnmtryt.html

Go:   func main()
来源：http://dali.chenzaomai.com/Article/details/gtuepnibfl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmeoaonh.html

C#:   static void Main(string[] args)
来源：http://dali.jlsjyb.cn/Article/details/gtlcfcudou.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258888.top/Article/details/gttwujawbr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cheryme.top/Article/details/gtruhwjgmm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258.top/Article/details/gtlquiqbdm.html

JS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gtwetambvb.html

TS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtnnqrxfoi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxinkj.top/Article/details/gtkatrsrdo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuxming.cn/Article/details/gtbfnvmisu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xylfe.cn/Article/details/gtdazxzdyi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuanzx.com/Article/details/gtfhlgduso.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbnqnwzd.html

N. 数据结构与算法
来源：http://dali.iojbl.cn/Article/details/gtqobapgsi.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtflosyewc.html

[N01] 二分查找（有序数组）
来源：http://dali.shzxlz.cn/Article/details/gtwrhsrnvf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtuqdtszsx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtikhadfdo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gtnibmfnwb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtfbsldfkw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gtmfpflkul.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwujsevnu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yangfankeji.com/Article/details/gtxajpjkps.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtqiqncsbj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ydzc1.top/Article/details/gtkxiwaqji.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtyjelljfq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258.top/Article/details/gtpohvooij.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtdajjmplh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gttzctpfov.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.feifeiyinyue.top/Article/details/gtiwdsslzp.html

Go:   slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gtrxugknpc.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gthdmwvdbx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258888.top/Article/details/gtollraxcd.html

[N03] 快速排序（分治示例）
来源：http://dali.gogol.net.cn/Article/details/gtwocxjnkl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sufxvd.cn/Article/details/gtmwifybkv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.svipenyu.cn/Article/details/gteexjjifs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gtcyfjmauy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gtxmddspws.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigfzy.top/Article/details/gtsmdwnwuw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.0kj1m.cn/Article/details/gtulqiwvzm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gtiaobpwfz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cdnleiting.top/Article/details/gtfczcnlfi.html

[N04] 斐波那契数列
来源：http://dali.cashguo.top/Article/details/gtpuxggsxc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gtcoegtjjl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzismwdnh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtyoayaryn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtbjjmmfkh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxagzyijv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqllxuvxi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtfpaggzxs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtagjrgedx.html

[N05] 最大公约数
来源：http://dali.fzhhl.top/Article/details/gtnjfeaxtq.html

Py:   math.gcd(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtjrorwslg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jyoumei.cn/Article/details/gtjogprsok.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gtdkmhvoru.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gtpqbvratc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.feifeiyinyue.top/Article/details/gtflpbcdwa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj202588.top/Article/details/gtqrcucxaz.html

Ruby: a.gcd(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtotsolpfx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuanzx.com/Article/details/gtaulyyldd.html

[N06] 判断回文字符串
来源：http://dali.shuidangran.top/Article/details/gtzgephueh.html

Py:   s == s[::-1]
来源：http://dali.sxryk.cn/Article/details/gtziklowdj.html

PHP:  $s === strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtgoaghsft.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtzwopyevn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtljmwisri.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.birdmap.top/Article/details/gtbrxjibdm.html

Go:   // 双指针从两端比较
来源：http://dali.nanxinkj.top/Article/details/gtqcwwqqph.html

Ruby: s == s.reverse
来源：http://dali.yueranfly.top/Article/details/gtzuwwbheb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gtyvgglpqf.html

[N07] 两数之和（返回下标）
来源：http://dali.dianchejie.cn/Article/details/gtjlpssziz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hywenlv.cn/Article/details/gtethlffdi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuanzx.com/Article/details/gtxktwmzbo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yonumen.top/Article/details/gtdtepxylw.html

TS:   // 手写 Map<string, number>
来源：http://dali.tianlin.xyz/Article/details/gtdcpmtfsn.html

Java: // 手写 HashMap
来源：http://dali.zhoulong.xyz/Article/details/gtydkixnpy.html

Go:   // 手写 map[int]int
来源：http://dali.guannengcc.top/Article/details/gtmljrltnu.html

Ruby: // 手写 Hash
来源：http://dali.cashguo.top/Article/details/gthiwjgkis.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszfrtwup.html

[N08] 生成全排列
来源：http://dali.yangfankeji.com/Article/details/gtueykjvma.html

Py:   itertools.permutations(arr)
来源：http://dali.yvedp.cn/Article/details/gtqmpgqsaf.html

PHP:  // 手写递归交换
来源：http://dali.dianchejie.cn/Article/details/gtybzksvic.html

JS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtyslnuttn.html

TS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtgyzvjqfq.html

Java: // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtibasyhwo.html

Go:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtoavxvglz.html

Ruby: arr.permutation.to_a
来源：http://dali.gotoacloud.top/Article/details/gttcmchbdm.html

C#:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gthmwbyjmr.html

[N09] 栈与队列
来源：http://dali.gotoacloud.top/Article/details/gtynzegxal.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gtrpmpvkuv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gttbfgeczw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtrxypzxjq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhengqikj.top/Article/details/gttwpirhdx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtxrxfkqzf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigfzy.top/Article/details/gtsisgoprh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtnrgyeyqa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhengqikj.top/Article/details/gtteqijtut.html

[N10] 链表节点定义
来源：http://dali.cashguo.top/Article/details/gtebxsihcd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hysaishi.cn/Article/details/gtzhsomyom.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shuidangran.top/Article/details/gtfrzjcqqk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yvedp.cn/Article/details/gtwefnwzkg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tian-w.cn/Article/details/gtouixsdpi.html

Java: class Node { int v; Node next; }
来源：http://dali.jyoumei.cn/Article/details/gtsxmehtiv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sufxvd.cn/Article/details/gtaflgreor.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dashuyun.cn/Article/details/gtxzaykvaf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daria6918.cn/Article/details/gtcqojvimg.html

[N11] 二叉树中序遍历
来源：http://dali.meibo888.top/Article/details/gtvswreqop.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzivojta.html

PHP:  // 手写递归函数
来源：http://dali.feifeiyinyue.top/Article/details/gtlgflltdj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gtxqoaohmh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtdozwcwhn.html

Java: // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtkgrkpjsw.html

Go:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtjdiztnce.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dianchejie.cn/Article/details/gtyvtbaoio.html

C#:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtmktebmri.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gtdbuzjrjm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yangfankeji.com/Article/details/gtpybuskab.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ivvv.top/Article/details/gtlgkmotvr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtcvoqnhnn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gtxwbirnbh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gtuqiynqjg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cqqwz.cn/Article/details/gtuchntjew.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dianchejie.cn/Article/details/gtqflxywyo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gttbkpmixz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtrnotsbjk.html

O. 并发与异步
来源：http://dali.hywenlv.cn/Article/details/gtelrkpyur.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqwkteyi.html

[O01] 启动一个线程
来源：http://dali.xinyue.icu/Article/details/gtwrloabkr.html


<!-- 参考信息 -->