代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.smart0.xyz/Article/details/gtabpxtyxy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gtddnsqzah.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtoauzotwr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtqsqqwysi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.andypj.xyz/Article/details/gtwkhgyiyw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yanxiufei.cn/Article/details/gtsrvhznjh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zycfv.cn/Article/details/gtjrdwyyby.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sweek.top/Article/details/gtfwzwrnty.html

[E14] URL 编码与 Base64
来源：http://dali.snrcjt.cn/Article/details/gtjijwdgur.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yangfankeji.com/Article/details/gtfteaxzww.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuxming.cn/Article/details/gtacepogub.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guannengcc.top/Article/details/gtfjnavpft.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aizwys.cn/Article/details/gtsodqdfxk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtyrnpyyit.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.feifeiyinyue.top/Article/details/gtrrefwmxq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtctywnxdq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tanke756.top/Article/details/gtoclmzmuf.html

[E15] HTML 转义 / 反转义
来源：http://dali.zdqjudy.top/Article/details/gtxjdhueyb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aibaodan.cn/Article/details/gtixttyhlt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258888.top/Article/details/gtrbsqxmie.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258888.top/Article/details/gtxczoepfn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hysaishi.cn/Article/details/gtnbtzvwrp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cdnleiting.top/Article/details/gtrdjiispw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gtsmpudgvj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gtipewbwza.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtttvgaitb.html

[E16] 数字千分位
来源：http://dali.ydzc1.top/Article/details/gtgjlrlspe.html

Py:   f"{1234567:,}"
来源：http://dali.hnxiangtu.top/Article/details/gtsiithlqg.html

PHP:  number_format(1234567);
来源：http://dali.hnxiangtu.top/Article/details/gttdndwfqm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gtgxcydmoj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gtarngwmsf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnqzz.top/Article/details/gtnswjhwla.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj202588.top/Article/details/gtrsdlimpe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqcynivz.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtncznnajb.html

[E17] 首字母大写
来源：http://dali.tianlin.xyz/Article/details/gtqoajjaiy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dianchejie.cn/Article/details/gtclwledfp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yongpay.top/Article/details/gthhvdfxma.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtclebxlxr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gtxrdyuvnb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xziqi.cn/Article/details/gtrkzkajzc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gtgwacjhaj.html

Ruby: s.capitalize
来源：http://dali.9152youxi.cn/Article/details/gtalbuyseq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.feifeiyinyue.top/Article/details/gtgenzpvyx.html

[E18] 模板占位符替换
来源：http://dali.yongpay.top/Article/details/gtuqlmqdfb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.smart0.xyz/Article/details/gtdwuiipme.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ybcxt.top/Article/details/gtryhtjxea.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtouqdgldl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtfaygyzei.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtzkczwneg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shuidangran.top/Article/details/gthzllakyn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hammf.cn/Article/details/gtrtrdfnhq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.0kj1m.cn/Article/details/gtkzazadmm.html

[E19] 多行文本按行拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtkahyfbfg.html

Py:   s.splitlines()
来源：http://dali.yongpay.top/Article/details/gtcwezwcxl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtlltnduts.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gtrqzycfls.html

TS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtguothxud.html

Java: s.lines().toList()
来源：http://dali.yueranfly.top/Article/details/gtpkirdgls.html

Go:   strings.Split(s, "\n")
来源：http://dali.yanxiufei.cn/Article/details/gticekogku.html

Ruby: s.lines
来源：http://dali.hywenlv.cn/Article/details/gtzzhwiyhf.html

C#:   s.Split('\n')
来源：http://dali.guannengcc.top/Article/details/gtelgfqnxq.html

[E20] 判断字符串是否为空
来源：http://dali.meibo888.top/Article/details/gtpbchydro.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gtduygaxda.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.iojbl.cn/Article/details/gtbtxyqlvo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gtfxhmeryx.html

TS:   if (s === "") {}
来源：http://dali.haohaochexian.top/Article/details/gtcywopuyf.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gtgxncoqqv.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gtwljjdoyu.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gtbirglgot.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zdqjudy.top/Article/details/gtdgtxiynb.html

[E21] 超长截断加省略号
来源：http://dali.ybcxt.top/Article/details/gttexniwdv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuanzhike.top/Article/details/gtteqpzfvg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvprypit.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtoourehxc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtrlxfemeb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtdvlgebfh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gtiydsvtxb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtdqhgnfmk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtojtigjxx.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigfzy.top/Article/details/gtorkjuite.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yongpay.top/Article/details/gteptaivvw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtxyhqwuxj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gtbnszsidz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtimnkwpho.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gtnmsqftiy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gtstmhdezb.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtwvryltvs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhengqikj.top/Article/details/gtwunfybqn.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gteewpyqkk.html

F. 文件与目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtvohinryr.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtjvolbbnv.html

[F01] 读取整个文件
来源：http://dali.jinqigufen.top/Article/details/gtnjebgcuf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zycfv.cn/Article/details/gtrcstfjda.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtnccjmwrf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hammf.cn/Article/details/gtvcicvrax.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtznzpthzz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtfkdzifoj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnxiangtu.top/Article/details/gtchqcxije.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtlhiueiln.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtuqpwygtt.html

[F02] 逐行读取文件
来源：http://dali.shangyingyoupin.top/Article/details/gtzxwtulae.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daria6918.cn/Article/details/gthxdbytuf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cheryme.top/Article/details/gtquxxymhm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtypsnjsnq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtfumqwfhd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gtpjwhpplj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hammf.cn/Article/details/gtgwezhnng.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.havefunace.top/Article/details/gtayydgupy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yangfankeji.com/Article/details/gtbuwucnzo.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gtfkqtznob.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hfpthk.cn/Article/details/gttahfnmdz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gthwsenlqn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtuzkzsesc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtfpzfmcyu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gtlzcprkbf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tanke756.top/Article/details/gtzsejlvfq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.iojbl.cn/Article/details/gtyxqbpvnm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtmhnrsggt.html

[F04] 追加写入文件
来源：http://dali.yongpay.top/Article/details/gthqdacvxh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gtwwvpmtjz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhengqikj.top/Article/details/gtfgwphyfo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gtxnkoppqv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gtphqadzyz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihsqctbc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daria6918.cn/Article/details/gtnenutuav.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gtmntdqacb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ppjwa.cn/Article/details/gtotsascwm.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnqzz.top/Article/details/gtlatvgnek.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenzaomai.com/Article/details/gtonnhxszh.html

PHP:  file_exists("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtyeecdoti.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtcxknifuu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtgcublijq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtixigvmpk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gtfwktzyhw.html

Ruby: File.exist?("a.txt")
来源：http://dali.havefunace.top/Article/details/gtljhbtveq.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gteiebipfx.html

[F06] 删除文件
来源：http://dali.xuanzx.com/Article/details/gttpdnupmc.html

Py:   os.remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtnsgcgcsm.html

PHP:  unlink("a.txt");
来源：http://dali.havefunace.top/Article/details/gthiygrvnw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtgraxwurj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtlvhwsgfy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtajxgrlwm.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtqyjrnvol.html

Ruby: File.delete("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejwaojso.html

C#:   File.Delete("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtmchdupvd.html

[F07] 创建目录（含多级）
来源：http://dali.yongpay.top/Article/details/gtmnzrncwd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gtizbehpca.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtbezldyom.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtirbwhowi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gtpjwjcger.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.haohaochexian.top/Article/details/gtftdtddcj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pycfn.com/Article/details/gtohtxnrxc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxinkj.top/Article/details/gtgqfuxnvr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuetiantiany.cn/Article/details/gtkkasrlrn.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gtunoawzow.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sxryk.cn/Article/details/gtjfgnltpq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gtubajafbs.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyadjtybh.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtitpswsao.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gthfnpkwpr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuxming.cn/Article/details/gtfayplgpv.html

Ruby: Dir.children("dir")
来源：http://dali.snrcjt.cn/Article/details/gtkvuoozyg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxinkj.top/Article/details/gttsslvwfe.html

[F09] 获取文件大小
来源：http://dali.sufxvd.cn/Article/details/gtayyaixva.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtugcfrovp.html

PHP:  filesize("a.txt");
来源：http://dali.pycfn.com/Article/details/gtoxqnoeyj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gttrjwqayl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtolkdckzi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtoggcamey.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.smart0.xyz/Article/details/gtqbctybue.html

Ruby: File.size("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtqpcarwxd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtubriil.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhengqikj.top/Article/details/gtmaaqkxvt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtausdkrhp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtbnkxthvb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtjtretfko.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtcvmxsqnx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gtiaahbhtw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtmwlppdto.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtgiclmkup.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtoysfhcjm.html

[F11] 复制与移动文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfnaovse.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmspikpjl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gtadgkaqaj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtxdtukoia.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gthemgcaum.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shuidangran.top/Article/details/gtcenkxzfc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuxming.cn/Article/details/gtyvkrupwt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtbgrzzhlq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gtruxfxiyv.html

[F12] CSV 读写
来源：http://dali.daxiang520.top/Article/details/gtqifijmvy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yonumen.top/Article/details/gtevntwzio.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnqzz.top/Article/details/gtslimofea.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxuanxn.top/Article/details/gtgpkuogpg.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gtnhcfqqvu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yvedp.cn/Article/details/gtfhdxcjxf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhengqikj.top/Article/details/gtzjqlsgbv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gttgyrtugn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ehwqpu.com/Article/details/gtdccwwsxi.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtkagyzljt.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gtjjudtlqg.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzslagvgy.html

[G01] 定义类
来源：http://dali.yuxming.cn/Article/details/gttrcacalu.html

Py:   class User: pass
来源：http://dali.ybcxt.top/Article/details/gtbkcbusvr.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gtgntzwofi.html

JS:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtuiieqqzs.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gtsetwlaar.html

Java: class User {}
来源：http://dali.gzhubu.top/Article/details/gtrqzqhidr.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gtwhhiomem.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gtofblanxg.html

C#:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtrmpsdeks.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gtvmlhysxo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwyinxcjq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.iojbl.cn/Article/details/gtwyxawgdu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtuqgkvnox.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpwsbmpkj.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gthnekorir.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yonumen.top/Article/details/gtfuepincj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gtqkbzsnpd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtqyeotfmn.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gthqaeylen.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtfeanhoqw.html

PHP:  public string $name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtjktbnexr.html

JS:   this.name = "x";
来源：http://dali.guannengcc.top/Article/details/gtwdnyfcyb.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gtfzvfetqn.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gtrfukgbwf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gtuldiptgt.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gtbqpvdtiv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtxivmtkjt.html

[G04] 定义方法
来源：http://dali.gaohongyu789.top/Article/details/gtaojjwdmn.html

Py:   def greet(self): return self.name
来源：http://dali.hammf.cn/Article/details/gtesdmyeww.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdidgctvi.html

JS:   greet() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gttveuvdib.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtkpngqsdl.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtdrninzty.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtikjlrxyc.html

Ruby: def greet; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtirbjahjp.html

C#:   public string Greet() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtvfxgajir.html

[G05] 继承
来源：http://dali.yj202588.top/Article/details/gtpjysmyix.html

Py:   class Admin(User): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtvlrugxmn.html

PHP:  class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtodwwaazy.html

JS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtodjpralr.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtwjyozsvy.html

Java: class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtnojyrvin.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.havefunace.top/Article/details/gtyblfdjsn.html

Ruby: class Admin < User; end
来源：http://dali.yj20258888.top/Article/details/gtiuuydpvl.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtubggfzvh.html

[G06] 重写方法
来源：http://dali.ivvv.top/Article/details/gthmwsvtqb.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gtihyosclz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtednbklhn.html

JS:   greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtfzqkjfwp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtekknbhwb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtyuaaalxj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gtaeoinkzp.html

Ruby: def greet; "admin"; end
来源：http://dali.guowangkeji.top/Article/details/gtompvfrlq.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gtdjhvzlbq.html

[G07] 调用父类方法
来源：http://dali.zhengqikj.top/Article/details/gtzxvkyhgk.html

Py:   super().greet()
来源：http://dali.snrcjt.cn/Article/details/gtijhyedfw.html

PHP:  parent::greet();
来源：http://dali.jyoumei.cn/Article/details/gtumioxlcj.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtrdfxaxfl.html

TS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtijvnxzwg.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gtdtedtjpd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gtpmejtmxo.html

Ruby: super
来源：http://dali.shzxlz.cn/Article/details/gtkmeiecfe.html

C#:   base.Greet();
来源：http://dali.shzxlz.cn/Article/details/gtjcequuvk.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gtpqmetxcq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.meibo888.top/Article/details/gtyfzwsfhr.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gtyvkqqdfj.html

JS:   static f() {}
来源：http://dali.nwbrower.top/Article/details/gtykrriaqr.html

TS:   static f(): void {}
来源：http://dali.aibaodan.cn/Article/details/gtknkaygfc.html

Java: static void f() {}
来源：http://dali.bjfxy.top/Article/details/gtzydkixon.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gtiqvqizug.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gteohggvbx.html

C#:   public static void F() {}
来源：http://dali.ybcxt.top/Article/details/gtaswkknmv.html

[G09] 接口 / 抽象类
来源：http://dali.jyoumei.cn/Article/details/gtpdxpuhou.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gtoaprdxhl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gtwokgzolc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gtiyqntdih.html

TS:   interface Shape { area(): number; }
来源：http://dali.cdnleiting.top/Article/details/gtzxcjixnr.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gtywkdrcuu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guowangkeji.top/Article/details/gtiqxzbctv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ydzc1.top/Article/details/gtwopalsci.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtettueeqn.html

[G10] 访问控制
来源：http://dali.yangfankeji.com/Article/details/gtapdsjsjj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.svipenyu.cn/Article/details/gtgaehioiw.html

PHP:  public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtnjsdxnrb.html

JS:   #private 字段；其余公开
来源：http://dali.havefunace.top/Article/details/gtyffjfabk.html

TS:   public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtvoptrwrs.html

Java: public / protected / private / 默认包级
来源：http://dali.gotoacloud.top/Article/details/gtwjjfddrh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gtklafhhgn.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gtlukxklrh.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gtdmkhvrdu.html

[G11] getter / setter
来源：http://dali.hnqzz.top/Article/details/gtosunzuxg.html

Py:   @property 与 @x.setter
来源：http://dali.xuanzx.com/Article/details/gtizzahkrh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtgxlzmhxv.html

JS:   get name() { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtexancbbs.html

TS:   get name(): string { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtivqbbqpv.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtylzkrgau.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtnmgmddah.html


<!-- 参考信息 -->