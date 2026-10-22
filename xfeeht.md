代发 wailian999

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.smart0.xyz/Article/details/gt2upzcedgz.html

[E03] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gt2tiqviids.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnxiangtu.top/Article/details/gt2tjuhvdxb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gt2pfawkimm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gt2wojvotbj.html

TS:   s.slice(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lbwlzrhp.html

Java: s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gt2jhjhhrla.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenlongwang.top/Article/details/gt2uufzkmuc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yongpay.top/Article/details/gt2fdxcfsho.html

C#:   s.Substring(1, 3)
来源：http://dali.fengsongda.top/Article/details/gt2qrqzlbwj.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wpkouvtz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gt2ctzzmpdg.html

PHP:  strpos($s, "x");
来源：http://dali.cucudq.cn/Article/details/gt2vxwgupyu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cqqwz.cn/Article/details/gt2jrmgnqvh.html

TS:   s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjkhubcx.html

Java: s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gt2pxduvedj.html

Go:   strings.Index(s, "x")
来源：http://dali.hywenlv.cn/Article/details/gt2gsctwsmd.html

Ruby: s.index("x")
来源：http://dali.zycfv.cn/Article/details/gt2isnyzuwr.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2grbiiaxf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jiagoushi.top/Article/details/gt2wcabuxnq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdzsxubd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yvedp.cn/Article/details/gt2kysxbfzs.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2ogsydviy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yongpay.top/Article/details/gt2jbxprjll.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gt2fwsdkqdp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgufenzy.top/Article/details/gt2lotjdakm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gzhubu.top/Article/details/gt2xyhxbbrw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iggsuvir.html

[E06] 替换子串
来源：http://dali.guowangkeji.top/Article/details/gt2qffkavxt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gt2xvhhigid.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shzxlz.cn/Article/details/gt2zztfgkht.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2yfmppjng.html

TS:   s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2bpgkwsmy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2tgavgtwn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gt2wbhoeiwl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2doszgmnu.html

C#:   s.Replace("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2sfnvtgxe.html

[E07] 按分隔符拆分
来源：http://dali.havefunace.top/Article/details/gt2alubemre.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mbuvngnp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2pbqnidqu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnxiangtu.top/Article/details/gt2drquazoz.html

TS:   s.split(",")
来源：http://dali.guannengcc.top/Article/details/gt2futesylf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzyuhola.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hmbpoirw.html

Ruby: s.split(",");  s.split
来源：http://dali.guowangkeji.top/Article/details/gt2uhluayun.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenlongwang.top/Article/details/gt2wfjkpbyg.html

[E08] 数组按分隔符合并
来源：http://dali.snrcjt.cn/Article/details/gt2hqtaozwz.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gt2ivjpsrfr.html

PHP:  implode(",", $items);
来源：http://dali.yueranfly.top/Article/details/gt2fusnobak.html

JS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gt2gjnlxnbw.html

TS:   items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gt2pqdqplfa.html

Java: String.join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gt2boxrgwtv.html

Go:   strings.Join(items, ",")
来源：http://dali.yj202588.top/Article/details/gt2lsirnmaw.html

Ruby: items.join(",")
来源：http://dali.mhx1999.top/Article/details/gt2tavuztgr.html

C#:   string.Join(",", items)
来源：http://dali.ydzc1.top/Article/details/gt2qpheezct.html

[E09] 去除所有空白字符
来源：http://dali.nwbrower.top/Article/details/gt2secvweul.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fengsongda.top/Article/details/gt2xcdqoyyc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2wlyafcsb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gt2juncoidu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gt2obvzyllz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gt2uzmswrav.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.c1oappe.top/Article/details/gt2bgrdcwlj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hfpthk.cn/Article/details/gt2qagxiyxh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.andypj.xyz/Article/details/gt2nkqwamas.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ivvv.top/Article/details/gt2cklaarlc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2jflsnccy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hibfykje.html

JS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gt2eqbsswsi.html

TS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gt2wwqobkph.html

Java: String.format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2arlpblov.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gt2viqzxjcw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gt2dwodugny.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.andypj.xyz/Article/details/gt2grreslak.html

[E11] 反转字符串
来源：http://dali.pycfn.com/Article/details/gt2qhldrjxm.html

Py:   s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gt2vjtyqjei.html

PHP:  strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gt2iqckuaop.html

JS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gt2lsvelmdv.html

TS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2gtcfowad.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.316326.xyz/Article/details/gt2rtwpuitu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gt2gvlocelz.html

Ruby: s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2dwglzsjk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvyrujwy.html

[E12] 统计某字符出现次数
来源：http://dali.hammf.cn/Article/details/gt2usvgqyma.html

Py:   s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gt2wvrioctq.html

PHP:  substr_count($s, "a");
来源：http://dali.ivvv.top/Article/details/gt2vssrcind.html

JS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gt2uttnkvlg.html

TS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2udtxjvjj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tanke756.top/Article/details/gt2fitlymqu.html

Go:   strings.Count(s, "a")
来源：http://dali.yj202588.top/Article/details/gt2iquowyit.html

Ruby: s.count("a")
来源：http://dali.havefunace.top/Article/details/gt2fjvljmpv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xylfe.cn/Article/details/gt2ckrfowxp.html

[E13] 逐字符遍历
来源：http://dali.yj20258.top/Article/details/gt2lhchexnh.html

Py:   for ch in s: print(ch)
来源：http://dali.316326.xyz/Article/details/gt2aabgtrkg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgufenzy.top/Article/details/gt2hubvydgj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2xusafffj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gt2crfzscqs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2ezouygft.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.9152youxi.cn/Article/details/gt2jtxifiuc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhixingplan.top/Article/details/gt2stzgofju.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cdnleiting.top/Article/details/gt2qcumfoyq.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gt2jpjycist.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cashguo.top/Article/details/gt2krmknice.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.svipenyu.cn/Article/details/gt2oyidbmtb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hammf.cn/Article/details/gt2qvictwhx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2mvqjqqup.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cccydsme.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jianghu66.top/Article/details/gt2zuqisypb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yanxiufei.cn/Article/details/gt2mxlupqlj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ehwqpu.com/Article/details/gt2josmlxvg.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258.top/Article/details/gt2pfnqkqkv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cashguo.top/Article/details/gt2ukjszlza.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2uatphdwq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shzxlz.cn/Article/details/gt2wxzvcsrm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tianlin.xyz/Article/details/gt2snfulojg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpgrcxwh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.bjfxy.top/Article/details/gt2zplfjfka.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangdashe.top/Article/details/gt2swelfmdt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jianghu66.top/Article/details/gt2orecltcj.html

[E16] 数字千分位
来源：http://dali.andypj.xyz/Article/details/gt2ytnyifdr.html

Py:   f"{1234567:,}"
来源：http://dali.hnxiangtu.top/Article/details/gt2lxvkthsi.html

PHP:  number_format(1234567);
来源：http://dali.jinqigufen.top/Article/details/gt2paaiorby.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gt2zeuaztrf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gt2wikyvxay.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fzeonomr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnqzz.top/Article/details/gt2dxaioswf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuxming.cn/Article/details/gt2gyrwdqxb.html

C#:   1234567.ToString("N0")
来源：http://dali.jianghu66.top/Article/details/gt2phclgeyj.html

[E17] 首字母大写
来源：http://dali.havefunace.top/Article/details/gt2mcrfxpwb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.0kj1m.cn/Article/details/gt2sglpzfhi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shuidangran.top/Article/details/gt2purbxned.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dirzllpc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gt2hjypxbtb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.0kj1m.cn/Article/details/gt2xjiuisxo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuxming.cn/Article/details/gt2qgamcpkz.html

Ruby: s.capitalize
来源：http://dali.iojbl.cn/Article/details/gt2cgbjlvzt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigfzy.top/Article/details/gt2ylhupbkk.html

[E18] 模板占位符替换
来源：http://dali.zdqjudy.top/Article/details/gt2lzbgpfpb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hwkjqllv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daria6918.cn/Article/details/gt2yjwopand.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gt2waxbxmyc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2olrcxtkb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gt2buzvectt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2ndmijjnx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gogol.net.cn/Article/details/gt2hgpvgjfl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shuidangran.top/Article/details/gt2fsfktmpv.html

[E19] 多行文本按行拆分
来源：http://dali.mhx1999.top/Article/details/gt2qnaclxyq.html

Py:   s.splitlines()
来源：http://dali.gaohongyu789.top/Article/details/gt2mpcjcscu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vbdvmgfp.html

JS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gt2rktuqghw.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gt2wirhfzwk.html

Java: s.lines().toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2fxekskpg.html

Go:   strings.Split(s, "\n")
来源：http://dali.zycfv.cn/Article/details/gt2xcajjtjs.html

Ruby: s.lines
来源：http://dali.chenzaomai.com/Article/details/gt2cthldcpw.html

C#:   s.Split('\n')
来源：http://dali.hongshengwenyu.top/Article/details/gt2yodslocf.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigufen.top/Article/details/gt2vszjlrgm.html

Py:   if not s:
来源：http://dali.xuanzx.com/Article/details/gt2oxlvizyu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daxiang520.top/Article/details/gt2ythvaxbq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owlrweua.html

TS:   if (s === "") {}
来源：http://dali.jinqigfzy.top/Article/details/gt2cqtrpnqs.html

Java: if (s.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gt2idmogtxe.html

Go:   if s == "" {}
来源：http://dali.jyoumei.cn/Article/details/gt2qqsknuuv.html

Ruby: if s.empty?
来源：http://dali.vqdsnc.cn/Article/details/gt2avsqyexv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.iojbl.cn/Article/details/gt2aztmljhs.html

[E21] 超长截断加省略号
来源：http://dali.feifeiyinyue.top/Article/details/gt2mepfejfd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.snrcjt.cn/Article/details/gt2pjngajfk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fiybfano.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tnvzcdum.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2qsncmsso.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhnsemsz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jlsjyb.cn/Article/details/gt2wqmxqepf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2hzizvkxt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2gnhlvqoo.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gt2vjnvkeej.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hfpthk.cn/Article/details/gt2plzekkva.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2hrctyfed.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gt2juqtzmbq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gt2iwhdytzf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tianlin.xyz/Article/details/gt2eojorfbm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tianlin.xyz/Article/details/gt2uuqmaxkq.html

Ruby: s.bytesize;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2nhblagoa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258888.top/Article/details/gt2ebifuagg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2pwsvsdrm.html

F. 文件与目录
来源：http://dali.xziqi.cn/Article/details/gt2fmtduwkj.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bchxzknj.html

[F01] 读取整个文件
来源：http://dali.yuanzhike.top/Article/details/gt2ynxhrsbc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xylfe.cn/Article/details/gt2qopcdnrr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2zifqaywv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.iojbl.cn/Article/details/gt2bckedrpp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gt2kiyzwoal.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gt2jdxecaqv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yueranfly.top/Article/details/gt2wxscjzyx.html

Ruby: File.read("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2epbzwlba.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2uevfqmsh.html

[F02] 逐行读取文件
来源：http://dali.hnxiangtu.top/Article/details/gt2wedgasro.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnqzz.top/Article/details/gt2shrenrix.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.mhx1999.top/Article/details/gt2stoigisn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gt2vanvennj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnrxbxgt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gt2mkjclzje.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gcwpcclk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hywenlv.cn/Article/details/gt2dqrurkdc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sweek.top/Article/details/gt2lquumyvq.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gt2krdeuwcz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gt2rehtgled.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gt2yzibhzcl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gt2xggpnazh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gt2vdmwbbgw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gt2izmnnkiz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigufen.top/Article/details/gt2sfbcckde.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gt2ieeksove.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gt2ngxnhpyx.html

[F04] 追加写入文件
来源：http://dali.quarkkingdee.top/Article/details/gt2yrvojgqz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lrhsyked.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dashuyun.cn/Article/details/gt2fedkxgjp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gt2vfjgrbov.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2owyvbmkm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xuanzx.com/Article/details/gt2qhqelgqh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnqzz.top/Article/details/gt2kuasrmsb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gt2gzsfgnxu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dashuyun.cn/Article/details/gt2tglzxeqr.html

[F05] 判断文件或目录是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2rsopgmuq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hywenlv.cn/Article/details/gt2wrjirnui.html

PHP:  file_exists("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2dhozprqz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jdjdvuhn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2ksdadhor.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2zrvyppes.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gt2zkslmbxd.html

Ruby: File.exist?("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2byypsvmy.html

C#:   File.Exists("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2bsthymov.html

[F06] 删除文件
来源：http://dali.yanxiufei.cn/Article/details/gt2zqmcbsoh.html

Py:   os.remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2bupyviju.html

PHP:  unlink("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2vqcgbczd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2ksoztpvu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2wspbjayd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2rmkaymnb.html

Go:   os.Remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2gzhllmnh.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2xksyreiz.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2yfatkcmi.html

[F07] 创建目录（含多级）
来源：http://dali.fengsongda.top/Article/details/gt2eqbzgykb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.0kj1m.cn/Article/details/gt2dlpwrlls.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gt2wekftotj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gt2hyfhjaxy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gt2izyjxjif.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sufxvd.cn/Article/details/gt2cioguaga.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yongpay.top/Article/details/gt2dswxbpsd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aizwys.cn/Article/details/gt2hnuqimjh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tian-w.cn/Article/details/gt2xklkbwzu.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gt2pneupgxh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yanxiufei.cn/Article/details/gt2eqeyvinr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj202588.top/Article/details/gt2zybmjokn.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dvomucix.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gt2gqgbljhl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gt2mqsbxwnr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gt2fbzahzqe.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gt2mxpedyha.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ybcxt.top/Article/details/gt2ncdzabvd.html

[F09] 获取文件大小
来源：http://dali.yonumen.top/Article/details/gt2gregobcw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttlmusae.html

PHP:  filesize("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2clhrfyxm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gt2myykuwet.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gt2yvcfulhv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2kpujzuzz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tianlin.xyz/Article/details/gt2nfyqiotd.html

Ruby: File.size("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dhisxxdj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cdnleiting.top/Article/details/gt2ltalvjqy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.mhx1999.top/Article/details/gt2ofaafuba.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2jngnhtls.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2hsdnzxpp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2vcwptgbr.html

TS:   path.extname("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2cjocohyt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ivvv.top/Article/details/gt2jhblmajs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2ywhtfrhx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2vsemsdyi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2chuvlgbj.html

[F11] 复制与移动文件
来源：http://dali.sweek.top/Article/details/gt2vpxhctmt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2ntywksgj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sweek.top/Article/details/gt2aodxjlit.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2vxzoqaeb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2xxqkvhzd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dcfobsvf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.quarkkingdee.top/Article/details/gt2xbvqsurn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2ygtuihkf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.mhx1999.top/Article/details/gt2tktywjnw.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gt2kupqexxj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhoulong.xyz/Article/details/gt2ygpdclty.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cdnleiting.top/Article/details/gt2agbckuph.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tianlin.xyz/Article/details/gt2ulxcgytd.html

TS:   // 同上
来源：http://dali.xylfe.cn/Article/details/gt2exomxzkq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gt2htklcnqp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbhjibqt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jianghu66.top/Article/details/gt2xqtemwsq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jianghu66.top/Article/details/gt2hquwcfuo.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2qfvftmjw.html

G. 面向对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uvnxsbpq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2pbjmwwzb.html

[G01] 定义类
来源：http://dali.ehwqpu.com/Article/details/gt2qzpjiaye.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gt2hugbzmnj.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2twizvfvw.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2eziyfnls.html

TS:   class User { name: string = ""; }
来源：http://dali.dashuyun.cn/Article/details/gt2fqmkgrct.html


<!-- 参考信息 -->