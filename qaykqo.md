代发 wailian999

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvfuyjpb.html

[E03] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gtifmrktzo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gzhubu.top/Article/details/gtpzkssrxx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyykazytn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gteinxcbro.html

TS:   s.slice(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtvehzfnhu.html

Java: s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtccuaoajn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xinyue.icu/Article/details/gtzwzdgqkk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.vqdsnc.cn/Article/details/gtnewyqfbv.html

C#:   s.Substring(1, 3)
来源：http://dali.wangdashe.top/Article/details/gtaxkqqvhl.html

[E04] 查找子串位置
来源：http://dali.hfpthk.cn/Article/details/gtgrriykgs.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gogol.net.cn/Article/details/gtwthcxppx.html

PHP:  strpos($s, "x");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemxdhtoj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhongyouzk.top/Article/details/gtfpahdpcw.html

TS:   s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gtbukelxrf.html

Java: s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gtokjqjmwp.html

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gtiptwvxnf.html

Ruby: s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gtukogenxn.html

C#:   s.IndexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gtothccxwj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ydzc1.top/Article/details/gtaspfsltz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gtmfkpuuya.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pycfn.com/Article/details/gtiyyjtaho.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtdyiaczcz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258.top/Article/details/gtfhzsobry.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtwmnngexi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.birdmap.top/Article/details/gtkdfermlj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxuanxn.top/Article/details/gtczpmfwsn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yvedp.cn/Article/details/gtopojjwvd.html

[E06] 替换子串
来源：http://dali.iojbl.cn/Article/details/gtorabkvaj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gtlzpqeibh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.c1oappe.top/Article/details/gtiiabtttr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtzvsgwczd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtnupscjhu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtqjovghyp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvmqxmjk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxeurehio.html

C#:   s.Replace("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtwwqloakt.html

[E07] 按分隔符拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxbrkyxf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gtgzodpmyg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtdstmxind.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xylfe.cn/Article/details/gtpqhyoirj.html

TS:   s.split(",")
来源：http://dali.zdqjudy.top/Article/details/gtxkgjgrsg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zycfv.cn/Article/details/gtnmauiklh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gtckoidwwj.html

Ruby: s.split(",");  s.split
来源：http://dali.ppjwa.cn/Article/details/gtghaqabwo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigufen.top/Article/details/gtzyqbffmm.html

[E08] 数组按分隔符合并
来源：http://dali.chenzaomai.com/Article/details/gtlykjklcn.html

Py:   ",".join(items)
来源：http://dali.mhx1999.top/Article/details/gthgwrrler.html

PHP:  implode(",", $items);
来源：http://dali.nanxuanxn.top/Article/details/gttcbxqujk.html

JS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtwosbgikq.html

TS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtxnurfygx.html

Java: String.join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gtgudojezq.html

Go:   strings.Join(items, ",")
来源：http://dali.pengpengdd.cyou/Article/details/gtszgldrol.html

Ruby: items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtggalxxaw.html

C#:   string.Join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtylhfvttq.html

[E09] 去除所有空白字符
来源：http://dali.sufxvd.cn/Article/details/gttnanuubu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.0kj1m.cn/Article/details/gtrienunaw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cheryme.top/Article/details/gthmzlzknd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gteqewudzj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gtoefdxlbh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gtiaspnlrq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shuidangran.top/Article/details/gtqiwrzaxg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sxryk.cn/Article/details/gtlnqegbvc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jianghu66.top/Article/details/gtjhxjwqkb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jqgufenzy.top/Article/details/gtzljokyet.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gteahbohsw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hywenlv.cn/Article/details/gtbmsfhpps.html

JS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtoddshvjf.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtwwtqjlcw.html

Java: String.format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtghzgsntr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtkwaddonn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtgcasarqe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tian-w.cn/Article/details/gtbrscedrk.html

[E11] 反转字符串
来源：http://dali.chenzaomai.com/Article/details/gtnxxqgrbs.html

Py:   s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtytqabohn.html

PHP:  strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gttosvrqrt.html

JS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtfnmahnyo.html

TS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gttwkmrmce.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gaohongyu789.top/Article/details/gtiqohqyto.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daxiang520.top/Article/details/gterbuvmgt.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtyayqmtrj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtlzloguuq.html

[E12] 统计某字符出现次数
来源：http://dali.tanke756.top/Article/details/gtryobpjlq.html

Py:   s.count("a")
来源：http://dali.xinyue.icu/Article/details/gtyztryofi.html

PHP:  substr_count($s, "a");
来源：http://dali.shzxlz.cn/Article/details/gtonwhprqq.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtescbpnqk.html

TS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtxiccatou.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.havefunace.top/Article/details/gtgxjmbzmq.html

Go:   strings.Count(s, "a")
来源：http://dali.jiagoushi.top/Article/details/gtwpkalqob.html

Ruby: s.count("a")
来源：http://dali.jlsjyb.cn/Article/details/gtkgkiesmk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sufxvd.cn/Article/details/gtaarvrzzx.html

[E13] 逐字符遍历
来源：http://dali.tianlin.xyz/Article/details/gtxkngxmzp.html

Py:   for ch in s: print(ch)
来源：http://dali.shangyingyoupin.top/Article/details/gtpsvocvrn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cheryme.top/Article/details/gtzeubkaxv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtfemytgoe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtxaailbpa.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhvnbywd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gaohongyu789.top/Article/details/gtcgmicfsd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhengqikj.top/Article/details/gtpqwigpuj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtabdmpaut.html

[E14] URL 编码与 Base64
来源：http://dali.xuanzx.com/Article/details/gthtuzxbtf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnxiangtu.top/Article/details/gtlgpnucyv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtkaqromib.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tian-w.cn/Article/details/gtczstgxkv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigfzy.top/Article/details/gtsckbqogf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigufen.top/Article/details/gttqxnjvju.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangtech.top/Article/details/gtbznyysdy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtdrputsyz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtkwiyviql.html

[E15] HTML 转义 / 反转义
来源：http://dali.smart0.xyz/Article/details/gtnvaeusyq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhoulong.xyz/Article/details/gtpyyadpds.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.svipenyu.cn/Article/details/gtpgjnsfuc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gtsosytchj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gtsddpenir.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pycfn.com/Article/details/gtcjqqwigh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cheryme.top/Article/details/gtxkekbpph.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj202588.top/Article/details/gtzvpskmkq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigfzy.top/Article/details/gtwznjbnfp.html

[E16] 数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gtqrzeoreb.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gtewhznvoq.html

PHP:  number_format(1234567);
来源：http://dali.daxiang520.top/Article/details/gtgtpldzdu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gticindpqn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gtauipadif.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.birdmap.top/Article/details/gtfbzbntzs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenjidiqi.icu/Article/details/gtbxpxplmq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sysykeji.top/Article/details/gtgugzmwhf.html

C#:   1234567.ToString("N0")
来源：http://dali.andypj.xyz/Article/details/gtlynccajj.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gtofdfwndi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hongshengwenyu.top/Article/details/gtxznyteyr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgfzy.top/Article/details/gtvvnwdacu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtaeuswgnt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gtmazervkn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmjlpajg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtwzagxtut.html

Ruby: s.capitalize
来源：http://dali.c1oappe.top/Article/details/gtcbdmkysk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfxdhsep.html

[E18] 模板占位符替换
来源：http://dali.ivvv.top/Article/details/gtzwcjnzri.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shzxlz.cn/Article/details/gtfxqpgcrn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwoopgtr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtupvjigmt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtfejlisdx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtjafipcup.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtmzrwpduj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangshuangyany.cn/Article/details/gtuturjvpl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gtubncjipb.html

[E19] 多行文本按行拆分
来源：http://dali.jiagoushi.top/Article/details/gtiwtctinv.html

Py:   s.splitlines()
来源：http://dali.jinqigfzy.top/Article/details/gtpzbwmekn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pycfn.com/Article/details/gtaniluaza.html

JS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtvllvmlko.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gthdhwgbio.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbknigrot.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigfzy.top/Article/details/gtqesfdjkr.html

Ruby: s.lines
来源：http://dali.pycfn.com/Article/details/gtxrjaxogy.html

C#:   s.Split('\n')
来源：http://dali.meibo888.top/Article/details/gtlbgiwxqn.html

[E20] 判断字符串是否为空
来源：http://dali.feifeiyinyue.top/Article/details/gtpjdqzpjs.html

Py:   if not s:
来源：http://dali.jqgufenzy.top/Article/details/gtohihgqgb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ybcxt.top/Article/details/gtkcpdyjho.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gaohongyu789.top/Article/details/gtsatllioc.html

TS:   if (s === "") {}
来源：http://dali.cashguo.top/Article/details/gtlbbjlrdw.html

Java: if (s.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gtdntxutvp.html

Go:   if s == "" {}
来源：http://dali.mhx1999.top/Article/details/gttccggjli.html

Ruby: if s.empty?
来源：http://dali.birdmap.top/Article/details/gtbepbrbwa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yueranfly.top/Article/details/gtpksnkauw.html

[E21] 超长截断加省略号
来源：http://dali.tianlin.xyz/Article/details/gtptwixfpx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yvedp.cn/Article/details/gtkesvscju.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtjredoppn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtptwczwip.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtnmvvqjlc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtecahjxht.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gtqfycfgcv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gteptokuzl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtsxshehzz.html

[E22] 字节长度与字符长度
来源：http://dali.yueranfly.top/Article/details/gtwjculspc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gtpmbliqjl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtlysyjtja.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gtapttizwn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtnijyidqx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhixingplan.top/Article/details/gtybiqlwbs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gtnkqirhmd.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtpjumpynh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.meibo888.top/Article/details/gtaobpzerm.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtusgteacf.html

F. 文件与目录
来源：http://dali.chenlongwang.top/Article/details/gtxsqzvlkp.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtmfbyfvae.html

[F01] 读取整个文件
来源：http://dali.zhoulong.xyz/Article/details/gtxmngrgkm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jianghu66.top/Article/details/gtkiuvwagb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtabmdhdck.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhiwuduotai.top/Article/details/gtgqfqpyqq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtwwzmfhdd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtbzzfymhc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ehwqpu.com/Article/details/gtryrgokfb.html

Ruby: File.read("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtkbcmmqcb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.smart0.xyz/Article/details/gteimhvfpk.html

[F02] 逐行读取文件
来源：http://dali.xinyue.icu/Article/details/gtxpqodbxr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jlsjyb.cn/Article/details/gtcpsdqvqs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbvgtfuzs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gtnzcljtef.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtztatinit.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gtprzsgeyz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yvedp.cn/Article/details/gtctaphuvl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cucudq.cn/Article/details/gtyiyfcfyj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xinyue.icu/Article/details/gtcnjoumoe.html

[F03] 写入文件（覆盖）
来源：http://dali.daxiang520.top/Article/details/gthuqmhnlz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.redwolf501.top/Article/details/gtzwcqeezd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gtosehfnoo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtakzjeijy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtyfisctmy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuanzx.com/Article/details/gtcaqgiumj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shuidangran.top/Article/details/gtohzdzocb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgufenzy.top/Article/details/gtpvorckwq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtdbfdhxls.html

[F04] 追加写入文件
来源：http://dali.xinyue.icu/Article/details/gtzfhxntxt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtbfekptfb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.andypj.xyz/Article/details/gtchkpqcvc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtsugclrtp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtvpeoantf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhiwuduotai.top/Article/details/gtjilqmbkl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yueranfly.top/Article/details/gtwrotgwdk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jiagoushi.top/Article/details/gtsxpzfzqw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zycfv.cn/Article/details/gtmwsenrvt.html

[F05] 判断文件或目录是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtgtzjjeuv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zdqjudy.top/Article/details/gtumsmjsfw.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtpnxdhcnv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtjlylgahy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtpxzngdhb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtpzatkfnj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnqzz.top/Article/details/gthuavevui.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtfbvrijxm.html

C#:   File.Exists("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtkjxqmpwo.html

[F06] 删除文件
来源：http://dali.pycfn.com/Article/details/gtlgfhpwwa.html

Py:   os.remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gttckgtcfp.html

PHP:  unlink("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtpmmfwnio.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtffhcanvm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtzsrpgzen.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtdviiexer.html

Go:   os.Remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtyfwmcghk.html

Ruby: File.delete("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtjzqeourk.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtjwjhrmhl.html

[F07] 创建目录（含多级）
来源：http://dali.shuidangran.top/Article/details/gtuuiigbrt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gtjrcsstmc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigfzy.top/Article/details/gtvkjtkegq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gtvwlimaye.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtqyrhbzkp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gtixikkxoc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.vqdsnc.cn/Article/details/gtzqrxgrhg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjxjbnkf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigufen.top/Article/details/gtvgnqlldd.html

[F08] 遍历目录
来源：http://dali.316326.xyz/Article/details/gtwefypqwm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tanke756.top/Article/details/gtienjerwc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.redwolf501.top/Article/details/gtxxqhbjzg.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtqromotvx.html

TS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gtvutyqfgv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtoueajgar.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gtlcyyyboz.html

Ruby: Dir.children("dir")
来源：http://dali.snrcjt.cn/Article/details/gtegjvqkff.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtcnrsfxag.html

[F09] 获取文件大小
来源：http://dali.dashuyun.cn/Article/details/gtozjhqepn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtuslnumcc.html

PHP:  filesize("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtrllpdwnn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtpxwbmlxe.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtikuibwpx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtingkvjwl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.316326.xyz/Article/details/gtkspwuleu.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gtgsxkzibp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sweek.top/Article/details/gtyliynqxs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangdashe.top/Article/details/gtatymdvbm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtolxvwens.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daxiang520.top/Article/details/gtcvyllztc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtedjjvkug.html

TS:   path.extname("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtprlhncxk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.meibo888.top/Article/details/gtinzeynhy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtbdvjtthh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtosldkhko.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtnlvziovk.html

[F11] 复制与移动文件
来源：http://dali.jlsjyb.cn/Article/details/gtrhymkupd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gttlhhkniq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xylfe.cn/Article/details/gtqywntzgh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtsqgwxeic.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtfndqzyro.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtfqvewshz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxinkj.top/Article/details/gtfipefcmt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtsizrywww.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cheryme.top/Article/details/gtemkaiffu.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gthflvxdhq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gzhubu.top/Article/details/gtfadelbzq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gtmsgntksa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.smart0.xyz/Article/details/gtrkveigtp.html

TS:   // 同上
来源：http://dali.shuidangran.top/Article/details/gtlleoyghp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258.top/Article/details/gttzvmbyqu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gtfjvzdjzb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gtxzboujwm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuanzx.com/Article/details/gttpfbelzl.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtkqjvraax.html

G. 面向对象
来源：http://dali.0kj1m.cn/Article/details/gtxomplnas.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtzprlmfwt.html

[G01] 定义类
来源：http://dali.kuanghao11.cn/Article/details/gtunyctkiu.html

Py:   class User: pass
来源：http://dali.chenlongwang.top/Article/details/gtyvzwmfus.html

PHP:  class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutlvdmes.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gtsnmukzmd.html

TS:   class User { name: string = ""; }
来源：http://dali.ydzc1.top/Article/details/gtkceagzib.html


<!-- 参考信息 -->