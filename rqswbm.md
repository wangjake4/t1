代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.yvedp.cn/Article/details/gt2uliquxvf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ppjwa.cn/Article/details/gt2omtvmvzn.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wubzdctr.html

TS:   structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mahlzjjv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xinyue.icu/Article/details/gt2gbjtyzwy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zycfv.cn/Article/details/gt2zzbldwyw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sxryk.cn/Article/details/gt2nrxryzhd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cashguo.top/Article/details/gt2ojxwkevy.html

[K06] 解析 URL 查询串
来源：http://dali.yuxming.cn/Article/details/gt2iayrikve.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gzhubu.top/Article/details/gt2wadglpci.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hysaishi.cn/Article/details/gt2gjvsvqvf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gt2cdrvysab.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gt2dpnatmqw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gotoacloud.top/Article/details/gt2satwehag.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gt2wonwfdxf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gt2pktguyft.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gt2awetvzxq.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gt2kxvyzoyq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2aesqrhqe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gt2sziisjvw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2zlhuaugl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2ozccvufa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2zdulxeev.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.c1oappe.top/Article/details/gt2evoeilwf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhongyouzk.top/Article/details/gt2whqtdozn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2eangyexr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.iojbl.cn/Article/details/gt2xmcfzfbj.html

Py:   pickle.dumps(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2vqyvrtus.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.smart0.xyz/Article/details/gt2mgpafudx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gt2eikglvfa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gt2yumgfwqn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gt2vvjwqmla.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gt2xundhmfl.html

Ruby: Marshal.dump(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2owzzuswb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gt2uvaralro.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ihiohrva.html

L. 网络请求
来源：http://dali.wangdashe.top/Article/details/gt2leyecqyz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2bwqhcquq.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gt2wmmyssbh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hongshengwenyu.top/Article/details/gt2leutsena.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.kuanghao11.cn/Article/details/gt2tvjqemtd.html

JS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2aahhbeqx.html

TS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gt2skgjjvtz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.snrcjt.cn/Article/details/gt2djwzkhsm.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ybqrmctf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.9152youxi.cn/Article/details/gt2ovzpeggr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2ojhwoczn.html

[L02] 发送 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gt2izrkljfn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gt2akjhogua.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenjidiqi.icu/Article/details/gt2buhxclth.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gt2lscnptan.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gt2njgmttke.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhengqikj.top/Article/details/gt2ziqvbadh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cqqwz.cn/Article/details/gt2qpcspuhn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.316326.xyz/Article/details/gt2ijbzfqka.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zdqjudy.top/Article/details/gt2cknfpyie.html

[L03] 设置自定义请求头
来源：http://dali.dashuyun.cn/Article/details/gt2nfuyaggn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.mhx1999.top/Article/details/gt2gqwaklis.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jianghu66.top/Article/details/gt2jnjrmcnl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gt2koefytno.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gt2edxgddip.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gt2soktxtpi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gt2hdynwcac.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.svipenyu.cn/Article/details/gt2lldxhgwb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gt2rybhndqh.html

[L04] 设置超时
来源：http://dali.yvedp.cn/Article/details/gt2jyfyaqba.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenzaomai.com/Article/details/gt2quizpemq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxinkj.top/Article/details/gt2clifjzxa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gt2lrqcrprs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gt2rkxunjik.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yongpay.top/Article/details/gt2conyxcut.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guowangkeji.top/Article/details/gt2psmnsrqu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.meibo888.top/Article/details/gt2tioblitt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tanke756.top/Article/details/gt2lfdkoejh.html

[L05] 上传文件（multipart）
来源：http://dali.fengsongda.top/Article/details/gt2tevhuvhi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xinyue.icu/Article/details/gt2mjttcztk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhixingplan.top/Article/details/gt2sdcelfok.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gt2gokbjjij.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gt2luuucekc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigufen.top/Article/details/gt2yvgjobva.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxuanxn.top/Article/details/gt2qggrxkms.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangshuangyany.cn/Article/details/gt2aijmfyjf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2jyeyibxd.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gt2yggexffd.html

Py:   resp.json()
来源：http://dali.gotoacloud.top/Article/details/gt2srhyghhl.html

PHP:  json_decode($body, true);
来源：http://dali.cucudq.cn/Article/details/gt2agwyvzpy.html

JS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gt2euognejh.html

TS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gt2oigzjind.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gt2qdmzoqcu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dozvrucm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gt2esdlkcif.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhoulong.xyz/Article/details/gt2wrcawazk.html

[L07] 处理 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gt2mvtlhhtm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.snrcjt.cn/Article/details/gt2qyifexph.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gt2tbpgoswd.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gt2jbfdiupb.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gt2abkdzmrm.html

Java: resp.statusCode()
来源：http://dali.0kj1m.cn/Article/details/gt2lwmpcqrc.html

Go:   resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gt2pyonuaqb.html

Ruby: resp.code.to_i
来源：http://dali.hnxiangtu.top/Article/details/gt2nvzhqlkj.html

C#:   (int)resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hirmxivw.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gt2tmugrhhz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gt2bpzwtxxw.html

PHP:  curl_multi_init() 系列
来源：http://dali.bjfxy.top/Article/details/gt2gmewaftm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gt2cbyhwutg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gt2nprimrrg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daxiang520.top/Article/details/gt2qapiczmd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.quarkkingdee.top/Article/details/gt2iqpzvohq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.redwolf501.top/Article/details/gt2sdgetbbb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2yjhzfayq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2nnrwwnrr.html

M. 命令行 / 进程 / 环境
来源：http://dali.xinyue.icu/Article/details/gt2xpeouyqy.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2kachybca.html

[M01] 读取命令行参数
来源：http://dali.tianlin.xyz/Article/details/gt2ibgizuln.html

Py:   sys.argv[1:]
来源：http://dali.ydzc1.top/Article/details/gt2waxkwfac.html

PHP:  $argv;  $argc;
来源：http://dali.c1oappe.top/Article/details/gt2yafrtjus.html

JS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gt2umimjqkc.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2stkyhczv.html

Java: args 数组（main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gt2kyuankix.html

Go:   os.Args[1:]
来源：http://dali.aibaodan.cn/Article/details/gt2zuulruoa.html

Ruby: ARGV
来源：http://dali.iojbl.cn/Article/details/gt2ggatpild.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gt2mmeovkmj.html

[M02] 读取环境变量
来源：http://dali.jlsjyb.cn/Article/details/gt2jiqydgea.html

Py:   os.environ.get("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2niyrrenu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yonumen.top/Article/details/gt2plrbfeqv.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gt2cazdiudm.html

TS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gt2lkmwgmyt.html

Java: System.getenv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2anzuzcox.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2oareambw.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gt2cdryvqtq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gt2qhsibkvt.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gt2xlmrbcuy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.9152youxi.cn/Article/details/gt2hqcrcjqi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhongyouzk.top/Article/details/gt2qbzcjekp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gt2vgmznmas.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gt2nxygyqgf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pengpengdd.cyou/Article/details/gt2rcknehlg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xziqi.cn/Article/details/gt2qjjeqjyi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgufenzy.top/Article/details/gt2vhmrqfzr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxinkj.top/Article/details/gt2nxosaaba.html

[M04] 获取当前工作目录
来源：http://dali.hnxiangtu.top/Article/details/gt2qqgpzxkg.html

Py:   os.getcwd()
来源：http://dali.fengsongda.top/Article/details/gt2dhyckobc.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gt2pofcvfnn.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gt2mvmxfrvm.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gt2equypkzp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuxming.cn/Article/details/gt2uityhgjg.html

Go:   os.Getwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2muwfdaxv.html

Ruby: Dir.pwd
来源：http://dali.dianchejie.cn/Article/details/gt2wtuhwxec.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhoulong.xyz/Article/details/gt2ddutypte.html

[M05] 设置退出码
来源：http://dali.0kj1m.cn/Article/details/gt2yemhvpyl.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2atikbvuq.html

PHP:  exit(1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2caavjrlb.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtcvmdc.html

TS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2iwacpspy.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2ztqcmvtx.html

Go:   os.Exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2gxleyzxs.html

Ruby: exit 1
来源：http://dali.chenzaomai.com/Article/details/gt2jloqyicb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yangfankeji.com/Article/details/gt2dnwljqtp.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gt2zocjsgxh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zgzbqjvk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aizwys.cn/Article/details/gt2ijxslycg.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gt2nmiqtxpx.html

TS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gt2uonqteiz.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2taohzcbg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gt2kxgbyxca.html

Ruby: warn "err"
来源：http://dali.smart0.xyz/Article/details/gt2tytberli.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ugpyrsjw.html

[M07] 判断是否为主入口
来源：http://dali.jiagoushi.top/Article/details/gt2beuaxpob.html

Py:   if __name__ == "__main__":
来源：http://dali.yangfankeji.com/Article/details/gt2qcksojsv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ppjwa.cn/Article/details/gt2ajeozeie.html

JS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gt2ihybtnkh.html

TS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gt2cgsynsei.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ujxuxpab.html

Go:   func main()
来源：http://dali.cqqwz.cn/Article/details/gt2pmtzpapq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bnnztwgv.html

C#:   static void Main(string[] args)
来源：http://dali.andypj.xyz/Article/details/gt2mjmhkgkg.html

[M08] 获取系统与运行时信息
来源：http://dali.hywenlv.cn/Article/details/gt2agtlvxyr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenjidiqi.icu/Article/details/gt2idakdjhv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cucudq.cn/Article/details/gt2igsvmmlw.html

JS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gt2yknzgztc.html

TS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gt2vdtszsjb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xinyue.icu/Article/details/gt2rkwfmxmj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gt2frledwat.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gt2vjrnfsbg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xinyue.icu/Article/details/gt2dzeolokg.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2pbyprpxr.html

N. 数据结构与算法
来源：http://dali.jinqigufen.top/Article/details/gt2tirzentz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2zmzzwbtv.html

[N01] 二分查找（有序数组）
来源：http://dali.jyoumei.cn/Article/details/gt2ahjzcpfk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2dgzspslm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgfzy.top/Article/details/gt2xvcxoubn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gt2unlvhwbz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gt2tyqjyxje.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2njtxnicr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zwjedfuo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cucudq.cn/Article/details/gt2nsyirgnl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2jkmcgztf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sccphrvq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnstptkt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cqqwz.cn/Article/details/gt2rpymnimy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gt2gohwbwlx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gt2xtqrwhkc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gt2dzexxxfs.html

Go:   slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2hxfysxif.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gt2cogdyfoo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ybcxt.top/Article/details/gt2zpzwzesp.html

[N03] 快速排序（分治示例）
来源：http://dali.hnxiangtu.top/Article/details/gt2ybttzahx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jiagoushi.top/Article/details/gt2nhypkycv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.iojbl.cn/Article/details/gt2hsycryem.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gt2owczcjlj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gt2vzdjulyt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.svipenyu.cn/Article/details/gt2zbsjjqnz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shzxlz.cn/Article/details/gt2gpsrkzro.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ybcxt.top/Article/details/gt2qsdvgqmx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.316326.xyz/Article/details/gt2xyxnajvp.html

[N04] 斐波那契数列
来源：http://dali.tian-w.cn/Article/details/gt2stddvwdy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gt2nwknhsgz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gt2rykyculm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2epwikasu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2ybvnbloc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.iojbl.cn/Article/details/gt2voeulytb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tanke756.top/Article/details/gt2cfsaymjq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gt2blsvscqa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gt2vcsbicgn.html

[N05] 最大公约数
来源：http://dali.zhoulong.xyz/Article/details/gt2bfzpifuh.html

Py:   math.gcd(a, b)
来源：http://dali.shzxlz.cn/Article/details/gt2wijdkwpd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2umjkycpt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htmnezju.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dobnenez.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shzxlz.cn/Article/details/gt2kwodkkoq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hammf.cn/Article/details/gt2pniatneb.html

Ruby: a.gcd(b)
来源：http://dali.ppjwa.cn/Article/details/gt2tetcimfs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jiagoushi.top/Article/details/gt2qwfgmcmh.html

[N06] 判断回文字符串
来源：http://dali.gotoacloud.top/Article/details/gt2aomvkkxi.html

Py:   s == s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gt2fqbchrol.html

PHP:  $s === strrev($s);
来源：http://dali.nwbrower.top/Article/details/gt2jzgrcjhy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dbmpdtyl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qkbwlqrh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gzhubu.top/Article/details/gt2yfukxper.html

Go:   // 双指针从两端比较
来源：http://dali.cqqwz.cn/Article/details/gt2mjedlhyf.html

Ruby: s == s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2ajkhpzmz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gt2oeaeewqy.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigfzy.top/Article/details/gt2twlddald.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jyoumei.cn/Article/details/gt2sxftplwv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xziqi.cn/Article/details/gt2wrzhyfrr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gogol.net.cn/Article/details/gt2pkyvtewn.html

TS:   // 手写 Map<string, number>
来源：http://dali.gaohongyu789.top/Article/details/gt2bqgbvavd.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gt2otoffjde.html

Go:   // 手写 map[int]int
来源：http://dali.xuetiantiany.cn/Article/details/gt2myfzzzvh.html

Ruby: // 手写 Hash
来源：http://dali.hongshengwenyu.top/Article/details/gt2esxqayne.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jyoumei.cn/Article/details/gt2xajhjpkh.html

[N08] 生成全排列
来源：http://dali.yj20258.top/Article/details/gt2kdumrwjj.html

Py:   itertools.permutations(arr)
来源：http://dali.yuxming.cn/Article/details/gt2kcmzsbyj.html

PHP:  // 手写递归交换
来源：http://dali.hongshengwenyu.top/Article/details/gt2imunhxvy.html

JS:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2dlsxwifp.html

TS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gt2bpuakjsf.html

Java: // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eabrzyff.html

Go:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2spekhqaw.html

Ruby: arr.permutation.to_a
来源：http://dali.c1oappe.top/Article/details/gt2buycwjey.html

C#:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2qmzmnqni.html

[N09] 栈与队列
来源：http://dali.jyoumei.cn/Article/details/gt2ztrnodxg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2plgepxxw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2tqvdfdey.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gt2adzhoray.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yuanzhike.top/Article/details/gt2nobvgcyx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sufxvd.cn/Article/details/gt2bltnxgom.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenzaomai.com/Article/details/gt2qdmsyhuz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2woanxmqh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.snrcjt.cn/Article/details/gt2xfswvsgk.html

[N10] 链表节点定义
来源：http://dali.redwolf501.top/Article/details/gt2lglgkyvv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gotoacloud.top/Article/details/gt2oqhhtgby.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jyoumei.cn/Article/details/gt2zkwulxfy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhixingplan.top/Article/details/gt2nzrkgmil.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.mhx1999.top/Article/details/gt2smyypttc.html

Java: class Node { int v; Node next; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqfqmaar.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shzxlz.cn/Article/details/gt2jsiskpnj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xylfe.cn/Article/details/gt2fwalbncz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuanzhike.top/Article/details/gt2oeujcwrk.html

[N11] 二叉树中序遍历
来源：http://dali.sweek.top/Article/details/gt2ycnkuoap.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gt2jffasovu.html

PHP:  // 手写递归函数
来源：http://dali.daxiang520.top/Article/details/gt2vrtqisyf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gt2lbwmgoxd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gt2irntopik.html

Java: // 手写递归
来源：http://dali.yuxming.cn/Article/details/gt2rveejtpg.html

Go:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gt2fivgadgn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yvedp.cn/Article/details/gt2iwfpkivx.html

C#:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2eglmlysh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hfpthk.cn/Article/details/gt2lwjyhuyy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aizwys.cn/Article/details/gt2qrojyysb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dcchjmft.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gt2iuostwqw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gt2viwyaiih.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gt2orcyvoyy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aizwys.cn/Article/details/gt2uiznrtcg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yangfankeji.com/Article/details/gt2gqwovekd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gt2zohwezmn.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2ubcobolu.html

O. 并发与异步
来源：http://dali.sysykeji.top/Article/details/gt2tmjepqut.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2txbacaro.html

[O01] 启动一个线程
来源：http://dali.xuanzx.com/Article/details/gt2ijdcnrjx.html


<!-- 参考信息 -->