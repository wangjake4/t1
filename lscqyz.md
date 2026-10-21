代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gtrqzjtbmu.html

Ruby: s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gtlnhlfgkj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gtiprnoaip.html

[E13] 逐字符遍历
来源：http://dali.fengsongda.top/Article/details/gtxkcjimqg.html

Py:   for ch in s: print(ch)
来源：http://dali.yanxiufei.cn/Article/details/gtimrgwygk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yvedp.cn/Article/details/gtmecpnwbv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtgnexwtog.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gtogejrnzc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdcmmrpu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aibaodan.cn/Article/details/gtbgsgbnyb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.redwolf501.top/Article/details/gtiydvdtlt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gzhubu.top/Article/details/gtvfawqjok.html

[E14] URL 编码与 Base64
来源：http://dali.yj202588.top/Article/details/gtinfytxbd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.svipenyu.cn/Article/details/gtsxolmwqz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigufen.top/Article/details/gtxzaonqdq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hywenlv.cn/Article/details/gtpjnkzdkg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xinyue.icu/Article/details/gtpdpwjeom.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtfsdycsox.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gtuyaiwujl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenjidiqi.icu/Article/details/gtipyoxyyb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gttnlbienl.html

[E15] HTML 转义 / 反转义
来源：http://dali.shuidangran.top/Article/details/gtavtibhkc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gtgrmeymot.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenzaomai.com/Article/details/gtkfsbhbdl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gogol.net.cn/Article/details/gtcxheukif.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtlavxytsf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.vqdsnc.cn/Article/details/gtzgtrbvar.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtmmguyjtf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtznqchkye.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gtladgxxjs.html

[E16] 数字千分位
来源：http://dali.ppjwa.cn/Article/details/gteiuzlctv.html

Py:   f"{1234567:,}"
来源：http://dali.dashuyun.cn/Article/details/gtbwyqmrsq.html

PHP:  number_format(1234567);
来源：http://dali.hnxiangtu.top/Article/details/gtvhmebmko.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpeyhexi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gtidvtffbv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gttupvrwgh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daria6918.cn/Article/details/gtwxwzvzyf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cucudq.cn/Article/details/gttvuyolib.html

C#:   1234567.ToString("N0")
来源：http://dali.xuetiantiany.cn/Article/details/gtzmdacell.html

[E17] 首字母大写
来源：http://dali.aizwys.cn/Article/details/gtwtbctouf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hysaishi.cn/Article/details/gtitywmcbg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gtuxhajdrs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gtweqhqlxo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtbcojkhue.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gtrzmqibmo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cheryme.top/Article/details/gtisybobja.html

Ruby: s.capitalize
来源：http://dali.0kj1m.cn/Article/details/gtgjhlivny.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.9152youxi.cn/Article/details/gtdgxdugre.html

[E18] 模板占位符替换
来源：http://dali.shzxlz.cn/Article/details/gtouybpnvk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258888.top/Article/details/gtyxglwytb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigfzy.top/Article/details/gtemsylmtn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfumohqe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtuuokbcpr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtfrvgoqeb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.havefunace.top/Article/details/gtrhkodwhn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yuxming.cn/Article/details/gtmqdzpjkl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fengsongda.top/Article/details/gtebzrixmb.html

[E19] 多行文本按行拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtqfvpqzyh.html

Py:   s.splitlines()
来源：http://dali.yuanzhike.top/Article/details/gttknpmjye.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pycfn.com/Article/details/gtmuaosavb.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmwnrftg.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezmuvnee.html

Java: s.lines().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtoqpjjuhb.html

Go:   strings.Split(s, "\n")
来源：http://dali.hammf.cn/Article/details/gtohpvbetg.html

Ruby: s.lines
来源：http://dali.cdnleiting.top/Article/details/gtzyhbkkdd.html

C#:   s.Split('\n')
来源：http://dali.zhengqikj.top/Article/details/gtjreigbix.html

[E20] 判断字符串是否为空
来源：http://dali.316326.xyz/Article/details/gtfxadjepa.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gtuahzotwp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgufenzy.top/Article/details/gtrfdvnadd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ybcxt.top/Article/details/gtrodwxpff.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gtwhayrpwu.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjqhpdph.html

Go:   if s == "" {}
来源：http://dali.daria6918.cn/Article/details/gtdskjfkud.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gtdjmyezia.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tianlin.xyz/Article/details/gttkoyrahe.html

[E21] 超长截断加省略号
来源：http://dali.hnqzz.top/Article/details/gthdiibctg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gtshjwlzag.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtvcppxclm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtlkbdhoiq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gttavsgimf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtblylqeza.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fzhhl.top/Article/details/gtjkdatmzd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtgofflptb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtcmszaqqx.html

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gtvrozttfi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.meibo888.top/Article/details/gtkwqldtli.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtbbpkcnmm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtkpathvvh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gtozdrtcua.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gtsobkymtg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xziqi.cn/Article/details/gtzlfmrwkv.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtznpwbwca.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gtqdinfkxt.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtgtcucjuv.html

F. 文件与目录
来源：http://dali.bjfxy.top/Article/details/gtrlbuxwlr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtrseohxje.html

[F01] 读取整个文件
来源：http://dali.hysaishi.cn/Article/details/gttnuuxxfl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cheryme.top/Article/details/gtepxwdssj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtbmrgjzdd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tanke756.top/Article/details/gticaytlto.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtieferrnu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtvllazcal.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuanzx.com/Article/details/gtrmmudxsv.html

Ruby: File.read("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtjjlxnogl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fzhhl.top/Article/details/gthwgziovw.html

[F02] 逐行读取文件
来源：http://dali.shzxlz.cn/Article/details/gtdcicreqt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sysykeji.top/Article/details/gtdmcggixl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cheryme.top/Article/details/gtimaksfcz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtlnhwzyhb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtweooijfz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtgvxwkxbe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrdublii.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ybcxt.top/Article/details/gtetfihugx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xylfe.cn/Article/details/gtrriyfvxq.html

[F03] 写入文件（覆盖）
来源：http://dali.yangfankeji.com/Article/details/gtzyiyxbha.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gtornpeuuc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtrfaoaeyg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjstnegnv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtzkmspzug.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gtpfasuetl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenzaomai.com/Article/details/gtgzvbdpxl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jlsjyb.cn/Article/details/gtrmkriecn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtagclwgkn.html

[F04] 追加写入文件
来源：http://dali.iojbl.cn/Article/details/gtfszmnzmc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangdashe.top/Article/details/gtvysmokru.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnxiangtu.top/Article/details/gtprqhptfr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gthttkbnlt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gtairhqmnu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jlsjyb.cn/Article/details/gtdmvltuag.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gtrerfmusp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yvedp.cn/Article/details/gtxvydgtvb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xylfe.cn/Article/details/gtdjsrmecn.html

[F05] 判断文件或目录是否存在
来源：http://dali.xinyue.icu/Article/details/gtekyaomav.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqzywuwy.html

PHP:  file_exists("a.txt");
来源：http://dali.fengsongda.top/Article/details/gttnnqdcgj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtlglxyitg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtlbdniksl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtzgheqsln.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gtvhiewgcv.html

Ruby: File.exist?("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gteyfpuceu.html

C#:   File.Exists("a.txt")
来源：http://dali.316326.xyz/Article/details/gttwztmgcj.html

[F06] 删除文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnndjsix.html

Py:   os.remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtticieqry.html

PHP:  unlink("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtkbygtjsl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtxgukhbpl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtulvesdjc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtxrsdpngk.html

Go:   os.Remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtpgnllxaq.html

Ruby: File.delete("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtkfzmlcps.html

C#:   File.Delete("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtopqxnkvj.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gtxhgdsynj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gtntmsymvf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqqjtsyw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtnpcqmmqh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtiwyrfnym.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.feifeiyinyue.top/Article/details/gtvwdmctae.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuanzhike.top/Article/details/gtaffhvgev.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj202588.top/Article/details/gtuiuemdqg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yvedp.cn/Article/details/gtvsbrbvvr.html

[F08] 遍历目录
来源：http://dali.yueranfly.top/Article/details/gtmtlqsxev.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuetiantiany.cn/Article/details/gtegwoiccn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guannengcc.top/Article/details/gtiaklteas.html

JS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtnowlkiwl.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtihwxtqhy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtzdcwpklf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gtcoevcygu.html

Ruby: Dir.children("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxpllqlw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hammf.cn/Article/details/gttudoclpc.html

[F09] 获取文件大小
来源：http://dali.fzhhl.top/Article/details/gtfreavibn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtmnzicrwb.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtvaymybnt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtqvlcjdwz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtzzaukvdc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtvjwwawjx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.snrcjt.cn/Article/details/gtxuwdgckd.html

Ruby: File.size("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtulirnbyg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tanke756.top/Article/details/gtpfhgxboq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guannengcc.top/Article/details/gtwakcleet.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtqlftcxzs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtvducsdht.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtwmxyqtxz.html

TS:   path.extname("a.txt")
来源：http://dali.tanke756.top/Article/details/gtpfxuairc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigufen.top/Article/details/gtunalnttc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtaekuomny.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gthoguwdsg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtdhagpwaq.html

[F11] 复制与移动文件
来源：http://dali.jyoumei.cn/Article/details/gtzswxwmzo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtmvmgjivq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtffukoasd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtolugmwtf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtnplvkhue.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlhtsujc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xinyue.icu/Article/details/gtnfljbmak.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtfbrdhmkm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gtrucndfuh.html

[F12] CSV 读写
来源：http://dali.chenlongwang.top/Article/details/gtcnygmlel.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gtgbkxwbap.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gtgujldfkc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guannengcc.top/Article/details/gtenxvtecn.html

TS:   // 同上
来源：http://dali.cucudq.cn/Article/details/gtgxhxsiwp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cucudq.cn/Article/details/gtloqpaglc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yvedp.cn/Article/details/gtktrqxnea.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyaqcmqn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gtirlkwogj.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtnossiugb.html

G. 面向对象
来源：http://dali.dashuyun.cn/Article/details/gtjnbpinuf.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gthfsorswt.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gtbrulrtwm.html

Py:   class User: pass
来源：http://dali.snrcjt.cn/Article/details/gtjzdyrzzi.html

PHP:  class User {}
来源：http://dali.yongpay.top/Article/details/gtzkvdlfar.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtgqcuxcbp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhengqikj.top/Article/details/gtcuslxkak.html

Java: class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtaotprccx.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gtgazndvrj.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gttlafdyqp.html

C#:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtcykzjyyy.html

[G02] 构造函数
来源：http://dali.jianghu66.top/Article/details/gtfuhyeiem.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.redwolf501.top/Article/details/gtssbfnzgt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yangfankeji.com/Article/details/gtyfuvrhvc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtgvybqrtf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuirscspf.html

Java: User(String name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtnmucdtfj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gthemfimaw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zdqjudy.top/Article/details/gtcjgivhao.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gtldzjhftn.html

[G03] 实例属性
来源：http://dali.hfpthk.cn/Article/details/gtxoajzklr.html

Py:   self.name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtxskeoeuy.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gtydkpnodd.html

JS:   this.name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtwjfzqfrj.html

TS:   name: string = "x";
来源：http://dali.wangdashe.top/Article/details/gtfxpwtfcd.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gtaiktjexv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dianchejie.cn/Article/details/gtwhshaspm.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtxdnucjvd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dianchejie.cn/Article/details/gtdzpvijrm.html

[G04] 定义方法
来源：http://dali.jqgufenzy.top/Article/details/gtpyixfwjq.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvhpjftm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtqivmahew.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtczvcmcbk.html

TS:   greet(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtdiirrqzs.html

Java: String greet() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtlokeatkm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtgadlvsdw.html

Ruby: def greet; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtckfktjon.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gtbfcluhrr.html

[G05] 继承
来源：http://dali.gzhubu.top/Article/details/gtvzbqgmmm.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gtclncvmql.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gttfhgyvzr.html

JS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtonzgpjrq.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtvuwxsigj.html

Java: class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtrfgadqrh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yangfankeji.com/Article/details/gtxptnrqgw.html

Ruby: class Admin < User; end
来源：http://dali.yuxming.cn/Article/details/gtaglcfzpi.html

C#:   class Admin : User {}
来源：http://dali.andypj.xyz/Article/details/gtkqodaimm.html

[G06] 重写方法
来源：http://dali.nwbrower.top/Article/details/gtkhemaxgi.html

Py:   def greet(self): return "admin"
来源：http://dali.zhixingplan.top/Article/details/gtldjyuitp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtxfpothnl.html

JS:   greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtmlzsygfv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtudzekuzg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtoqaqfugm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gtghitjbrq.html

Ruby: def greet; "admin"; end
来源：http://dali.yuanzhike.top/Article/details/gttewunnpm.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gtpdkafpkw.html

[G07] 调用父类方法
来源：http://dali.pengpengdd.cyou/Article/details/gtyekfrywh.html

Py:   super().greet()
来源：http://dali.meibo888.top/Article/details/gtvoeawbii.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gtnqxkwsrl.html

JS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtggknetqf.html

TS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gthdtcilqy.html

Java: super.greet();
来源：http://dali.yj202588.top/Article/details/gthgifdomd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gtpakngafc.html

Ruby: super
来源：http://dali.cheryme.top/Article/details/gtbjyqewkb.html

C#:   base.Greet();
来源：http://dali.redwolf501.top/Article/details/gtcjkmgmjc.html

[G08] 静态方法与属性
来源：http://dali.dianchejie.cn/Article/details/gtlrzoyxfh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hysaishi.cn/Article/details/gtwuhycwnn.html

PHP:  public static function f() {}
来源：http://dali.fzhhl.top/Article/details/gtwozpbcst.html

JS:   static f() {}
来源：http://dali.andypj.xyz/Article/details/gtadqthvqz.html

TS:   static f(): void {}
来源：http://dali.xziqi.cn/Article/details/gtiisqzsrc.html

Java: static void f() {}
来源：http://dali.pycfn.com/Article/details/gtumaavmuy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gtxhwknwep.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gtshfoxmqm.html

C#:   public static void F() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpqxptvy.html

[G09] 接口 / 抽象类
来源：http://dali.hongshengwenyu.top/Article/details/gtmkbczvzy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhiwuduotai.top/Article/details/gtepadfxib.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.havefunace.top/Article/details/gtfipcchvr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cashguo.top/Article/details/gtdayxdrxc.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtnizzteoa.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtoldrvdbx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gtvaayixmp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gtqlvzsmvr.html

C#:   interface IShape { double Area(); }
来源：http://dali.cheryme.top/Article/details/gtkvueuebg.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gtpqrzfidy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daria6918.cn/Article/details/gtpzzmepbz.html

PHP:  public / protected / private
来源：http://dali.wangdashe.top/Article/details/gteqbpjfbe.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gtygqufviz.html

TS:   public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtgthxbcvm.html

Java: public / protected / private / 默认包级
来源：http://dali.shuidangran.top/Article/details/gtucvbxsfp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pengpengdd.cyou/Article/details/gtiviwgqof.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtisnwgxot.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gtipkterry.html

[G11] getter / setter
来源：http://dali.jinqigufen.top/Article/details/gticwcwlwp.html

Py:   @property 与 @x.setter
来源：http://dali.jqgufenzy.top/Article/details/gtbmcofaqp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpemhnvtk.html


<!-- 参考信息 -->