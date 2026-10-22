代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gtcdyaqegs.html

[E11] 反转字符串
来源：http://dali.sufxvd.cn/Article/details/gtuhgxfuya.html

Py:   s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtvvqwmxvi.html

PHP:  strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtnrmbhxsk.html

JS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtcfxscyie.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnwifdmm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gthoyiovig.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtpdscofjd.html

Ruby: s.reverse
来源：http://dali.hnqzz.top/Article/details/gtnsyisueu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gtajunijac.html

[E12] 统计某字符出现次数
来源：http://dali.sysykeji.top/Article/details/gtxstzymsl.html

Py:   s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtmibmwxqr.html

PHP:  substr_count($s, "a");
来源：http://dali.daxiang520.top/Article/details/gtavkbepqk.html

JS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gtfacsfivy.html

TS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gtnuucfjyy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ydzc1.top/Article/details/gttqebturj.html

Go:   strings.Count(s, "a")
来源：http://dali.sufxvd.cn/Article/details/gtdlpiynqs.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtexubhdzo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gtplsegnun.html

[E13] 逐字符遍历
来源：http://dali.meibo888.top/Article/details/gtllihpjpb.html

Py:   for ch in s: print(ch)
来源：http://dali.aizwys.cn/Article/details/gtxofsbsny.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.quarkkingdee.top/Article/details/gtjautstxe.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtfxgkacwk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtnnpzqtim.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuxming.cn/Article/details/gtdftwpxfx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.quarkkingdee.top/Article/details/gtpzmmomnu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.vqdsnc.cn/Article/details/gtsvnhonel.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtaxobktfa.html

[E14] URL 编码与 Base64
来源：http://dali.sweek.top/Article/details/gtjfqoffmg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.haohaochexian.top/Article/details/gtfzguvlra.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hfpthk.cn/Article/details/gtxunwlghk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tianlin.xyz/Article/details/gtquduxbii.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtietizicw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtjgaykwsg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yueranfly.top/Article/details/gtgphvmolz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tianlin.xyz/Article/details/gtifsnkosg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuxming.cn/Article/details/gtjajgndaw.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuanzhike.top/Article/details/gtewghvudz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigfzy.top/Article/details/gtlgsvdvga.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.0kj1m.cn/Article/details/gtvrsevejv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gtdmrijlaf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jlsjyb.cn/Article/details/gttnaafsmq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nwbrower.top/Article/details/gtdtkagdpn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gthrydmmnr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhongyouzk.top/Article/details/gtjxhwlkqr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigufen.top/Article/details/gtuoiwnrkj.html

[E16] 数字千分位
来源：http://dali.ehwqpu.com/Article/details/gtmsdmptvl.html

Py:   f"{1234567:,}"
来源：http://dali.cdnleiting.top/Article/details/gtipcjjyut.html

PHP:  number_format(1234567);
来源：http://dali.svipenyu.cn/Article/details/gtgfcjlnfa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gtmfoeydnl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtrmzxhqqo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.redwolf501.top/Article/details/gttuucmzwv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangshuangyany.cn/Article/details/gtugjiujzc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.c1oappe.top/Article/details/gttewmlnee.html

C#:   1234567.ToString("N0")
来源：http://dali.yongpay.top/Article/details/gtsvauxoxs.html

[E17] 首字母大写
来源：http://dali.ivvv.top/Article/details/gtrsirgsuw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yangfankeji.com/Article/details/gtjncnzlys.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gtyyrekqkq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtfvowmsad.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrstycja.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jianghu66.top/Article/details/gtiodlhvxh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.bjfxy.top/Article/details/gtzuuceeyx.html

Ruby: s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gtogpcqusq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hongshengwenyu.top/Article/details/gtchajyujv.html

[E18] 模板占位符替换
来源：http://dali.havefunace.top/Article/details/gtikaenklg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.snrcjt.cn/Article/details/gtugpubmoa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.c1oappe.top/Article/details/gtpkwzbbeo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtjejwmfdr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtbvcrilte.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtlvfubxpo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtosgqhhfk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jlsjyb.cn/Article/details/gtwytncjnb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.0kj1m.cn/Article/details/gtgkmxnmqp.html

[E19] 多行文本按行拆分
来源：http://dali.meibo888.top/Article/details/gtfuzjetcl.html

Py:   s.splitlines()
来源：http://dali.jqgufenzy.top/Article/details/gthvilenqj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtqzhdnqcq.html

JS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtfzwppnok.html

TS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gttvcbwqut.html

Java: s.lines().toList()
来源：http://dali.gogol.net.cn/Article/details/gtnvwmsjqe.html

Go:   strings.Split(s, "\n")
来源：http://dali.jianghu66.top/Article/details/gtwcbywzxy.html

Ruby: s.lines
来源：http://dali.jiagoushi.top/Article/details/gteopjicea.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gtjodvlqvn.html

[E20] 判断字符串是否为空
来源：http://dali.tanke756.top/Article/details/gtoltdzvbl.html

Py:   if not s:
来源：http://dali.daxiang520.top/Article/details/gtdnvgbsdk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gzhubu.top/Article/details/gtlxnardnw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tian-w.cn/Article/details/gtxneycfme.html

TS:   if (s === "") {}
来源：http://dali.jyoumei.cn/Article/details/gtbysjqoha.html

Java: if (s.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtpdwhrurs.html

Go:   if s == "" {}
来源：http://dali.xuanzx.com/Article/details/gthwczzbvb.html

Ruby: if s.empty?
来源：http://dali.daria6918.cn/Article/details/gthcxzypdt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgfzy.top/Article/details/gtwssskkma.html

[E21] 超长截断加省略号
来源：http://dali.daxiang520.top/Article/details/gtdtqzghai.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jiagoushi.top/Article/details/gttvewhcdi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtdinetqpq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtjjsfnayn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gteybbkibx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtloilehfo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhixingplan.top/Article/details/gtewureqze.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtjuoefmrh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtcutmtlmt.html

[E22] 字节长度与字符长度
来源：http://dali.cucudq.cn/Article/details/gtbtcktmke.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zycfv.cn/Article/details/gtfwaspssx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtbjdnbdux.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtzbmiyjzw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gtjwbyrkja.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yueranfly.top/Article/details/gtsvhpyxog.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.kuanghao11.cn/Article/details/gtrtushmun.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwytntda.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajzcdhfh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtitbcnqtg.html

F. 文件与目录
来源：http://dali.hnqzz.top/Article/details/gtkxnkbtpk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtldtvildj.html

[F01] 读取整个文件
来源：http://dali.jianghu66.top/Article/details/gtlqnyzrvj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuxming.cn/Article/details/gtlzsstbeo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtgydzommc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gtuteqvosu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcuqkrfi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtofnjscpb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sweek.top/Article/details/gtawmrscfw.html

Ruby: File.read("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtwzbewjeq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtetqljwjd.html

[F02] 逐行读取文件
来源：http://dali.yuxming.cn/Article/details/gtiytmjrxc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gtpvtokrqd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tanke756.top/Article/details/gtsdyvohfp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtsipnaehp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtixqvwxwf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtxhwupvgr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gtdevvrcum.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dianchejie.cn/Article/details/gtbpymjzfx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhoulong.xyz/Article/details/gtaasaypeg.html

[F03] 写入文件（覆盖）
来源：http://dali.hfpthk.cn/Article/details/gtkbpvoacq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sysykeji.top/Article/details/gtbcppmfdt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtufolwznh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtqiudlkxy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtkufleonq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtjbucmjen.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenzaomai.com/Article/details/gtzcybglkl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.redwolf501.top/Article/details/gtxhdgarwe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtqtsbfatl.html

[F04] 追加写入文件
来源：http://dali.shangyingyoupin.top/Article/details/gtomqnvyrb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hammf.cn/Article/details/gtmoxzprci.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dashuyun.cn/Article/details/gtnafyhazo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gtjonnytqs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtjayuqmgo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gtonrfrbzw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.redwolf501.top/Article/details/gttqkabxqt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jianghu66.top/Article/details/gtdyfpjwgo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jlsjyb.cn/Article/details/gtdzjgdahe.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gtxaarcbnr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigufen.top/Article/details/gtqoyxvidz.html

PHP:  file_exists("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtjwdbrnkg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtoaqvfeff.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtvhklnpql.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtvnmiypjo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jianghu66.top/Article/details/gtikbhhyif.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtjyfrworz.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gtczrbnhve.html

[F06] 删除文件
来源：http://dali.wangshuangyany.cn/Article/details/gtdqjzdsvc.html

Py:   os.remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtogqqasee.html

PHP:  unlink("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtvgzclmsp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtwvzregdl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtpjjltotd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtoyohwxuk.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvzzhiyc.html

Ruby: File.delete("a.txt")
来源：http://dali.fzhhl.top/Article/details/gttscbelsl.html

C#:   File.Delete("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtfxtrivsc.html

[F07] 创建目录（含多级）
来源：http://dali.havefunace.top/Article/details/gtwjoffeju.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gtqczfwfyf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jianghu66.top/Article/details/gtbhvslcna.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gtkusjwouw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gtplaoszmx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hongshengwenyu.top/Article/details/gtbtjrlqtf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfnbdkul.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dianchejie.cn/Article/details/gtxvcrsysg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuetiantiany.cn/Article/details/gtfftldihk.html

[F08] 遍历目录
来源：http://dali.cheryme.top/Article/details/gtgfwjzdva.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.quarkkingdee.top/Article/details/gtwhluwkyz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sweek.top/Article/details/gtpmnrisem.html

JS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtkxblpvry.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gtbhddvjpr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtajjgrvle.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ppjwa.cn/Article/details/gtrwjjcrvm.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gtnndcodps.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtnansowni.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gtncctuoqg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtfjnmxsfb.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtdxkcqdog.html

JS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gttwbdidvt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gtdjuowrqb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtgutuuype.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttngcjgcv.html

Ruby: File.size("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtldifjlgb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gtwucaoscp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.meibo888.top/Article/details/gtxrvsqnqb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtgdrmycjx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtprkktwmg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtdztsmhju.html

TS:   path.extname("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtyepjyjgb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gtudacuvmh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtnpbtmaoe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gthfnmudeb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtenanhcid.html

[F11] 复制与移动文件
来源：http://dali.yuxming.cn/Article/details/gtottlcazr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gttngxfsqj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtrwhheiiq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtclcmxvqw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtjsepcqqz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yueranfly.top/Article/details/gtusqbclgp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cucudq.cn/Article/details/gtuqanhbou.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtlepwclvb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gzhubu.top/Article/details/gtmrrfelpz.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjvulioc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnqzz.top/Article/details/gtvsmqlljz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gtapwxhnma.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ivvv.top/Article/details/gtinyuuqlp.html

TS:   // 同上
来源：http://dali.bjfxy.top/Article/details/gtewijrwra.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gtuedxthhe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zdqjudy.top/Article/details/gtygclwqio.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aizwys.cn/Article/details/gtabtfswyh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.havefunace.top/Article/details/gtzgtzljvc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtwzgzdvnd.html

G. 面向对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozsygphb.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtzcjuteeu.html

[G01] 定义类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwkjmzmv.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gtpertrlib.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gtmsronrvm.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtrqjyapzv.html

TS:   class User { name: string = ""; }
来源：http://dali.hnxiangtu.top/Article/details/gtxdadvcaw.html

Java: class User {}
来源：http://dali.cucudq.cn/Article/details/gtqxzhwtmt.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gtejujyhgn.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gtykjcxsqg.html

C#:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtshybxpvv.html

[G02] 构造函数
来源：http://dali.c1oappe.top/Article/details/gtalkzdeiy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.feifeiyinyue.top/Article/details/gtvmcyotsj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gtjaozgden.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgtpeccr.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gtdyjtplnb.html

Java: User(String name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtfxuidnwt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtwfktpi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gtydafdtgv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtaujqsxhi.html

[G03] 实例属性
来源：http://dali.dianchejie.cn/Article/details/gtlbrybdjk.html

Py:   self.name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gtgzvblxxk.html

PHP:  public string $name = "x";
来源：http://dali.smart0.xyz/Article/details/gtwqjrgmzu.html

JS:   this.name = "x";
来源：http://dali.birdmap.top/Article/details/gtmrypyqtp.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gtnpzoothe.html

Java: private String name;
来源：http://dali.gotoacloud.top/Article/details/gtsmauvveh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gtomclcryk.html

Ruby: @name = "x"
来源：http://dali.guowangkeji.top/Article/details/gtavpsfcec.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtrsrnkatu.html

[G04] 定义方法
来源：http://dali.fengsongda.top/Article/details/gtovouhvpi.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwnddpxl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gttmaokijv.html

JS:   greet() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtlesipfwa.html

TS:   greet(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtyhwflypm.html

Java: String greet() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtvglnruvy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtvmgehsuv.html

Ruby: def greet; @name; end
来源：http://dali.daxiang520.top/Article/details/gtvjiplrry.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gtklcqfndu.html

[G05] 继承
来源：http://dali.nanxinkj.top/Article/details/gtayqtncef.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gtvgnsatop.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqrysugl.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtlookckok.html

TS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtuxrkgevz.html

Java: class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtdgbhpwgw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gogol.net.cn/Article/details/gtvylmydmo.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gtukixkzol.html

C#:   class Admin : User {}
来源：http://dali.sxryk.cn/Article/details/gthklcnndr.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gtefbjbnom.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtdurzhsmb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtlgaxgacj.html

JS:   greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtfjswzdpx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gteyxbmtwa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtpjfjhhjd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gtodblmvay.html

Ruby: def greet; "admin"; end
来源：http://dali.9152youxi.cn/Article/details/gteimtdfxi.html

C#:   public override string Greet() => "admin";
来源：http://dali.hfpthk.cn/Article/details/gtilmnvwpe.html

[G07] 调用父类方法
来源：http://dali.chenjidiqi.icu/Article/details/gtxrzlmnld.html

Py:   super().greet()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbxijdfq.html

PHP:  parent::greet();
来源：http://dali.jiagoushi.top/Article/details/gtlnpxawgv.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtgelpcoub.html

TS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtsmmpooxd.html

Java: super.greet();
来源：http://dali.fzhhl.top/Article/details/gtmlpdrlnp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jyoumei.cn/Article/details/gtinlhwpjm.html

Ruby: super
来源：http://dali.ybcxt.top/Article/details/gtzvdewkln.html

C#:   base.Greet();
来源：http://dali.quarkkingdee.top/Article/details/gtakloeavf.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gtdtufoxae.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gtdmqizsyz.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gtatqwajst.html

JS:   static f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaozjdjkv.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gtolzgskig.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gtutsjtgms.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfthsfkmz.html

Ruby: def self.f; end
来源：http://dali.yangfankeji.com/Article/details/gtdvytvjdg.html

C#:   public static void F() {}
来源：http://dali.yangfankeji.com/Article/details/gtfdkosavg.html

[G09] 接口 / 抽象类
来源：http://dali.nanxinkj.top/Article/details/gtzzvlluhu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tian-w.cn/Article/details/gtltjapucq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jyoumei.cn/Article/details/gtrxgcxrsl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgfzy.top/Article/details/gtfredqiaf.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gtrssuqpbp.html


<!-- 参考信息 -->