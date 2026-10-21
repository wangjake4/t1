代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.meibo888.top/Article/details/gtocjkgoye.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hfpthk.cn/Article/details/gtdzcaautc.html

[E08] 数组按分隔符合并
来源：http://dali.ybcxt.top/Article/details/gtuupoxpqt.html

Py:   ",".join(items)
来源：http://dali.fengsongda.top/Article/details/gtcffqthja.html

PHP:  implode(",", $items);
来源：http://dali.ydzc1.top/Article/details/gthfmmidmi.html

JS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtfbnhzjpi.html

TS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtqjoccajl.html

Java: String.join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gtthvfrwcd.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtupbapizg.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtzzyyrfid.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsvksaix.html

[E09] 去除所有空白字符
来源：http://dali.aizwys.cn/Article/details/gtxahipfbt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yvedp.cn/Article/details/gtlsawhwhf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sxryk.cn/Article/details/gtieaojojr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gtbyjqowwf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskbzfdxs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cucudq.cn/Article/details/gtwblgpbmp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmuqloke.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.meibo888.top/Article/details/gtcsvnuiul.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gtktddyauf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xinyue.icu/Article/details/gtpznaxwjf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gthhwjfrft.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gthilvufpy.html

JS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtjgpggxmh.html

TS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtvoydrwbl.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsepbvyfd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtvvvhhjpz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtqefpjgtr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.snrcjt.cn/Article/details/gtsfmzwgds.html

[E11] 反转字符串
来源：http://dali.andypj.xyz/Article/details/gtuurjbmao.html

Py:   s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtopcrhqop.html

PHP:  strrev($s);
来源：http://dali.redwolf501.top/Article/details/gtjztczplo.html

JS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtcfuhzoda.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtjykxwwkm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtiwindyft.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jianghu66.top/Article/details/gtffjajikg.html

Ruby: s.reverse
来源：http://dali.pycfn.com/Article/details/gtqvlouiwf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gtfnxjcexp.html

[E12] 统计某字符出现次数
来源：http://dali.nanxuanxn.top/Article/details/gtsvrlugfk.html

Py:   s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gtrgccifcd.html

PHP:  substr_count($s, "a");
来源：http://dali.daxiang520.top/Article/details/gtmfdloffb.html

JS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrbolobr.html

TS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtvnrnoklj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.meibo888.top/Article/details/gtmfsygbom.html

Go:   strings.Count(s, "a")
来源：http://dali.aibaodan.cn/Article/details/gtgssrafdz.html

Ruby: s.count("a")
来源：http://dali.cucudq.cn/Article/details/gtixmvnyzu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtfcrtrv.html

[E13] 逐字符遍历
来源：http://dali.yongpay.top/Article/details/gtonucobil.html

Py:   for ch in s: print(ch)
来源：http://dali.feifeiyinyue.top/Article/details/gthfatvjvt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cdnleiting.top/Article/details/gtgygigjpf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gtrnjmgzyf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgddvfnbm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xziqi.cn/Article/details/gtslwxjxcp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtchxbeens.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhixingplan.top/Article/details/gttxonmiip.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtcyayehcw.html

[E14] URL 编码与 Base64
来源：http://dali.tianlin.xyz/Article/details/gtkqkpgkwx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gtaldompbf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dianchejie.cn/Article/details/gtporyusey.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvnujgqd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cucudq.cn/Article/details/gtkbeanppg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtvhaueeya.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigfzy.top/Article/details/gtzhsgoxsn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258888.top/Article/details/gtprxonqpr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyupxleu.html

[E15] HTML 转义 / 反转义
来源：http://dali.yangfankeji.com/Article/details/gthkhsoapn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yvedp.cn/Article/details/gtgqihyjnl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdrrpscx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.mhx1999.top/Article/details/gtvuatbztv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jyoumei.cn/Article/details/gtiwglmhrg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sweek.top/Article/details/gtxlltmgxt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenzaomai.com/Article/details/gtxomtefeu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenlongwang.top/Article/details/gtfixiyily.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgufenzy.top/Article/details/gtkkeifcfc.html

[E16] 数字千分位
来源：http://dali.dianchejie.cn/Article/details/gtftcemsrs.html

Py:   f"{1234567:,}"
来源：http://dali.yuxming.cn/Article/details/gtixjmccov.html

PHP:  number_format(1234567);
来源：http://dali.9152youxi.cn/Article/details/gtqoftsrfg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gthiaboyto.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gtgiluwwxu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.havefunace.top/Article/details/gtphmtvcrj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgufenzy.top/Article/details/gtflitkdjc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258.top/Article/details/gtysyfwtjd.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmhshqiw.html

[E17] 首字母大写
来源：http://dali.sxryk.cn/Article/details/gtjigvyxst.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zdqjudy.top/Article/details/gttawtjuna.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gtgalnuhzs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aizwys.cn/Article/details/gtwswuiefv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gtjaouxfqw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuanzx.com/Article/details/gtlajauecr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258.top/Article/details/gtozsdehnu.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gtayyrhgsj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gtcdcvsazq.html

[E18] 模板占位符替换
来源：http://dali.iojbl.cn/Article/details/gtwsvxivii.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gotoacloud.top/Article/details/gtknwesorl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aizwys.cn/Article/details/gtbqllkbat.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gthqvgxmcc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtyleerwwi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtvvyhtmfw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yongpay.top/Article/details/gtmojulloi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tianlin.xyz/Article/details/gtjtbkupob.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gtrhcnqtoj.html

[E19] 多行文本按行拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtpwnfbshu.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gtoyrdenzg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtlbblvyio.html

JS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtooptipxm.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gtwsdgyqew.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gtxczsherl.html

Go:   strings.Split(s, "\n")
来源：http://dali.sufxvd.cn/Article/details/gtejpulmyp.html

Ruby: s.lines
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfaafjbuy.html

C#:   s.Split('\n')
来源：http://dali.zhongyouzk.top/Article/details/gtpxbahlvu.html

[E20] 判断字符串是否为空
来源：http://dali.zycfv.cn/Article/details/gtukfnzkon.html

Py:   if not s:
来源：http://dali.wangdashe.top/Article/details/gtprezwlkk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tanke756.top/Article/details/gthkukxcse.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gtvqsjcahy.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gteovwluhw.html

Java: if (s.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gtoulkcrtj.html

Go:   if s == "" {}
来源：http://dali.haohaochexian.top/Article/details/gtjdasmsgb.html

Ruby: if s.empty?
来源：http://dali.gogol.net.cn/Article/details/gtsoekavbd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.c1oappe.top/Article/details/gtdtajywim.html

[E21] 超长截断加省略号
来源：http://dali.0kj1m.cn/Article/details/gtmbmknetn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuanzhike.top/Article/details/gtajkregty.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtjibimshi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtgxmtaikq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtldsdeunq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtpezuolsv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ppjwa.cn/Article/details/gtzlvoeztl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtagnzuukz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtltxhwzsa.html

[E22] 字节长度与字符长度
来源：http://dali.jlsjyb.cn/Article/details/gtjfbnrumz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gtsayisrke.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtxyyfkzzz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtexnvpyau.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgfjqrni.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuxming.cn/Article/details/gtsbbklvsy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yvedp.cn/Article/details/gtxrgaddja.html

Ruby: s.bytesize;  s.length
来源：http://dali.yonumen.top/Article/details/gttnmivict.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aizwys.cn/Article/details/gtsjwnbwlc.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtjxiqysvq.html

F. 文件与目录
来源：http://dali.hfpthk.cn/Article/details/gtkxjfduji.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtpnebneal.html

[F01] 读取整个文件
来源：http://dali.haohaochexian.top/Article/details/gtqrgvcjzo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cheryme.top/Article/details/gtgdbhungs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpnfgcxu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnqzz.top/Article/details/gtwevqgxgs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtstgnoxbv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtovxvsyyo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuanzhike.top/Article/details/gtbnlpbxyr.html

Ruby: File.read("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtkovhkdyr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtuopjinlk.html

[F02] 逐行读取文件
来源：http://dali.shuidangran.top/Article/details/gtofhftawr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tanke756.top/Article/details/gtayrgzpqw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.dashuyun.cn/Article/details/gtgmkmsqem.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtaezzmplt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gtzinndvqw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtibgyyfwh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnqzz.top/Article/details/gtggochrlb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dianchejie.cn/Article/details/gtomvtabxz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gtzomezfcc.html

[F03] 写入文件（覆盖）
来源：http://dali.hammf.cn/Article/details/gtxlzgkudf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hywenlv.cn/Article/details/gtjormcxqv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtjtxzewvt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gttznpipli.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtowemvqxl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dashuyun.cn/Article/details/gtzyhtvazf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwewwbrh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.havefunace.top/Article/details/gtshsxdaep.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtwxdlwwrk.html

[F04] 追加写入文件
来源：http://dali.sweek.top/Article/details/gtbbsyzpsa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtdqycrtui.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gzhubu.top/Article/details/gtaityfgtd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtlkiuauvc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtgkoqjbjd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nwbrower.top/Article/details/gtfrjlahbv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdolycqf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yonumen.top/Article/details/gtkhwfhgaz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhoulong.xyz/Article/details/gtsqttojid.html

[F05] 判断文件或目录是否存在
来源：http://dali.hfpthk.cn/Article/details/gtbiyoyepb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gtvjugowcq.html

PHP:  file_exists("a.txt");
来源：http://dali.meibo888.top/Article/details/gtmnswkaai.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtppjxnvhc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtprbrgsir.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgzbbbiv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigufen.top/Article/details/gtugsvxboh.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtppijviti.html

C#:   File.Exists("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtmsxtltcu.html

[F06] 删除文件
来源：http://dali.gzhubu.top/Article/details/gtxbkitnav.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfeuhbrqn.html

PHP:  unlink("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtwqwxyixt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtxpcjjgjj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gthqmpukgr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtlixbwota.html

Go:   os.Remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtybwxrbwp.html

Ruby: File.delete("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gthnlamiff.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtcdsqukvr.html

[F07] 创建目录（含多级）
来源：http://dali.cqqwz.cn/Article/details/gtyidoxryp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gtkhfmrbgm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cheryme.top/Article/details/gtuwxyrlky.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gtmwagubah.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gtkxxbqhbz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.vqdsnc.cn/Article/details/gtgidzojxe.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcxrljzv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jlsjyb.cn/Article/details/gtnmdfodxt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.havefunace.top/Article/details/gtbcfqdyfz.html

[F08] 遍历目录
来源：http://dali.daria6918.cn/Article/details/gtlvxbbbgc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ppjwa.cn/Article/details/gtoirzybmu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ybcxt.top/Article/details/gtlubjvjhg.html

JS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtryycpzch.html

TS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtlqgcuphc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gtxzasrgbi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtifiiligx.html

Ruby: Dir.children("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtcynrmqqx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jiagoushi.top/Article/details/gtamvjbwpz.html

[F09] 获取文件大小
来源：http://dali.zycfv.cn/Article/details/gtarmrcrdp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtqcgtcpic.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtphikkrhw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtuhvtlhvz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gtxmogkpst.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtxhitiwus.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gtcfrtlagc.html

Ruby: File.size("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtvcjfepqu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gtdpnuxkji.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.haohaochexian.top/Article/details/gtehnzvxbg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtualmxvga.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.meibo888.top/Article/details/gtxbrdihqo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtmdhdxrrq.html

TS:   path.extname("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtpmspvwnq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.andypj.xyz/Article/details/gtwgfqadyx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtpegjluon.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkamqxieq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtxyfbwhgz.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gtqetgbowv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtatyvpjim.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtzzopuude.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtoamscmgh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtzffcibgw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gtqkllaeba.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cheryme.top/Article/details/gtvrsldivr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtggcccchn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gotoacloud.top/Article/details/gtvdttyxdi.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gtlbuydtnl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenzaomai.com/Article/details/gtqkpdpgwb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gtzpbvpnqv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gtuxnqllsu.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gtrevlmqds.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gtafgwfwok.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.quarkkingdee.top/Article/details/gtqapndldp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.birdmap.top/Article/details/gtdcfgnzhx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sysykeji.top/Article/details/gtozhliciu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtfnofarxa.html

G. 面向对象
来源：http://dali.daria6918.cn/Article/details/gtfbwdvuwk.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtpebfvkpy.html

[G01] 定义类
来源：http://dali.pengpengdd.cyou/Article/details/gtejmeogsv.html

Py:   class User: pass
来源：http://dali.yanxiufei.cn/Article/details/gtgfnmfziq.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtyoesgmoj.html

JS:   class User {}
来源：http://dali.cheryme.top/Article/details/gtpzryurmb.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gtxwfxcxws.html

Java: class User {}
来源：http://dali.andypj.xyz/Article/details/gtfqnocgvl.html

Go:   type User struct { Name string }
来源：http://dali.zhengqikj.top/Article/details/gtvlgnwryp.html

Ruby: class User; end
来源：http://dali.xziqi.cn/Article/details/gtflqqpqii.html

C#:   class User {}
来源：http://dali.ivvv.top/Article/details/gtpxvffcqy.html

[G02] 构造函数
来源：http://dali.c1oappe.top/Article/details/gtzchmtqan.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sweek.top/Article/details/gtglejnkjv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.andypj.xyz/Article/details/gtdkqxuadf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gtkcoysdpf.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gttuneqmgi.html

Java: User(String name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gthitghfql.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gtrztetiqz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hysaishi.cn/Article/details/gtkadtvyqm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtqysbylly.html

[G03] 实例属性
来源：http://dali.yuanzhike.top/Article/details/gtwvcyqxrx.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtczpfpsla.html

PHP:  public string $name = "x";
来源：http://dali.gotoacloud.top/Article/details/gtokutdksh.html

JS:   this.name = "x";
来源：http://dali.redwolf501.top/Article/details/gtvaapjtaf.html

TS:   name: string = "x";
来源：http://dali.hnqzz.top/Article/details/gtrwivgbyu.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gtnygjvgli.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhengqikj.top/Article/details/gtpjlenpjz.html

Ruby: @name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtcbcgozfp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yongpay.top/Article/details/gtmqyukgid.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gteuevxuha.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gtbkecfuao.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gteqmadvhj.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtskoxadvl.html

TS:   greet(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtxfhexylt.html

Java: String greet() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtmyojxzew.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtpcoivehk.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gtmnqdrxls.html

C#:   public string Greet() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtjlvgklzv.html

[G05] 继承
来源：http://dali.nwbrower.top/Article/details/gtimgfpvic.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gtwoojyitx.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtynlgpjqy.html

JS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtlnyzaeyt.html

TS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtmupcboye.html

Java: class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmmdrfrew.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhengqikj.top/Article/details/gtivexgaci.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gtwmjuhuor.html

C#:   class Admin : User {}
来源：http://dali.fengsongda.top/Article/details/gtazwnddfv.html

[G06] 重写方法
来源：http://dali.bjfxy.top/Article/details/gtdpzqoulp.html

Py:   def greet(self): return "admin"
来源：http://dali.daxiang520.top/Article/details/gtcdclvagy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtvlmlyjcd.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtubeifsxj.html


<!-- 参考信息 -->