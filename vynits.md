代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jyoumei.cn/Article/details/gtgperpyiv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtnkqkndtb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.redwolf501.top/Article/details/gtotbcwpqo.html

Py:   pickle.dumps(obj)
来源：http://dali.cheryme.top/Article/details/gtkcsenqkl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gtagqpedhq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gtdjwxshdy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gtvqjpbxdk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pengpengdd.cyou/Article/details/gtozxglegq.html

Go:   encoding/gob
来源：http://dali.ivvv.top/Article/details/gtbbctnfsv.html

Ruby: Marshal.dump(obj)
来源：http://dali.cashguo.top/Article/details/gtgpujxhka.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtxzgzqfka.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtwinvhlks.html

L. 网络请求
来源：http://dali.smart0.xyz/Article/details/gthxntmmsh.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gttdpsiahx.html

[L01] 发送 GET 请求
来源：http://dali.xuetiantiany.cn/Article/details/gtosjxrboj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuetiantiany.cn/Article/details/gtbgyhlocd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guannengcc.top/Article/details/gtjolxyxqc.html

JS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gtrvuclisw.html

TS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtumrcmxxj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shangyingyoupin.top/Article/details/gtlzvyaoql.html

Go:   resp, err := http.Get(url)
来源：http://dali.aizwys.cn/Article/details/gtgetugnoa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.mhx1999.top/Article/details/gtitzwsyxp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.andypj.xyz/Article/details/gttfrhhujs.html

[L02] 发送 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gtbgdkrctq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuanzx.com/Article/details/gtoodjiibv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gtubbrmusj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gtyzjoiwmu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gtaeqgttko.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tianlin.xyz/Article/details/gtgwpnadob.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.redwolf501.top/Article/details/gtrrrmjodi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuxming.cn/Article/details/gtgmfezhoa.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dashuyun.cn/Article/details/gtttqdurcb.html

[L03] 设置自定义请求头
来源：http://dali.chenjidiqi.icu/Article/details/gtyqpqrdnl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yonumen.top/Article/details/gtbubbqqpj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhixingplan.top/Article/details/gtuscfwdxl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gtfemowdht.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtatcizfsc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.c1oappe.top/Article/details/gtnnudbehc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gtbarwgpcj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyglunqie.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gtffxykvzg.html

[L04] 设置超时
来源：http://dali.wangshuangyany.cn/Article/details/gtypppsjvi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yvedp.cn/Article/details/gthocesbkb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yanxiufei.cn/Article/details/gtqlecaagd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtikjyugcm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gtvjyofokr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sweek.top/Article/details/gtnbcdawno.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gtpwhtdodm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxuanxn.top/Article/details/gtgzpnleuq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gtcgxuavsr.html

[L05] 上传文件（multipart）
来源：http://dali.smart0.xyz/Article/details/gtsghzgbxd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxuanxn.top/Article/details/gtrmixqjlm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jianghu66.top/Article/details/gtgiigpjaf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtchjariqi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtdocfpzmv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shzxlz.cn/Article/details/gtqggitpnr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yongpay.top/Article/details/gtxyffajxr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenjidiqi.icu/Article/details/gtekuiucvp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxaydksh.html

[L06] 解析响应为 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtghuwjjft.html

Py:   resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtoalvjkhv.html

PHP:  json_decode($body, true);
来源：http://dali.yuxming.cn/Article/details/gtwxhhowqy.html

JS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtqsfjgqui.html

TS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gtmlacmmdy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfymfkxxc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tian-w.cn/Article/details/gtdvtgscqf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gtzaipedjn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gtwwcorxoa.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gtnitxqkvz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigfzy.top/Article/details/gtszbvdjta.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtxsxjgacl.html

JS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtjgqlqdvx.html

TS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtahrusssb.html

Java: resp.statusCode()
来源：http://dali.andypj.xyz/Article/details/gtlbfhdclv.html

Go:   resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtgysvwibh.html

Ruby: resp.code.to_i
来源：http://dali.zhixingplan.top/Article/details/gtpcrhsejl.html

C#:   (int)resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gtbzaozlcq.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gtsrjeqnbo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyodbptj.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhixingplan.top/Article/details/gtwhanfika.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzttchvj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrfivxxu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ehwqpu.com/Article/details/gtvgsmaoik.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guannengcc.top/Article/details/gtlqkxgwoc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtkilfkhov.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daria6918.cn/Article/details/gttjlkinho.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmccclssi.html

M. 命令行 / 进程 / 环境
来源：http://dali.daxiang520.top/Article/details/gtrramqbre.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtkbynxqti.html

[M01] 读取命令行参数
来源：http://dali.316326.xyz/Article/details/gtuvltpojz.html

Py:   sys.argv[1:]
来源：http://dali.hysaishi.cn/Article/details/gtkdtrfktr.html

PHP:  $argv;  $argc;
来源：http://dali.cqqwz.cn/Article/details/gthuedffbl.html

JS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gtufrbdmao.html

TS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gtlymzcxcv.html

Java: args 数组（main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtenbtjcgx.html

Go:   os.Args[1:]
来源：http://dali.xuanzx.com/Article/details/gtlaokomro.html

Ruby: ARGV
来源：http://dali.ydzc1.top/Article/details/gtlqdgmigo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkdgszny.html

[M02] 读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmceodext.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtskvnagyr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtwwjcdxok.html

JS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gtnjemsfwe.html

TS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtksnnswvi.html

Java: System.getenv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtwxfdlufb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtzqpvazui.html

Ruby: ENV["HOME"]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdkdjtln.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtaorsuaot.html

[M03] 执行外部命令
来源：http://dali.ydzc1.top/Article/details/gtdgvkaimi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gtfoszlzvo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gtowizxlyb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gtishttcez.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtiokshvrd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pengpengdd.cyou/Article/details/gtsqycslcv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlfzafto.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenlongwang.top/Article/details/gtkhvuvgvm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ppjwa.cn/Article/details/gtaoqofver.html

[M04] 获取当前工作目录
来源：http://dali.hysaishi.cn/Article/details/gtvfnzubjf.html

Py:   os.getcwd()
来源：http://dali.nanxuanxn.top/Article/details/gtnaywgqyn.html

PHP:  getcwd();
来源：http://dali.sweek.top/Article/details/gtslzrzngg.html

JS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufxrzupc.html

TS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtzqqhpcup.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gtncpnolfp.html

Go:   os.Getwd()
来源：http://dali.gotoacloud.top/Article/details/gtdqhvrwsj.html

Ruby: Dir.pwd
来源：http://dali.cheryme.top/Article/details/gthytnviqs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxinkj.top/Article/details/gtutladvtk.html

[M05] 设置退出码
来源：http://dali.gotoacloud.top/Article/details/gtmlsdvhwt.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtoalylrau.html

PHP:  exit(1);
来源：http://dali.cqqwz.cn/Article/details/gttqljhdoa.html

JS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gtuiidzwan.html

TS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtsyznnxtt.html

Java: System.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtiziqmdbn.html

Go:   os.Exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtzmwrmlnv.html

Ruby: exit 1
来源：http://dali.daria6918.cn/Article/details/gtzzmbwexv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.316326.xyz/Article/details/gtujvfvmqn.html

[M06] 向标准错误输出
来源：http://dali.xinyue.icu/Article/details/gtueozqksy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gtsuzbmvrx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gtnrjkmlxa.html

JS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtvlkoufdh.html

TS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gtnrqwkfxs.html

Java: System.err.println("err")
来源：http://dali.jianghu66.top/Article/details/gttwkkpqhd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.bjfxy.top/Article/details/gthmevbhis.html

Ruby: warn "err"
来源：http://dali.jianghu66.top/Article/details/gtcrijdaee.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hammf.cn/Article/details/gtcxrjtuuh.html

[M07] 判断是否为主入口
来源：http://dali.yongpay.top/Article/details/gteiwkvyrs.html

Py:   if __name__ == "__main__":
来源：http://dali.hywenlv.cn/Article/details/gtdpflhkdu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hfpthk.cn/Article/details/gtsnnrknzc.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtwnrxdpfo.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtzwqpfjwe.html

Java: public static void main(String[] args)
来源：http://dali.nanxinkj.top/Article/details/gtgvfjljzw.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gtherzagiu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gtsstlbwhi.html

C#:   static void Main(string[] args)
来源：http://dali.bjfxy.top/Article/details/gtsgzuhhft.html

[M08] 获取系统与运行时信息
来源：http://dali.sweek.top/Article/details/gtppzmmjae.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hysaishi.cn/Article/details/gtzkaynhxd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sxryk.cn/Article/details/gtytanuajk.html

JS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gtctkgtxhu.html

TS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gtioejettu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuanzhike.top/Article/details/gtgsouobra.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.9152youxi.cn/Article/details/gtwsayuhxm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gtuupxjlov.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zycfv.cn/Article/details/gtizfrorat.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtmhuefypi.html

N. 数据结构与算法
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvkbdgnd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxoipjrw.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gtrrnuejif.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtuzmtntop.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtwttmhzas.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gthxolwhtj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtlzrtwsrf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gttwtddxyr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtajcnozaz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shangyingyoupin.top/Article/details/gticrhczdw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtbnmnevsj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yueranfly.top/Article/details/gtdpoqrqfc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gtrkzfvubk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhengqikj.top/Article/details/gtpphxzkrz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtisbjdyud.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtphyxbglq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gzhubu.top/Article/details/gtofizgook.html

Go:   slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gtzdtcfvek.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gtobruunzw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yongpay.top/Article/details/gtcuaptvaw.html

[N03] 快速排序（分治示例）
来源：http://dali.jianghu66.top/Article/details/gtbuvkpqtn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yvedp.cn/Article/details/gtgzmcuqks.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fzhhl.top/Article/details/gthcvoydrl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gtsltxsikq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtivdaczaw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daxiang520.top/Article/details/gtykdybxxb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangdashe.top/Article/details/gtyhuifyiz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.feifeiyinyue.top/Article/details/gtcidkgoao.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yangfankeji.com/Article/details/gtfrbozvtp.html

[N04] 斐波那契数列
来源：http://dali.wangdashe.top/Article/details/gtfbeksqyu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gthikeqgfy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258.top/Article/details/gtglxkupow.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtocmsbbdc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtledxkaet.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gtpddzjcmb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenlongwang.top/Article/details/gtcfborjfb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtqavoohsv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtgccffmtp.html

[N05] 最大公约数
来源：http://dali.redwolf501.top/Article/details/gthdqezzah.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtibtmrlfw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ppjwa.cn/Article/details/gtufppaogk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gtltoocrvq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gtbyfgevvg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pengpengdd.cyou/Article/details/gtfwypmwrc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ydzc1.top/Article/details/gtachrjsul.html

Ruby: a.gcd(b)
来源：http://dali.yuanzhike.top/Article/details/gtkpyoxxiz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.quarkkingdee.top/Article/details/gtzexowprk.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gtmqaedlzx.html

Py:   s == s[::-1]
来源：http://dali.smart0.xyz/Article/details/gtwizdahpe.html

PHP:  $s === strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gturnycpoi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtixowqwfv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtsvsklucf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xinyue.icu/Article/details/gtezgvcmrr.html

Go:   // 双指针从两端比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcymehqqu.html

Ruby: s == s.reverse
来源：http://dali.hfpthk.cn/Article/details/gtdxccsnst.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gtvouktiog.html

[N07] 两数之和（返回下标）
来源：http://dali.kuanghao11.cn/Article/details/gtqoptqnqs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gotoacloud.top/Article/details/gtteovuryj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gaohongyu789.top/Article/details/gtazlmgtcx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yueranfly.top/Article/details/gtujbdtmsb.html

TS:   // 手写 Map<string, number>
来源：http://dali.kuanghao11.cn/Article/details/gtoktsmrze.html

Java: // 手写 HashMap
来源：http://dali.jinqigufen.top/Article/details/gtmzuagrwd.html

Go:   // 手写 map[int]int
来源：http://dali.jqgfzy.top/Article/details/gthldrwvwo.html

Ruby: // 手写 Hash
来源：http://dali.ydzc1.top/Article/details/gtujoegnzb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hfpthk.cn/Article/details/gtcmywnqmt.html

[N08] 生成全排列
来源：http://dali.ivvv.top/Article/details/gtztkqeryi.html

Py:   itertools.permutations(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtqsdwmdrs.html

PHP:  // 手写递归交换
来源：http://dali.birdmap.top/Article/details/gtgwlsptdx.html

JS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtouxdsxgr.html

TS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtcbimsdhz.html

Java: // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrmcpvsr.html

Go:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtbofwuvhl.html

Ruby: arr.permutation.to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsboibpgd.html

C#:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtishvsark.html

[N09] 栈与队列
来源：http://dali.tanke756.top/Article/details/gtsjhijdwv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zycfv.cn/Article/details/gtbptmspfo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtgbxmfpjh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtvexznggo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guowangkeji.top/Article/details/gthqgzeulr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gtleenwozq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.quarkkingdee.top/Article/details/gtowsdvoyb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtelwvbzkt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jiagoushi.top/Article/details/gtunsphkvu.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gtkwtrbhwl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhixingplan.top/Article/details/gtdqkpoaoc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvpswgvlp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gotoacloud.top/Article/details/gtkjzxwnye.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.birdmap.top/Article/details/gtmjmzkxbp.html

Java: class Node { int v; Node next; }
来源：http://dali.gotoacloud.top/Article/details/gtpqduzvld.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.smart0.xyz/Article/details/gtimygjbkn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yangfankeji.com/Article/details/gtomelvmvg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.316326.xyz/Article/details/gtlgdkckkz.html

[N11] 二叉树中序遍历
来源：http://dali.ehwqpu.com/Article/details/gttexhzrmb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gttnvaxqvf.html

PHP:  // 手写递归函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcisqakrs.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gtcnltyrhj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gtcbgjqdcw.html

Java: // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtylxxwppk.html

Go:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtxodoesrt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqmopdgf.html

C#:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtfxldkaxv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.snrcjt.cn/Article/details/gtntqvahjn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fengsongda.top/Article/details/gtjdzlbqzc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sysykeji.top/Article/details/gtfkvhovqj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gtefmgtwug.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtdugosdlt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtookaspxu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shuidangran.top/Article/details/gtylmrbacd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtvlkctdml.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gtuhxqwkxx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtpkvuscwb.html

O. 并发与异步
来源：http://dali.dianchejie.cn/Article/details/gtxowvdckf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gthnqmlmab.html

[O01] 启动一个线程
来源：http://dali.yongpay.top/Article/details/gtbjmfjkzf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sxryk.cn/Article/details/gtvzhhowzi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zycfv.cn/Article/details/gtbucfnyqf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gtkhoaprec.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtunnvazxa.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenzaomai.com/Article/details/gtnvayindh.html

Go:   go f()
来源：http://dali.dianchejie.cn/Article/details/gtntpwotku.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gttfycbmlf.html

C#:   Task.Run(() => F());
来源：http://dali.fzhhl.top/Article/details/gtcspypwci.html

[O02] 使用线程池
来源：http://dali.snrcjt.cn/Article/details/gtverpevgm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pengpengdd.cyou/Article/details/gtrpfudcxe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gzhubu.top/Article/details/gtxxzoddws.html

JS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gtujccadrl.html

TS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gtnwdgtqfh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhixingplan.top/Article/details/gttetzsvnd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daxiang520.top/Article/details/gtqrdbpjoc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yangfankeji.com/Article/details/gtbdeuaqau.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cdnleiting.top/Article/details/gtmnqldzme.html

[O03] 加锁保护共享数据
来源：http://dali.daria6918.cn/Article/details/gtdmjxgqou.html

Py:   with lock: shared += 1
来源：http://dali.jqgufenzy.top/Article/details/gtgayfgkhv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tian-w.cn/Article/details/gtqxrrwtaq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gogol.net.cn/Article/details/gtwromtonn.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtapwpxarw.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtpszzpifb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shangyingyoupin.top/Article/details/gtunkdbqcb.html


<!-- 参考信息 -->