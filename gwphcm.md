代发 wailian999

[E02] 重复字符串
来源：http://dali.jqgufenzy.top/Article/details/gtlkxbfpqs.html

Py:   "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gttehhcxpj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gtnxszulfr.html

JS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtlglypnin.html

TS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtnvvsmyuh.html

Java: "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtbcswibgn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.snrcjt.cn/Article/details/gtxwrkgbcs.html

Ruby: "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gtgmagicim.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xziqi.cn/Article/details/gthmdplzsd.html

[E03] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gtbmbljcwx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.snrcjt.cn/Article/details/gtbdfnwrqb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtamhegplb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtzrhznaen.html

TS:   s.slice(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtkjreaues.html

Java: s.substring(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtzukknqiq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigufen.top/Article/details/gtlscfkhdz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gtvqbungyc.html

C#:   s.Substring(1, 3)
来源：http://dali.xuanzx.com/Article/details/gtextpacwv.html

[E04] 查找子串位置
来源：http://dali.hywenlv.cn/Article/details/gthgcdhfhr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gtkqljgslc.html

PHP:  strpos($s, "x");
来源：http://dali.sysykeji.top/Article/details/gtenwlnwxv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pycfn.com/Article/details/gtgysiwemq.html

TS:   s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtaqefzjsv.html

Java: s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtczrwoz.html

Go:   strings.Index(s, "x")
来源：http://dali.jiagoushi.top/Article/details/gtyfwgshvo.html

Ruby: s.index("x")
来源：http://dali.jinqigufen.top/Article/details/gtveqapjje.html

C#:   s.IndexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtkihvpgjn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dianchejie.cn/Article/details/gtuitsupix.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yongpay.top/Article/details/gtdibpkbba.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cdnleiting.top/Article/details/gtjvrcnlev.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gtgqvwecmk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinqigufen.top/Article/details/gtfsxthteo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gthszffiam.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tianlin.xyz/Article/details/gtqfazslxi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawfgpfyi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtwfnqqczt.html

[E06] 替换子串
来源：http://dali.yuanzhike.top/Article/details/gtshtmrxlj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtmpdrrkyc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aibaodan.cn/Article/details/gtgoejfpzq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclidrgyp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtcgiivwxh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtgjeornoc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gtfywaytnz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtrcpubqts.html

C#:   s.Replace("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtbimvvduy.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gtihgconyz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenlongwang.top/Article/details/gtryrzzdrr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfqttean.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guannengcc.top/Article/details/gtvwqxzazx.html

TS:   s.split(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtpkkogbgi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuetiantiany.cn/Article/details/gtfgbgppbm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.c1oappe.top/Article/details/gtrzxgdqax.html

Ruby: s.split(",");  s.split
来源：http://dali.hywenlv.cn/Article/details/gtwxcxrpfg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hammf.cn/Article/details/gtjzltltpo.html

[E08] 数组按分隔符合并
来源：http://dali.cqqwz.cn/Article/details/gtzanhayce.html

Py:   ",".join(items)
来源：http://dali.zhiwuduotai.top/Article/details/gtkphmvknr.html

PHP:  implode(",", $items);
来源：http://dali.daxiang520.top/Article/details/gtzyodfrok.html

JS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gtnkhpklhl.html

TS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtesjqrgge.html

Java: String.join(",", items)
来源：http://dali.zycfv.cn/Article/details/gtxgajqbce.html

Go:   strings.Join(items, ",")
来源：http://dali.zhongyouzk.top/Article/details/gtbzogllzj.html

Ruby: items.join(",")
来源：http://dali.aizwys.cn/Article/details/gthikqpdhg.html

C#:   string.Join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtnophnihh.html

[E09] 去除所有空白字符
来源：http://dali.xuetiantiany.cn/Article/details/gtmkwmjtaq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sufxvd.cn/Article/details/gtzluaoboc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shzxlz.cn/Article/details/gtoyteqqbu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gtdnhxoptv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gtlpvsrhue.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtrvpwvtfu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guowangkeji.top/Article/details/gttmkoazou.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ppjwa.cn/Article/details/gteqpwbumh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yanxiufei.cn/Article/details/gtbygcvwaf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daxiang520.top/Article/details/gtuswprtlo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtkehcpche.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ehwqpu.com/Article/details/gtbeiblyvr.html

JS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtlaaavimc.html

TS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtdjbwpxlu.html

Java: String.format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtqdyqlucc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtmuimdsxx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtgjjhklhz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sysykeji.top/Article/details/gtkwxmomhc.html

[E11] 反转字符串
来源：http://dali.shzxlz.cn/Article/details/gtaimdzgjt.html

Py:   s[::-1]
来源：http://dali.cucudq.cn/Article/details/gthubbpgth.html

PHP:  strrev($s);
来源：http://dali.cucudq.cn/Article/details/gtzxzuaqyy.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtjoyuhnxp.html

TS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtwpinmvvn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fzhhl.top/Article/details/gtorsitrkc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyeachudv.html

Ruby: s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyiymkleb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gtubkkloqn.html

[E12] 统计某字符出现次数
来源：http://dali.mhx1999.top/Article/details/gtyuiloiev.html

Py:   s.count("a")
来源：http://dali.birdmap.top/Article/details/gtisoznifa.html

PHP:  substr_count($s, "a");
来源：http://dali.snrcjt.cn/Article/details/gtqywgzcab.html

JS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gttfbpddcv.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtzauyjbqf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.0kj1m.cn/Article/details/gtfjsqumeb.html

Go:   strings.Count(s, "a")
来源：http://dali.yueranfly.top/Article/details/gtodcvnstm.html

Ruby: s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteorvphya.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gtpwscaczx.html

[E13] 逐字符遍历
来源：http://dali.jyoumei.cn/Article/details/gtayttnnuh.html

Py:   for ch in s: print(ch)
来源：http://dali.gotoacloud.top/Article/details/gtxqhicifc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ppjwa.cn/Article/details/gtmqkanupc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtadzlxhby.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtoxkttjit.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtxzwdxild.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jyoumei.cn/Article/details/gtqxtzobej.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhixingplan.top/Article/details/gtlcbnvgww.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtefewoojv.html

[E14] URL 编码与 Base64
来源：http://dali.pycfn.com/Article/details/gtpholssjt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxzrkhke.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfxhabqa.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yueranfly.top/Article/details/gtfrnkxgtd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dianchejie.cn/Article/details/gtasbqoocm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gteuxpwqnp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hysaishi.cn/Article/details/gtlvxzcfpt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jianghu66.top/Article/details/gtscfzpnrr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cheryme.top/Article/details/gtluxfiyol.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gtkuexoehe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tian-w.cn/Article/details/gtcupmdgyi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.mhx1999.top/Article/details/gtzgkrquon.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenlongwang.top/Article/details/gtefpizdzp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.meibo888.top/Article/details/gtyjgsynou.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jiagoushi.top/Article/details/gttccceuiw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gtrkibdyqk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gtrfwlxuby.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hfpthk.cn/Article/details/gtzlvwehwl.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtdehhpzgz.html

Py:   f"{1234567:,}"
来源：http://dali.snrcjt.cn/Article/details/gtfjmnzzyj.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcpeljta.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gtkyleqbqj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtzpeqbnku.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gthrdclejz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fzhhl.top/Article/details/gtvejfwmyy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxinkj.top/Article/details/gtcidjwgdt.html

C#:   1234567.ToString("N0")
来源：http://dali.cdnleiting.top/Article/details/gtucbhignp.html

[E17] 首字母大写
来源：http://dali.ppjwa.cn/Article/details/gtcnedguhd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.meibo888.top/Article/details/gtabguqtoy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yueranfly.top/Article/details/gtouieewzb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtaetpmjpw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtfihigwyx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.bjfxy.top/Article/details/gtnshksmwa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.mhx1999.top/Article/details/gtnrrkkiqj.html

Ruby: s.capitalize
来源：http://dali.yanxiufei.cn/Article/details/gtlaqogvfp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hfpthk.cn/Article/details/gtghggmoww.html

[E18] 模板占位符替换
来源：http://dali.chenlongwang.top/Article/details/gtrwqhcenq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.9152youxi.cn/Article/details/gtzrkattgj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnqzz.top/Article/details/gttwwytzaf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gthzmrazzo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gturujhowh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtmgdfwsqw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtaglbyawh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zycfv.cn/Article/details/gtzlwmrohz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenzaomai.com/Article/details/gtxvwhkfuz.html

[E19] 多行文本按行拆分
来源：http://dali.nanxinkj.top/Article/details/gttaezwfgj.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpnvqbwd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtbhlnrkmb.html

JS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtzerxelwh.html

TS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gtminpmewq.html

Java: s.lines().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtfppyhptu.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenlongwang.top/Article/details/gtvjkjvsjm.html

Ruby: s.lines
来源：http://dali.guowangkeji.top/Article/details/gtpfurtrol.html

C#:   s.Split('\n')
来源：http://dali.xziqi.cn/Article/details/gtdhacpnfn.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gtmftyloil.html

Py:   if not s:
来源：http://dali.gaohongyu789.top/Article/details/gtzokfxzdm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gaohongyu789.top/Article/details/gtesduyqvg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xziqi.cn/Article/details/gtlrobuyfn.html

TS:   if (s === "") {}
来源：http://dali.vqdsnc.cn/Article/details/gtdnachpfb.html

Java: if (s.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gtxptzneda.html

Go:   if s == "" {}
来源：http://dali.tianlin.xyz/Article/details/gtdrjkjddg.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gtbemxvopb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnqzz.top/Article/details/gtbnnmbnat.html

[E21] 超长截断加省略号
来源：http://dali.zhengqikj.top/Article/details/gtowvqubsw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.snrcjt.cn/Article/details/gtexhuppdm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtrrowgeiy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtweflnwpi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtdfyfdiea.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtpulsewuy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gzhubu.top/Article/details/gtaeoghtfl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gtgnbdqgjs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtbynnmoyh.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gtsboiomgd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.smart0.xyz/Article/details/gtdaktimhu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtzwdvktye.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtahnzsvln.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtjpxzqpso.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gtlmushhnp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shangyingyoupin.top/Article/details/gtlfqrsvaw.html

Ruby: s.bytesize;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtjzewjawh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dashuyun.cn/Article/details/gtomqwordq.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtbprnmmqs.html

F. 文件与目录
来源：http://dali.meibo888.top/Article/details/gtpduvscgx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtbiuhoakq.html

[F01] 读取整个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuoqlsmij.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqbxestl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtnoopecty.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gtfhnohsrd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cheryme.top/Article/details/gttzbmttdq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtinhkdmsg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gtnhienfkk.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtnnepiyzy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtvncqrkyp.html

[F02] 逐行读取文件
来源：http://dali.shzxlz.cn/Article/details/gtprrugzxt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hfpthk.cn/Article/details/gtxyhkfoin.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pycfn.com/Article/details/gtyotrqtnj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtuglybtwb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtqdfpxmje.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gtxnuyhpdo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnqzz.top/Article/details/gtjkkgcvvv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.meibo888.top/Article/details/gtfbpcgjli.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuanzx.com/Article/details/gtypocxefu.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258.top/Article/details/gtyaazzvpf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtjoabvvpc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtutopzney.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtqyasaxta.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gteuahcedv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.quarkkingdee.top/Article/details/gtzrkpgith.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gaohongyu789.top/Article/details/gtiarucnlf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sysykeji.top/Article/details/gtbgrqseva.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtzutwnofk.html

[F04] 追加写入文件
来源：http://dali.xuanzx.com/Article/details/gtdrxrvefg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenzaomai.com/Article/details/gtvvllgqua.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuanzhike.top/Article/details/gtxmscmjhw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtgcqtarsj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtdxngrvkv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gotoacloud.top/Article/details/gtfmjdlkax.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ivvv.top/Article/details/gtdsdqxpxt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.havefunace.top/Article/details/gthnycrxvr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtckhmfikp.html

[F05] 判断文件或目录是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtxgplcdnq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hywenlv.cn/Article/details/gtuwmmxvgi.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtrlguwpww.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtrzptekad.html

TS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gthqwnozdl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gttfdnwesk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gtlisxizal.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtaxhrthpl.html

C#:   File.Exists("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtzhklsuba.html

[F06] 删除文件
来源：http://dali.xziqi.cn/Article/details/gtjihzaapm.html

Py:   os.remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtriawbirv.html

PHP:  unlink("a.txt");
来源：http://dali.ivvv.top/Article/details/gtlegndfqz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtaynufimi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtaesgrpne.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtgamzjhzu.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtpvypzynq.html

Ruby: File.delete("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtrnealovo.html

C#:   File.Delete("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtnjdskjpg.html

[F07] 创建目录（含多级）
来源：http://dali.birdmap.top/Article/details/gtaxrdlebi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gtpbokvqcn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yanxiufei.cn/Article/details/gteahnpcjc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gtqmyvdkeh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gtfleulncp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sysykeji.top/Article/details/gtfinnxtpn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258888.top/Article/details/gtatmitqef.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gtabswpasa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhiwuduotai.top/Article/details/gtldkyckts.html

[F08] 遍历目录
来源：http://dali.smart0.xyz/Article/details/gtguekwvrf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gtglxprjab.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fengsongda.top/Article/details/gtaggvgbvl.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtxkifjrpr.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtvdxqmrcr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtixreirnp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gticvmwdya.html

Ruby: Dir.children("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtoacsexli.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jyoumei.cn/Article/details/gtoechhjyq.html

[F09] 获取文件大小
来源：http://dali.mhx1999.top/Article/details/gtarnaapkt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuanzx.com/Article/details/gthkulzdyz.html

PHP:  filesize("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtqjzyhydw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnyoyvfo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtbthwfgum.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtuuwragir.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.vqdsnc.cn/Article/details/gtrxdmrvaq.html

Ruby: File.size("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtxkhcqkpv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ybcxt.top/Article/details/gtxypvbscq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sweek.top/Article/details/gtprihnunb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtschfzbzi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtvsnatxci.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtzjdhihbx.html

TS:   path.extname("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtudrwqgmq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hysaishi.cn/Article/details/gtjpcyvxia.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtkmbjfzxq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtjcxokgtx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtlkwfwsdd.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gtcrqxlqbj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtyfqzritd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenzaomai.com/Article/details/gtqweztykx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkexslgn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtccidixnk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtpsvfrohx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jianghu66.top/Article/details/gtzwomruoa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtedjzsuzs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuetiantiany.cn/Article/details/gtztbbsrid.html

[F12] CSV 读写
来源：http://dali.jyoumei.cn/Article/details/gtiefmdzlf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangdashe.top/Article/details/gtpcydpgun.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cashguo.top/Article/details/gtalbunfxa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuetiantiany.cn/Article/details/gttwfpdptu.html

TS:   // 同上
来源：http://dali.nanxuanxn.top/Article/details/gtbirlirbo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.birdmap.top/Article/details/gtwwykelrp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gtqsdtafzf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gtaqrjutbr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gtfnozxtbr.html


<!-- 参考信息 -->