代发 wailian999

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zdqjudy.top/Article/details/gtwuhuzfdy.html

[E03] 截取子串
来源：http://dali.sxryk.cn/Article/details/gtcolfuqkz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yvedp.cn/Article/details/gtgrzzlofz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtmulckwyx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtrodbcgme.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gttvwmfubh.html

Java: s.substring(1, 4)
来源：http://dali.aizwys.cn/Article/details/gtixizpspf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gtfdmyluhc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gzhubu.top/Article/details/gtzffpyjux.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gtcaexnymk.html

[E04] 查找子串位置
来源：http://dali.gogol.net.cn/Article/details/gtvpwlhyzn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gtmbwubasj.html

PHP:  strpos($s, "x");
来源：http://dali.nanxinkj.top/Article/details/gtnydhbktr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.bjfxy.top/Article/details/gtweqpdffq.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzsevpdr.html

Java: s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtjmksnfqb.html

Go:   strings.Index(s, "x")
来源：http://dali.sufxvd.cn/Article/details/gtxwvmjels.html

Ruby: s.index("x")
来源：http://dali.redwolf501.top/Article/details/gtyhiymxlg.html

C#:   s.IndexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtijmpoyuu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigufen.top/Article/details/gtyjehfezw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hfpthk.cn/Article/details/gtmuhcevkf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxuanxn.top/Article/details/gtarrexvdh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtgkxmyxve.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgouwbga.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvywcfpab.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cheryme.top/Article/details/gtbclfrfos.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jiagoushi.top/Article/details/gteguzspxy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gthbdxgcjz.html

[E06] 替换子串
来源：http://dali.nanxinkj.top/Article/details/gtcjvalezt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gtopungdui.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tian-w.cn/Article/details/gteahnkdul.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtkthennpa.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtpjdfxmxx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtngwkkloy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gtvtirbsvd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtiyfymahu.html

C#:   s.Replace("a", "b")
来源：http://dali.meibo888.top/Article/details/gtqbtvjzje.html

[E07] 按分隔符拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtefcrwwga.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhengqikj.top/Article/details/gtasqvcele.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cheryme.top/Article/details/gtmwssdxvi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.9152youxi.cn/Article/details/gtzgndnmfk.html

TS:   s.split(",")
来源：http://dali.yonumen.top/Article/details/gtyrpojqyn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.meibo888.top/Article/details/gtsphxikqb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhongyouzk.top/Article/details/gtmzgoollx.html

Ruby: s.split(",");  s.split
来源：http://dali.hnqzz.top/Article/details/gtxvdswlnj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ybcxt.top/Article/details/gtawmbusaq.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigfzy.top/Article/details/gtevqtuxcq.html

Py:   ",".join(items)
来源：http://dali.jianghu66.top/Article/details/gtmhptntdx.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gtfuyvjsna.html

JS:   items.join(",")
来源：http://dali.xylfe.cn/Article/details/gtvumjccpk.html

TS:   items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtvxpuetad.html

Java: String.join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gtbekpfsuy.html

Go:   strings.Join(items, ",")
来源：http://dali.gaohongyu789.top/Article/details/gtycbffhxa.html

Ruby: items.join(",")
来源：http://dali.yj20258888.top/Article/details/gttazncmlb.html

C#:   string.Join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gtmvtqhjbu.html

[E09] 去除所有空白字符
来源：http://dali.gaohongyu789.top/Article/details/gtuavhyukk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jlsjyb.cn/Article/details/gtfbbsimna.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzeyoqthn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gthvdenfyr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gtqjhehzba.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gtgpoqmtdm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yongpay.top/Article/details/gtnzmlpqmq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnxiangtu.top/Article/details/gtjqtsdfrx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cucudq.cn/Article/details/gthaoceabl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gotoacloud.top/Article/details/gtkijmjfha.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yongpay.top/Article/details/gtrtyoomvv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhongyouzk.top/Article/details/gtonlweahs.html

JS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtrmgzprhq.html

TS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtqhhkvgib.html

Java: String.format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gttuxwosfp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtcdefsxtj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtzzotbafv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258888.top/Article/details/gtlvmedhec.html

[E11] 反转字符串
来源：http://dali.guannengcc.top/Article/details/gtfecnemcv.html

Py:   s[::-1]
来源：http://dali.aizwys.cn/Article/details/gtdweztlbc.html

PHP:  strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gtlhtukjam.html

JS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtikxehjdv.html

TS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtnbyctpke.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtrgxcbxzv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.svipenyu.cn/Article/details/gtbbnoehxk.html

Ruby: s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykhwkgag.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gtxkqatlxw.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigufen.top/Article/details/gtcrcdztpk.html

Py:   s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gtttngaugm.html

PHP:  substr_count($s, "a");
来源：http://dali.nwbrower.top/Article/details/gtpmbnsdxz.html

JS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gtqtepgrqk.html

TS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtopbqzrad.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkensodti.html

Go:   strings.Count(s, "a")
来源：http://dali.guannengcc.top/Article/details/gtyhyhaqjj.html

Ruby: s.count("a")
来源：http://dali.yj20258.top/Article/details/gtbboedffc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigfzy.top/Article/details/gtlzohcwpq.html

[E13] 逐字符遍历
来源：http://dali.yanxiufei.cn/Article/details/gtgzhdrggn.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gtngnjelnj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gtiqjxukfb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtqoxktmmd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtkchnvpoh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtwkedmhcx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fengsongda.top/Article/details/gtcshndmtz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fengsongda.top/Article/details/gtvebtxeqq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gthxdphyir.html

[E14] URL 编码与 Base64
来源：http://dali.hysaishi.cn/Article/details/gteoglnono.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hywenlv.cn/Article/details/gtdyfrcxga.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gtuxyizywy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigufen.top/Article/details/gtuxchqtef.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnqzz.top/Article/details/gtemylqvqg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sxryk.cn/Article/details/gtjgftqnvn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ivvv.top/Article/details/gtjzdhcjnu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hammf.cn/Article/details/gtwbxgepdv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtrvlhaaot.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhixingplan.top/Article/details/gtwjwjdumb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangdashe.top/Article/details/gttpbanptw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aibaodan.cn/Article/details/gtkksmvjhr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yongpay.top/Article/details/gtygpmshwg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.0kj1m.cn/Article/details/gthlcyyuby.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnjyzdfm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtuwttijjd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.mhx1999.top/Article/details/gtjgwwkahl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomeiaova.html

[E16] 数字千分位
来源：http://dali.hysaishi.cn/Article/details/gtootzoomx.html

Py:   f"{1234567:,}"
来源：http://dali.cdnleiting.top/Article/details/gtiesdtyiv.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzikqncy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtcrmqkcvs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gtaiymsvji.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cucudq.cn/Article/details/gtzjtahies.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxuanxn.top/Article/details/gtbdzyelvp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yongpay.top/Article/details/gtswodeawg.html

C#:   1234567.ToString("N0")
来源：http://dali.chenzaomai.com/Article/details/gtyjigbdgh.html

[E17] 首字母大写
来源：http://dali.daxiang520.top/Article/details/gtmkrffujr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.0kj1m.cn/Article/details/gtryczqcly.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tianlin.xyz/Article/details/gtnpblxxnm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gtdvvjkkgj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtzguflzew.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.meibo888.top/Article/details/gttibixhks.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigufen.top/Article/details/gtwqrlfihm.html

Ruby: s.capitalize
来源：http://dali.andypj.xyz/Article/details/gtgyyfwtxc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yangfankeji.com/Article/details/gtpmrevinz.html

[E18] 模板占位符替换
来源：http://dali.sufxvd.cn/Article/details/gtgeeuwrgw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.vqdsnc.cn/Article/details/gtawfkoxpq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xziqi.cn/Article/details/gtvkfboqhc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtcetlrumq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtarbqbpwu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtwqgdgxic.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtwftyiqbl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ybcxt.top/Article/details/gtyczcmqhs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gtnoxidtek.html

[E19] 多行文本按行拆分
来源：http://dali.iojbl.cn/Article/details/gtbeqwyliz.html

Py:   s.splitlines()
来源：http://dali.chenzaomai.com/Article/details/gtkwjwchfw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtsfloxcsh.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gtsbpciivj.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gtezfzdcni.html

Java: s.lines().toList()
来源：http://dali.cqqwz.cn/Article/details/gtcpwcwjzh.html

Go:   strings.Split(s, "\n")
来源：http://dali.gogol.net.cn/Article/details/gthnurymol.html

Ruby: s.lines
来源：http://dali.daxiang520.top/Article/details/gtacwrxitg.html

C#:   s.Split('\n')
来源：http://dali.ydzc1.top/Article/details/gtxdlswxdx.html

[E20] 判断字符串是否为空
来源：http://dali.jiagoushi.top/Article/details/gtrfpxczqh.html

Py:   if not s:
来源：http://dali.jinqigufen.top/Article/details/gtxdlqzpym.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dianchejie.cn/Article/details/gtuwfezuyn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxuanxn.top/Article/details/gtjcxjmhji.html

TS:   if (s === "") {}
来源：http://dali.jinqigfzy.top/Article/details/gtxkgugavi.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gtcsdmtpyy.html

Go:   if s == "" {}
来源：http://dali.gogol.net.cn/Article/details/gteqazeyyc.html

Ruby: if s.empty?
来源：http://dali.yuxming.cn/Article/details/gttvzfgttt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuanzx.com/Article/details/gtygxgzire.html

[E21] 超长截断加省略号
来源：http://dali.gzhubu.top/Article/details/gtqpjavtef.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxinkj.top/Article/details/gtaeneyeyz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtxnlnowuv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtqrlpgxjg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtknxpakbi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtxsduiqey.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aizwys.cn/Article/details/gtakfvzqkf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtbbezegsv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtdxwvouvo.html

[E22] 字节长度与字符长度
来源：http://dali.fengsongda.top/Article/details/gtajpxqmxi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuxming.cn/Article/details/gtpjtqcsyj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtwtwwdeim.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtnrmfycad.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gtfxywlwnp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtdxmwygvr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hywenlv.cn/Article/details/gtggemwkdg.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gtsoruavpx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sxryk.cn/Article/details/gthdztvtup.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtqlfjabym.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gtxhbkgebw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtmdbshnrf.html

[F01] 读取整个文件
来源：http://dali.ivvv.top/Article/details/gtvjcmfmyg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cdnleiting.top/Article/details/gtyqxeccfh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtofojybcn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nwbrower.top/Article/details/gtmrqlyiiy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtabehndnz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtemrgwaen.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xziqi.cn/Article/details/gtpmesfysz.html

Ruby: File.read("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtucdddfys.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtydoyfmir.html

[F02] 逐行读取文件
来源：http://dali.nanxinkj.top/Article/details/gtjoawqbpx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuetiantiany.cn/Article/details/gtxehrprmv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.iojbl.cn/Article/details/gtbqexdmwb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gtgdzzgpyr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtojdcccog.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gtbnngqdyi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cucudq.cn/Article/details/gtruhubkog.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gzhubu.top/Article/details/gtbsojoxtg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cqqwz.cn/Article/details/gtlioxunbm.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gtwzbgzmjf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zycfv.cn/Article/details/gtmesrjnkg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtfxaztgwn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gtyhcrmfet.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtcqpryqya.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtyzvwnnnm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gtahekwodz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gtddbffjts.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gtgoymkrla.html

[F04] 追加写入文件
来源：http://dali.shuidangran.top/Article/details/gtzcqjvhtu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tianlin.xyz/Article/details/gtvodefcbe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ppjwa.cn/Article/details/gtafcdkkae.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtkbypgbmz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gtxukhgozw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cucudq.cn/Article/details/gtelfbdbka.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daxiang520.top/Article/details/gtihtlnfpn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tanke756.top/Article/details/gtfuesnzsm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fzhhl.top/Article/details/gtjkcnitig.html

[F05] 判断文件或目录是否存在
来源：http://dali.shuidangran.top/Article/details/gtzzyvdupg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dianchejie.cn/Article/details/gtiekmxvuj.html

PHP:  file_exists("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtxakcxtey.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtavkvlhcz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtssmomnup.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtdxyauuro.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jlsjyb.cn/Article/details/gtyhyumvva.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtpmtxvzmw.html

C#:   File.Exists("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtpvzisrwu.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gtabnvldrp.html

Py:   os.remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtepvgummw.html

PHP:  unlink("a.txt");
来源：http://dali.birdmap.top/Article/details/gtflamlrva.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtnpmwaqbu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqqgsczn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtoogclwgv.html

Go:   os.Remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gttndsezzt.html

Ruby: File.delete("a.txt")
来源：http://dali.daxiang520.top/Article/details/gttalywshu.html

C#:   File.Delete("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtzsdtojeh.html

[F07] 创建目录（含多级）
来源：http://dali.andypj.xyz/Article/details/gtwhfeipzc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gtclhjjtuj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtsyqahokx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtulbechpm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gtvdtodyph.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hywenlv.cn/Article/details/gteglnlprf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gtlorvdjtn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ivvv.top/Article/details/gtxucqleyx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jlsjyb.cn/Article/details/gtskjhxfme.html

[F08] 遍历目录
来源：http://dali.sysykeji.top/Article/details/gtuxiydpkb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nwbrower.top/Article/details/gtnjlwhgfh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.c1oappe.top/Article/details/gtleyhuyqu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtzddszekb.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtqffjzmfj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtcoliljqp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxoqqmet.html

Ruby: Dir.children("dir")
来源：http://dali.yuanzhike.top/Article/details/gtqczfxgxn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gtsbjocafa.html

[F09] 获取文件大小
来源：http://dali.guannengcc.top/Article/details/gtmcvrrxim.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtbtwqdjyl.html

PHP:  filesize("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtpooclpdf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gtidawziye.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtzajipepu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtlzoidxkc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gtxpchaawu.html

Ruby: File.size("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtllvuniki.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.kuanghao11.cn/Article/details/gtmuscocun.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuanzx.com/Article/details/gtntdfjqla.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtgwawwljo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtorjumefu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtpidqcvgo.html

TS:   path.extname("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtbwpgxuyu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gtpwkirvny.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtldwxmiwy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtuanhcego.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtbfoopijz.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gtjdmdgkhh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gthzdoakhe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.9152youxi.cn/Article/details/gtudfqrekg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gttcbkgcta.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtsvoeriaa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtemyzlugc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuanzx.com/Article/details/gthmhcecur.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtpkhszbsg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.316326.xyz/Article/details/gtzkkkkhal.html

[F12] CSV 读写
来源：http://dali.zhixingplan.top/Article/details/gtbqoeggmp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guowangkeji.top/Article/details/gtpvghizqh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ppjwa.cn/Article/details/gtcqkyqggy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj202588.top/Article/details/gtdiosdvsf.html

TS:   // 同上
来源：http://dali.gaohongyu789.top/Article/details/gtwmdnmzht.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.kuanghao11.cn/Article/details/gtizjhdmtf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gtmdzkttkt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gtpcdfieto.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gtrxpmepkk.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtpdrcyjaf.html

G. 面向对象
来源：http://dali.birdmap.top/Article/details/gtcibzmfus.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttkkbmfpp.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gtgpjrrrte.html

Py:   class User: pass
来源：http://dali.hammf.cn/Article/details/gtqnwnxwna.html

PHP:  class User {}
来源：http://dali.ehwqpu.com/Article/details/gtrtwimzpq.html

JS:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtmhkzwvuj.html

TS:   class User { name: string = ""; }
来源：http://dali.yj202588.top/Article/details/gtjiohtara.html


<!-- 参考信息 -->