代发 wailian999

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xziqi.cn/Article/details/gtvdltvuyv.html

[E03] 截取子串
来源：http://dali.havefunace.top/Article/details/gtweyfocfq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guowangkeji.top/Article/details/gtymimvaax.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtpyuqaplv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtildkieyk.html

TS:   s.slice(1, 4)
来源：http://dali.havefunace.top/Article/details/gtdhsfgjne.html

Java: s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gtqavridkg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hammf.cn/Article/details/gtxwyaomta.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxuanxn.top/Article/details/gtiifvercs.html

C#:   s.Substring(1, 3)
来源：http://dali.yuanzhike.top/Article/details/gtfavhmslz.html

[E04] 查找子串位置
来源：http://dali.xuetiantiany.cn/Article/details/gtrtahyode.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gtoaajgdyj.html

PHP:  strpos($s, "x");
来源：http://dali.jqgfzy.top/Article/details/gtzjitdezf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dashuyun.cn/Article/details/gtheggakdc.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtnepgmbeb.html

Java: s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gtsmqylgai.html

Go:   strings.Index(s, "x")
来源：http://dali.tanke756.top/Article/details/gtpfndweij.html

Ruby: s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtgnmujwrl.html

C#:   s.IndexOf("x")
来源：http://dali.jianghu66.top/Article/details/gthshdpeby.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tianlin.xyz/Article/details/gtzgqoqezk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhixingplan.top/Article/details/gthrfynffw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigfzy.top/Article/details/gtxcazjmrl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtebreajfs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jlsjyb.cn/Article/details/gtgvhrdjwc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtddatwgqz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jlsjyb.cn/Article/details/gttoffnrwf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigufen.top/Article/details/gtafthlaks.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtiapxpecb.html

[E06] 替换子串
来源：http://dali.pycfn.com/Article/details/gtigtkbvok.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gteoigrxbz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gaohongyu789.top/Article/details/gtajfdarxa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtiknlnvzs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtitlopxpp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtpnekcfek.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhoulong.xyz/Article/details/gthpevzoil.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gteeiehykl.html

C#:   s.Replace("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtyswvxome.html

[E07] 按分隔符拆分
来源：http://dali.kuanghao11.cn/Article/details/gtsbihgewn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajcrdxwj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtvctcmojp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shzxlz.cn/Article/details/gtasyumzhs.html

TS:   s.split(",")
来源：http://dali.ehwqpu.com/Article/details/gtdenyxwcq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.c1oappe.top/Article/details/gtzwcimjsb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yvedp.cn/Article/details/gtqbktmnwr.html

Ruby: s.split(",");  s.split
来源：http://dali.fzhhl.top/Article/details/gtpgmdnoce.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.316326.xyz/Article/details/gtenecwdlp.html

[E08] 数组按分隔符合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuskkdtkb.html

Py:   ",".join(items)
来源：http://dali.aizwys.cn/Article/details/gtjvvjbuzx.html

PHP:  implode(",", $items);
来源：http://dali.ydzc1.top/Article/details/gtcyhgmsuh.html

JS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gtvpfelzpk.html

TS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtvecfqgmw.html

Java: String.join(",", items)
来源：http://dali.andypj.xyz/Article/details/gtoeriplyy.html

Go:   strings.Join(items, ",")
来源：http://dali.tian-w.cn/Article/details/gtccpqtfmn.html

Ruby: items.join(",")
来源：http://dali.xinyue.icu/Article/details/gtjodjwpkr.html

C#:   string.Join(",", items)
来源：http://dali.tian-w.cn/Article/details/gtfpjhmheq.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gtgzjrzacm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sysykeji.top/Article/details/gtpqhtkibb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.redwolf501.top/Article/details/gtifcbeozd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtshnxmgcb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtmbmcbybt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtmtjucbke.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sweek.top/Article/details/gtywbfvtcm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhixingplan.top/Article/details/gtqzgactbq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gtpwqejpjp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jiagoushi.top/Article/details/gtmujohovp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtkjpcbror.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tianlin.xyz/Article/details/gtmpxmzcss.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtbydkpsqv.html

TS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtawulylos.html

Java: String.format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtoefekcjd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtgdnunadc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtjsdrqnqy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenzaomai.com/Article/details/gtnzeeiqgo.html

[E11] 反转字符串
来源：http://dali.ehwqpu.com/Article/details/gtphaahzfj.html

Py:   s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gtxbouslfn.html

PHP:  strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gtrahepxyq.html

JS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtfouridht.html

TS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtlxkgkxog.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jlsjyb.cn/Article/details/gtradnjfpc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.meibo888.top/Article/details/gtbdcclbml.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gtpnjcrdsr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gthstelzbi.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzmqdobi.html

Py:   s.count("a")
来源：http://dali.yj20258888.top/Article/details/gtrjyarruo.html

PHP:  substr_count($s, "a");
来源：http://dali.zycfv.cn/Article/details/gtioeivfcy.html

JS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcznobqa.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtxztkruzh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xinyue.icu/Article/details/gtmzigxuit.html

Go:   strings.Count(s, "a")
来源：http://dali.hnxiangtu.top/Article/details/gtfssorzzr.html

Ruby: s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gtdzraacjv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dashuyun.cn/Article/details/gtqpcsswxk.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtjitmufek.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gtowpwxlsh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.bjfxy.top/Article/details/gtlgvmnrxo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtkgimytao.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtoxipemjn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuevouqm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gtlboxtgzv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj202588.top/Article/details/gtuzbymhqq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cashguo.top/Article/details/gtokmyiwut.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gtokifnaho.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cashguo.top/Article/details/gtmjmjsjci.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzrkrpwn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yangfankeji.com/Article/details/gtalqgcmsr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gaohongyu789.top/Article/details/gthxcvknns.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.mhx1999.top/Article/details/gtuhbxqezn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhongyouzk.top/Article/details/gtydisjoaz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gtqzueisto.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.andypj.xyz/Article/details/gtmqyskpxe.html

[E15] HTML 转义 / 反转义
来源：http://dali.hfpthk.cn/Article/details/gtaejbjjhg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gthhqddgqi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuxming.cn/Article/details/gtvlkygwdt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yongpay.top/Article/details/gtzruyolhf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.quarkkingdee.top/Article/details/gtgwmczxtl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gtwrtqscui.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.c1oappe.top/Article/details/gtglqxxcmy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuobygqbl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gtgbnlicdk.html

[E16] 数字千分位
来源：http://dali.yangfankeji.com/Article/details/gtheeubdfs.html

Py:   f"{1234567:,}"
来源：http://dali.haohaochexian.top/Article/details/gtwjwgjrsb.html

PHP:  number_format(1234567);
来源：http://dali.sxryk.cn/Article/details/gtykbvoviu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gtodpwebgw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gtcdiylmoi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gtpukibajt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hysaishi.cn/Article/details/gthfqqkzux.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gogol.net.cn/Article/details/gtxbdggzwm.html

C#:   1234567.ToString("N0")
来源：http://dali.zhengqikj.top/Article/details/gtiigqkpuk.html

[E17] 首字母大写
来源：http://dali.hnqzz.top/Article/details/gtjomvtksp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gtqmjepwok.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ydzc1.top/Article/details/gtgfxikgqx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gtyiuuqhqt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gtwpqlkpgq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuxming.cn/Article/details/gtdgudjdzk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtgokayqzu.html

Ruby: s.capitalize
来源：http://dali.yj202588.top/Article/details/gtxlccjylp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgfzy.top/Article/details/gtaylsketw.html

[E18] 模板占位符替换
来源：http://dali.sufxvd.cn/Article/details/gtalrfefsz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pengpengdd.cyou/Article/details/gtmirfxxzj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.iojbl.cn/Article/details/gticlxkdfw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtlapjaims.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtxjcrnqrv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gthifrhnzb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.havefunace.top/Article/details/gtipdzvkzl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yonumen.top/Article/details/gtzqgbpgzw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.redwolf501.top/Article/details/gtzvjiuvqi.html

[E19] 多行文本按行拆分
来源：http://dali.316326.xyz/Article/details/gtvozktrrf.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gtqskkuzqm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtvjbqqsob.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gtlvezmgls.html

TS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gtsqrutfor.html

Java: s.lines().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtbbavphgz.html

Go:   strings.Split(s, "\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyuavogfq.html

Ruby: s.lines
来源：http://dali.hongshengwenyu.top/Article/details/gtjaoxojut.html

C#:   s.Split('\n')
来源：http://dali.yonumen.top/Article/details/gtbnofjuad.html

[E20] 判断字符串是否为空
来源：http://dali.cheryme.top/Article/details/gtbbjoywvy.html

Py:   if not s:
来源：http://dali.ydzc1.top/Article/details/gtrdqqhhhf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aibaodan.cn/Article/details/gtfsyttllq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hammf.cn/Article/details/gtaddwckfl.html

TS:   if (s === "") {}
来源：http://dali.yuanzhike.top/Article/details/gtxlfcpejq.html

Java: if (s.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gtkxdigipu.html

Go:   if s == "" {}
来源：http://dali.jyoumei.cn/Article/details/gtrkqdvmis.html

Ruby: if s.empty?
来源：http://dali.vqdsnc.cn/Article/details/gthsfcndqd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigufen.top/Article/details/gtsqhreblx.html

[E21] 超长截断加省略号
来源：http://dali.aizwys.cn/Article/details/gteptyrrjk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jianghu66.top/Article/details/gttgtxnpmn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtuspapmdk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtkxfgocrk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtlqmmqxrb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtrwfrplip.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cdnleiting.top/Article/details/gtqqtykrln.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtiftkkelm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtrobvnewa.html

[E22] 字节长度与字符长度
来源：http://dali.shzxlz.cn/Article/details/gtzqzuatnx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtsheyqxsh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sweek.top/Article/details/gtfxvqheit.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtpouirfae.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtrraaiklz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtuvefmbca.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yueranfly.top/Article/details/gtirhcddle.html

Ruby: s.bytesize;  s.length
来源：http://dali.fzhhl.top/Article/details/gtvdrlptfj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuanzx.com/Article/details/gtasdihdcv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtbqnkxrtz.html

F. 文件与目录
来源：http://dali.yvedp.cn/Article/details/gtdhvbndma.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtzsevuiri.html

[F01] 读取整个文件
来源：http://dali.wangdashe.top/Article/details/gtehiqxwpg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jiagoushi.top/Article/details/gthqdydxnj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtpsstdvrs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ppjwa.cn/Article/details/gtlezwngur.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258.top/Article/details/gtvktdraka.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtqnmifmuv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gtakfjppvz.html

Ruby: File.read("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtvlbtxuqe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtkiuben.html

[F02] 逐行读取文件
来源：http://dali.gaohongyu789.top/Article/details/gtkyevtbdq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigfzy.top/Article/details/gtzjuvdlpd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuxming.cn/Article/details/gtjvwhowjs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gtcwstsnjw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtbegobbsr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtifnmeqyj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgufenzy.top/Article/details/gtsabozevo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangshuangyany.cn/Article/details/gtemybiyrg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gttwptpklt.html

[F03] 写入文件（覆盖）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvsrytau.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yvedp.cn/Article/details/gtyoohikcd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gtxljfpmta.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gticzpjxwx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtqwtdaqwj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tianlin.xyz/Article/details/gtssritedh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.iojbl.cn/Article/details/gtfhzfgbft.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.0kj1m.cn/Article/details/gtgzlfnejj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gteuyewaqe.html

[F04] 追加写入文件
来源：http://dali.xinyue.icu/Article/details/gtcxcxlkra.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tanke756.top/Article/details/gtsylodiqy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.0kj1m.cn/Article/details/gtjomgzboi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtkiiwygpp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gtkcjomuwe.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xinyue.icu/Article/details/gtzszhtjig.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zdqjudy.top/Article/details/gtdjzvstwb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnxiangtu.top/Article/details/gtjznruyun.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.mhx1999.top/Article/details/gtussghfau.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangdashe.top/Article/details/gttrvcanki.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aizwys.cn/Article/details/gtdluexukc.html

PHP:  file_exists("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtganmxoqi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtzvetybfm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtycdvvuvf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtcauynnsn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sysykeji.top/Article/details/gtgqlgdfvy.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gtmpxzwrec.html

C#:   File.Exists("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtxrfarprq.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gtdzvqqskp.html

Py:   os.remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtuyqwjwpe.html

PHP:  unlink("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtnxjkslcs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtsswtwdjo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtieevoold.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtleaavcla.html

Go:   os.Remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtcdnsmqcf.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtyhjbhaxp.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtatmjdyma.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gtfmhpvhrq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gtuczfknqm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.0kj1m.cn/Article/details/gtfcggwrwk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gtzuihjnxf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtibkwatov.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jiagoushi.top/Article/details/gtcdzhqcfw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangdashe.top/Article/details/gttpzxtgkm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.svipenyu.cn/Article/details/gtaqigmdda.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangshuangyany.cn/Article/details/gtufhajkpf.html

[F08] 遍历目录
来源：http://dali.yj20258888.top/Article/details/gtwwgewsbg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gtyvmvexvg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gtupwktwgo.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmtpmkgc.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtwkaranpf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gtzioibymj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gttgnfemxc.html

Ruby: Dir.children("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtdmwwgpzs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtijgazffd.html

[F09] 获取文件大小
来源：http://dali.bjfxy.top/Article/details/gtaccxlonq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtsghwoiqb.html

PHP:  filesize("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtfajlqwxv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gtbhyheqin.html

TS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gttlamkkfv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtifervihp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhoulong.xyz/Article/details/gtalhvqifd.html

Ruby: File.size("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtaxqyswjw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gtfohpkesp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhixingplan.top/Article/details/gtlldcsfoq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtendvurra.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtzkybuxuq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtkjuwqiai.html

TS:   path.extname("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtnpyijzrk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gtlpsjtdpa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtlfunqeaj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtmttncass.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gthxvqvnxm.html

[F11] 复制与移动文件
来源：http://dali.316326.xyz/Article/details/gtbhtyeidc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtnmtrhvke.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.snrcjt.cn/Article/details/gtrejowuah.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtofeoiijc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtpvdgseha.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtfgpmadnt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dianchejie.cn/Article/details/gttvaoqhfb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtgvmqrxgv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gtottdyslh.html

[F12] CSV 读写
来源：http://dali.xziqi.cn/Article/details/gtonvhcwcs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xinyue.icu/Article/details/gtydspelso.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hammf.cn/Article/details/gtgbhawpfd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zycfv.cn/Article/details/gtahllhqeh.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtlyuawrqh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gtumwrvwwh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gtzcvvubrr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ehwqpu.com/Article/details/gtziipciec.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhoulong.xyz/Article/details/gtlnncfuro.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtxavhyqlx.html

G. 面向对象
来源：http://dali.nwbrower.top/Article/details/gtesgalath.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtmwxnflbb.html

[G01] 定义类
来源：http://dali.sufxvd.cn/Article/details/gtaruqqqyz.html

Py:   class User: pass
来源：http://dali.wangdashe.top/Article/details/gtlfhyqtew.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlguazmv.html

JS:   class User {}
来源：http://dali.hammf.cn/Article/details/gtxwghigvc.html

TS:   class User { name: string = ""; }
来源：http://dali.yangfankeji.com/Article/details/gtygyczmom.html


<!-- 参考信息 -->