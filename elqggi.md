代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cheryme.top/Article/details/gtwmovwheg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gteojjjidg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gtzwiclklq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtmjgeyurn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gtiebgxnej.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtfuhjfjjn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtfroovelz.html

[K05] 深拷贝对象
来源：http://dali.aibaodan.cn/Article/details/gtjmsmllox.html

Py:   copy.deepcopy(obj)
来源：http://dali.yueranfly.top/Article/details/gtaclithwb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gtllllbkyz.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtzilbtssj.html

TS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gtmkdfzpit.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuanzhike.top/Article/details/gtczdvvhcy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cucudq.cn/Article/details/gtzioyfhds.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gtfpipuqwr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xziqi.cn/Article/details/gtcamwzarv.html

[K06] 解析 URL 查询串
来源：http://dali.jlsjyb.cn/Article/details/gtyprdzppf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258888.top/Article/details/gttcswkvyy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shangyingyoupin.top/Article/details/gttghaiwhh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtbgasenss.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gtqmwuzilt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xylfe.cn/Article/details/gtwlezoulg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtvtsaktcj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtdzscoswj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtowwxevyj.html

[K07] 进制转换
来源：http://dali.shangyingyoupin.top/Article/details/gtwdquwvbx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtwgsdeyir.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinghuilouyu.cn/Article/details/gtpysswghu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtolwjrlmi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtesbaxcnt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtgrlybpvq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ydzc1.top/Article/details/gtvufubzsi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnxiangtu.top/Article/details/gtfqrhpdlr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtrsmgmhpf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gtyohpndgx.html

Py:   pickle.dumps(obj)
来源：http://dali.fengsongda.top/Article/details/gtasycnohj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtcrxbsnbo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gtplxwvzso.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gtbdxcsigc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gtvaodwwtt.html

Go:   encoding/gob
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovmrwpdh.html

Ruby: Marshal.dump(obj)
来源：http://dali.0kj1m.cn/Article/details/gtmjuqpypp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtamyfuhxb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnaggucoq.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gtowwandhw.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gttqbmfgkk.html

[L01] 发送 GET 请求
来源：http://dali.cdnleiting.top/Article/details/gthgqgtwhp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hammf.cn/Article/details/gtnwdxkrwt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gtglvmxyzb.html

JS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtiomdduht.html

TS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gtqujdzkod.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtruukizmh.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnqzz.top/Article/details/gtbepimiyv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gaohongyu789.top/Article/details/gtijvhczxc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shuidangran.top/Article/details/gtjgcdfucu.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjidgfpvb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.birdmap.top/Article/details/gtxcrtklpo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hysaishi.cn/Article/details/gtbeilposi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtvoscaiia.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtawgyacbq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fzhhl.top/Article/details/gtprgszikq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.quarkkingdee.top/Article/details/gthwpztvvq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hongshengwenyu.top/Article/details/gtjwxazuod.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cheryme.top/Article/details/gtodlscoqw.html

[L03] 设置自定义请求头
来源：http://dali.hnqzz.top/Article/details/gtydkykrgb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gtzpvwpybe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.9152youxi.cn/Article/details/gtsljaxmwt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtnvynkije.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtajopxrve.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhixingplan.top/Article/details/gtxqisxkna.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gtzvkjekhd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gtuezeezaf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gtgjnaaaqi.html

[L04] 设置超时
来源：http://dali.chenlongwang.top/Article/details/gthnitntli.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fengsongda.top/Article/details/gtlrpnqqzm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtunboeert.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gtnzlpvwne.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlzzwlfo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zycfv.cn/Article/details/gtdakfxcke.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yueranfly.top/Article/details/gtamrytccm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shuidangran.top/Article/details/gtrokcxwvw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hfpthk.cn/Article/details/gtlszzvovu.html

[L05] 上传文件（multipart）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpjrikoo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yangfankeji.com/Article/details/gtchrmxvqh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hysaishi.cn/Article/details/gttucdyhqw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gtfzucwjry.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtlmvmuljo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmsnaupw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fzhhl.top/Article/details/gtfwenjfns.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cheryme.top/Article/details/gtokphzyop.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtqsesbdam.html

[L06] 解析响应为 JSON
来源：http://dali.redwolf501.top/Article/details/gtdgwcvatb.html

Py:   resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtebzezgil.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gtwrothvdl.html

JS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gtczfxhacu.html

TS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gtcjhafgci.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtaagefkxl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gtwekwhmbw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.vqdsnc.cn/Article/details/gtlxuoxect.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gttosjkzfv.html

[L07] 处理 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtmwuetwfi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.meibo888.top/Article/details/gtqznqdzks.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258888.top/Article/details/gtywcmzrwn.html

JS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtzzrmuojb.html

TS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gtwcjusonf.html

Java: resp.statusCode()
来源：http://dali.yangfankeji.com/Article/details/gtxuekcpsy.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnffqsyih.html

Ruby: resp.code.to_i
来源：http://dali.cucudq.cn/Article/details/gtqvdqyxxh.html

C#:   (int)resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gthtjxgkmu.html

[L08] 并发请求多个地址
来源：http://dali.xziqi.cn/Article/details/gtiwytjnkr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhongyouzk.top/Article/details/gtvbrsarlj.html

PHP:  curl_multi_init() 系列
来源：http://dali.feifeiyinyue.top/Article/details/gtoilllwhg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtlokkgaxp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtpvbmocaa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gtmhvjaqgm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cheryme.top/Article/details/gtcgebeixh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258888.top/Article/details/gtqfccjrqe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gtagbvylgr.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtmgcaahjw.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxinkj.top/Article/details/gtgasddzxk.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtfwmvmoxf.html

[M01] 读取命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtmgzhmjxp.html

Py:   sys.argv[1:]
来源：http://dali.aibaodan.cn/Article/details/gtksxqaqpm.html

PHP:  $argv;  $argc;
来源：http://dali.xuetiantiany.cn/Article/details/gtpwnhdsdx.html

JS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtazvtanol.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtxslxkqzr.html

Java: args 数组（main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gtqmexjgdp.html

Go:   os.Args[1:]
来源：http://dali.tanke756.top/Article/details/gtlfwbkwvr.html

Ruby: ARGV
来源：http://dali.nanxinkj.top/Article/details/gtjauyjqzk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gtjnnvwvec.html

[M02] 读取环境变量
来源：http://dali.xuanzx.com/Article/details/gtbizsfnar.html

Py:   os.environ.get("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtkslocuca.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxqtbuvm.html

JS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gtashglqfd.html

TS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gtrawexovm.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gthqicqfgz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuanzx.com/Article/details/gthhpvipaa.html

Ruby: ENV["HOME"]
来源：http://dali.jinghuilouyu.cn/Article/details/gtwuxwhxhg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fzhhl.top/Article/details/gtuihckisc.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gtpdllmblw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.c1oappe.top/Article/details/gtmvbnmufs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gtueydzpfy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gtvqhlvxdx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gtfhhykfbv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxuanxn.top/Article/details/gtcfqdzuwg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gtiylulohl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxinkj.top/Article/details/gtphlkfjpq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnxiangtu.top/Article/details/gtgllrjjym.html

[M04] 获取当前工作目录
来源：http://dali.fengsongda.top/Article/details/gtkbqlykdo.html

Py:   os.getcwd()
来源：http://dali.vqdsnc.cn/Article/details/gtmiqjxrjm.html

PHP:  getcwd();
来源：http://dali.c1oappe.top/Article/details/gtgbeyfamh.html

JS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gtkgoxpzpi.html

TS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtnpzyazkz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghfkxsiy.html

Go:   os.Getwd()
来源：http://dali.hfpthk.cn/Article/details/gttdlgyaey.html

Ruby: Dir.pwd
来源：http://dali.yj202588.top/Article/details/gtbufssoaq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dashuyun.cn/Article/details/gtkdppvtzw.html

[M05] 设置退出码
来源：http://dali.zycfv.cn/Article/details/gtlftfogun.html

Py:   sys.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtuyykvwkw.html

PHP:  exit(1);
来源：http://dali.sysykeji.top/Article/details/gtlignxofu.html

JS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtbchvelve.html

TS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtdzlovdzx.html

Java: System.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtakciglnx.html

Go:   os.Exit(1)
来源：http://dali.ybcxt.top/Article/details/gtctzxfnez.html

Ruby: exit 1
来源：http://dali.yanxiufei.cn/Article/details/gtrzgjomoy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hysaishi.cn/Article/details/gtqqmaxdlg.html

[M06] 向标准错误输出
来源：http://dali.xinyue.icu/Article/details/gtapsmahzp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xziqi.cn/Article/details/gtciifykhn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hysaishi.cn/Article/details/gtkxcifyvh.html

JS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gtjpyhhrso.html

TS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gttapnedgj.html

Java: System.err.println("err")
来源：http://dali.xuanzx.com/Article/details/gthulvihzx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daria6918.cn/Article/details/gtdnhizbfd.html

Ruby: warn "err"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolezkpkz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daxiang520.top/Article/details/gtmogicuwq.html

[M07] 判断是否为主入口
来源：http://dali.chenjidiqi.icu/Article/details/gtobfyxbyf.html

Py:   if __name__ == "__main__":
来源：http://dali.guowangkeji.top/Article/details/gtymcdwhcy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gtpymnufcy.html

JS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtnljtotqy.html

TS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gtdoypcsbe.html

Java: public static void main(String[] args)
来源：http://dali.shuidangran.top/Article/details/gtlsoluebl.html

Go:   func main()
来源：http://dali.jiagoushi.top/Article/details/gtkcwrcdsb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hysaishi.cn/Article/details/gtswusrhmm.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258.top/Article/details/gtcrruajuq.html

[M08] 获取系统与运行时信息
来源：http://dali.9152youxi.cn/Article/details/gtoyzoeyjq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gtftpqktcb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gtssbzunvh.html

JS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gtsyoseuqc.html

TS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtrdgfwpqs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gaohongyu789.top/Article/details/gtroyxegwv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.quarkkingdee.top/Article/details/gtqmvuqkcc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gtdskjpkpj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgfzy.top/Article/details/gtwkyrcstx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtakfyplyf.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gtqbewktcv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtookemsum.html

[N01] 二分查找（有序数组）
来源：http://dali.yonumen.top/Article/details/gtxsteemcp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtjtlxjopr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gtiyoozltf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gtilqagidr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtzvdqcsob.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtvpraksbv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.havefunace.top/Article/details/gtxgjpgbte.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.smart0.xyz/Article/details/gtmimagpcp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtwsgljigu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gtscphxmbx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtaplybiim.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnqzz.top/Article/details/gtczavraco.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtunivlvge.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtqlphtknc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgufenzy.top/Article/details/gtmuagfieu.html

Go:   slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtnmglewua.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gtajdlanbp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xylfe.cn/Article/details/gtqeirqprl.html

[N03] 快速排序（分治示例）
来源：http://dali.sufxvd.cn/Article/details/gtlceybkui.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangshuangyany.cn/Article/details/gtjgvtjkhj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pengpengdd.cyou/Article/details/gtqlvpaepn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtqclxsivq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gtrzkredwg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj202588.top/Article/details/gttgwhgyyc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cqqwz.cn/Article/details/gtbhbwdtye.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxuanxn.top/Article/details/gtarktkeun.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xinyue.icu/Article/details/gtuvhrmtrh.html

[N04] 斐波那契数列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaavimxup.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gtkmyatjgk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gthmktsskc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtdzsphsqx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gttucdosbj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtjontlyfg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangshuangyany.cn/Article/details/gtnkieuzzn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gthaikzpfd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtczpythvt.html

[N05] 最大公约数
来源：http://dali.wangshuangyany.cn/Article/details/gtsaechkgv.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtiayhnscu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgoqkdtn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gtdofxgmgm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtnctumxpm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sweek.top/Article/details/gtdsjidsft.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcxomuqw.html

Ruby: a.gcd(b)
来源：http://dali.sysykeji.top/Article/details/gtuudvsfrr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xinyue.icu/Article/details/gtyggeyylr.html

[N06] 判断回文字符串
来源：http://dali.daxiang520.top/Article/details/gtjvcwhqfs.html

Py:   s == s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gtkatwhtsc.html

PHP:  $s === strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gtjmemvuef.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtbqblbxkt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtsdmjdsvr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pengpengdd.cyou/Article/details/gtqdpfadpr.html

Go:   // 双指针从两端比较
来源：http://dali.yongpay.top/Article/details/gtzzxvvolj.html

Ruby: s == s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtwsjbptnc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gtnzxkgdvd.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gtobhyoiol.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sysykeji.top/Article/details/gtvsiogovb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.vqdsnc.cn/Article/details/gtrnvzdtej.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigfzy.top/Article/details/gtepyyxrwm.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258888.top/Article/details/gtwagxydtg.html

Java: // 手写 HashMap
来源：http://dali.hysaishi.cn/Article/details/gtxdjbxwfy.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gtgixftovz.html

Ruby: // 手写 Hash
来源：http://dali.meibo888.top/Article/details/gtgdyonywv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhixingplan.top/Article/details/gtrkoqnrsb.html

[N08] 生成全排列
来源：http://dali.zhongyouzk.top/Article/details/gtjyshxbtf.html

Py:   itertools.permutations(arr)
来源：http://dali.zdqjudy.top/Article/details/gtqthmpvuy.html

PHP:  // 手写递归交换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrfykwft.html

JS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtgrfbuzzt.html

TS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtvxveeybi.html

Java: // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtxwgdcxcp.html

Go:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gthqtmlovm.html

Ruby: arr.permutation.to_a
来源：http://dali.daria6918.cn/Article/details/gtzquanhhj.html

C#:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtyudmdsak.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gthrgykmpg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shuidangran.top/Article/details/gtwbeambzr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtpuiqeaqg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtmgxqpclv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nwbrower.top/Article/details/gtleccvjep.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sweek.top/Article/details/gtphwzbpfr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigfzy.top/Article/details/gtuttonivw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gtirnhivld.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jyoumei.cn/Article/details/gtqqwtuoow.html

[N10] 链表节点定义
来源：http://dali.pycfn.com/Article/details/gtsflitaex.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tianlin.xyz/Article/details/gtzyyergzc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sufxvd.cn/Article/details/gtficvanta.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yvedp.cn/Article/details/gtcigzgkhy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxinkj.top/Article/details/gtkhnfgbmw.html

Java: class Node { int v; Node next; }
来源：http://dali.vqdsnc.cn/Article/details/gtgcclystl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenzaomai.com/Article/details/gthrjdhqut.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tianlin.xyz/Article/details/gtrxhjaezg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gaohongyu789.top/Article/details/gtxkgxlftz.html

[N11] 二叉树中序遍历
来源：http://dali.ydzc1.top/Article/details/gtvxbtpndh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gtnotxmivo.html

PHP:  // 手写递归函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksvwheau.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gtzdnkiotw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gtiycaiooe.html

Java: // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gtvxkgsvtv.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtysafkvnw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuanzx.com/Article/details/gtespefsnw.html

C#:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtwsvrwzkm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gtfkhbjzzx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fzhhl.top/Article/details/gtnnglubuq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daria6918.cn/Article/details/gtbmipvvsd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gthshhqvsf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gthjkldcnn.html


<!-- 参考信息 -->