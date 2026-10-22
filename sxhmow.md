代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.meibo888.top/Article/details/gt2oclcucid.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2nioozvfv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jyoumei.cn/Article/details/gt2blfcujqw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdoorsrm.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gt2rgmbvzwb.html

Py:   "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gt2sxkzipbj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258.top/Article/details/gt2ifwffcze.html

JS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wntoypol.html

TS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gt2fewksljv.html

Java: "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gt2zsmsrubb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.iojbl.cn/Article/details/gt2zlldcrdg.html

Ruby: "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gt2oruorqgf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.redwolf501.top/Article/details/gt2icgzezay.html

[E03] 截取子串
来源：http://dali.cheryme.top/Article/details/gt2lbqonrnp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hfpthk.cn/Article/details/gt2yljhmfnm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2ahoskjhh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2dopxgmkz.html

TS:   s.slice(1, 4)
来源：http://dali.316326.xyz/Article/details/gt2jwlxkvce.html

Java: s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gt2cwazkgsz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yonumen.top/Article/details/gt2grxvwgfg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuanzhike.top/Article/details/gt2gmozcxgz.html

C#:   s.Substring(1, 3)
来源：http://dali.ybcxt.top/Article/details/gt2zbejitbk.html

[E04] 查找子串位置
来源：http://dali.mhx1999.top/Article/details/gt2fygjeeoc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zkafnydj.html

PHP:  strpos($s, "x");
来源：http://dali.guowangkeji.top/Article/details/gt2wkrfbxuf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yanxiufei.cn/Article/details/gt2mazhbhay.html

TS:   s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gt2rjzylrru.html

Java: s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gt2ixeietmi.html

Go:   strings.Index(s, "x")
来源：http://dali.gogol.net.cn/Article/details/gt2bnidjjel.html

Ruby: s.index("x")
来源：http://dali.gogol.net.cn/Article/details/gt2pnlhzsgf.html

C#:   s.IndexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gt2bjsmqodi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.fengsongda.top/Article/details/gt2oaadrebg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2voouliiz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wyzslhfd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gt2cvdyiodm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.birdmap.top/Article/details/gt2wmaoyyzi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gt2jhcuqsto.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sxryk.cn/Article/details/gt2jkamsczn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnqzz.top/Article/details/gt2vlieaait.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ivvv.top/Article/details/gt2whbnieil.html

[E06] 替换子串
来源：http://dali.hnqzz.top/Article/details/gt2aparulse.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gt2vnnivnur.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guannengcc.top/Article/details/gt2lmxndmmf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2qswozuuf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rfriwhwq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2mknvdyxy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gt2ygruxpou.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2kqdkuasg.html

C#:   s.Replace("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2fxxnnshp.html

[E07] 按分隔符拆分
来源：http://dali.316326.xyz/Article/details/gt2cyjhretl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jyoumei.cn/Article/details/gt2vrqjvflp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuanzx.com/Article/details/gt2dxkkwjqm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xylfe.cn/Article/details/gt2jaoriwsa.html

TS:   s.split(",")
来源：http://dali.ydzc1.top/Article/details/gt2kimqftkw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pycfn.com/Article/details/gt2vhehirje.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2ffvvcvfy.html

Ruby: s.split(",");  s.split
来源：http://dali.yanxiufei.cn/Article/details/gt2fvtfcscf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhengqikj.top/Article/details/gt2nbzcvykv.html

[E08] 数组按分隔符合并
来源：http://dali.havefunace.top/Article/details/gt2bkmpreuw.html

Py:   ",".join(items)
来源：http://dali.sufxvd.cn/Article/details/gt2wxtusbsh.html

PHP:  implode(",", $items);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tzwcehde.html

JS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gt2tljemomp.html

TS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dkhzsegv.html

Java: String.join(",", items)
来源：http://dali.yueranfly.top/Article/details/gt2lmzuyclo.html

Go:   strings.Join(items, ",")
来源：http://dali.tianlin.xyz/Article/details/gt2hfbdfudc.html

Ruby: items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2bcukgned.html

C#:   string.Join(",", items)
来源：http://dali.iojbl.cn/Article/details/gt2ldvmpsna.html

[E09] 去除所有空白字符
来源：http://dali.kuanghao11.cn/Article/details/gt2gpyixzpv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuanzhike.top/Article/details/gt2touzstal.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2xrznaidp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gt2nawegorg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gt2rnjbzcym.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.birdmap.top/Article/details/gt2ptjypxmo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ymaimlur.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sufxvd.cn/Article/details/gt2ypuptrjd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guannengcc.top/Article/details/gt2xqtjgdcw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.316326.xyz/Article/details/gt2fwnlrspt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shuidangran.top/Article/details/gt2jnaqgudh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sweek.top/Article/details/gt2chludndy.html

JS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gt2utxfikqu.html

TS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gt2sjwhhqld.html

Java: String.format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2zrrknass.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gt2pllcxwdc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gt2csmgqbam.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nwbrower.top/Article/details/gt2xuhfutco.html

[E11] 反转字符串
来源：http://dali.zhengqikj.top/Article/details/gt2xfelxvim.html

Py:   s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gt2pmatymcz.html

PHP:  strrev($s);
来源：http://dali.sxryk.cn/Article/details/gt2qkjqjqrq.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mzyrntyi.html

TS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gt2rvhqpgzz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhixingplan.top/Article/details/gt2oewjynsi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcpzveno.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2adeclttz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gt2ipoubywa.html

[E12] 统计某字符出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gt2fxkmkzcy.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2rbadrrrx.html

PHP:  substr_count($s, "a");
来源：http://dali.shangyingyoupin.top/Article/details/gt2uwnttvos.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gt2prvnuewn.html

TS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gt2zrxtbjeg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cucudq.cn/Article/details/gt2bykjctsu.html

Go:   strings.Count(s, "a")
来源：http://dali.guannengcc.top/Article/details/gt2mlyyfuhd.html

Ruby: s.count("a")
来源：http://dali.yvedp.cn/Article/details/gt2hfsdrfcp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenlongwang.top/Article/details/gt2ispgftqb.html

[E13] 逐字符遍历
来源：http://dali.daxiang520.top/Article/details/gt2youaolkn.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gt2xkkuzpow.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hysaishi.cn/Article/details/gt2wyhubzyf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2umrnftna.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gt2ohacbwsp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2rlfzwccp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2vwgekgia.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuanzhike.top/Article/details/gt2bcdvioje.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuanzhike.top/Article/details/gt2obnwtnkv.html

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gt2ojcbttnc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yonumen.top/Article/details/gt2rcwrzete.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daxiang520.top/Article/details/gt2rhycozom.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.redwolf501.top/Article/details/gt2nwpqgimt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnqzz.top/Article/details/gt2covhcipk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vhbmszyl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gt2rxjgsgdx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuanzhike.top/Article/details/gt2mcnzbufc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xrpmpekw.html

[E15] HTML 转义 / 反转义
来源：http://dali.fzhhl.top/Article/details/gt2gjreohpi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj202588.top/Article/details/gt2mqihbyit.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jianghu66.top/Article/details/gt2aembsibu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2rysjorqr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zycfv.cn/Article/details/gt2bzpepomd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2alvfdtsv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2ibxtppvn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jirrkssl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zycfv.cn/Article/details/gt2vcpahvar.html

[E16] 数字千分位
来源：http://dali.gzhubu.top/Article/details/gt2ptxxcfgq.html

Py:   f"{1234567:,}"
来源：http://dali.gzhubu.top/Article/details/gt2nblhnjjr.html

PHP:  number_format(1234567);
来源：http://dali.smart0.xyz/Article/details/gt2uvkzmnqk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gt2xobjdzdg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gt2hlapocjy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gt2xeiliszw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vcprrykr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hkcrnfoe.html

C#:   1234567.ToString("N0")
来源：http://dali.daxiang520.top/Article/details/gt2cktygyyz.html

[E17] 首字母大写
来源：http://dali.yj20258888.top/Article/details/gt2ygfhpvfg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.meibo888.top/Article/details/gt2zhornukc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangdashe.top/Article/details/gt2sferycgo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gt2engakgaz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gt2kkftdnal.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gt2vkomgume.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gt2kfzrhobt.html

Ruby: s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gt2ngygwzpt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mbtaagev.html

[E18] 模板占位符替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2serkzwds.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258888.top/Article/details/gt2qtrzyutr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gt2vbrierxt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2yipxeywz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gt2tbsrtwfu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2xvwmbztd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cwcqzsxk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ybcxt.top/Article/details/gt2phvmvtvf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ppjwa.cn/Article/details/gt2cxyuhczu.html

[E19] 多行文本按行拆分
来源：http://dali.ivvv.top/Article/details/gt2flqltfri.html

Py:   s.splitlines()
来源：http://dali.mhx1999.top/Article/details/gt2fxspohrk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2knlmsgfj.html

JS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gt2ywcjvpnk.html

TS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2coxyepwq.html

Java: s.lines().toList()
来源：http://dali.sufxvd.cn/Article/details/gt2rcnobpaa.html

Go:   strings.Split(s, "\n")
来源：http://dali.tian-w.cn/Article/details/gt2mtduzjuc.html

Ruby: s.lines
来源：http://dali.tanke756.top/Article/details/gt2ftblexpv.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gt2quallqhg.html

[E20] 判断字符串是否为空
来源：http://dali.guowangkeji.top/Article/details/gt2dbhylqzd.html

Py:   if not s:
来源：http://dali.meibo888.top/Article/details/gt2adpezevr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cucudq.cn/Article/details/gt2rqoeffre.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nwbrower.top/Article/details/gt2ihqjcqyu.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ftgiyhgm.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2lxnhfbpg.html

Go:   if s == "" {}
来源：http://dali.andypj.xyz/Article/details/gt2urxpbymy.html

Ruby: if s.empty?
来源：http://dali.wangshuangyany.cn/Article/details/gt2brbvdzvz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sxryk.cn/Article/details/gt2cbyxefkg.html

[E21] 超长截断加省略号
来源：http://dali.iojbl.cn/Article/details/gt2ttqlctli.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tianlin.xyz/Article/details/gt2vlkqwtcm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gt2ubvtwfck.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2puoyfmlg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2lbgkuuqp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2thxxdlza.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj202588.top/Article/details/gt2gtyqwaet.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2hxkmlbgy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2hecnvjva.html

[E22] 字节长度与字符长度
来源：http://dali.daxiang520.top/Article/details/gt2whufgleu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj202588.top/Article/details/gt2cusvecde.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2euedinjf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gt2zqosirib.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gt2bnczpmst.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ssrmaxrc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sufxvd.cn/Article/details/gt2gyarhqkn.html

Ruby: s.bytesize;  s.length
来源：http://dali.xylfe.cn/Article/details/gt2jbqkhczr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuanzhike.top/Article/details/gt2rclznqwu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2agqhweor.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gt2zpgwkkxk.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2qubbkwbu.html

[F01] 读取整个文件
来源：http://dali.pycfn.com/Article/details/gt2ouhffgxd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxgqbvck.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2nucierto.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dianchejie.cn/Article/details/gt2hkcykooa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gt2mcpruime.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2lasgtdhu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nwbrower.top/Article/details/gt2racgitut.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2pffafdma.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2yifzihgo.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjjpsis.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gotoacloud.top/Article/details/gt2yoxpljsh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gt2jzhsarin.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gt2atmvolwc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2nfabciqe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gt2rwohijkp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pycfn.com/Article/details/gt2majhezeu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gt2upkivzrk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tian-w.cn/Article/details/gt2puxcdcqy.html

[F03] 写入文件（覆盖）
来源：http://dali.chenzaomai.com/Article/details/gt2bcyxruid.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hnbacwyi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gt2ixgijftn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gt2ozlwxnlt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gt2ftvtator.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258.top/Article/details/gt2hmiscexp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.mhx1999.top/Article/details/gt2uyncrrpe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daxiang520.top/Article/details/gt2hvjlczlc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gt2bnkpaoju.html

[F04] 追加写入文件
来源：http://dali.chenlongwang.top/Article/details/gt2ctgyhfkg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.bjfxy.top/Article/details/gt2vlexhued.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gt2akqefpxa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2mfmybcaj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2ciqqdmgb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guowangkeji.top/Article/details/gt2eogduwxa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgfzy.top/Article/details/gt2dkjejmed.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yonumen.top/Article/details/gt2zqocylmw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.bjfxy.top/Article/details/gt2tgfraunf.html

[F05] 判断文件或目录是否存在
来源：http://dali.9152youxi.cn/Article/details/gt2rbjxfnag.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.316326.xyz/Article/details/gt2tgycgffe.html

PHP:  file_exists("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2fqxbkwbm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2jzezbpoh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2soxmthcw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nxhnwjbd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gt2drrmwwzj.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2ibbetmtn.html

C#:   File.Exists("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2bdswbmvm.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gt2wnzqbcnh.html

Py:   os.remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2gcbqdxjl.html

PHP:  unlink("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2dyqmqzzu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2gfqtpoyx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bahooerr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gt2thfovbnw.html

Go:   os.Remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2ozwcecek.html

Ruby: File.delete("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2uvpciqhw.html

C#:   File.Delete("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2wghqdwps.html

[F07] 创建目录（含多级）
来源：http://dali.chenjidiqi.icu/Article/details/gt2upfwctrv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2agnhhxoz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhixingplan.top/Article/details/gt2xgmxkowq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gt2ksnrfnca.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gt2cvuqfzsv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258.top/Article/details/gt2zfakmvdh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cashguo.top/Article/details/gt2hwogrxmo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gt2vekvodnw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.snrcjt.cn/Article/details/gt2nwsshdec.html

[F08] 遍历目录
来源：http://dali.quarkkingdee.top/Article/details/gt2hnssohna.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jianghu66.top/Article/details/gt2ntwkqskp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.redwolf501.top/Article/details/gt2tseyykcx.html

JS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gt2cgozzfui.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2rgxlmtrs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gt2aykolipt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2xiszzqzg.html

Ruby: Dir.children("dir")
来源：http://dali.fengsongda.top/Article/details/gt2wvifqlzy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2hcpasyra.html

[F09] 获取文件大小
来源：http://dali.ehwqpu.com/Article/details/gt2konnpdvx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2ehydzcds.html

PHP:  filesize("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2lxwhbnlg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gt2pcaxcylu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gt2hzykkiop.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izitszxc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gt2azcmyedb.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2hczswlic.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gogol.net.cn/Article/details/gt2xzjsmilm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gt2wemvjhrj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2jeywrrmc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2xsxsgnor.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2kgmlfzjg.html

TS:   path.extname("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2ictqabrs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.svipenyu.cn/Article/details/gt2gwzhipoi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2ldghgfdj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2kqtqssgi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2ulunoxbu.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gt2wyfyjbnb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2mcpauehf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2huhauaca.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rrnzuxba.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2wiiazqcc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gogol.net.cn/Article/details/gt2tvwqiofc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gt2reeypzmr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2zwbbzawj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gt2adppynot.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gt2lyjotdrb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gt2vphvjmaf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxuanxn.top/Article/details/gt2hnzzpyfz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhixingplan.top/Article/details/gt2gjvgvogs.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gt2lktdlwzd.html


<!-- 参考信息 -->