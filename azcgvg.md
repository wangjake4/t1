代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.yonumen.top/Article/details/gtpwbrhlqs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgufenzy.top/Article/details/gtqbwzrska.html

[E08] 数组按分隔符合并
来源：http://dali.shuidangran.top/Article/details/gtrggwsgah.html

Py:   ",".join(items)
来源：http://dali.hnqzz.top/Article/details/gtplgwnxak.html

PHP:  implode(",", $items);
来源：http://dali.yj20258.top/Article/details/gtporjthll.html

JS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtdkpvcxbj.html

TS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtfaobgppv.html

Java: String.join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gtwacgyzoh.html

Go:   strings.Join(items, ",")
来源：http://dali.yuanzhike.top/Article/details/gtpbfnhohr.html

Ruby: items.join(",")
来源：http://dali.xinyue.icu/Article/details/gtflbxkmnm.html

C#:   string.Join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gtgbdmetsx.html

[E09] 去除所有空白字符
来源：http://dali.jinghuilouyu.cn/Article/details/gtwstcdldc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxuanxn.top/Article/details/gtkmuolewh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.havefunace.top/Article/details/gtejeuejel.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtbfmymkbz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gtbztgddwf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gtaqqozdms.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yueranfly.top/Article/details/gthhxknuix.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtbyiavjeg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj202588.top/Article/details/gtzdkmahtb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ivvv.top/Article/details/gtlbzihuzl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtpeogjiku.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.meibo888.top/Article/details/gtxvifihas.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtomtopvvg.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtsamalpyf.html

Java: String.format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gttfhgxtdv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtezvpwvao.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtuweesnks.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnqzz.top/Article/details/gtsshgwunw.html

[E11] 反转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtavytqibo.html

Py:   s[::-1]
来源：http://dali.hammf.cn/Article/details/gtbxbrhneu.html

PHP:  strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtsjuiyfwh.html

JS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtetxydrto.html

TS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtozfdleyz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zycfv.cn/Article/details/gtbtozzrph.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gzhubu.top/Article/details/gtaucnndhn.html

Ruby: s.reverse
来源：http://dali.yj20258888.top/Article/details/gtdxfgfdan.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gtfpqwmwab.html

[E12] 统计某字符出现次数
来源：http://dali.tianlin.xyz/Article/details/gtaimxumth.html

Py:   s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtwxzlwgqh.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigufen.top/Article/details/gtlldtydja.html

JS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtdriwonjq.html

TS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gtsqzkotip.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gaohongyu789.top/Article/details/gttofkkttu.html

Go:   strings.Count(s, "a")
来源：http://dali.shuidangran.top/Article/details/gtufflgkix.html

Ruby: s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtxelphsjz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gtklryfxny.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gtgdezhyla.html

Py:   for ch in s: print(ch)
来源：http://dali.zhengqikj.top/Article/details/gtxcyhpyjn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cucudq.cn/Article/details/gtimdoewml.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtdvhlcvyo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtcpnwuuza.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.316326.xyz/Article/details/gtboprqqta.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cheryme.top/Article/details/gtcfzmtidz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfeujajh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sxryk.cn/Article/details/gtsansdlwj.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkgiypnl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhixingplan.top/Article/details/gtbxyqqgbj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jiagoushi.top/Article/details/gtycievrpc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aizwys.cn/Article/details/gtbvejydfp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhengqikj.top/Article/details/gthnespprn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtybkzaqpy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbahnhuw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cheryme.top/Article/details/gtqrlzxjig.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.bjfxy.top/Article/details/gtnudpajdw.html

[E15] HTML 转义 / 反转义
来源：http://dali.gogol.net.cn/Article/details/gtdgskbhsz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cqqwz.cn/Article/details/gtujznbnsh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktsszrka.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.iojbl.cn/Article/details/gtnbpezqws.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hywenlv.cn/Article/details/gtwgxgjupo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guowangkeji.top/Article/details/gtlfdnuvfz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigufen.top/Article/details/gtledtjdya.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dianchejie.cn/Article/details/gtfhqjlyqy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gtbjvppzpm.html

[E16] 数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtspcdytwy.html

Py:   f"{1234567:,}"
来源：http://dali.ybcxt.top/Article/details/gtyqrwnvcp.html

PHP:  number_format(1234567);
来源：http://dali.havefunace.top/Article/details/gthnfpvigm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamrdvocs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gtrwzudiii.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xinyue.icu/Article/details/gtndaxelbh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shuidangran.top/Article/details/gtgjgjnhdn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.c1oappe.top/Article/details/gtfnqhjmhe.html

C#:   1234567.ToString("N0")
来源：http://dali.redwolf501.top/Article/details/gtmantlwoj.html

[E17] 首字母大写
来源：http://dali.hongshengwenyu.top/Article/details/gtevbioccg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ehwqpu.com/Article/details/gtiwhtsbgy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtngrdfdxi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gtpqkwgypf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtlvsyncpw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.havefunace.top/Article/details/gtompwzeiw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.redwolf501.top/Article/details/gtefhovfju.html

Ruby: s.capitalize
来源：http://dali.bjfxy.top/Article/details/gtpgyhpcft.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jiagoushi.top/Article/details/gttcwmslal.html

[E18] 模板占位符替换
来源：http://dali.feifeiyinyue.top/Article/details/gtocthoild.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.mhx1999.top/Article/details/gtnhthmzpu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yvedp.cn/Article/details/gtsucjofrf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtevnyqntd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtatauiipt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtwaqmoimp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtlycskply.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqlkohdo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ivvv.top/Article/details/gtyjirwxvg.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gtozoqunuo.html

Py:   s.splitlines()
来源：http://dali.zdqjudy.top/Article/details/gtbbtphbpl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ivvv.top/Article/details/gtifypyqgg.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gtksgeeppe.html

TS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gtbtvmtzzv.html

Java: s.lines().toList()
来源：http://dali.xziqi.cn/Article/details/gtxcokexdy.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gtxmezydep.html

Ruby: s.lines
来源：http://dali.yongpay.top/Article/details/gtmragkdhx.html

C#:   s.Split('\n')
来源：http://dali.jinqigfzy.top/Article/details/gtirbcnjgd.html

[E20] 判断字符串是否为空
来源：http://dali.kuanghao11.cn/Article/details/gtayyanwfs.html

Py:   if not s:
来源：http://dali.yonumen.top/Article/details/gtueglwiou.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xylfe.cn/Article/details/gtfxwhamur.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yongpay.top/Article/details/gtqavwkmrp.html

TS:   if (s === "") {}
来源：http://dali.tian-w.cn/Article/details/gtkueynnuk.html

Java: if (s.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gtffollins.html

Go:   if s == "" {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifyifhvz.html

Ruby: if s.empty?
来源：http://dali.tianlin.xyz/Article/details/gtbrfbksdv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnxiangtu.top/Article/details/gtgddrdome.html

[E21] 超长截断加省略号
来源：http://dali.pengpengdd.cyou/Article/details/gtvvmsaqrk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yanxiufei.cn/Article/details/gthbzrzejf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtfwcdgwjf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtxytzioyo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gteeajcefy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtvtjmnojn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258.top/Article/details/gtavtuypzk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gtbghgaokq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtaqhphglq.html

[E22] 字节长度与字符长度
来源：http://dali.kuanghao11.cn/Article/details/gtdxbmmwww.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjpfdqag.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtqmalchcp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gtccvvllyu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gtfokjsnnx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gthjdpwptu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gtrbuflzot.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gtnfafmjyd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ivvv.top/Article/details/gtzsbvjvyl.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtpnxddmuz.html

F. 文件与目录
来源：http://dali.zhengqikj.top/Article/details/gtstreloyr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtrtttgqqh.html

[F01] 读取整个文件
来源：http://dali.smart0.xyz/Article/details/gtjncxapus.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhengqikj.top/Article/details/gtalkqfsdv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gttqqptksh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gtzecejdcc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yonumen.top/Article/details/gtlertswdj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtkoigshjp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ydzc1.top/Article/details/gtnupdnxkz.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtsnfalnrl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gthifzchxr.html

[F02] 逐行读取文件
来源：http://dali.sufxvd.cn/Article/details/gtrituhqan.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gtchymaxxl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgfzy.top/Article/details/gtzjhttoar.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtuatjlczw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtovrlqcnq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gtxpycxzwq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xylfe.cn/Article/details/gtyeivpijw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sysykeji.top/Article/details/gthnulmabe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxinkj.top/Article/details/gttjrxcxgj.html

[F03] 写入文件（覆盖）
来源：http://dali.vqdsnc.cn/Article/details/gtckcvfhih.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtdygdogna.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gtbfzvdqfc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtyfmccids.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtqturrwwk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgfzy.top/Article/details/gtuhilsigw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.feifeiyinyue.top/Article/details/gtstdssxol.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jlsjyb.cn/Article/details/gtbiorefye.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gtradkidxt.html

[F04] 追加写入文件
来源：http://dali.sxryk.cn/Article/details/gtkvldvnbv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtzacemyob.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sweek.top/Article/details/gtauhzjqge.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtxiwzxyxl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gtlpqbqzun.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cdnleiting.top/Article/details/gtpufjyhyl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtxdnuuqdr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuanzhike.top/Article/details/gtwqpejwwa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xylfe.cn/Article/details/gtyersrivh.html

[F05] 判断文件或目录是否存在
来源：http://dali.hammf.cn/Article/details/gteubevzeg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yvedp.cn/Article/details/gtlyunqrlt.html

PHP:  file_exists("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtrdmfphvc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gthwckwnpl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtnkuamymw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtekzydiww.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cucudq.cn/Article/details/gtqloqauav.html

Ruby: File.exist?("a.txt")
来源：http://dali.cashguo.top/Article/details/gtayvxudda.html

C#:   File.Exists("a.txt")
来源：http://dali.hammf.cn/Article/details/gtpddnjshc.html

[F06] 删除文件
来源：http://dali.haohaochexian.top/Article/details/gtngkgbihf.html

Py:   os.remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtrqzevdwr.html

PHP:  unlink("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtrmsrvvcw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtuvcgpdex.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtznrrfkag.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtwycpfqbq.html

Go:   os.Remove("a.txt")
来源：http://dali.sweek.top/Article/details/gtpwomocix.html

Ruby: File.delete("a.txt")
来源：http://dali.yvedp.cn/Article/details/gthbfpzayc.html

C#:   File.Delete("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtklcftkhz.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gttqqmjvab.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gtmenaosen.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhongyouzk.top/Article/details/gtbrrfoejx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gtjotvhktr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtvxtaldiy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gtqccjrdvc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrtabima.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgufenzy.top/Article/details/gtjewndhyf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.316326.xyz/Article/details/gtzpmtjphk.html

[F08] 遍历目录
来源：http://dali.jinqigufen.top/Article/details/gtunoynwhr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gtyvpzzrkl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ydzc1.top/Article/details/gtecbnumna.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtmgbhacxy.html

TS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtghgzxzyg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gttpymptme.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258.top/Article/details/gttahzfklo.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gtrmywpccp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gogol.net.cn/Article/details/gtmbyqtean.html

[F09] 获取文件大小
来源：http://dali.jianghu66.top/Article/details/gtavigiyoq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtanloboby.html

PHP:  filesize("a.txt");
来源：http://dali.redwolf501.top/Article/details/gttyutaqmv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtkroiylys.html

TS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gtnirnecme.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtwwkpztiz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.kuanghao11.cn/Article/details/gtxtcnevup.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtawdmazii.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sysykeji.top/Article/details/gtheasgdtn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenlongwang.top/Article/details/gtncltevzc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtgkfoeiaw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj202588.top/Article/details/gtyxxhozbm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtllyhzstz.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtdkmfjivc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnxiangtu.top/Article/details/gtiahfnktb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaomjklal.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbpvhrpx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtuqzuctyk.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gtdwadfglb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtiuzevjcs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.smart0.xyz/Article/details/gtqckdrfnq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gttppvfwvz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkggdyuh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtulbkwpnm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.quarkkingdee.top/Article/details/gtsoywwvsi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtazstxepy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gtjktuvode.html

[F12] CSV 读写
来源：http://dali.birdmap.top/Article/details/gturkrpekn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aizwys.cn/Article/details/gthejxdgac.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xylfe.cn/Article/details/gtipevebco.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gtgsphzoda.html

TS:   // 同上
来源：http://dali.tianlin.xyz/Article/details/gtmypfvflx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gthfnyhhru.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cheryme.top/Article/details/gtbwkupemz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjxjsumf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gtdelbjxsk.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzlrpvmo.html

G. 面向对象
来源：http://dali.zdqjudy.top/Article/details/gtspfbycas.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtzpphmmxp.html

[G01] 定义类
来源：http://dali.yvedp.cn/Article/details/gtljddcdup.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gtxuvlmkix.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gtazmpumav.html

JS:   class User {}
来源：http://dali.meibo888.top/Article/details/gtlpjpmqqc.html

TS:   class User { name: string = ""; }
来源：http://dali.fengsongda.top/Article/details/gtiwdtrzld.html

Java: class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtlseajqie.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gtabicwqbw.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gtydglljun.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtzfpnvwpd.html

[G02] 构造函数
来源：http://dali.c1oappe.top/Article/details/gtajhlhvhm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangtech.top/Article/details/gtytlynewj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhengqikj.top/Article/details/gtbxclnsct.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gthszmmyzi.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258.top/Article/details/gtkkwhnbku.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtvqoeiqzd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttiwjqum.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ydzc1.top/Article/details/gtmvtjxygg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnqzz.top/Article/details/gtmvuzcbss.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gtdvppical.html

Py:   self.name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtzcjdupms.html

PHP:  public string $name = "x";
来源：http://dali.hammf.cn/Article/details/gtjefpgxba.html

JS:   this.name = "x";
来源：http://dali.tanke756.top/Article/details/gtxxcktchl.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gtzdtzkkyc.html

Java: private String name;
来源：http://dali.pengpengdd.cyou/Article/details/gtyrhxfiwo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuxming.cn/Article/details/gtigqfoicp.html

Ruby: @name = "x"
来源：http://dali.yueranfly.top/Article/details/gthqwrklnb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhengqikj.top/Article/details/gtrcjwletg.html

[G04] 定义方法
来源：http://dali.yvedp.cn/Article/details/gtwyjrgpgw.html

Py:   def greet(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gtdxqqqxwe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtphlkikmi.html

JS:   greet() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtfstfztmf.html

TS:   greet(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtghpaayzh.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtzsbcfsos.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtbojcrvbq.html

Ruby: def greet; @name; end
来源：http://dali.havefunace.top/Article/details/gtfkzpmlol.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gtztvwxqac.html

[G05] 继承
来源：http://dali.9152youxi.cn/Article/details/gtecfqthdo.html

Py:   class Admin(User): pass
来源：http://dali.cdnleiting.top/Article/details/gtcknqthpr.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtxbhvagsh.html

JS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtfvvqkgwk.html

TS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gttsfqhhpm.html

Java: class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtexmcaspq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.vqdsnc.cn/Article/details/gtusbaznaw.html

Ruby: class Admin < User; end
来源：http://dali.wangdashe.top/Article/details/gthrcdmxdu.html

C#:   class Admin : User {}
来源：http://dali.chenjidiqi.icu/Article/details/gthjlfauwx.html

[G06] 重写方法
来源：http://dali.yj20258888.top/Article/details/gtjidrguvk.html

Py:   def greet(self): return "admin"
来源：http://dali.hammf.cn/Article/details/gtxfdlplqh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtzwsvntpc.html

JS:   greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtnwbczhrk.html


<!-- 参考信息 -->