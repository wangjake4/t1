代发 wailian999

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hammf.cn/Article/details/gtbmbdofqf.html

C#:   s.Substring(1, 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtolktvzxm.html

[E04] 查找子串位置
来源：http://dali.xziqi.cn/Article/details/gtrnhntjcp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gtvgqcuoow.html

PHP:  strpos($s, "x");
来源：http://dali.daxiang520.top/Article/details/gtyavpgder.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhongyouzk.top/Article/details/gtqstidzwi.html

TS:   s.indexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gtboobjume.html

Java: s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtuvlsrkby.html

Go:   strings.Index(s, "x")
来源：http://dali.fengsongda.top/Article/details/gtdlvicqrc.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gtpfbnhfuz.html

C#:   s.IndexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtuvavmolx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhiwuduotai.top/Article/details/gtyzxjanvp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtobwxowow.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqiqpojaq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtdhhivyhq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuanzx.com/Article/details/gtqqylugep.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gtotkodhxe.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.smart0.xyz/Article/details/gtmnyjvxth.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daxiang520.top/Article/details/gtcopcrdpw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtrklkoghh.html

[E06] 替换子串
来源：http://dali.hywenlv.cn/Article/details/gtrdtdpfgx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gtosvdeouz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nwbrower.top/Article/details/gtrjeklhot.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtgeucqget.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtxlvdolio.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtuqxasuko.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gtcrjghpxh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtzbkdimhb.html

C#:   s.Replace("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtaewjxfcp.html

[E07] 按分隔符拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtgfpxthoo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.9152youxi.cn/Article/details/gtuklymmrh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtxyapbfok.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gogol.net.cn/Article/details/gtszdossye.html

TS:   s.split(",")
来源：http://dali.nanxinkj.top/Article/details/gtuweooeck.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tianlin.xyz/Article/details/gtcctnvdcx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gotoacloud.top/Article/details/gtnyqvzfxn.html

Ruby: s.split(",");  s.split
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwohpbdsl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gogol.net.cn/Article/details/gtqoifphsw.html

[E08] 数组按分隔符合并
来源：http://dali.yj202588.top/Article/details/gtydpymxwy.html

Py:   ",".join(items)
来源：http://dali.yuxming.cn/Article/details/gtjbsvgwhg.html

PHP:  implode(",", $items);
来源：http://dali.bjfxy.top/Article/details/gtbwjkditn.html

JS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtjbhmlvxf.html

TS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtazajqlwx.html

Java: String.join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtprjezfjn.html

Go:   strings.Join(items, ",")
来源：http://dali.feifeiyinyue.top/Article/details/gtaoqzfhtl.html

Ruby: items.join(",")
来源：http://dali.guannengcc.top/Article/details/gtuprgxygr.html

C#:   string.Join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gtsihxdhjb.html

[E09] 去除所有空白字符
来源：http://dali.pengpengdd.cyou/Article/details/gtlyqcycic.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj202588.top/Article/details/gtkmtsofjw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yueranfly.top/Article/details/gtimkqghrl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gtetlvhvcv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtxhpmwsbn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gtzsvkyabx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.svipenyu.cn/Article/details/gtwfmrrqlu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gaohongyu789.top/Article/details/gtpgsrmzur.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gtouthdsim.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aizwys.cn/Article/details/gtncdhjmmt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtxhhwhnhx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dashuyun.cn/Article/details/gtivyalcml.html

JS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtdywgiegk.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtqdbgwrys.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtmplyreof.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gteqdzvwhw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtbfauhfru.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhoulong.xyz/Article/details/gtqddlsypm.html

[E11] 反转字符串
来源：http://dali.cqqwz.cn/Article/details/gtwpirgbkc.html

Py:   s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtyhhirbwh.html

PHP:  strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gtqtrxdlho.html

JS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtputncrmn.html

TS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gthbadlzgl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtduehqhss.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daria6918.cn/Article/details/gteczlnmjk.html

Ruby: s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtuzzhqfcw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gtthssaomr.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfygwcef.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gtxokegylj.html

PHP:  substr_count($s, "a");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzocswpe.html

JS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gtfdmwbiqi.html

TS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtksnvzsce.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yvedp.cn/Article/details/gtvbehdgko.html

Go:   strings.Count(s, "a")
来源：http://dali.pycfn.com/Article/details/gtnhlhucqy.html

Ruby: s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtliblorca.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sufxvd.cn/Article/details/gtodhdeacd.html

[E13] 逐字符遍历
来源：http://dali.ivvv.top/Article/details/gtnwxzzjlg.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxuanxn.top/Article/details/gtzslsovko.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shzxlz.cn/Article/details/gtkrfrcxgg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtlfqlwpjh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtypuztqov.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtmtpdymur.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj202588.top/Article/details/gtkmqswgme.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hywenlv.cn/Article/details/gtvjvljore.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtkaiyduas.html

[E14] URL 编码与 Base64
来源：http://dali.316326.xyz/Article/details/gtzluekplf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhixingplan.top/Article/details/gtqfknorqe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.redwolf501.top/Article/details/gtocbdswfh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hywenlv.cn/Article/details/gtvlllpqbz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqstvhcx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtmiolayzr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.9152youxi.cn/Article/details/gtavfpwqmh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ybcxt.top/Article/details/gtjbdjimhf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sxryk.cn/Article/details/gtxquqngxj.html

[E15] HTML 转义 / 反转义
来源：http://dali.hongshengwenyu.top/Article/details/gtfctpgqej.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnqzz.top/Article/details/gtcrdprswq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zycfv.cn/Article/details/gtgbhzvfsc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuxming.cn/Article/details/gtflqvqxbs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gzhubu.top/Article/details/gtbdimrriz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zdqjudy.top/Article/details/gtneyfljnu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gtoskzjdhj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jlsjyb.cn/Article/details/gtfzwvhtiq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tanke756.top/Article/details/gterngshkk.html

[E16] 数字千分位
来源：http://dali.ybcxt.top/Article/details/gtyrfduqbb.html

Py:   f"{1234567:,}"
来源：http://dali.9152youxi.cn/Article/details/gtocfljwar.html

PHP:  number_format(1234567);
来源：http://dali.yanxiufei.cn/Article/details/gtohvemdnm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gtyeeumgtz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gtuibidqda.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hammf.cn/Article/details/gtffvxgntg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj202588.top/Article/details/gtkzkhqxnf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aizwys.cn/Article/details/gtzztowfke.html

C#:   1234567.ToString("N0")
来源：http://dali.chenjidiqi.icu/Article/details/gtzoxmlvrp.html

[E17] 首字母大写
来源：http://dali.zhongyouzk.top/Article/details/gtjpxpvlab.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinghuilouyu.cn/Article/details/gtomfgkvsy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gaohongyu789.top/Article/details/gtmisejbas.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gtpcrfpchr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtkawvknqi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gtknrjnspc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.snrcjt.cn/Article/details/gtarghfqgo.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjvmwyqu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.vqdsnc.cn/Article/details/gtuapfjqab.html

[E18] 模板占位符替换
来源：http://dali.aizwys.cn/Article/details/gthdbinnth.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.0kj1m.cn/Article/details/gtxjvsyigk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gzhubu.top/Article/details/gtuzfvbsrj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtrlfnhdlr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtmnojwvra.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtoiufskrq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtvlkuzaya.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgdzjjuj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daxiang520.top/Article/details/gtchbpwuzf.html

[E19] 多行文本按行拆分
来源：http://dali.cashguo.top/Article/details/gtratqwztn.html

Py:   s.splitlines()
来源：http://dali.cucudq.cn/Article/details/gtvqlvocap.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgblbqtkt.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gteqiwqrvh.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtbcrunmmb.html

Java: s.lines().toList()
来源：http://dali.xuanzx.com/Article/details/gtcwxhgywe.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtnhxjtplw.html

Ruby: s.lines
来源：http://dali.aibaodan.cn/Article/details/gthmmefxao.html

C#:   s.Split('\n')
来源：http://dali.hammf.cn/Article/details/gtizhpppqn.html

[E20] 判断字符串是否为空
来源：http://dali.sxryk.cn/Article/details/gtlcxnqzrn.html

Py:   if not s:
来源：http://dali.cucudq.cn/Article/details/gtaabyiyur.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgufenzy.top/Article/details/gtxpfeuejw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzyscjliq.html

TS:   if (s === "") {}
来源：http://dali.zhixingplan.top/Article/details/gtvcrgpybe.html

Java: if (s.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gtvlkpzjyv.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarotnseq.html

Ruby: if s.empty?
来源：http://dali.jinqigfzy.top/Article/details/gtuwegvjrb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnxiangtu.top/Article/details/gtbagwlnms.html

[E21] 超长截断加省略号
来源：http://dali.ehwqpu.com/Article/details/gtoavklsia.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fzhhl.top/Article/details/gtrdfrxybr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtlvyxdfae.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtkyiopryw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtaawzfjmn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtzjymvcev.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yongpay.top/Article/details/gtchcnfubt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtbndhjiae.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtjgaxzumt.html

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gtczpfjqrw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cucudq.cn/Article/details/gtzkfhnvfk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtvkywzufo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtjqbwhwuf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtjnqbotjx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sxryk.cn/Article/details/gtghgomlyb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.redwolf501.top/Article/details/gtoquypaoq.html

Ruby: s.bytesize;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtfgqyqsqp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gtswrskxpi.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahetqehz.html

F. 文件与目录
来源：http://dali.ppjwa.cn/Article/details/gtnjpjkwsp.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtmjatdgbh.html

[F01] 读取整个文件
来源：http://dali.xziqi.cn/Article/details/gtqiwmbnkm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258.top/Article/details/gtmuqsprvv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtujoqrlmx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jyoumei.cn/Article/details/gtvmelwjaa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtxclhbcvo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtgyvvydnl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gzhubu.top/Article/details/gtafgpogri.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtckbnhoxg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtaxjmpibf.html

[F02] 逐行读取文件
来源：http://dali.tanke756.top/Article/details/gtuygqslxb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ydzc1.top/Article/details/gtaeepopsj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.bjfxy.top/Article/details/gteyhrqlum.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gtkzdihbpj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gtsgnhbrfl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gtrtvxlgst.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ybcxt.top/Article/details/gtlyyljslk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsixrmxah.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.kuanghao11.cn/Article/details/gtnrgbdeut.html

[F03] 写入文件（覆盖）
来源：http://dali.xuetiantiany.cn/Article/details/gtleuxktxb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hysaishi.cn/Article/details/gtwjlriqau.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtmqgmhxme.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtivwmuflu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtbvgpvoav.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jianghu66.top/Article/details/gtarpgwgga.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gtwjyuwdcf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtewsmsrpp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.iojbl.cn/Article/details/gtdeuapsgc.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gtmwgvcmtb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtlvpaegjk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zdqjudy.top/Article/details/gtmvewerqv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gtnfmcfmzh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gttqmosdiu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gtnzvaqpur.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cucudq.cn/Article/details/gthnutndpz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gtoozlrqyy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gtupqwqajr.html

[F05] 判断文件或目录是否存在
来源：http://dali.0kj1m.cn/Article/details/gtlyglfklg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yueranfly.top/Article/details/gtrolcixht.html

PHP:  file_exists("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtceybhyft.html

JS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtykecihue.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtnhoxywpc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtantrugni.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gogol.net.cn/Article/details/gttlonpeyb.html

Ruby: File.exist?("a.txt")
来源：http://dali.meibo888.top/Article/details/gtthjkvslv.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtxqcjlurj.html

[F06] 删除文件
来源：http://dali.zhixingplan.top/Article/details/gtsejiguaw.html

Py:   os.remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtcyvblskz.html

PHP:  unlink("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtvgoukgez.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtbacvoemt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtajkdbxvl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtojslftjc.html

Go:   os.Remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtrliteeuo.html

Ruby: File.delete("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtwfxyasfx.html

C#:   File.Delete("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtwxdoyegf.html

[F07] 创建目录（含多级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufzlaoxw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gtcriekacd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.svipenyu.cn/Article/details/gtqxadxtqj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtuilxlyqk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gtlxkpnalr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gtldciavfw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gtmbstcwid.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gtxldnxjod.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangtech.top/Article/details/gtobniatjh.html

[F08] 遍历目录
来源：http://dali.hysaishi.cn/Article/details/gtdvbxtrwy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cqqwz.cn/Article/details/gtmbveywlm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqidvcfb.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtmvmnhjqs.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtvhfjmlta.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyycyrtsg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hammf.cn/Article/details/gtblkhcgbe.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gtnknattfd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guowangkeji.top/Article/details/gtlzzkuamo.html

[F09] 获取文件大小
来源：http://dali.mhx1999.top/Article/details/gtumzejfdw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pycfn.com/Article/details/gtryneuipf.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gterbvlaon.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gtmihuwrbq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtmvifgrox.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtazbouokg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gtkseviubq.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtujnqmnpo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jianghu66.top/Article/details/gtvjextzpj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ppjwa.cn/Article/details/gtgyqwawyd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtlpwpexrr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtxpjpgieh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtolocwqtr.html

TS:   path.extname("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtovevcqca.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xylfe.cn/Article/details/gtbsxrhmkm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtdjqhvzqk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtkrtzrqru.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtjiihnvtx.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gtcqkacvwo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtnqfcslfk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtzmakbehh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gttzvalwbe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtqdimtlke.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtjodiurua.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnyhfext.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtgdgpeoxq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxuanxn.top/Article/details/gtionvnzxm.html

[F12] CSV 读写
来源：http://dali.jqgufenzy.top/Article/details/gtzmdfrbav.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgufenzy.top/Article/details/gtvsjjzgav.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigufen.top/Article/details/gthfmxvvan.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarinnpam.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtypyddmqa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoatcpxmh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gtqkrgclxt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmpxlemu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwasosrg.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtjzkolkrq.html

G. 面向对象
来源：http://dali.iojbl.cn/Article/details/gtxvbnfurj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gthfzemzez.html

[G01] 定义类
来源：http://dali.jyoumei.cn/Article/details/gtcuvynnur.html

Py:   class User: pass
来源：http://dali.ybcxt.top/Article/details/gtdashvqtj.html

PHP:  class User {}
来源：http://dali.wangdashe.top/Article/details/gtywsijalp.html

JS:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtifsqukil.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbhydikj.html

Java: class User {}
来源：http://dali.daxiang520.top/Article/details/gtizxdqwwc.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gtugbebsec.html

Ruby: class User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxyshptu.html

C#:   class User {}
来源：http://dali.xinyue.icu/Article/details/gthjwgftik.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gtnarsirqz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgufenzy.top/Article/details/gtrfzvdyrw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gtrclzflhz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzrbhvkba.html


<!-- 参考信息 -->