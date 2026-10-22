代发 wailian999

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gt2jbxzzxnr.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ogvaaezq.html

[L01] 发送 GET 请求
来源：http://dali.sweek.top/Article/details/gt2cmsusfdb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aibaodan.cn/Article/details/gt2tuziodos.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jyoumei.cn/Article/details/gt2uwaoqipv.html

JS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gt2epahcwlo.html

TS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bcopaoua.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.iojbl.cn/Article/details/gt2lqqkbuji.html

Go:   resp, err := http.Get(url)
来源：http://dali.xylfe.cn/Article/details/gt2gwnfhctc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuxming.cn/Article/details/gt2ddlnbsvc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2syffwmbm.html

[L02] 发送 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gt2ewoaivxr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xinyue.icu/Article/details/gt2hpcpcoff.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gt2gbwiclje.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gt2gpizwizi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gt2pphqmrfu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhirnwjl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvflhmav.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.iojbl.cn/Article/details/gt2bdptaxpz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hywenlv.cn/Article/details/gt2abloxawl.html

[L03] 设置自定义请求头
来源：http://dali.andypj.xyz/Article/details/gt2zjvcsbbz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ytqbefpm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hfpthk.cn/Article/details/gt2vkbufjha.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gt2ivntpomh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gt2ozezvbqr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhengqikj.top/Article/details/gt2olblkiob.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pibgsicy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhengqikj.top/Article/details/gt2wtnfhphc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gt2ioflxmhn.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gt2ljbrgqpq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daxiang520.top/Article/details/gt2oixefsyo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangdashe.top/Article/details/gt2vcyhlajo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gt2ftwtovhx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gt2viqyrdtm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.birdmap.top/Article/details/gt2zaqeaseb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.c1oappe.top/Article/details/gt2wyxnqron.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gogol.net.cn/Article/details/gt2ylqddpex.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.c1oappe.top/Article/details/gt2focawoot.html

[L05] 上传文件（multipart）
来源：http://dali.zhiwuduotai.top/Article/details/gt2gzmgrswx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.mhx1999.top/Article/details/gt2nzubkgym.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gzhubu.top/Article/details/gt2olggvaql.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gt2gsansajx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gt2higbhmog.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jianghu66.top/Article/details/gt2vtmczwyo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nwbrower.top/Article/details/gt2qawhegvm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258888.top/Article/details/gt2cdzfwidx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gt2kkwahcsj.html

[L06] 解析响应为 JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2hvwzcuoh.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gt2ttmpidqc.html

PHP:  json_decode($body, true);
来源：http://dali.sweek.top/Article/details/gt2qeadqrmu.html

JS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gt2terdttcy.html

TS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gt2guetchbi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2ymblffps.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2opbqnzin.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhoulong.xyz/Article/details/gt2lfmedamk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258888.top/Article/details/gt2iflskcxl.html

[L07] 处理 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gt2rrvqzcvu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gt2ddvxozes.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuxming.cn/Article/details/gt2orpyrlkg.html

JS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gt2tsttbfem.html

TS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gt2gjqrefed.html

Java: resp.statusCode()
来源：http://dali.redwolf501.top/Article/details/gt2bhurkijv.html

Go:   resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gt2gacljkdz.html

Ruby: resp.code.to_i
来源：http://dali.smart0.xyz/Article/details/gt2wgmdwpaq.html

C#:   (int)resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gt2rfcjllhg.html

[L08] 并发请求多个地址
来源：http://dali.0kj1m.cn/Article/details/gt2unabipbo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gt2xnfjwypi.html

PHP:  curl_multi_init() 系列
来源：http://dali.mhx1999.top/Article/details/gt2fjytdzzf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2zmfxpgbd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gt2hlhsnpuy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gt2lskxvrea.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.kuanghao11.cn/Article/details/gt2tpnsgxyn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tanke756.top/Article/details/gt2vvkfoqvp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bejzzfjs.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2pkhotrod.html

M. 命令行 / 进程 / 环境
来源：http://dali.feifeiyinyue.top/Article/details/gt2dgksvupt.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2rgjacjny.html

[M01] 读取命令行参数
来源：http://dali.yuanzhike.top/Article/details/gt2tnxoewac.html

Py:   sys.argv[1:]
来源：http://dali.andypj.xyz/Article/details/gt2lwzysutc.html

PHP:  $argv;  $argc;
来源：http://dali.hfpthk.cn/Article/details/gt2graodvey.html

JS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gt2lingtglf.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gt2nlfjkxef.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vgedzcdx.html

Go:   os.Args[1:]
来源：http://dali.chenzaomai.com/Article/details/gt2hpuvvocw.html

Ruby: ARGV
来源：http://dali.quarkkingdee.top/Article/details/gt2gnecyjiy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gt2jswidnnc.html

[M02] 读取环境变量
来源：http://dali.shuidangran.top/Article/details/gt2xkeswkpg.html

Py:   os.environ.get("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2sxlxojds.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gt2qevhntgl.html

JS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gt2zkfsijhe.html

TS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gt2mtasxoit.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2rxlbhirv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2nbgttout.html

Ruby: ENV["HOME"]
来源：http://dali.hammf.cn/Article/details/gt2nnpawenk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2sfpptens.html

[M03] 执行外部命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bdrzfdee.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gt2xsvmzlkn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gt2syplgkdy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gt2cyybesol.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gt2bihjeeqk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yueranfly.top/Article/details/gt2vqhmlssc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hammf.cn/Article/details/gt2trvtxdfl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cdnleiting.top/Article/details/gt2hqjpyeif.html

C#:   Process.Start("ls", "-l");
来源：http://dali.birdmap.top/Article/details/gt2qwxxftvi.html

[M04] 获取当前工作目录
来源：http://dali.kuanghao11.cn/Article/details/gt2uohtikqn.html

Py:   os.getcwd()
来源：http://dali.sufxvd.cn/Article/details/gt2lzvhcdpo.html

PHP:  getcwd();
来源：http://dali.svipenyu.cn/Article/details/gt2dmswbhoq.html

JS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gt2yaqivxan.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxpgdylt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhengqikj.top/Article/details/gt2nbgazoxy.html

Go:   os.Getwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ldtyyswg.html

Ruby: Dir.pwd
来源：http://dali.shzxlz.cn/Article/details/gt2rkjnqsrz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhoulong.xyz/Article/details/gt2meygnnat.html

[M05] 设置退出码
来源：http://dali.yonumen.top/Article/details/gt2raxpudll.html

Py:   sys.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2zmeddxyb.html

PHP:  exit(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkgnpqcv.html

JS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gt2wkicvbwr.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2vqdwwbbs.html

Java: System.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2sujonfxd.html

Go:   os.Exit(1)
来源：http://dali.birdmap.top/Article/details/gt2wwfqethl.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gt2ginxexjq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.feifeiyinyue.top/Article/details/gt2znkgjwkd.html

[M06] 向标准错误输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kfupbtiu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gt2bomerffx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aerjnozl.html

JS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gt2nbagzhiz.html

TS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gt2xplzafnw.html

Java: System.err.println("err")
来源：http://dali.ppjwa.cn/Article/details/gt2svqdztrj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ydzc1.top/Article/details/gt2fawwagcv.html

Ruby: warn "err"
来源：http://dali.wangshuangyany.cn/Article/details/gt2frjkvqko.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2bqyimiau.html

[M07] 判断是否为主入口
来源：http://dali.xinyue.icu/Article/details/gt2hpdqprzx.html

Py:   if __name__ == "__main__":
来源：http://dali.andypj.xyz/Article/details/gt2bsawxaep.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zycfv.cn/Article/details/gt2wothvdrn.html

JS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gt2gfunuxxl.html

TS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gt2wzsxzzkp.html

Java: public static void main(String[] args)
来源：http://dali.aibaodan.cn/Article/details/gt2jmdkqygo.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gt2csdvtyjn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.quarkkingdee.top/Article/details/gt2godownyy.html

C#:   static void Main(string[] args)
来源：http://dali.gaohongyu789.top/Article/details/gt2dgzgssro.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gt2fhpfgsuw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ydzc1.top/Article/details/gt2pcspibmi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ybcxt.top/Article/details/gt2evcnyolp.html

JS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gt2zrjeegdw.html

TS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gt2ctevcvho.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fzhhl.top/Article/details/gt2yvqaxkwm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yvedp.cn/Article/details/gt2pmtksqhi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.iojbl.cn/Article/details/gt2iziyxwnv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxinkj.top/Article/details/gt2svtsfmdh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2umqgzxmq.html

N. 数据结构与算法
来源：http://dali.jyoumei.cn/Article/details/gt2qpzmbqdy.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2zsgqosdj.html

[N01] 二分查找（有序数组）
来源：http://dali.yongpay.top/Article/details/gt2haohktpl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2nlbifgkt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2gatbkusl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gt2sdqvouft.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gt2skmpovsm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2zytztwag.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brsmvxcp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guannengcc.top/Article/details/gt2qyuuxbig.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2cywtrwtr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gt2eiewumtg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gt2tyrgqynz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jlsjyb.cn/Article/details/gt2kkccltgi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gt2qzikhxgt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gt2kornfylg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuxming.cn/Article/details/gt2igzehzav.html

Go:   slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2euvkoudw.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2zpvutsqg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hywenlv.cn/Article/details/gt2birlpnbv.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gt2cewhgxth.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhengqikj.top/Article/details/gt2rynosbll.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aibaodan.cn/Article/details/gt2cwgihktj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gt2cnlsebzb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gt2nymtggps.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gt2snuvbuds.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigufen.top/Article/details/gt2iywscrqv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cashguo.top/Article/details/gt2uqdiynex.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ybcxt.top/Article/details/gt2uibkqldi.html

[N04] 斐波那契数列
来源：http://dali.yuanzhike.top/Article/details/gt2wjcwejkz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gt2iohsuwej.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qfneeozf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2bpwfgjca.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gt2zafupnih.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gt2ojdtjdbw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.0kj1m.cn/Article/details/gt2oyvtpmpp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gt2svnxoske.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gt2jlzeupnv.html

[N05] 最大公约数
来源：http://dali.hnxiangtu.top/Article/details/gt2xdicvxeh.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2vlenjijp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.smart0.xyz/Article/details/gt2rovczflt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gt2wtvvhxfy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gt2czriprwh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ehwqpu.com/Article/details/gt2enfytlji.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxuanxn.top/Article/details/gt2qctdfmkv.html

Ruby: a.gcd(b)
来源：http://dali.svipenyu.cn/Article/details/gt2xkrgkhks.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhoulong.xyz/Article/details/gt2phrwshvi.html

[N06] 判断回文字符串
来源：http://dali.cashguo.top/Article/details/gt2ajuwdasm.html

Py:   s == s[::-1]
来源：http://dali.yj202588.top/Article/details/gt2fvgotnij.html

PHP:  $s === strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gt2ahghewqj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gt2mfhdphld.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2kcnxfuat.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ppjwa.cn/Article/details/gt2bzxttclo.html

Go:   // 双指针从两端比较
来源：http://dali.fzhhl.top/Article/details/gt2alelfutv.html

Ruby: s == s.reverse
来源：http://dali.cucudq.cn/Article/details/gt2ctytnqyr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xyjziybm.html

[N07] 两数之和（返回下标）
来源：http://dali.zhiwuduotai.top/Article/details/gt2pykwhxsv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xinyue.icu/Article/details/gt2xpiatcql.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xinyue.icu/Article/details/gt2tepfilei.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ivvv.top/Article/details/gt2sebqqdvq.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2nubxhiyh.html

Java: // 手写 HashMap
来源：http://dali.dashuyun.cn/Article/details/gt2sqgfpjvk.html

Go:   // 手写 map[int]int
来源：http://dali.dianchejie.cn/Article/details/gt2ofvbrbqs.html

Ruby: // 手写 Hash
来源：http://dali.yvedp.cn/Article/details/gt2civadrnl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aibaodan.cn/Article/details/gt2tufmsgru.html

[N08] 生成全排列
来源：http://dali.yuxming.cn/Article/details/gt2yycxwzwo.html

Py:   itertools.permutations(arr)
来源：http://dali.sweek.top/Article/details/gt2fnrezcoz.html

PHP:  // 手写递归交换
来源：http://dali.nanxinkj.top/Article/details/gt2mqdrwjct.html

JS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2vnmkixoo.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2urlabvvh.html

Java: // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gt2zhosrjzi.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bxqsofay.html

Ruby: arr.permutation.to_a
来源：http://dali.hnqzz.top/Article/details/gt2srrzctvb.html

C#:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gt2aizafipj.html

[N09] 栈与队列
来源：http://dali.cheryme.top/Article/details/gt2mgklitvw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2ivowwlmq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yueranfly.top/Article/details/gt2xmvncphi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gt2mtxgxrph.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.vqdsnc.cn/Article/details/gt2sigryecq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.316326.xyz/Article/details/gt2rksinung.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenlongwang.top/Article/details/gt2rvnsithy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gt2bescpgta.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gt2hgnzcrwu.html

[N10] 链表节点定义
来源：http://dali.andypj.xyz/Article/details/gt2oxzwdlhg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dianchejie.cn/Article/details/gt2vqjszijn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.c1oappe.top/Article/details/gt2czfkgyyk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yvedp.cn/Article/details/gt2kcaxitzz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jlsjyb.cn/Article/details/gt2knfvress.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gt2tvirjvdg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sxryk.cn/Article/details/gt2azrrygpz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigufen.top/Article/details/gt2loodgasv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnqzz.top/Article/details/gt2lujyvzir.html

[N11] 二叉树中序遍历
来源：http://dali.andypj.xyz/Article/details/gt2naqftxxb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhixingplan.top/Article/details/gt2igusjefg.html

PHP:  // 手写递归函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2woaqvrxq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gt2cqifzeuh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ulwylryu.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2rsdsbkmd.html

Go:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gt2ttzhgfeh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.havefunace.top/Article/details/gt2txutvjxu.html

C#:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2lvjmdcjl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhiwuduotai.top/Article/details/gt2nlkmuurs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gotoacloud.top/Article/details/gt2jkifcfgj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hysaishi.cn/Article/details/gt2vnyyklbj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gt2mzmitupg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gt2sxeiclub.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gt2jicqchmy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.316326.xyz/Article/details/gt2voaeemcp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ussljhst.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gt2tkmeakud.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2vlviuirz.html

O. 并发与异步
来源：http://dali.yongpay.top/Article/details/gt2yrqujgqe.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2fdvdgvfn.html

[O01] 启动一个线程
来源：http://dali.zhengqikj.top/Article/details/gt2tfzwmxhj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cucudq.cn/Article/details/gt2rcmungpc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aizwys.cn/Article/details/gt2nfmajcgh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daxiang520.top/Article/details/gt2dvwcfieb.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gt2ifvkpauc.html

Java: new Thread(() -> f()).start()
来源：http://dali.gzhubu.top/Article/details/gt2splauncm.html

Go:   go f()
来源：http://dali.guannengcc.top/Article/details/gt2ixorglkx.html

Ruby: Thread.new { f }
来源：http://dali.hywenlv.cn/Article/details/gt2lbyvfyzg.html

C#:   Task.Run(() => F());
来源：http://dali.c1oappe.top/Article/details/gt2siokydxz.html

[O02] 使用线程池
来源：http://dali.pycfn.com/Article/details/gt2uteqhbjg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qvaozkfo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgfzy.top/Article/details/gt2qcqaucir.html

JS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yyukvnkk.html

TS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gt2kmjfgxjq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cucudq.cn/Article/details/gt2qwxlsehl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gt2lcctfzqd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sysykeji.top/Article/details/gt2sutjfjji.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.redwolf501.top/Article/details/gt2qkdielik.html

[O03] 加锁保护共享数据
来源：http://dali.9152youxi.cn/Article/details/gt2ixzaqxoz.html

Py:   with lock: shared += 1
来源：http://dali.zdqjudy.top/Article/details/gt2qejpcphk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhmgzsho.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgkjyckd.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gt2yieustth.html

Java: synchronized (this) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gt2hddwvgrm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.smart0.xyz/Article/details/gt2pvcqqxqq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.birdmap.top/Article/details/gt2wajdtyev.html

C#:   lock (gate) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gt2klewuqae.html

[O04] 定义异步函数并等待
来源：http://dali.yuxming.cn/Article/details/gt2qmxehofq.html

Py:   async def f():⏎    await g()
来源：http://dali.bjfxy.top/Article/details/gt2ivwbugzb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jianghu66.top/Article/details/gt2htrruomn.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gtqwlapx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2vrvvyrlv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xinyue.icu/Article/details/gt2yuxjpmuv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.mhx1999.top/Article/details/gt2kdpkigae.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guowangkeji.top/Article/details/gt2lzehdqpy.html

C#:   async Task F() { await G(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vjxdnxjp.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuetiantiany.cn/Article/details/gt2itpckidy.html


<!-- 参考信息 -->