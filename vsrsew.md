代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tanke756.top/Article/details/gt2mnbbpdvh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.havefunace.top/Article/details/gt2dzkoscwl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenlongwang.top/Article/details/gt2codultyl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fengsongda.top/Article/details/gt2xtkfkiru.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigfzy.top/Article/details/gt2crijpyts.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gt2uyvwuevo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mcaykgzn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ebnvhgdd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gt2mzufunwo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258.top/Article/details/gt2ietqqhbg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gt2detooqru.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gt2eljbpdjj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2hdeclrmn.html

[K07] 进制转换
来源：http://dali.gzhubu.top/Article/details/gt2xceybodc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2cszrqupg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gt2zmgqvctm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2fvxrjiys.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2umijrqnq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2eoimizsr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gt2ljigywjx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuanzhike.top/Article/details/gt2apslosii.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2bdwhmwmn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.kuanghao11.cn/Article/details/gt2ybzhvbib.html

Py:   pickle.dumps(obj)
来源：http://dali.cheryme.top/Article/details/gt2htkhbajl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhengqikj.top/Article/details/gt2feqmiqjt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gt2rsajwnfy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gt2phkernpd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tanke756.top/Article/details/gt2mktrfjlp.html

Go:   encoding/gob
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jekwcegd.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2efeaplwi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gt2anmklsra.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2gkzgnbsa.html

L. 网络请求
来源：http://dali.fengsongda.top/Article/details/gt2azukahwt.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2vvdpggnv.html

[L01] 发送 GET 请求
来源：http://dali.yj20258888.top/Article/details/gt2vhjblqri.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.quarkkingdee.top/Article/details/gt2jajsmlmj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhiwuduotai.top/Article/details/gt2clzlycmt.html

JS:   await fetch(url)
来源：http://dali.xylfe.cn/Article/details/gt2suotcpxv.html

TS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gt2smwtkzyk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhiwuduotai.top/Article/details/gt2brxizcpd.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnqzz.top/Article/details/gt2raiuxbmu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gt2cdcllcqt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2mnoespxt.html

[L02] 发送 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gt2aavmrnnf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gt2iqeglbwc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gt2wylhkswg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gt2rxcradkh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gt2efovhacn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.havefunace.top/Article/details/gt2ngganohj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gt2aookgcib.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dashuyun.cn/Article/details/gt2yzoagzxs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258.top/Article/details/gt2hfgmheyl.html

[L03] 设置自定义请求头
来源：http://dali.yangfankeji.com/Article/details/gt2wlgtzbbr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gt2dknnuoax.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sweek.top/Article/details/gt2neotrpwk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmypqzpd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gt2fbscqpqu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhiwuduotai.top/Article/details/gt2tygdhcul.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gt2jytkpzaq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.redwolf501.top/Article/details/gt2jpqwvybw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gt2xhcebgjm.html

[L04] 设置超时
来源：http://dali.jiagoushi.top/Article/details/gt2krbnfjkg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ivvv.top/Article/details/gt2didyipaz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gaohongyu789.top/Article/details/gt2tzoabozw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gt2gprjelfg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gt2mqcnhwtn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uesncgnl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigfzy.top/Article/details/gt2fofjmjqf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xziqi.cn/Article/details/gt2hjrtwnin.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tmnvuokz.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfzotjg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.c1oappe.top/Article/details/gt2molcnplo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daria6918.cn/Article/details/gt2zjbtfdbh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gt2bxirjjou.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gt2fqtfrghm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.bjfxy.top/Article/details/gt2flpwbftr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigfzy.top/Article/details/gt2oesbvdfl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jyoumei.cn/Article/details/gt2nmrktpsr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pycfn.com/Article/details/gt2tjrujtta.html

[L06] 解析响应为 JSON
来源：http://dali.guannengcc.top/Article/details/gt2pqdxgjzg.html

Py:   resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gt2wgzghihb.html

PHP:  json_decode($body, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2omnpzcwt.html

JS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gt2asquktju.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2skfeajhv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gt2zypqgjdv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzxrwyc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gt2cioposnd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jlsjyb.cn/Article/details/gt2zakwnxzh.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlxbpgo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cdnleiting.top/Article/details/gt2jsfczloh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gt2rljdjrsr.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gt2eogkadba.html

TS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gt2truznwbd.html

Java: resp.statusCode()
来源：http://dali.fengsongda.top/Article/details/gt2pppulrrc.html

Go:   resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gt2uyhledrf.html

Ruby: resp.code.to_i
来源：http://dali.gzhubu.top/Article/details/gt2mijwzdph.html

C#:   (int)resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gt2rhogpvrc.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gt2zmkotefu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcltkpin.html

PHP:  curl_multi_init() 系列
来源：http://dali.xinyue.icu/Article/details/gt2alwvwzix.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gt2uacycobg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2fsuviwaf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xziqi.cn/Article/details/gt2xvmtaewn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nwbrower.top/Article/details/gt2olaujnyl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ydzc1.top/Article/details/gt2mtuqvein.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gt2whphyzjk.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2lfpitoko.html

M. 命令行 / 进程 / 环境
来源：http://dali.xinyue.icu/Article/details/gt2ytfhyjfy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2djecqkuc.html

[M01] 读取命令行参数
来源：http://dali.haohaochexian.top/Article/details/gt2ulbqthvk.html

Py:   sys.argv[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2psqryvkj.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mucetyvw.html

JS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ixyxkabn.html

TS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gt2qecysvao.html

Java: args 数组（main 方法参数）
来源：http://dali.pycfn.com/Article/details/gt2ifdatsjh.html

Go:   os.Args[1:]
来源：http://dali.birdmap.top/Article/details/gt2wkhimohz.html

Ruby: ARGV
来源：http://dali.nwbrower.top/Article/details/gt2fbmpschg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gt2zumrgwex.html

[M02] 读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gt2podvvguc.html

Py:   os.environ.get("HOME")
来源：http://dali.pycfn.com/Article/details/gt2shntboux.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gt2kzzimown.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gt2ydqbzmeo.html

TS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gt2hrohgpyj.html

Java: System.getenv("HOME")
来源：http://dali.ivvv.top/Article/details/gt2ilpvspdq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2gyxlhmtf.html

Ruby: ENV["HOME"]
来源：http://dali.ivvv.top/Article/details/gt2sijwfgad.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2bywvpgth.html

[M03] 执行外部命令
来源：http://dali.c1oappe.top/Article/details/gt2pbxatwjg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gt2wtqrzdvb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gt2lmvwxsqe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2obydiivj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gt2mzfmlnrj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aizwys.cn/Article/details/gt2wwvmspae.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenlongwang.top/Article/details/gt2pqsihxni.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gt2cplnhwwg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cashguo.top/Article/details/gt2hihuotto.html

[M04] 获取当前工作目录
来源：http://dali.fzhhl.top/Article/details/gt2niefeube.html

Py:   os.getcwd()
来源：http://dali.havefunace.top/Article/details/gt2szcjwckh.html

PHP:  getcwd();
来源：http://dali.jinqigfzy.top/Article/details/gt2qkfjfsmb.html

JS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hjiumcoz.html

TS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmfvesps.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xinyue.icu/Article/details/gt2ycjmteos.html

Go:   os.Getwd()
来源：http://dali.sysykeji.top/Article/details/gt2bspkuula.html

Ruby: Dir.pwd
来源：http://dali.mhx1999.top/Article/details/gt2wdvgwxxv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuanzhike.top/Article/details/gt2qtrbfmug.html

[M05] 设置退出码
来源：http://dali.yueranfly.top/Article/details/gt2yutzykgg.html

Py:   sys.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2exucdjfl.html

PHP:  exit(1);
来源：http://dali.sufxvd.cn/Article/details/gt2pzhkndem.html

JS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2upatcefp.html

TS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2mzqmjccf.html

Java: System.exit(1)
来源：http://dali.jianghu66.top/Article/details/gt2emfbkilb.html

Go:   os.Exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2xjtwxhvf.html

Ruby: exit 1
来源：http://dali.yangfankeji.com/Article/details/gt2smcocjso.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gt2pfgqvxdb.html

[M06] 向标准错误输出
来源：http://dali.zycfv.cn/Article/details/gt2cxuvtqoo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gt2auyysccy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2beqapkji.html

JS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gt2jvvwkwtu.html

TS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gt2fetirawb.html

Java: System.err.println("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2dwzelgls.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.mhx1999.top/Article/details/gt2vpukboch.html

Ruby: warn "err"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eknruxhi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkylgmne.html

[M07] 判断是否为主入口
来源：http://dali.ybcxt.top/Article/details/gt2hwsymwqt.html

Py:   if __name__ == "__main__":
来源：http://dali.yvedp.cn/Article/details/gt2vkaizdak.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hfpthk.cn/Article/details/gt2rnxniqva.html

JS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gt2jernsjpj.html

TS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gt2ydrefhul.html

Java: public static void main(String[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bohvtudt.html

Go:   func main()
来源：http://dali.havefunace.top/Article/details/gt2ihfzqjue.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xylfe.cn/Article/details/gt2paafxpki.html

C#:   static void Main(string[] args)
来源：http://dali.316326.xyz/Article/details/gt2xsgcjrir.html

[M08] 获取系统与运行时信息
来源：http://dali.shuidangran.top/Article/details/gt2fyiyuksj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnxiangtu.top/Article/details/gt2jooaipsc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xylfe.cn/Article/details/gt2tdkskdcg.html

JS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gt2wuydggvs.html

TS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gt2lugljtxh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sysykeji.top/Article/details/gt2miazjjbc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sxryk.cn/Article/details/gt2tefguigc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jianghu66.top/Article/details/gt2vutlkwdk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.316326.xyz/Article/details/gt2cbreasgs.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2qumpmcxl.html

N. 数据结构与算法
来源：http://dali.cucudq.cn/Article/details/gt2hboxnpbn.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2mvqfkbvv.html

[N01] 二分查找（有序数组）
来源：http://dali.jyoumei.cn/Article/details/gt2wahfwbkk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2heeksree.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iwmaulkc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gt2ekbnsuvm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gt2hgeabwjx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2qonznimg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2vmvkjmoe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.feifeiyinyue.top/Article/details/gt2sifgvvuh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2mrqsdkwb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tanke756.top/Article/details/gt2sokcfvig.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gt2gimibfpb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ehwqpu.com/Article/details/gt2eddsojtq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gt2sxyqsteb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gt2trdfmjei.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhengqikj.top/Article/details/gt2qunpjoih.html

Go:   slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cfgphfii.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gt2ywpsbihy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ybcxt.top/Article/details/gt2wrfdqdcm.html

[N03] 快速排序（分治示例）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xolvitja.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258888.top/Article/details/gt2wrrdlvho.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnxiangtu.top/Article/details/gt2iynkatvc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gt2jmhymqwc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gt2ewxpaybo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.c1oappe.top/Article/details/gt2ctyrjilb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.iojbl.cn/Article/details/gt2nucywkke.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.meibo888.top/Article/details/gt2fpqifuiq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnxiangtu.top/Article/details/gt2ounrvbnd.html

[N04] 斐波那契数列
来源：http://dali.jinqigufen.top/Article/details/gt2wqggacwo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gt2bxzfllmr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zycfv.cn/Article/details/gt2ldsnmkqc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gt2iirtkihp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gt2plkfnekc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gt2hanrphdd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2awsuymvk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gt2nbzpyzfz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gt2vgtqqxiv.html

[N05] 最大公约数
来源：http://dali.ydzc1.top/Article/details/gt2iysnepdk.html

Py:   math.gcd(a, b)
来源：http://dali.guannengcc.top/Article/details/gt2vrflvole.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ydzc1.top/Article/details/gt2wbwszznv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2nflrrsrf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gt2hhsngudg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guowangkeji.top/Article/details/gt2stiulqne.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhixingplan.top/Article/details/gt2ldmopzmk.html

Ruby: a.gcd(b)
来源：http://dali.aibaodan.cn/Article/details/gt2jgqrqqpl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258888.top/Article/details/gt2ggtqoiug.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gt2kzfrvvir.html

Py:   s == s[::-1]
来源：http://dali.redwolf501.top/Article/details/gt2uonkcfvy.html

PHP:  $s === strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gt2hfpkxlkb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2ohjltfyk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2ownahzsd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cheryme.top/Article/details/gt2cgxxnceh.html

Go:   // 双指针从两端比较
来源：http://dali.yonumen.top/Article/details/gt2aumqfznj.html

Ruby: s == s.reverse
来源：http://dali.xziqi.cn/Article/details/gt2cvyeqvzv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gt2suktlhjm.html

[N07] 两数之和（返回下标）
来源：http://dali.jiagoushi.top/Article/details/gt2mphewoey.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.mhx1999.top/Article/details/gt2sraurbdf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nwbrower.top/Article/details/gt2ynhrzgly.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnxiangtu.top/Article/details/gt2svewmekf.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuanzx.com/Article/details/gt2xrljustb.html

Java: // 手写 HashMap
来源：http://dali.zhongyouzk.top/Article/details/gt2aknjvphf.html

Go:   // 手写 map[int]int
来源：http://dali.smart0.xyz/Article/details/gt2kneopeki.html

Ruby: // 手写 Hash
来源：http://dali.daxiang520.top/Article/details/gt2qbhhlhgw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aibaodan.cn/Article/details/gt2awebtcqq.html

[N08] 生成全排列
来源：http://dali.yanxiufei.cn/Article/details/gt2dzvjcqwi.html

Py:   itertools.permutations(arr)
来源：http://dali.cashguo.top/Article/details/gt2thrmfidk.html

PHP:  // 手写递归交换
来源：http://dali.chenlongwang.top/Article/details/gt2ddnlydms.html

JS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gt2rdxvbjtk.html

TS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gt2zmusozvq.html

Java: // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gt2ktbysbtr.html

Go:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdbwwdih.html

Ruby: arr.permutation.to_a
来源：http://dali.zycfv.cn/Article/details/gt2ljqncvvj.html

C#:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2osdtxcei.html

[N09] 栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hojwyvwp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sweek.top/Article/details/gt2qdnznqee.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2zhvpbbkx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2zvecnurl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sweek.top/Article/details/gt2iexudnaz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gt2fhrzovsd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cdnleiting.top/Article/details/gt2qnfinjwg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gt2fyyhgkyv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuxming.cn/Article/details/gt2rugsexer.html

[N10] 链表节点定义
来源：http://dali.hfpthk.cn/Article/details/gt2ldexdwbf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gt2fmizsekl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guowangkeji.top/Article/details/gt2qhyophhc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhfrulpx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gt2njvgywsw.html

Java: class Node { int v; Node next; }
来源：http://dali.cdnleiting.top/Article/details/gt2qltfxits.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.bjfxy.top/Article/details/gt2iygskdpb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yeihhtpo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hysaishi.cn/Article/details/gt2qbxqzhec.html

[N11] 二叉树中序遍历
来源：http://dali.iojbl.cn/Article/details/gt2lckppadr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2drkhtyaq.html

PHP:  // 手写递归函数
来源：http://dali.wangdashe.top/Article/details/gt2ellsgbxm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gt2nitvqbgb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gt2rnqkzsgh.html

Java: // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gt2aqaiashk.html

Go:   // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gt2mhvblwox.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ubwwogwy.html

C#:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gt2jcuowerr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.meibo888.top/Article/details/gt2aizvqydp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hammf.cn/Article/details/gt2wuyhctck.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sxryk.cn/Article/details/gt2brdwbmxm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gt2hugyyltt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gt2yuxftnkt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gt2rekdueow.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.mhx1999.top/Article/details/gt2huwsiwnq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nwbrower.top/Article/details/gt2cknsxhnj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gt2lxdxasvb.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wcseoaeb.html

O. 并发与异步
来源：http://dali.gaohongyu789.top/Article/details/gt2xlnnqlhc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2uduuzcuh.html

[O01] 启动一个线程
来源：http://dali.cucudq.cn/Article/details/gt2ukxiumfj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jyoumei.cn/Article/details/gt2apuevzis.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2vimzwhgo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cheryme.top/Article/details/gt2grwpirab.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gt2poclmtgk.html


<!-- 参考信息 -->