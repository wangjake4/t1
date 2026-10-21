代发 wailian999

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtzdevqokz.html

TS:   s.slice(1, 4)
来源：http://dali.xinyue.icu/Article/details/gthutgryhc.html

Java: s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gtselwdbzt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtjcvqwowp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cashguo.top/Article/details/gtgqmwwrkg.html

C#:   s.Substring(1, 3)
来源：http://dali.chenlongwang.top/Article/details/gtioqxupbl.html

[E04] 查找子串位置
来源：http://dali.shzxlz.cn/Article/details/gtlpmscmli.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gtbhlpojht.html

PHP:  strpos($s, "x");
来源：http://dali.shangyingyoupin.top/Article/details/gtqrfjyluk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yvedp.cn/Article/details/gtylfdgmfb.html

TS:   s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtbrhwbiht.html

Java: s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gtbjzylhbm.html

Go:   strings.Index(s, "x")
来源：http://dali.tanke756.top/Article/details/gtqhzgoapn.html

Ruby: s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gteoiukyyb.html

C#:   s.IndexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtzthvkdjh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jianghu66.top/Article/details/gtamgtperw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ivvv.top/Article/details/gtmzojjhst.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxinkj.top/Article/details/gtqjnjdjnr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtovcicymu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yonumen.top/Article/details/gtiirpkvkp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gthnqbfocl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnxiangtu.top/Article/details/gtrziaevlj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xylfe.cn/Article/details/gtufgygtho.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtobhkbujm.html

[E06] 替换子串
来源：http://dali.tian-w.cn/Article/details/gtbatglsbx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtqmtkpcxx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzfcoywi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gthsdvhdrp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgcoggnu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gtogtlvrrc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gtsvwmeccu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtvqpqrphc.html

C#:   s.Replace("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtelgngtlw.html

[E07] 按分隔符拆分
来源：http://dali.zhiwuduotai.top/Article/details/gtiqnxwwxd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gtgbpjnasx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtlnrfxtsy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ehwqpu.com/Article/details/gtngexkwpr.html

TS:   s.split(",")
来源：http://dali.cqqwz.cn/Article/details/gtiuoxmjef.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuetiantiany.cn/Article/details/gtqlbfgivj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guannengcc.top/Article/details/gtqautwjwf.html

Ruby: s.split(",");  s.split
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbvulxaz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hammf.cn/Article/details/gtetfvkvlm.html

[E08] 数组按分隔符合并
来源：http://dali.pycfn.com/Article/details/gtwupgipsk.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gtzysypbxk.html

PHP:  implode(",", $items);
来源：http://dali.sufxvd.cn/Article/details/gteiggutgv.html

JS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtlffuflsu.html

TS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsxwehqm.html

Java: String.join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gtditthtcp.html

Go:   strings.Join(items, ",")
来源：http://dali.wangdashe.top/Article/details/gtqqwvidze.html

Ruby: items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtcboneajo.html

C#:   string.Join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gtqrzwazup.html

[E09] 去除所有空白字符
来源：http://dali.birdmap.top/Article/details/gtsiuxdufa.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.quarkkingdee.top/Article/details/gtsvxlgyux.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtelceqdip.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtdoodavul.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gtzasfrfam.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aizwys.cn/Article/details/gtsvntgudb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pycfn.com/Article/details/gtflkqxogq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fzhhl.top/Article/details/gtkqmfalty.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtnkminihy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.9152youxi.cn/Article/details/gtshmdovnf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtdmtaxlys.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuxming.cn/Article/details/gtmuqxkzzc.html

JS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtszaminbm.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzaudzwwy.html

Java: String.format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtajnhacft.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtlkzzkuoo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtjmeokoxl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gtcgxkmnfg.html

[E11] 反转字符串
来源：http://dali.haohaochexian.top/Article/details/gtqteyresm.html

Py:   s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gtgatxcizf.html

PHP:  strrev($s);
来源：http://dali.yj20258888.top/Article/details/gtcnarbitp.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjnhplpo.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtxvyxauhn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgxvtcpm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtwrergrjc.html

Ruby: s.reverse
来源：http://dali.yj20258.top/Article/details/gtdcfucjnz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gtatcosjia.html

[E12] 统计某字符出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gtlxwbeulg.html

Py:   s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gthyvevxty.html

PHP:  substr_count($s, "a");
来源：http://dali.yuanzhike.top/Article/details/gttieniorx.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtfvfjothf.html

TS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gtwfwrhycm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.redwolf501.top/Article/details/gtioposrke.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxinkj.top/Article/details/gtajunsuot.html

Ruby: s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gtzxogpvhg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.havefunace.top/Article/details/gtyvgehutt.html

[E13] 逐字符遍历
来源：http://dali.guannengcc.top/Article/details/gtgrujdscn.html

Py:   for ch in s: print(ch)
来源：http://dali.c1oappe.top/Article/details/gtshxzixez.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sufxvd.cn/Article/details/gtckhyqmol.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtoydawsyd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtcymuyojd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.mhx1999.top/Article/details/gtcfzucgfy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daxiang520.top/Article/details/gtmkrahdyc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gtmafrlxvp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtfdbgezax.html

[E14] URL 编码与 Base64
来源：http://dali.gogol.net.cn/Article/details/gtqwtufsvx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqlgbdfu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jianghu66.top/Article/details/gtwcxrwvbc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gzhubu.top/Article/details/gtzvlavgso.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.iojbl.cn/Article/details/gtturmapis.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtgxiyuuar.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cucudq.cn/Article/details/gtcxikvuyj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.snrcjt.cn/Article/details/gtqgpjtnal.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258888.top/Article/details/gtxlxummqo.html

[E15] HTML 转义 / 反转义
来源：http://dali.daxiang520.top/Article/details/gtxokuenfp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shuidangran.top/Article/details/gttchczbjd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gtubonptbw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttulqevog.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.meibo888.top/Article/details/gtpzdmokvy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxuanxn.top/Article/details/gtilqahbuq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cqqwz.cn/Article/details/gtkmqfeaoc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtirhwzjtb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhongyouzk.top/Article/details/gtonuqqdxj.html

[E16] 数字千分位
来源：http://dali.jianghu66.top/Article/details/gtmlymjscv.html

Py:   f"{1234567:,}"
来源：http://dali.hfpthk.cn/Article/details/gtbsehoepm.html

PHP:  number_format(1234567);
来源：http://dali.hongshengwenyu.top/Article/details/gtuqxrokwz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtczwevnke.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtdevdgsml.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.smart0.xyz/Article/details/gtqzogyehc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zdqjudy.top/Article/details/gtgaqoanyn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hywenlv.cn/Article/details/gtpseehjsq.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gtxhgcetbc.html

[E17] 首字母大写
来源：http://dali.sufxvd.cn/Article/details/gtwotfjgig.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gtqtcdpuva.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigufen.top/Article/details/gtkbuhyqbi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtoxmumpev.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtvdxrdqrz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgufenzy.top/Article/details/gtadmojfcf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jlsjyb.cn/Article/details/gteumuvlxv.html

Ruby: s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gtxfzjcjgp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yongpay.top/Article/details/gtkqmhgldy.html

[E18] 模板占位符替换
来源：http://dali.c1oappe.top/Article/details/gtktvcvcea.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yanxiufei.cn/Article/details/gtfowutadj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daria6918.cn/Article/details/gtvnmyvwuh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtctnakhkn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtddbtrftj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sweek.top/Article/details/gthpdevuvz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hammf.cn/Article/details/gtkhnduzad.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gtvbwzomqg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.redwolf501.top/Article/details/gtiovoskrx.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gtrnsrnjxo.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gtrimrrgxs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtnfwaqnog.html

JS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gtphstdijx.html

TS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gtnxjsrzhb.html

Java: s.lines().toList()
来源：http://dali.wangdashe.top/Article/details/gtgzdbyclr.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gtbqqqmvhi.html

Ruby: s.lines
来源：http://dali.birdmap.top/Article/details/gtfnpaogbe.html

C#:   s.Split('\n')
来源：http://dali.hywenlv.cn/Article/details/gtcmpomjuj.html

[E20] 判断字符串是否为空
来源：http://dali.316326.xyz/Article/details/gtgbdusjje.html

Py:   if not s:
来源：http://dali.redwolf501.top/Article/details/gtsbxujxze.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zycfv.cn/Article/details/gttoieepmt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsssjjzmk.html

TS:   if (s === "") {}
来源：http://dali.wangshuangyany.cn/Article/details/gtkcocgtiy.html

Java: if (s.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtqytodjxl.html

Go:   if s == "" {}
来源：http://dali.xylfe.cn/Article/details/gtyktjvhlj.html

Ruby: if s.empty?
来源：http://dali.sweek.top/Article/details/gthoeslrap.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zycfv.cn/Article/details/gtemireppx.html

[E21] 超长截断加省略号
来源：http://dali.xziqi.cn/Article/details/gtowhhemzv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.c1oappe.top/Article/details/gtcrvjpqmf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtxkdqzlpd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtfewmokbi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtldijffvu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtskvwjyde.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cqqwz.cn/Article/details/gtmsklwnaf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtaigplmfo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtlnqxfmtq.html

[E22] 字节长度与字符长度
来源：http://dali.fzhhl.top/Article/details/gtbeyrclum.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gtuldesjnj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtlprfnkwe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtgwtcxcsg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtnskpmhre.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtmzsxvzbu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xziqi.cn/Article/details/gtmrtjovgc.html

Ruby: s.bytesize;  s.length
来源：http://dali.sweek.top/Article/details/gtsuyhakcf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwpkzqfy.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtcveyqugg.html

F. 文件与目录
来源：http://dali.jyoumei.cn/Article/details/gtlaulauox.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtbgcmrjqk.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gtmcbfocxy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenjidiqi.icu/Article/details/gtpstwdzou.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtyrkpazdr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hammf.cn/Article/details/gtebbcxhiq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtvqhcveax.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtzwddqhpg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ppjwa.cn/Article/details/gtvdbcmlzn.html

Ruby: File.read("a.txt")
来源：http://dali.bjfxy.top/Article/details/gthvhemfpp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtwhxcrljn.html

[F02] 逐行读取文件
来源：http://dali.zhengqikj.top/Article/details/gtqkzcoyum.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.vqdsnc.cn/Article/details/gtcjzjvsvw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.dashuyun.cn/Article/details/gtkogjpdsz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gtzjhijapb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtfeyyuopy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gtlwdfjxsn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yueranfly.top/Article/details/gtfzryfkdh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nwbrower.top/Article/details/gtohvxpach.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ppjwa.cn/Article/details/gtkrmkyseo.html

[F03] 写入文件（覆盖）
来源：http://dali.mhx1999.top/Article/details/gtppibrinu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ydzc1.top/Article/details/gtormghnyu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtjfwwaqum.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtzbscepqt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtlezzmrng.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnaidkcfg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gtozcgxgla.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gzhubu.top/Article/details/gtrlsjmnph.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtlbsfymze.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gtzpsuairf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sweek.top/Article/details/gtejaffdvj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daxiang520.top/Article/details/gthcxmynrr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gtowrdjwgt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gtshiowgwl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xziqi.cn/Article/details/gtvbwirnyf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aizwys.cn/Article/details/gtqrpkvtjm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhengqikj.top/Article/details/gtdrzvqolt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.c1oappe.top/Article/details/gteugvtyge.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gtuwrarhmi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258.top/Article/details/gtrbhhrdkf.html

PHP:  file_exists("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtrlvwvmcx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gteorhecjd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtdwphxnpe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gttkjvzfwj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhixingplan.top/Article/details/gtoctitlpe.html

Ruby: File.exist?("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtlwsjhxui.html

C#:   File.Exists("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtyclzejfy.html

[F06] 删除文件
来源：http://dali.hnxiangtu.top/Article/details/gttxtttpzg.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtktazluge.html

PHP:  unlink("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtmyyxkjgv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtwiazjfaf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtxoasujzh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtvqdkaaqi.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtbphkoaku.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtgxrqjewy.html

C#:   File.Delete("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtzofmvflu.html

[F07] 创建目录（含多级）
来源：http://dali.c1oappe.top/Article/details/gtsxcxpvbm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gtmdjnatqs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gogol.net.cn/Article/details/gtvktjzrvb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gtyasmmzmn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtfupxzjjo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.havefunace.top/Article/details/gtygqkoszm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zdqjudy.top/Article/details/gtpgcyhsoi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuanzx.com/Article/details/gtedssidxr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sweek.top/Article/details/gtrakcxchq.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gtgpkisqwl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yueranfly.top/Article/details/gtngiwrqli.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aizwys.cn/Article/details/gtcsqdncsc.html

JS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gtxrfetzti.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtxerwyrum.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gtdjkrqmfz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sufxvd.cn/Article/details/gtfngpajbi.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gtyhmnbqrn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ydzc1.top/Article/details/gtacqthljs.html

[F09] 获取文件大小
来源：http://dali.feifeiyinyue.top/Article/details/gtostdvlty.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pycfn.com/Article/details/gtzdwhjexk.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtrabryihq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtkrzfqlal.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtpvsdhgul.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtkbtybwhc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gtskgrbcwt.html

Ruby: File.size("a.txt")
来源：http://dali.havefunace.top/Article/details/gtaqnsjmvb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cqqwz.cn/Article/details/gtqiplrvmv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxnydsoc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtdauxwqup.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ivvv.top/Article/details/gtnjjxjakw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgudczdc.html

TS:   path.extname("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtaeccfmoh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ehwqpu.com/Article/details/gtpvypsxjk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtluwkmbhu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtuyoxgdyd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtoxpdfhrk.html

[F11] 复制与移动文件
来源：http://dali.aizwys.cn/Article/details/gtzocyyqdp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtzshvfqlk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnqzz.top/Article/details/gtmjyzijxe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtvdhiqkef.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtatruukdz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gtwaoyfuow.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnxiangtu.top/Article/details/gtcacakgum.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gteqwbbtst.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sufxvd.cn/Article/details/gtqjkxbfco.html

[F12] CSV 读写
来源：http://dali.pycfn.com/Article/details/gtltlckflb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gtbpawvgrw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sufxvd.cn/Article/details/gtgrmxsrlk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gtdllbqnxa.html

TS:   // 同上
来源：http://dali.yangfankeji.com/Article/details/gtdtyqianf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.bjfxy.top/Article/details/gtisukgwft.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hongshengwenyu.top/Article/details/gtpwnaogpl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.smart0.xyz/Article/details/gtyikbksjt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxinkj.top/Article/details/gtqyiqbwra.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtpzljpxhk.html

G. 面向对象
来源：http://dali.yueranfly.top/Article/details/gtasilimqn.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdxzriwm.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gtpunidsec.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gtvpuxpvnn.html

PHP:  class User {}
来源：http://dali.yj202588.top/Article/details/gtutgwjogb.html

JS:   class User {}
来源：http://dali.hnqzz.top/Article/details/gtpctiqvlk.html

TS:   class User { name: string = ""; }
来源：http://dali.fzhhl.top/Article/details/gtjfewmown.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtqkhzbhbm.html

Go:   type User struct { Name string }
来源：http://dali.wangdashe.top/Article/details/gtyloauuas.html

Ruby: class User; end
来源：http://dali.wangshuangyany.cn/Article/details/gtcrhbufxw.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtqcszvizk.html


<!-- 参考信息 -->