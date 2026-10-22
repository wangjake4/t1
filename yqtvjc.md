代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.c1oappe.top/Article/details/gt2lwzyohnv.html

TS:   s.split(",")
来源：http://dali.jinqigufen.top/Article/details/gt2ymwdajbj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sysykeji.top/Article/details/gt2uhgherny.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xylfe.cn/Article/details/gt2wgynxhnu.html

Ruby: s.split(",");  s.split
来源：http://dali.vqdsnc.cn/Article/details/gt2vwczbnnm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xpugiazn.html

[E08] 数组按分隔符合并
来源：http://dali.xylfe.cn/Article/details/gt2sqxxjgze.html

Py:   ",".join(items)
来源：http://dali.yuanzhike.top/Article/details/gt2dgreuvsd.html

PHP:  implode(",", $items);
来源：http://dali.birdmap.top/Article/details/gt2fzmdainp.html

JS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ceipxwpi.html

TS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gt2htacuslu.html

Java: String.join(",", items)
来源：http://dali.guannengcc.top/Article/details/gt2ntxrqwqh.html

Go:   strings.Join(items, ",")
来源：http://dali.yuxming.cn/Article/details/gt2cyimmddg.html

Ruby: items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gt2yzczxfxg.html

C#:   string.Join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gt2wsblnwqo.html

[E09] 去除所有空白字符
来源：http://dali.cheryme.top/Article/details/gt2kpevipko.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258.top/Article/details/gt2jztfsmqo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnqzz.top/Article/details/gt2ohbfkhlj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gt2psejbqac.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gt2dwwicbkj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gt2wswpabkg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gotoacloud.top/Article/details/gt2owmyfelb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ehwqpu.com/Article/details/gt2lufbuodj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hammf.cn/Article/details/gt2vatrgass.html

[E10] 左侧补零 / 定长填充
来源：http://dali.9152youxi.cn/Article/details/gt2hkjavsql.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gt2hafvbxhr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tian-w.cn/Article/details/gt2qturgjzu.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rqkxzhpe.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qnrcqmrk.html

Java: String.format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gt2kwwcrokz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gt2dflneykd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gt2bqilhgyi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.316326.xyz/Article/details/gt2ujfjphjt.html

[E11] 反转字符串
来源：http://dali.yvedp.cn/Article/details/gt2bjggzwns.html

Py:   s[::-1]
来源：http://dali.redwolf501.top/Article/details/gt2itunyqin.html

PHP:  strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2xpsswcmc.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2ctdwstxp.html

TS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2fzmoxhed.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zycfv.cn/Article/details/gt2fhzmawrp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gt2oklshnic.html

Ruby: s.reverse
来源：http://dali.snrcjt.cn/Article/details/gt2iyrcqfho.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gt2skzuyqdi.html

[E12] 统计某字符出现次数
来源：http://dali.quarkkingdee.top/Article/details/gt2jrwbynwz.html

Py:   s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2nyogwutu.html

PHP:  substr_count($s, "a");
来源：http://dali.andypj.xyz/Article/details/gt2talahrbz.html

JS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gt2jjccmvhv.html

TS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gt2zzteahdy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.birdmap.top/Article/details/gt2rpirsscn.html

Go:   strings.Count(s, "a")
来源：http://dali.aibaodan.cn/Article/details/gt2hkokextr.html

Ruby: s.count("a")
来源：http://dali.pycfn.com/Article/details/gt2kpbmgplf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnqzz.top/Article/details/gt2nrjohsox.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gt2jugxviuq.html

Py:   for ch in s: print(ch)
来源：http://dali.jyoumei.cn/Article/details/gt2lfgvkeah.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gt2bllbzdqg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gt2lujahaeb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gt2btvtbsmk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2dwsppgrp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yueranfly.top/Article/details/gt2gqavrelx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gt2fpgbkauz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2yfdkjwtw.html

[E14] URL 编码与 Base64
来源：http://dali.feifeiyinyue.top/Article/details/gt2yqacxlan.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gt2ufmmnfpz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.haohaochexian.top/Article/details/gt2bblvhaxy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.0kj1m.cn/Article/details/gt2xaursmog.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zpbxzwuz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2unlmvbuh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hysaishi.cn/Article/details/gt2gznonvmz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenzaomai.com/Article/details/gt2grxfknkc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258.top/Article/details/gt2vgqzcmrd.html

[E15] HTML 转义 / 反转义
来源：http://dali.quarkkingdee.top/Article/details/gt2gjroekwv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxinkj.top/Article/details/gt2dkakgvzo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.andypj.xyz/Article/details/gt2mliyrinb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhixingplan.top/Article/details/gt2eaozutkd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cheryme.top/Article/details/gt2sajsjfby.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tianlin.xyz/Article/details/gt2krwkiozm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sufxvd.cn/Article/details/gt2xhlewfat.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yongpay.top/Article/details/gt2nhokgbku.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xziqi.cn/Article/details/gt2ojnosssn.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbpauhk.html

Py:   f"{1234567:,}"
来源：http://dali.dashuyun.cn/Article/details/gt2maznbacs.html

PHP:  number_format(1234567);
来源：http://dali.havefunace.top/Article/details/gt2biretqon.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gt2otjbubxt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gt2edeanslx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.andypj.xyz/Article/details/gt2seclcrwh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jiagoushi.top/Article/details/gt2tnmtwksl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2huirumms.html

C#:   1234567.ToString("N0")
来源：http://dali.shuidangran.top/Article/details/gt2fqiyowwx.html

[E17] 首字母大写
来源：http://dali.chenlongwang.top/Article/details/gt2ipjxtbne.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.kuanghao11.cn/Article/details/gt2dgylrxtq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nwbrower.top/Article/details/gt2yxqbbbte.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gt2bbpecfav.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gt2mprfnmzl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangdashe.top/Article/details/gt2nkakfvel.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhongyouzk.top/Article/details/gt2kuvesjlh.html

Ruby: s.capitalize
来源：http://dali.cashguo.top/Article/details/gt2egxiuqbz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hfpthk.cn/Article/details/gt2pwkmxmur.html

[E18] 模板占位符替换
来源：http://dali.hnqzz.top/Article/details/gt2rciyulxw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xziqi.cn/Article/details/gt2ljhbgpyu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hammf.cn/Article/details/gt2bjsmezrj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gt2vxorhwfh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gt2snevpmkk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2jsvlmjnw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zycfv.cn/Article/details/gt2edmqkooi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xylfe.cn/Article/details/gt2dhwdolut.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nwbrower.top/Article/details/gt2dmrpmfnp.html

[E19] 多行文本按行拆分
来源：http://dali.hnqzz.top/Article/details/gt2dlzeuphj.html

Py:   s.splitlines()
来源：http://dali.zycfv.cn/Article/details/gt2qmiuuzvr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2ifnsvqky.html

JS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gt2zzlzrlrj.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gt2kiqbjifn.html

Java: s.lines().toList()
来源：http://dali.9152youxi.cn/Article/details/gt2caoyogyt.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2btipsngi.html

Ruby: s.lines
来源：http://dali.jqgfzy.top/Article/details/gt2fidhhgoq.html

C#:   s.Split('\n')
来源：http://dali.xziqi.cn/Article/details/gt2opfxlxfm.html

[E20] 判断字符串是否为空
来源：http://dali.ivvv.top/Article/details/gt2ooqwgudy.html

Py:   if not s:
来源：http://dali.kuanghao11.cn/Article/details/gt2ngwsxvyp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dashuyun.cn/Article/details/gt2tzydmujc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.smart0.xyz/Article/details/gt2papiared.html

TS:   if (s === "") {}
来源：http://dali.chenlongwang.top/Article/details/gt2leboqhkj.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gt2hqnlkckc.html

Go:   if s == "" {}
来源：http://dali.guannengcc.top/Article/details/gt2qwhcsbyc.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gt2qteggbnl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dashuyun.cn/Article/details/gt2ygbjefdq.html

[E21] 超长截断加省略号
来源：http://dali.aibaodan.cn/Article/details/gt2cvoglpcv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tian-w.cn/Article/details/gt2wbnxmfjx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2mmzacioo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2hslurlle.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gt2wylmjgyf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2onqdxtpq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gt2rpdathar.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2jxobjhyc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2kkfzneqn.html

[E22] 字节长度与字符长度
来源：http://dali.cucudq.cn/Article/details/gt2tjkzzsmi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sufxvd.cn/Article/details/gt2adnkzday.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gt2vtonhadx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gt2rpujdmqu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gt2tsvrsxwg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gt2xjhpydjq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhoulong.xyz/Article/details/gt2ptrjsggb.html

Ruby: s.bytesize;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gt2dtdddegd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenzaomai.com/Article/details/gt2vxfwywyj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2phbuxpft.html

F. 文件与目录
来源：http://dali.daria6918.cn/Article/details/gt2bcjmtcmc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2qowxjqfe.html

[F01] 读取整个文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2iwntmbdu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gt2fxlvggel.html

PHP:  file_get_contents("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2raeaibap.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenzaomai.com/Article/details/gt2rvuswubr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2qqknvbdn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2umhkliyi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nwbrower.top/Article/details/gt2ghaurfpv.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bsobzhmx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2wkordgeu.html

[F02] 逐行读取文件
来源：http://dali.smart0.xyz/Article/details/gt2ygmlzrjq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenzaomai.com/Article/details/gt2obhxeonw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.smart0.xyz/Article/details/gt2twmxfkwu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gt2zpcuhxty.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gt2fuqldcxu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gt2mkihodxm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gt2mwigtwro.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yanxiufei.cn/Article/details/gt2zpzfxxfs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jqgufenzy.top/Article/details/gt2qsvxqssj.html

[F03] 写入文件（覆盖）
来源：http://dali.svipenyu.cn/Article/details/gt2rqvltppz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gzfprggv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gt2eibazkjf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gt2cmekeczn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gt2bpczeuuu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zycfv.cn/Article/details/gt2juagxkzf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gt2heixzkdb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.vqdsnc.cn/Article/details/gt2zonudmhu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gt2xmagxbxr.html

[F04] 追加写入文件
来源：http://dali.redwolf501.top/Article/details/gt2vooygile.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2xnuxlpvj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnxiangtu.top/Article/details/gt2hyisidyf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2dwustnxs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2byrumaqv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuxming.cn/Article/details/gt2taclcpxa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2jizsgkxi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenlongwang.top/Article/details/gt2pvtxhksz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jianghu66.top/Article/details/gt2vhruugik.html

[F05] 判断文件或目录是否存在
来源：http://dali.jyoumei.cn/Article/details/gt2kfpfedvc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ybcxt.top/Article/details/gt2kvmhdviu.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2qbcnikal.html

JS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hcpusvpi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2tvgwyski.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2jardhtsh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2diiztbhi.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fqzjrwwt.html

C#:   File.Exists("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2cktnillb.html

[F06] 删除文件
来源：http://dali.daria6918.cn/Article/details/gt2wekoyqjx.html

Py:   os.remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2otyrdcou.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2aekwxopt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2mcxqsudd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2mdtgjtgu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gt2twbfhhaw.html

Go:   os.Remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2ecajvvju.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gfstyrvv.html

C#:   File.Delete("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2ypkbnbsq.html

[F07] 创建目录（含多级）
来源：http://dali.hysaishi.cn/Article/details/gt2fwodtysd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2examirsz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shzxlz.cn/Article/details/gt2gcesvunf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gt2izzkqkuu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gt2vleufhxt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.mhx1999.top/Article/details/gt2pldutjgv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sysykeji.top/Article/details/gt2hrolesxm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxuanxn.top/Article/details/gt2vforcmmw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gt2cilaxkwn.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gt2tmhehqgs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yanxiufei.cn/Article/details/gt2wupxpncc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xylfe.cn/Article/details/gt2abijgsqq.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2zskbmsik.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gt2dbnrqlri.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gt2npzekoqq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2jfcvkrhz.html

Ruby: Dir.children("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2poofkpuu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2jhozrnei.html

[F09] 获取文件大小
来源：http://dali.xinyue.icu/Article/details/gt2aipzzhmz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfctbmh.html

PHP:  filesize("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2aukdrvxa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gt2khekosgr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gt2rhgjgzww.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2wqnvydmi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gotoacloud.top/Article/details/gt2xwqiemrv.html

Ruby: File.size("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2lgoapyah.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2gtidejhb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gt2ipgmcvab.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2ymqtjyuw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tanke756.top/Article/details/gt2ithyknie.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2yrybvamp.html

TS:   path.extname("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2xoqkuovv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.feifeiyinyue.top/Article/details/gt2yxwqiklu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2azehntqi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2zrnpxnol.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2bcioeeks.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gt2ociurrmx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2nvhffuiu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fzhhl.top/Article/details/gt2unxnussd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gt2ocmcpvvu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2ckihrmem.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gt2lqowlybw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gt2sghcsqgf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gt2dhwkarja.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gqglmyee.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gt2vovqrkoo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gt2sxwubynd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gt2ldtywsae.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gt2ocmapjcg.html

TS:   // 同上
来源：http://dali.ppjwa.cn/Article/details/gt2ytzwlcpv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sweek.top/Article/details/gt2rhngxehd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuxming.cn/Article/details/gt2wttccthb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sxryk.cn/Article/details/gt2vqdtlbrp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxinkj.top/Article/details/gt2ftacqsrr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ezwmwtyn.html

G. 面向对象
来源：http://dali.kuanghao11.cn/Article/details/gt2nyopqkvn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2yqmiglfh.html

[G01] 定义类
来源：http://dali.andypj.xyz/Article/details/gt2szhnlnpn.html

Py:   class User: pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zsdzifqi.html

PHP:  class User {}
来源：http://dali.yvedp.cn/Article/details/gt2nzyapazb.html

JS:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbjfbqix.html

TS:   class User { name: string = ""; }
来源：http://dali.yvedp.cn/Article/details/gt2nlmnxrri.html

Java: class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2zeqwrsxr.html

Go:   type User struct { Name string }
来源：http://dali.haohaochexian.top/Article/details/gt2dletmylp.html

Ruby: class User; end
来源：http://dali.316326.xyz/Article/details/gt2btwoqpuo.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2kpfrobmx.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2urkwoowv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xinyue.icu/Article/details/gt2gidfvodn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2wekubakr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gt2lmqfrdif.html

TS:   constructor(public name: string) {}
来源：http://dali.sysykeji.top/Article/details/gt2bckaqlzy.html

Java: User(String name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gt2miaynwlg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2etmsmlld.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gt2tvptrfyp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pazednye.html

[G03] 实例属性
来源：http://dali.tian-w.cn/Article/details/gt2avqtccft.html

Py:   self.name = "x"
来源：http://dali.aibaodan.cn/Article/details/gt2lhmzhccz.html

PHP:  public string $name = "x";
来源：http://dali.redwolf501.top/Article/details/gt2jfbtlcuu.html

JS:   this.name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gt2gdykkxkr.html

TS:   name: string = "x";
来源：http://dali.daxiang520.top/Article/details/gt2ljxxdrti.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gt2hztubluf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gotoacloud.top/Article/details/gt2lwaecvdz.html

Ruby: @name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gt2atccciel.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gt2flmivetq.html

[G04] 定义方法
来源：http://dali.shuidangran.top/Article/details/gt2kvqhjpyb.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gt2dbyfgjjn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2rabzagye.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2fetajfjq.html

TS:   greet(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2zighpknv.html

Java: String greet() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wfgpdzyx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2tsfowsuv.html

Ruby: def greet; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2uuapjvcs.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258.top/Article/details/gt2uxrjfxfj.html

[G05] 继承
来源：http://dali.wangdashe.top/Article/details/gt2bbkryeew.html

Py:   class Admin(User): pass
来源：http://dali.yj20258.top/Article/details/gt2fbfdgaqy.html

PHP:  class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2jcxhwygp.html

JS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2pvrryxku.html

TS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2wsfvgdhh.html

Java: class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2rorrzovx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangdashe.top/Article/details/gt2uyoxhqcx.html

Ruby: class Admin < User; end
来源：http://dali.0kj1m.cn/Article/details/gt2icezuqjo.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gt2kvvklstc.html


<!-- 参考信息 -->