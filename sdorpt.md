代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.cdnleiting.top/Article/details/gtgwzlzjqe.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxuanxn.top/Article/details/gtzjnekvnv.html

[E08] 数组按分隔符合并
来源：http://dali.havefunace.top/Article/details/gtnhvfmomb.html

Py:   ",".join(items)
来源：http://dali.jlsjyb.cn/Article/details/gtnabgvyry.html

PHP:  implode(",", $items);
来源：http://dali.andypj.xyz/Article/details/gtrujbbxoi.html

JS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskyfgnaw.html

TS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtguwcbwmj.html

Java: String.join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gtykfhoeeh.html

Go:   strings.Join(items, ",")
来源：http://dali.quarkkingdee.top/Article/details/gtkxdbrcky.html

Ruby: items.join(",")
来源：http://dali.guannengcc.top/Article/details/gtloybevth.html

C#:   string.Join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gtvmeqkjiv.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gtkdlevgnj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhixingplan.top/Article/details/gtkdxsgcif.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tianlin.xyz/Article/details/gtyhmnnrnf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gtkbradwlt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtaseznrav.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aizwys.cn/Article/details/gtehefdzea.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.andypj.xyz/Article/details/gtvfaztdxv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ppjwa.cn/Article/details/gtmfirxbqp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sxryk.cn/Article/details/gtlewwtdpp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhiwuduotai.top/Article/details/gtmjbpcrpy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtdubbgovj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nwbrower.top/Article/details/gtrbhgkgpv.html

JS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtkapzvlfd.html

TS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtirtmdlcj.html

Java: String.format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtsamvohkb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtmriwotct.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtspxmxzvc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.iojbl.cn/Article/details/gtpyyaxtnw.html

[E11] 反转字符串
来源：http://dali.cdnleiting.top/Article/details/gtuxzzjztr.html

Py:   s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gtaqtliiqd.html

PHP:  strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqpnlttt.html

JS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtpxnunwhl.html

TS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtzdetjvcv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnqzz.top/Article/details/gtmfhdahbm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtxeeiqojj.html

Ruby: s.reverse
来源：http://dali.aizwys.cn/Article/details/gtjzsrbrgw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gtrxcotmjc.html

[E12] 统计某字符出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gtierxrhtw.html

Py:   s.count("a")
来源：http://dali.yueranfly.top/Article/details/gtfqklkfke.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gtbwdlbsyz.html

JS:   s.split("a").length - 1
来源：http://dali.daria6918.cn/Article/details/gttoowuyla.html

TS:   s.split("a").length - 1
来源：http://dali.zhixingplan.top/Article/details/gtsqtshdov.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.iojbl.cn/Article/details/gtojwbibmo.html

Go:   strings.Count(s, "a")
来源：http://dali.sufxvd.cn/Article/details/gtbblouneh.html

Ruby: s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtyxrrjvgd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj202588.top/Article/details/gtklbqydna.html

[E13] 逐字符遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanojqbxj.html

Py:   for ch in s: print(ch)
来源：http://dali.hnxiangtu.top/Article/details/gtujzkkzqf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnxiangtu.top/Article/details/gtbqmsvonb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gtfydloekx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtnatezscu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hammf.cn/Article/details/gtdxdercul.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilyidddu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhiwuduotai.top/Article/details/gtjdljacaa.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtlzurfpgv.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gthhevxgcg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xylfe.cn/Article/details/gtkxjfvbba.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.haohaochexian.top/Article/details/gtsoxvtytj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yanxiufei.cn/Article/details/gtodshyjpp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xylfe.cn/Article/details/gtyyaxjqoa.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtxvjcogtu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gtvytffjvf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aizwys.cn/Article/details/gtwdhxvhgp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtmfnstjca.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gtiztuxyda.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.smart0.xyz/Article/details/gtwjdzohyt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.andypj.xyz/Article/details/gtxkasbncn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.kuanghao11.cn/Article/details/gtqcbdkazk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hysaishi.cn/Article/details/gtyuqgwbhl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cqqwz.cn/Article/details/gtmacjmtsc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hammf.cn/Article/details/gtlkigapnr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gtogmzljkb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yvedp.cn/Article/details/gtiyltqsur.html

[E16] 数字千分位
来源：http://dali.chenlongwang.top/Article/details/gthyqrlbwi.html

Py:   f"{1234567:,}"
来源：http://dali.vqdsnc.cn/Article/details/gtumipwanh.html

PHP:  number_format(1234567);
来源：http://dali.0kj1m.cn/Article/details/gtrsclwcix.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegpbxnpc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gtipghdzds.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gtbqtumaia.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shzxlz.cn/Article/details/gttzfqydce.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.mhx1999.top/Article/details/gtuuxjxcju.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gtiquzdhmj.html

[E17] 首字母大写
来源：http://dali.guannengcc.top/Article/details/gtsolwwrhu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yanxiufei.cn/Article/details/gtbmiepvyn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zdqjudy.top/Article/details/gteqjsnyyt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtrbniwulq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gtjmfattkm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.redwolf501.top/Article/details/gtsnqqukqs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sweek.top/Article/details/gtaimztcor.html

Ruby: s.capitalize
来源：http://dali.xuanzx.com/Article/details/gtzyyutcwr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.316326.xyz/Article/details/gtwfaphyeu.html

[E18] 模板占位符替换
来源：http://dali.c1oappe.top/Article/details/gtztpsyosn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj202588.top/Article/details/gtmylpwius.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.snrcjt.cn/Article/details/gtvlxbgcmk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtlhoftdso.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtlvexisgv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtgtznqhid.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtemvstlhw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gaohongyu789.top/Article/details/gtafpqbxpz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangshuangyany.cn/Article/details/gtecvvbvwy.html

[E19] 多行文本按行拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtmeoeelup.html

Py:   s.splitlines()
来源：http://dali.hfpthk.cn/Article/details/gtcrcjxrgb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangdashe.top/Article/details/gtiwdkyeik.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gtkkiqrrnj.html

TS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtuftspdrl.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtedfjwjgo.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gtdstonomm.html

Ruby: s.lines
来源：http://dali.gogol.net.cn/Article/details/gtazgsffqy.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gtjomjhgvt.html

[E20] 判断字符串是否为空
来源：http://dali.iojbl.cn/Article/details/gtvwnjzvuk.html

Py:   if not s:
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsmubrzl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.bjfxy.top/Article/details/gtzzmtxrjs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ydzc1.top/Article/details/gtjuxeuxxv.html

TS:   if (s === "") {}
来源：http://dali.hnqzz.top/Article/details/gtrsfggvat.html

Java: if (s.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gtjbzewonc.html

Go:   if s == "" {}
来源：http://dali.shangyingyoupin.top/Article/details/gtodfygbxx.html

Ruby: if s.empty?
来源：http://dali.gzhubu.top/Article/details/gtpmhjuswg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtwhikoinw.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gtugpknjmy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyihvbov.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtreomctws.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtevohsyfw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtiygmgqtb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtwqsqdxyx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cdnleiting.top/Article/details/gtjotaewbd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtlvrfsoom.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtioivtdhx.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktfabsdn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sufxvd.cn/Article/details/gtvmxsxoxu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcaulmgjm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcnmeilu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gtxyrrwgqz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtqjzhqsrs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gtnimkiihp.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gteizdefxd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenzaomai.com/Article/details/gthnqosaez.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtiigkkqhz.html

F. 文件与目录
来源：http://dali.nwbrower.top/Article/details/gtujwicudg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtxyrvhcvg.html

[F01] 读取整个文件
来源：http://dali.yanxiufei.cn/Article/details/gtpkdscvas.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cashguo.top/Article/details/gtuldmjxkh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtlmldiapi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xziqi.cn/Article/details/gtuwjlfuva.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtnqgvrwdn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtuqmrommk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yvedp.cn/Article/details/gteashesva.html

Ruby: File.read("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtnaqnbanj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtdsmltdeh.html

[F02] 逐行读取文件
来源：http://dali.yuanzhike.top/Article/details/gtzbbpsteo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gotoacloud.top/Article/details/gtllvotyzk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gtgqnlllgi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtietzvqnc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtricfntmb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gtretafzau.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhixingplan.top/Article/details/gtvnqffzdz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhoulong.xyz/Article/details/gtouprysfv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gtdctzezqr.html

[F03] 写入文件（覆盖）
来源：http://dali.yvedp.cn/Article/details/gtgxyzvzvz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shzxlz.cn/Article/details/gtstyxzqst.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gtitbwkknw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gtmeemlexj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtklxqgoqv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gteynpvqjm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.kuanghao11.cn/Article/details/gtzcvnghjo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhixingplan.top/Article/details/gtislxsons.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtbupwwgqj.html

[F04] 追加写入文件
来源：http://dali.cqqwz.cn/Article/details/gtkhcrfcdh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoeihcmxq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258.top/Article/details/gtwaspkdxy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gtxdxkabmj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtgqzggqyu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yvedp.cn/Article/details/gtxfmgnnqx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtoucxowjt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sysykeji.top/Article/details/gtwbjhnvrv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gtznxdghpu.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtmxbftyan.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jianghu66.top/Article/details/gtbmycsadd.html

PHP:  file_exists("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivpuzamf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtmoftayin.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtnxxkjvfa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gticbovgnl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gtkglqubrx.html

Ruby: File.exist?("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtbvxxnluv.html

C#:   File.Exists("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtkcsupclk.html

[F06] 删除文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshlwpyco.html

Py:   os.remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtktnyqlba.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpikgbdu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtpckhycrk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtfgxubamf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtbkfjixav.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtlwytupoe.html

Ruby: File.delete("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtdcrbaval.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtlazwucqu.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gtowdlpcmp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxslovsi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ehwqpu.com/Article/details/gtvvgobwgy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtutygpkwc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtreezsmpl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jlsjyb.cn/Article/details/gtlciriicg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangdashe.top/Article/details/gtzafnucng.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.andypj.xyz/Article/details/gtwgubzspi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jlsjyb.cn/Article/details/gtomscukfq.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gtyiyfbqey.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sysykeji.top/Article/details/gtswdxpjvc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tianlin.xyz/Article/details/gtfrphjzmb.html

JS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzexuqqz.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gtkakbgnuu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtprjovgea.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xziqi.cn/Article/details/gtjbzgtchz.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gtxgnojzyh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jianghu66.top/Article/details/gtckbqnufb.html

[F09] 获取文件大小
来源：http://dali.yonumen.top/Article/details/gttynckifq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtgzpjfdrj.html

PHP:  filesize("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtxpncasdh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gtodmgcocz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtolyrmvwy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtagewsxys.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuxming.cn/Article/details/gtmozuxuhj.html

Ruby: File.size("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtgpvmdiiz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tian-w.cn/Article/details/gtszhhnoho.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gtmlaqwsrs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtzhqordee.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtskbyjcvn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtgxcrjabl.html

TS:   path.extname("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtialyuqmu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxuanxn.top/Article/details/gtsimptnfp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtvksygceq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtxnskwwsf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtnucjhkfe.html

[F11] 复制与移动文件
来源：http://dali.mhx1999.top/Article/details/gtdasiuflf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtehcmbqks.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvbjedkn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtkwkushfs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtpdqhazqf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gtpmfjoxvm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yongpay.top/Article/details/gtgeblkvmp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtipkfchqf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.iojbl.cn/Article/details/gtuxsqqzgh.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmueqckv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuxming.cn/Article/details/gtwkjdiwqv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jiagoushi.top/Article/details/gtvxqosdje.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dianchejie.cn/Article/details/gtufnwuljr.html

TS:   // 同上
来源：http://dali.bjfxy.top/Article/details/gtbaaoxncs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gtbaguaruy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhengqikj.top/Article/details/gtypgkgadg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cdnleiting.top/Article/details/gtwcrxmkjl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gtcvbwsaix.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtdqahgqks.html

G. 面向对象
来源：http://dali.dashuyun.cn/Article/details/gtegwqsybk.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtchxqzway.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gtiwkmxoun.html

Py:   class User: pass
来源：http://dali.cqqwz.cn/Article/details/gtaddusfth.html

PHP:  class User {}
来源：http://dali.andypj.xyz/Article/details/gtrsxlntqg.html

JS:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtjaaetezk.html

TS:   class User { name: string = ""; }
来源：http://dali.zycfv.cn/Article/details/gtwfdetvuf.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtqlqoigui.html

Go:   type User struct { Name string }
来源：http://dali.fengsongda.top/Article/details/gtdweipeha.html

Ruby: class User; end
来源：http://dali.yj20258.top/Article/details/gtukvpbjxc.html

C#:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gtvzidyutn.html

[G02] 构造函数
来源：http://dali.hywenlv.cn/Article/details/gtohdcruab.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangdashe.top/Article/details/gtwlxqxzte.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tianlin.xyz/Article/details/gtpazuycpl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gtcmkorofo.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gtqknlbxsu.html

Java: User(String name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtdfnhorgn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gtxhsausam.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gogol.net.cn/Article/details/gtakbqwxcp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xylfe.cn/Article/details/gtpbtakncd.html

[G03] 实例属性
来源：http://dali.snrcjt.cn/Article/details/gtimigacej.html

Py:   self.name = "x"
来源：http://dali.guannengcc.top/Article/details/gtlgbvznar.html

PHP:  public string $name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtcsighifx.html

JS:   this.name = "x";
来源：http://dali.guowangkeji.top/Article/details/gtktkwxgyq.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gtqtustiew.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gtcsfmrgoy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gtrylgybfg.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gthihwwwao.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gtnzjhmwgc.html

[G04] 定义方法
来源：http://dali.daxiang520.top/Article/details/gtjpyfkkky.html

Py:   def greet(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtqtrzvpeb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtxxoguusw.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmjqqrbf.html

TS:   greet(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtcxbxdaye.html

Java: String greet() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtnprvmuwi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtjlsfjbtt.html

Ruby: def greet; @name; end
来源：http://dali.jianghu66.top/Article/details/gtvnxyxoak.html

C#:   public string Greet() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtkwtwfdia.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gtkxlpgpzo.html

Py:   class Admin(User): pass
来源：http://dali.ppjwa.cn/Article/details/gtnuxysbqs.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtlzvfhinu.html

JS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtmwgdvdtc.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtduxdrlug.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdlwxnsy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ehwqpu.com/Article/details/gtmhibfmyn.html

Ruby: class Admin < User; end
来源：http://dali.316326.xyz/Article/details/gttkpqqgjd.html

C#:   class Admin : User {}
来源：http://dali.yj20258888.top/Article/details/gtjnwuxyns.html

[G06] 重写方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtecpatwrz.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gtjmbrqdcb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtzooukkjn.html

JS:   greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtqdhdyudf.html


<!-- 参考信息 -->