代发 wailian999

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtzoalsyjf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtwfnuoxuw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gtwyqjkcgy.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gtnbkilnkn.html

Py:   copy.deepcopy(obj)
来源：http://dali.aibaodan.cn/Article/details/gtkontviia.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dashuyun.cn/Article/details/gtqsreeyij.html

JS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtddwtsvej.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtzmfupimd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dianchejie.cn/Article/details/gtkplswdnv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.0kj1m.cn/Article/details/gtioclnnix.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gtmjmnerqe.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gtevqbdimm.html

[K06] 解析 URL 查询串
来源：http://dali.tanke756.top/Article/details/gtcmhtgwha.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gtctattyue.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ehwqpu.com/Article/details/gtmymelbiv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtcqtplenj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gtxxfgpkfp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ivvv.top/Article/details/gtrkgceaov.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gtgvzsjxvj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtodpdbuph.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtdfhipkpa.html

[K07] 进制转换
来源：http://dali.cheryme.top/Article/details/gtqtdnirtr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtjatxuqzu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cashguo.top/Article/details/gtnfhijhva.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtrfovwayl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtszvfkpdk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtkdbsujax.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.kuanghao11.cn/Article/details/gtyupcvkoa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzrqujal.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtktzoewua.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.9152youxi.cn/Article/details/gtrtxyxyru.html

Py:   pickle.dumps(obj)
来源：http://dali.andypj.xyz/Article/details/gtqsjiemwn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tanke756.top/Article/details/gtelujgrdq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbzfmwzl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtcutlnkyx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tianlin.xyz/Article/details/gtqxqpxpur.html

Go:   encoding/gob
来源：http://dali.yvedp.cn/Article/details/gtkniujoyc.html

Ruby: Marshal.dump(obj)
来源：http://dali.cucudq.cn/Article/details/gthazatngx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtxchjkdkm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtpvctmlbx.html

L. 网络请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwackdyl.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtwkuvixyy.html

[L01] 发送 GET 请求
来源：http://dali.sxryk.cn/Article/details/gtwbnuerna.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yongpay.top/Article/details/gtaxairzlt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daxiang520.top/Article/details/gtiskkrzzi.html

JS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvoqbrbt.html

TS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gtqakcnvmn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.svipenyu.cn/Article/details/gtmnaujugi.html

Go:   resp, err := http.Get(url)
来源：http://dali.xylfe.cn/Article/details/gtdoapvqly.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shangyingyoupin.top/Article/details/gtkejtlzce.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daria6918.cn/Article/details/gtimhmxwph.html

[L02] 发送 POST JSON
来源：http://dali.yj20258.top/Article/details/gtcbozqgbw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.birdmap.top/Article/details/gtodvsqdqb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuetiantiany.cn/Article/details/gtwhlvmvlw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gtegrlnxhi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gtzactzvhc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gaohongyu789.top/Article/details/gtdiznfsqx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.c1oappe.top/Article/details/gtfynrmdym.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cucudq.cn/Article/details/gtnhzaimfm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xinyue.icu/Article/details/gtldnrycgl.html

[L03] 设置自定义请求头
来源：http://dali.hywenlv.cn/Article/details/gthhgbdcdh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gtvlyedivb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcubpopuy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtvwplgymt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyyrhksg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yongpay.top/Article/details/gtmxgxmteu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gtbchizdzj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangdashe.top/Article/details/gtqoxujkjn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gtxrfegdbj.html

[L04] 设置超时
来源：http://dali.yonumen.top/Article/details/gtsbvwyjgx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jyoumei.cn/Article/details/gtdxuubagw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenzaomai.com/Article/details/gtykgwpear.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtsejbmmrf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gtfyfxbfeq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuanzx.com/Article/details/gtaxrbisat.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cdnleiting.top/Article/details/gtixpjwbtp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgfzy.top/Article/details/gtwkqwotcp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenlongwang.top/Article/details/gtimtglsqh.html

[L05] 上传文件（multipart）
来源：http://dali.nanxinkj.top/Article/details/gtpfgmxyih.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hammf.cn/Article/details/gtvymlizeh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgufenzy.top/Article/details/gtrclbbnqe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gtxbqhjkhh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gtlhntwpvi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.9152youxi.cn/Article/details/gtgzkbopmb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yanxiufei.cn/Article/details/gtunlepzyy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nwbrower.top/Article/details/gtxmpdkmiq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.redwolf501.top/Article/details/gtfznaksab.html

[L06] 解析响应为 JSON
来源：http://dali.zycfv.cn/Article/details/gtjioomhgy.html

Py:   resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtjoulansh.html

PHP:  json_decode($body, true);
来源：http://dali.yanxiufei.cn/Article/details/gtmbmhzsjh.html

JS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gtoylrzuus.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gtgrtjpfkv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehftwthw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fengsongda.top/Article/details/gthrqxlgjd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jyoumei.cn/Article/details/gtavqcashb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tanke756.top/Article/details/gtznzmkeau.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtyohepily.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangdashe.top/Article/details/gtiqfogamo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xziqi.cn/Article/details/gtloyxsbus.html

JS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtdfuthngc.html

TS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtzjevbwhe.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gtwfozabzr.html

Go:   resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gtjbjvttik.html

Ruby: resp.code.to_i
来源：http://dali.fengsongda.top/Article/details/gtdarxkapq.html

C#:   (int)resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwdcmmfo.html

[L08] 并发请求多个地址
来源：http://dali.snrcjt.cn/Article/details/gtxwlzaxnb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.quarkkingdee.top/Article/details/gtzqfgslwl.html

PHP:  curl_multi_init() 系列
来源：http://dali.shangyingyoupin.top/Article/details/gtbvbzxcie.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtaemnqazy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtxztwvgrd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gtarqbgirg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ydzc1.top/Article/details/gtljzuzbcu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sweek.top/Article/details/gtkvbbwlcp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtjjdutcpt.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfpivnuo.html

M. 命令行 / 进程 / 环境
来源：http://dali.zycfv.cn/Article/details/gtrohctkkb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtvlcotvnp.html

[M01] 读取命令行参数
来源：http://dali.fengsongda.top/Article/details/gttldbakph.html

Py:   sys.argv[1:]
来源：http://dali.fengsongda.top/Article/details/gtsnkzqdug.html

PHP:  $argv;  $argc;
来源：http://dali.zycfv.cn/Article/details/gtslzhfjpc.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtpmpaiuyd.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtmdxjnhyt.html

Java: args 数组（main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtunhjmxkm.html

Go:   os.Args[1:]
来源：http://dali.xylfe.cn/Article/details/gttynehfhc.html

Ruby: ARGV
来源：http://dali.birdmap.top/Article/details/gtllbozwtq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gtyzlfepzo.html

[M02] 读取环境变量
来源：http://dali.jyoumei.cn/Article/details/gtqnzxygco.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtllnvdtzg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gtxmcbafal.html

JS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtacrbhhkv.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfykrscij.html

Java: System.getenv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtxlbssqij.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtfgyswtqa.html

Ruby: ENV["HOME"]
来源：http://dali.jianghu66.top/Article/details/gtzriwtojz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtaqpxgdmp.html

[M03] 执行外部命令
来源：http://dali.cdnleiting.top/Article/details/gtpamokdrv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hammf.cn/Article/details/gtilxyazjg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zycfv.cn/Article/details/gtfjmttbdh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gtqhajcuqs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtzrwzkcxo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fengsongda.top/Article/details/gtzyhmdoov.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yangfankeji.com/Article/details/gtsvgluhmw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jyoumei.cn/Article/details/gtxovuinkf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuanzhike.top/Article/details/gtolregvsj.html

[M04] 获取当前工作目录
来源：http://dali.aibaodan.cn/Article/details/gtvxvbikhf.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gtzuhsofcd.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gtoeerugtg.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtwytjbuwh.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcanqfwyg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsjeynqz.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gteqgepfeo.html

Ruby: Dir.pwd
来源：http://dali.zhiwuduotai.top/Article/details/gtyktngsho.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzypcyzfg.html

[M05] 设置退出码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhhesxfy.html

Py:   sys.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtofsrohog.html

PHP:  exit(1);
来源：http://dali.svipenyu.cn/Article/details/gtoqhktvbb.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtlttvqfwf.html

TS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtxamkagwo.html

Java: System.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtiihntkmh.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtwamdpdwr.html

Ruby: exit 1
来源：http://dali.jinqigfzy.top/Article/details/gtmdcqaphj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmwpkedz.html

[M06] 向标准错误输出
来源：http://dali.jiagoushi.top/Article/details/gtqrycgnvk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gtpxzambox.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yueranfly.top/Article/details/gtbdqwojcw.html

JS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gtiqxbcljt.html

TS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydqdmwya.html

Java: System.err.println("err")
来源：http://dali.sweek.top/Article/details/gtpicxmafa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tian-w.cn/Article/details/gtpemrmwon.html

Ruby: warn "err"
来源：http://dali.pycfn.com/Article/details/gtejavczui.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pycfn.com/Article/details/gtbjlmbfcv.html

[M07] 判断是否为主入口
来源：http://dali.guowangkeji.top/Article/details/gtvcpnyhjj.html

Py:   if __name__ == "__main__":
来源：http://dali.hammf.cn/Article/details/gtphyccoge.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtipsikjjp.html

JS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gtxkvvcjls.html

TS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gtyyavhico.html

Java: public static void main(String[] args)
来源：http://dali.jinqigufen.top/Article/details/gtzxizwehw.html

Go:   func main()
来源：http://dali.sysykeji.top/Article/details/gtbeehjeax.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenlongwang.top/Article/details/gtfpdebuaq.html

C#:   static void Main(string[] args)
来源：http://dali.yonumen.top/Article/details/gtrwynhoys.html

[M08] 获取系统与运行时信息
来源：http://dali.hywenlv.cn/Article/details/gtwkhpjyui.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hongshengwenyu.top/Article/details/gtbebriota.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yongpay.top/Article/details/gtyvrukouz.html

JS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gttdcoymxt.html

TS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtcurkdalz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258888.top/Article/details/gtqzxmroio.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.mhx1999.top/Article/details/gtmslwicdi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sufxvd.cn/Article/details/gtrpaeagsn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuetiantiany.cn/Article/details/gtcoeucgjq.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtkkelvvkn.html

N. 数据结构与算法
来源：http://dali.tianlin.xyz/Article/details/gtfeeglqvk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtzxsfjddd.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupcxqyfh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.meibo888.top/Article/details/gtdjwskohw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gtqukowoiw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtyaeepcsf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gtsvnreljw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtuuebyvgs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gttsvtkxev.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.feifeiyinyue.top/Article/details/gtovwdlsno.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtntjkpczc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgfzy.top/Article/details/gteslsgbcx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gtehyoanee.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tian-w.cn/Article/details/gtljjbhiqm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtanofddze.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gthodbimhj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuxming.cn/Article/details/gtcskqawsn.html

Go:   slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gtlucrysqt.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtlcutdcyk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cdnleiting.top/Article/details/gtcytemuua.html

[N03] 快速排序（分治示例）
来源：http://dali.yueranfly.top/Article/details/gtcjufnrms.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pycfn.com/Article/details/gttswtjmwv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigfzy.top/Article/details/gtyrrzlryz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtgegmmfsw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxjicqjv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtvbkawxil.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gzhubu.top/Article/details/gtdpmdqbeg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.mhx1999.top/Article/details/gtfcymtnoo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jiagoushi.top/Article/details/gteipqwxqy.html

[N04] 斐波那契数列
来源：http://dali.ivvv.top/Article/details/gtuxijrmhg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gtnrqwvcfn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gtueljcmzi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtqzknkggz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtfvwbuzhl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtxxftnsvw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuetiantiany.cn/Article/details/gtppdaqfpv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtodtopibc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gttdfablvg.html

[N05] 最大公约数
来源：http://dali.svipenyu.cn/Article/details/gtolwysocs.html

Py:   math.gcd(a, b)
来源：http://dali.xziqi.cn/Article/details/gtfwaortet.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.havefunace.top/Article/details/gtfltlcazm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gtckfymobd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gtrvoiacfr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daxiang520.top/Article/details/gtixvyzxsb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nwbrower.top/Article/details/gtjljyvbqa.html

Ruby: a.gcd(b)
来源：http://dali.xinyue.icu/Article/details/gtwlpuaxjt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenjidiqi.icu/Article/details/gtyaiivfuy.html

[N06] 判断回文字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmjdgcnr.html

Py:   s == s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gtekcxjerp.html

PHP:  $s === strrev($s);
来源：http://dali.yj202588.top/Article/details/gtxjxyvyse.html

JS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtyrjawkpo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuxgnccl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.snrcjt.cn/Article/details/gtvuhxyvaw.html

Go:   // 双指针从两端比较
来源：http://dali.hnqzz.top/Article/details/gtufgggevc.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtgimpeblw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gtafikvead.html

[N07] 两数之和（返回下标）
来源：http://dali.kuanghao11.cn/Article/details/gtzvmbickj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigfzy.top/Article/details/gtnahxmmzz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnxiangtu.top/Article/details/gtqdrxxmzn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.mhx1999.top/Article/details/gtneialfdl.html

TS:   // 手写 Map<string, number>
来源：http://dali.ppjwa.cn/Article/details/gtpjicatty.html

Java: // 手写 HashMap
来源：http://dali.yanxiufei.cn/Article/details/gtmdlgziba.html

Go:   // 手写 map[int]int
来源：http://dali.0kj1m.cn/Article/details/gthnusenzj.html

Ruby: // 手写 Hash
来源：http://dali.xuetiantiany.cn/Article/details/gtkuqenwhg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cdnleiting.top/Article/details/gtljvvuuvr.html

[N08] 生成全排列
来源：http://dali.zhoulong.xyz/Article/details/gtuqqkhhbt.html

Py:   itertools.permutations(arr)
来源：http://dali.andypj.xyz/Article/details/gtsfsswkzn.html

PHP:  // 手写递归交换
来源：http://dali.xylfe.cn/Article/details/gtbpwxmypk.html

JS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtpjxavmwl.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtonyzgznm.html

Java: // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtvbabzyti.html

Go:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtouvygyhi.html

Ruby: arr.permutation.to_a
来源：http://dali.zhoulong.xyz/Article/details/gtgrdoatox.html

C#:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqmyxybu.html

[N09] 栈与队列
来源：http://dali.pycfn.com/Article/details/gtxeglwfvh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sufxvd.cn/Article/details/gtpphvnncf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gtywjkgmkh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gthfxxceyr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cashguo.top/Article/details/gtiuxpbcsq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gthamekkcv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.316326.xyz/Article/details/gtbikcyfdk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfqjmaqf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.meibo888.top/Article/details/gtivadbjfl.html

[N10] 链表节点定义
来源：http://dali.redwolf501.top/Article/details/gtckzwfufu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenzaomai.com/Article/details/gtawoffits.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gtfkqhdnie.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhiwuduotai.top/Article/details/gttykhgvum.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangshuangyany.cn/Article/details/gtxovhxqid.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgufenzy.top/Article/details/gtsiwzaptj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.bjfxy.top/Article/details/gtwbuwcbir.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjaorrqv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gogol.net.cn/Article/details/gtedntwwqx.html

[N11] 二叉树中序遍历
来源：http://dali.chenzaomai.com/Article/details/gtgqkuaqco.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.havefunace.top/Article/details/gtkpxjuucv.html

PHP:  // 手写递归函数
来源：http://dali.tanke756.top/Article/details/gtibszsboy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gtdcsngshx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gtkoffcurn.html

Java: // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpwuasrn.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblmybply.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhongyouzk.top/Article/details/gtaoferclr.html

C#:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtuiyavmry.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yonumen.top/Article/details/gtiuxyachw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgfzy.top/Article/details/gtdfmzpcij.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tian-w.cn/Article/details/gtdvbgqbzt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gtzfynimnj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gtpbkrbdqp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtwjgkksyy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sysykeji.top/Article/details/gteyliyyec.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gtkpbmeouv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gtzszcceal.html


<!-- 参考信息 -->