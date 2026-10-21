代发 wailian999

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhengqikj.top/Article/details/gtzbrldqoi.html

[E03] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtrblmdbus.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shangyingyoupin.top/Article/details/gtcffflkby.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtyjeqwmct.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtatoxwfbv.html

TS:   s.slice(1, 4)
来源：http://dali.birdmap.top/Article/details/gtorhsssan.html

Java: s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtmeacqofs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthaxvxvhp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tanke756.top/Article/details/gttupiwgil.html

C#:   s.Substring(1, 3)
来源：http://dali.0kj1m.cn/Article/details/gtyncqjldh.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gtiocgczil.html

Py:   s.find("x");  s.index("x")
来源：http://dali.c1oappe.top/Article/details/gtlpywdiqs.html

PHP:  strpos($s, "x");
来源：http://dali.shangyingyoupin.top/Article/details/gtxxlqswpk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedkjxyyb.html

TS:   s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabtojbgc.html

Java: s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtknnixcua.html

Go:   strings.Index(s, "x")
来源：http://dali.yonumen.top/Article/details/gtrennbjcx.html

Ruby: s.index("x")
来源：http://dali.zycfv.cn/Article/details/gtkjxnujtq.html

C#:   s.IndexOf("x")
来源：http://dali.sweek.top/Article/details/gtncwoyyyz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hywenlv.cn/Article/details/gtdmbbvtnv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenzaomai.com/Article/details/gtzbfdwcvc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cdnleiting.top/Article/details/gtazcuzmmt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtkyonzvgo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258888.top/Article/details/gtvzyvnqoj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtrsrligfo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tanke756.top/Article/details/gtbuhndhkl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tianlin.xyz/Article/details/gtbqkvasvt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gteqhkfllj.html

[E06] 替换子串
来源：http://dali.jinqigufen.top/Article/details/gtqxtazgsz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtbwdeqwco.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ybcxt.top/Article/details/gtffnogndz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtjtsvkbys.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtamuytvnv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtuhafatlx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gtmzmhqtjk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yonumen.top/Article/details/gtyusdhqgx.html

C#:   s.Replace("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtedvutiqc.html

[E07] 按分隔符拆分
来源：http://dali.tanke756.top/Article/details/gtkxqjtyil.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fengsongda.top/Article/details/gtqytbxupu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ivvv.top/Article/details/gtfjltzfqa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgfzy.top/Article/details/gteotfaobx.html

TS:   s.split(",")
来源：http://dali.xylfe.cn/Article/details/gtqzosoaoy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhiwuduotai.top/Article/details/gtyxrwbfwl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.andypj.xyz/Article/details/gtmeabfrtv.html

Ruby: s.split(",");  s.split
来源：http://dali.cqqwz.cn/Article/details/gtgkoxdccg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuezzvtqw.html

[E08] 数组按分隔符合并
来源：http://dali.316326.xyz/Article/details/gtwezekngz.html

Py:   ",".join(items)
来源：http://dali.hfpthk.cn/Article/details/gteyjoorrw.html

PHP:  implode(",", $items);
来源：http://dali.smart0.xyz/Article/details/gtogpzajyx.html

JS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtsqgskluj.html

TS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtychcjmwi.html

Java: String.join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtlnuauwbh.html

Go:   strings.Join(items, ",")
来源：http://dali.zhengqikj.top/Article/details/gtxregkkuz.html

Ruby: items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtihkivlmt.html

C#:   string.Join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtbgncjxhy.html

[E09] 去除所有空白字符
来源：http://dali.cheryme.top/Article/details/gtsdqcnjwe.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gtrgberjwi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jianghu66.top/Article/details/gtskfxavyc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gtcdwpejun.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtvybuhmyr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gtxmlsnyqv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zycfv.cn/Article/details/gtqrbpbjil.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aizwys.cn/Article/details/gtxsgvndxa.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gtkzwipirj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gtkynabfuy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtrcmmaupj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkcbnicv.html

JS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtkulvhocj.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcccxjwia.html

Java: String.format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtbeioboxa.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtmfyztnqb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gtisdopimc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfyhrfug.html

[E11] 反转字符串
来源：http://dali.yueranfly.top/Article/details/gtfhebdufr.html

Py:   s[::-1]
来源：http://dali.xylfe.cn/Article/details/gtlrqpfrvr.html

PHP:  strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gtbrlflluz.html

JS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gthudssyqq.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtumshuifh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sweek.top/Article/details/gtufwtkfyt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtbjwbweph.html

Ruby: s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtamyfgcby.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gtadrcreco.html

[E12] 统计某字符出现次数
来源：http://dali.cdnleiting.top/Article/details/gtuvidobjg.html

Py:   s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gtepzzasff.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtabdwxfyg.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gtwzcsohbm.html

TS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gtrtgoewmc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gtujdzmohb.html

Go:   strings.Count(s, "a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbaifaph.html

Ruby: s.count("a")
来源：http://dali.xylfe.cn/Article/details/gtkohskxxi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.snrcjt.cn/Article/details/gtfixmdkni.html

[E13] 逐字符遍历
来源：http://dali.ppjwa.cn/Article/details/gtlvxugxck.html

Py:   for ch in s: print(ch)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbgmcndz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.iojbl.cn/Article/details/gtopogtkek.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtalthowxo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtrtlivolv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtdxllmpmt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwinvkjns.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hongshengwenyu.top/Article/details/gtixnyjwyy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtisawfxjo.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gtdcscbgsb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gtwoloyzdw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yueranfly.top/Article/details/gtvvxntmmy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.vqdsnc.cn/Article/details/gtanjzuvaw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.pycfn.com/Article/details/gtyrzbdvyw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtflidiaar.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbskbprs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gtvbpogwvr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtwmgpfzuu.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdwesrqc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhengqikj.top/Article/details/gtcsktmtoe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258888.top/Article/details/gtqkqnmqlz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuanzhike.top/Article/details/gtyjjgyseb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guannengcc.top/Article/details/gthtaqxqsl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmrrcilb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajjbxmmj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgufenzy.top/Article/details/gtplhqzfci.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ehwqpu.com/Article/details/gtaispybag.html

[E16] 数字千分位
来源：http://dali.yangfankeji.com/Article/details/gtyrgmqysu.html

Py:   f"{1234567:,}"
来源：http://dali.xuetiantiany.cn/Article/details/gtduwuhdkd.html

PHP:  number_format(1234567);
来源：http://dali.yuxming.cn/Article/details/gthijwdden.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtlzcgrjhg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gtigxzfedi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.meibo888.top/Article/details/gtkztjlhrz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dashuyun.cn/Article/details/gtclxpjhid.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gtjglcobyi.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gtidogsuqm.html

[E17] 首字母大写
来源：http://dali.daxiang520.top/Article/details/gtoikfvden.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cashguo.top/Article/details/gtdynicjci.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtgxhkvbxg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gtyiclzkrn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtpfsozfjt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuanzhike.top/Article/details/gtgewmpzni.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fengsongda.top/Article/details/gtylrvkjmm.html

Ruby: s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gtxbbnkcwh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgfzy.top/Article/details/gtjnygyxaw.html

[E18] 模板占位符替换
来源：http://dali.guowangkeji.top/Article/details/gtjpghcxxp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pycfn.com/Article/details/gtczxfwdnz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhoulong.xyz/Article/details/gtooswnexe.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtxqzclubd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtxbjnczcw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtiiayqwny.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtugeoisms.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sufxvd.cn/Article/details/gtpanlspjd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gteziirxzi.html

[E19] 多行文本按行拆分
来源：http://dali.meibo888.top/Article/details/gtulxqnrys.html

Py:   s.splitlines()
来源：http://dali.dianchejie.cn/Article/details/gtaedoesof.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtrjsbhgpq.html

JS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gtacmwqspp.html

TS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtqtpgadey.html

Java: s.lines().toList()
来源：http://dali.meibo888.top/Article/details/gtpycppzju.html

Go:   strings.Split(s, "\n")
来源：http://dali.0kj1m.cn/Article/details/gtcnasadnm.html

Ruby: s.lines
来源：http://dali.xziqi.cn/Article/details/gtsqtmfito.html

C#:   s.Split('\n')
来源：http://dali.cashguo.top/Article/details/gtkapetakd.html

[E20] 判断字符串是否为空
来源：http://dali.tian-w.cn/Article/details/gtyrxwjiru.html

Py:   if not s:
来源：http://dali.wangdashe.top/Article/details/gthmbhuyzt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigfzy.top/Article/details/gtflkkwytm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cheryme.top/Article/details/gtqwncxcnj.html

TS:   if (s === "") {}
来源：http://dali.fengsongda.top/Article/details/gtcoqhepdi.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtvdqjyaip.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gthekfjhfz.html

Ruby: if s.empty?
来源：http://dali.shuidangran.top/Article/details/gtjkcoowgh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.smart0.xyz/Article/details/gtkogymvud.html

[E21] 超长截断加省略号
来源：http://dali.yvedp.cn/Article/details/gtimofeizk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.redwolf501.top/Article/details/gtahbmpqbz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gttwbqqhqa.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtoyebvkpm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtbgzkpiel.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtgfgcxwjz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.haohaochexian.top/Article/details/gtsdstmysy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtdycgdeqz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtpjtrlbud.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gtfgeiyqhe.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sufxvd.cn/Article/details/gtnthgdvnr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtrberuosr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtrsyhzlde.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtyccjlyiq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtbeoeuiqx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gzhubu.top/Article/details/gtymirkcal.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtamegzeqq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hysaishi.cn/Article/details/gtjifylmqk.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtajpqyfmj.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gtyyxjvofe.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtduxnusfo.html

[F01] 读取整个文件
来源：http://dali.zhixingplan.top/Article/details/gtdhzgwanx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fzhhl.top/Article/details/gtgldonjdp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtrlemzsnr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yonumen.top/Article/details/gtkmeijuik.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pycfn.com/Article/details/gtamhdiljw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtfzdvbvrv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zdqjudy.top/Article/details/gtjgmvetfo.html

Ruby: File.read("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtnsbnuueq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtijlnadxo.html

[F02] 逐行读取文件
来源：http://dali.feifeiyinyue.top/Article/details/gtqnkocwpu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xziqi.cn/Article/details/gthlzmbjux.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gtnkvllpwm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtwbadxtrn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gtnrhhudlt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtzfsrbcuu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ehwqpu.com/Article/details/gtapvezgbf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.snrcjt.cn/Article/details/gtsnjwktpb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gtpsaimpiz.html

[F03] 写入文件（覆盖）
来源：http://dali.tianlin.xyz/Article/details/gtdpcufsxc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.birdmap.top/Article/details/gtpbndmver.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gtzpnxztwg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtgidalgil.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtdaytyeex.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hywenlv.cn/Article/details/gtxlnfhafz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gaohongyu789.top/Article/details/gtmgpbdvlo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gtxrgtmcqq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gtsauwyuma.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gtixavepqf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxfyiptf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.birdmap.top/Article/details/gttbzlaxrh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtrcnqqjjn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gtulemomig.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sufxvd.cn/Article/details/gtrwxrzpps.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtexlkzdyh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gtjiqlgjec.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.andypj.xyz/Article/details/gtwdyhtjmc.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gtoxoaxnkr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangshuangyany.cn/Article/details/gtcxfpypuj.html

PHP:  file_exists("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtgsvhnlxf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtvxrrkdxe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbimoqix.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtfuaskxrm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hysaishi.cn/Article/details/gtjanqfjtn.html

Ruby: File.exist?("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtgbnbizxc.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtquvmaeoe.html

[F06] 删除文件
来源：http://dali.nwbrower.top/Article/details/gtznobtphv.html

Py:   os.remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gteuenzphr.html

PHP:  unlink("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtsngsoytu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gthozcdijp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtjtqatxsf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtqweleczi.html

Go:   os.Remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtbmgsykge.html

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtvzhdsvai.html

C#:   File.Delete("a.txt");
来源：http://dali.yj202588.top/Article/details/gtdiwqkpic.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gtksywkzal.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yvedp.cn/Article/details/gtcomhapyx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.smart0.xyz/Article/details/gtjyxrixvt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtrhkhobew.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtxqvirgwv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zycfv.cn/Article/details/gtcperoooq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yueranfly.top/Article/details/gttfpnsswm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yanxiufei.cn/Article/details/gtmvowzqxj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvdlpuqm.html

[F08] 遍历目录
来源：http://dali.jianghu66.top/Article/details/gtpwfpftja.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.birdmap.top/Article/details/gtwejatnnp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.birdmap.top/Article/details/gtxnjerzog.html

JS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gteuygiwbr.html

TS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gtmprccwxz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gtpjvviayc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtamywymma.html

Ruby: Dir.children("dir")
来源：http://dali.gogol.net.cn/Article/details/gtgpjjzowl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtxdptqipd.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gtrjfmntfr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtrbrbezgy.html

PHP:  filesize("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtgbssogtc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gtbxcuuvdi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gtkmeioxtt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtzexsgrcq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.andypj.xyz/Article/details/gtazuasikh.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258.top/Article/details/gtapdgnzxu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzurvoso.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pycfn.com/Article/details/gtqguxgcgw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gttalexaxo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gtjjcjvaja.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtifoktgwx.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvuectnb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gtbueussjw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gthrgpuzcv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtrhhlojed.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtqqhpxzzk.html

[F11] 复制与移动文件
来源：http://dali.xuetiantiany.cn/Article/details/gtaocfxqkx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtcmvtgdqf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gogol.net.cn/Article/details/gtfblfqbff.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtoanqeocl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtsgdcpzxw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gtbdqycqqo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shzxlz.cn/Article/details/gtftyauear.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtcpdhaibe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuetiantiany.cn/Article/details/gtqcqpgnsu.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkubakuf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gtiedsrsgc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yangfankeji.com/Article/details/gtimtptlaj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daxiang520.top/Article/details/gtbakrxfnq.html

TS:   // 同上
来源：http://dali.316326.xyz/Article/details/gtkkpstfoz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yongpay.top/Article/details/gtxkjgsish.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gtlwvxhydm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbophwbfj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nwbrower.top/Article/details/gtdbixbcqg.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtcphvjbdj.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gteqsonopg.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtpdmbczwe.html

[G01] 定义类
来源：http://dali.cashguo.top/Article/details/gtngzohmfp.html

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gtiowszjzq.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gtgbyfmpez.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gttromvurx.html

TS:   class User { name: string = ""; }
来源：http://dali.chenlongwang.top/Article/details/gtvyawxsxx.html


<!-- 参考信息 -->