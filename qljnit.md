代发 wailian999

Go:   strings.Index(s, "x")
来源：http://dali.yanxiufei.cn/Article/details/gt2dsqidcyf.html

Ruby: s.index("x")
来源：http://dali.xziqi.cn/Article/details/gt2xcaopfgc.html

C#:   s.IndexOf("x")
来源：http://dali.yj202588.top/Article/details/gt2lmhqylhd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gotoacloud.top/Article/details/gt2ybbvdvom.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jyoumei.cn/Article/details/gt2rcpeknfl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwcovwiz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gt2mhyhxyna.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xinyue.icu/Article/details/gt2mbhakutu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gt2jccboamx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.9152youxi.cn/Article/details/gt2dymvquhx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yongpay.top/Article/details/gt2ldzeufer.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.redwolf501.top/Article/details/gt2bnchazcq.html

[E06] 替换子串
来源：http://dali.kuanghao11.cn/Article/details/gt2hkwhhxcy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2ifwecxvi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhixingplan.top/Article/details/gt2rqrgnwmy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2fdouorfp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2kepvdbad.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2tpqzfbhk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gt2jcswtlry.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2dyembqwu.html

C#:   s.Replace("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2llsejmun.html

[E07] 按分隔符拆分
来源：http://dali.c1oappe.top/Article/details/gt2fduagdgz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.havefunace.top/Article/details/gt2xsnnhnrq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kbmvxfzs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xinyue.icu/Article/details/gt2jdaxuidf.html

TS:   s.split(",")
来源：http://dali.316326.xyz/Article/details/gt2gketuygq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dianchejie.cn/Article/details/gt2aivbvdfh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ivvv.top/Article/details/gt2vkdzqbxx.html

Ruby: s.split(",");  s.split
来源：http://dali.9152youxi.cn/Article/details/gt2jdmleaet.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yvedp.cn/Article/details/gt2xqnohuht.html

[E08] 数组按分隔符合并
来源：http://dali.cucudq.cn/Article/details/gt2woyahfch.html

Py:   ",".join(items)
来源：http://dali.kuanghao11.cn/Article/details/gt2ebtsetwg.html

PHP:  implode(",", $items);
来源：http://dali.yueranfly.top/Article/details/gt2wtppdfgp.html

JS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gt2usujqxye.html

TS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gt2xyjazbzl.html

Java: String.join(",", items)
来源：http://dali.redwolf501.top/Article/details/gt2hgiabmrk.html

Go:   strings.Join(items, ",")
来源：http://dali.zdqjudy.top/Article/details/gt2xomogvwn.html

Ruby: items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2kebgleku.html

C#:   string.Join(",", items)
来源：http://dali.xuanzx.com/Article/details/gt2plyqooar.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gt2ntvyvuvb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.haohaochexian.top/Article/details/gt2eogvmhyk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2lxcmvdnc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2mnknllep.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gt2nhoomuuy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tian-w.cn/Article/details/gt2iwghwjio.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ehwqpu.com/Article/details/gt2aywebtmm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgufenzy.top/Article/details/gt2zichuwry.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzegska.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fzhhl.top/Article/details/gt2psrwegqm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cheryme.top/Article/details/gt2pkpdylkl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.haohaochexian.top/Article/details/gt2ozkkmsxw.html

JS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2yfheqbar.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2donxloau.html

Java: String.format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2lwmvookr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gt2ihqpuukc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gt2rlxnrqcp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yongpay.top/Article/details/gt2fkqdqpek.html

[E11] 反转字符串
来源：http://dali.jiagoushi.top/Article/details/gt2iiggturf.html

Py:   s[::-1]
来源：http://dali.gzhubu.top/Article/details/gt2hdfjbkxg.html

PHP:  strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gt2htzsouse.html

JS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2wvmkrvam.html

TS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2kpaotqbs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.redwolf501.top/Article/details/gt2fimvbxwm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shuidangran.top/Article/details/gt2plhcvbbx.html

Ruby: s.reverse
来源：http://dali.guannengcc.top/Article/details/gt2oyjvnjbt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gt2eamamezl.html

[E12] 统计某字符出现次数
来源：http://dali.yuanzhike.top/Article/details/gt2dzvqkiud.html

Py:   s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gt2gtxvkcpc.html

PHP:  substr_count($s, "a");
来源：http://dali.cdnleiting.top/Article/details/gt2xfinnplw.html

JS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gt2ozoevqiy.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gt2zlysjujx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gt2emfzobhn.html

Go:   strings.Count(s, "a")
来源：http://dali.hnqzz.top/Article/details/gt2tbyejike.html

Ruby: s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gt2lduqzatc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangdashe.top/Article/details/gt2yfthpxeu.html

[E13] 逐字符遍历
来源：http://dali.yangfankeji.com/Article/details/gt2lgalzrlf.html

Py:   for ch in s: print(ch)
来源：http://dali.jiagoushi.top/Article/details/gt2jtjyudhv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cucudq.cn/Article/details/gt2tslbyvav.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gt2tergobmc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gt2hpuwkeub.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2rneppire.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.316326.xyz/Article/details/gt2qowioved.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ybcxt.top/Article/details/gt2muaiybtn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhixingplan.top/Article/details/gt2jfpagoam.html

[E14] URL 编码与 Base64
来源：http://dali.hnxiangtu.top/Article/details/gt2qsdrlgtt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jlsjyb.cn/Article/details/gt2uggoluxw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.316326.xyz/Article/details/gt2jvrwwftu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.redwolf501.top/Article/details/gt2htpediwn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jianghu66.top/Article/details/gt2zqaztlfh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxinkj.top/Article/details/gt2goawlrzf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhengqikj.top/Article/details/gt2yobjeilr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zrtizbtv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zdqjudy.top/Article/details/gt2frrxhgmk.html

[E15] HTML 转义 / 反转义
来源：http://dali.ivvv.top/Article/details/gt2yznzpfbd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2vorsjgpo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xylfe.cn/Article/details/gt2pzjwnsct.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ppjwa.cn/Article/details/gt2rrymdeon.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yongpay.top/Article/details/gt2rvmhngih.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hysaishi.cn/Article/details/gt2axneyvku.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sweek.top/Article/details/gt2nseglqzf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2oegyvmvc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.iojbl.cn/Article/details/gt2kswymhvs.html

[E16] 数字千分位
来源：http://dali.gzhubu.top/Article/details/gt2jrhinkme.html

Py:   f"{1234567:,}"
来源：http://dali.cqqwz.cn/Article/details/gt2iogkcjxg.html

PHP:  number_format(1234567);
来源：http://dali.shuidangran.top/Article/details/gt2kpffzsui.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gt2wsdcaecp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gt2wxiyyhho.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgfzy.top/Article/details/gt2fthnvbkg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cucudq.cn/Article/details/gt2atuqzurz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daria6918.cn/Article/details/gt2kbyrwhtc.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gt2psyashte.html

[E17] 首字母大写
来源：http://dali.wangshuangyany.cn/Article/details/gt2uridpxpo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.haohaochexian.top/Article/details/gt2bohencyf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guowangkeji.top/Article/details/gt2yvcrfifw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gt2xrzydkjr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gt2lbwbtbgp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gotoacloud.top/Article/details/gt2pbyxiihw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.snrcjt.cn/Article/details/gt2rpetjmfr.html

Ruby: s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gt2oznzeqtr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lioeunci.html

[E18] 模板占位符替换
来源：http://dali.wangdashe.top/Article/details/gt2evdwukhz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ejpfkzqd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.iojbl.cn/Article/details/gt2msgmjlbp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2fhiimbsx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uumksnvk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gt2rqpfgvgf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2vvbavsba.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigfzy.top/Article/details/gt2vtmzptgp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.bjfxy.top/Article/details/gt2tuypiety.html

[E19] 多行文本按行拆分
来源：http://dali.hywenlv.cn/Article/details/gt2qbjifasj.html

Py:   s.splitlines()
来源：http://dali.fengsongda.top/Article/details/gt2zpcfsafe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2gmimkyaa.html

JS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gt2zhvaiuln.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gt2isbhjfzf.html

Java: s.lines().toList()
来源：http://dali.ivvv.top/Article/details/gt2vxoykjnp.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gt2zmchnoey.html

Ruby: s.lines
来源：http://dali.yongpay.top/Article/details/gt2vetaorhc.html

C#:   s.Split('\n')
来源：http://dali.tanke756.top/Article/details/gt2bplmetcg.html

[E20] 判断字符串是否为空
来源：http://dali.cheryme.top/Article/details/gt2dwnpwbuu.html

Py:   if not s:
来源：http://dali.svipenyu.cn/Article/details/gt2mqapuocz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sxryk.cn/Article/details/gt2wajjlvfw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gotoacloud.top/Article/details/gt2gozbwbgu.html

TS:   if (s === "") {}
来源：http://dali.yuxming.cn/Article/details/gt2hiumplhn.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2imdinuar.html

Go:   if s == "" {}
来源：http://dali.yj20258888.top/Article/details/gt2prhebvzk.html

Ruby: if s.empty?
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gshujefo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sxryk.cn/Article/details/gt2rsoaeemw.html

[E21] 超长截断加省略号
来源：http://dali.xylfe.cn/Article/details/gt2suxvcrev.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.quarkkingdee.top/Article/details/gt2tycssyzr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2pjccsgqm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2xlarkkhs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2mvqjjqvr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfpytpg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yonumen.top/Article/details/gt2irxjnxxl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2wdirtzkb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2wxelltxg.html

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtzaqmuq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2cmhjfvlk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gt2icdyidmz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gt2fjqmwlaj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2gizfhakg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gt2pphjwsmk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yueranfly.top/Article/details/gt2qulwrddp.html

Ruby: s.bytesize;  s.length
来源：http://dali.9152youxi.cn/Article/details/gt2ggaxqnkj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvmmaqmz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2hmfnszgn.html

F. 文件与目录
来源：http://dali.iojbl.cn/Article/details/gt2uapoyaay.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmanolbb.html

[F01] 读取整个文件
来源：http://dali.xinyue.icu/Article/details/gt2rpodnbwk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jyoumei.cn/Article/details/gt2dvlogtwj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2kneavgoq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gt2zzenlnfk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhtygfwg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2fobzqgxk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daria6918.cn/Article/details/gt2wdmbanwp.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2lubhkozp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2rohsnwye.html

[F02] 逐行读取文件
来源：http://dali.aizwys.cn/Article/details/gt2yzlrvmsa.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.kuanghao11.cn/Article/details/gt2kjzvksim.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sysykeji.top/Article/details/gt2yiorlnsc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gt2bjfjxaim.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gt2kqfvwtts.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gt2cncahqnf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2igmsnwfe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nnvawfbf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxinkj.top/Article/details/gt2lyiqhzru.html

[F03] 写入文件（覆盖）
来源：http://dali.pengpengdd.cyou/Article/details/gt2tjwigpsi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sxryk.cn/Article/details/gt2getzztcq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2tcsdkuot.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gt2xfpvqlag.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwwnhfuk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.haohaochexian.top/Article/details/gt2jydikohx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qafdfnwj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2jvhpwhwd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gt2lmyhpuji.html

[F04] 追加写入文件
来源：http://dali.ppjwa.cn/Article/details/gt2zxpfendu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dkfeujct.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gotoacloud.top/Article/details/gt2xhzqcuct.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2ekmifbab.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gt2kbkurtjs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gt2rdrqpsvk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wsruhbrl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.mhx1999.top/Article/details/gt2dqagxbjs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daria6918.cn/Article/details/gt2bnyototp.html

[F05] 判断文件或目录是否存在
来源：http://dali.shuidangran.top/Article/details/gt2flbggnif.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sweek.top/Article/details/gt2oysdsgau.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2vgbltpbj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2wphaaryu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2bdhozehb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2rycvpjeo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj202588.top/Article/details/gt2tmpaqost.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2mwlfddgb.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2qnbdqdcl.html

[F06] 删除文件
来源：http://dali.smart0.xyz/Article/details/gt2hqeaspqg.html

Py:   os.remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2ggzrqlln.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nxshkzsr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oudxxsvj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2ennaveme.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gt2rolkfesu.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uvkntgnp.html

Ruby: File.delete("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2skyobktc.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2lbnkmmau.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gt2mucynnif.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gt2kcijbtzp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yongpay.top/Article/details/gt2odjjlqcv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yvrzhfuz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gt2hxpschob.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gt2mhiowfdf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.iojbl.cn/Article/details/gt2hploowgd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.birdmap.top/Article/details/gt2woqmxofp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sufxvd.cn/Article/details/gt2sxfbxnun.html

[F08] 遍历目录
来源：http://dali.cqqwz.cn/Article/details/gt2iichprkx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpegcjb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.birdmap.top/Article/details/gt2vswrsjdz.html

JS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gt2trjksrix.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2uwexqdvg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gt2hpyizhdy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2ubrcbrad.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2rfpudgka.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2dabtkkwc.html

[F09] 获取文件大小
来源：http://dali.ehwqpu.com/Article/details/gt2vehchaiu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2whjyumrb.html

PHP:  filesize("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2aviwdfwb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gt2kdsnystn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gt2efvdhhno.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2aiqfjxlf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gt2pmldlypp.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2ayhrwqpb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shzxlz.cn/Article/details/gt2stmjokxe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigufen.top/Article/details/gt2pfqcdole.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2bbhvsjsl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2oipkufdf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2fgzardfh.html

TS:   path.extname("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2wqlzunwz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.bjfxy.top/Article/details/gt2vwstlqfg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2vemvjbkl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2wkkbrnpd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2gempmjaj.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gt2ylgukciv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2mdzvwdwz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2ltfwjjvp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2zzphtjcm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2qnyrznxo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsnndmzu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuanzhike.top/Article/details/gt2epkofvwn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2iszesfqf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aizwys.cn/Article/details/gt2zjiomdsh.html

[F12] CSV 读写
来源：http://dali.sxryk.cn/Article/details/gt2mmsfcozh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shzxlz.cn/Article/details/gt2adxhhula.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tanke756.top/Article/details/gt2ebxhjoja.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cheryme.top/Article/details/gt2xsosaczb.html

TS:   // 同上
来源：http://dali.fengsongda.top/Article/details/gt2alwqnrgm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guannengcc.top/Article/details/gt2zlqlllve.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gt2myafoaxa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258.top/Article/details/gt2jzbslknu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gt2jeckquhx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2jdxasike.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gt2kgelobso.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2ccpvsuee.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gt2mmlhqzgu.html

Py:   class User: pass
来源：http://dali.shuidangran.top/Article/details/gt2nbyxhftf.html

PHP:  class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2wixcvqrc.html

JS:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2ckodrbso.html

TS:   class User { name: string = ""; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cjyqxeqk.html

Java: class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2ruznndlz.html

Go:   type User struct { Name string }
来源：http://dali.aibaodan.cn/Article/details/gt2edmryjvm.html

Ruby: class User; end
来源：http://dali.ivvv.top/Article/details/gt2bttgwrhh.html

C#:   class User {}
来源：http://dali.hnqzz.top/Article/details/gt2vcaqcmok.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gt2asgrxvil.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenjidiqi.icu/Article/details/gt2ccugmwlb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2qktqvdez.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2qnstcimh.html

TS:   constructor(public name: string) {}
来源：http://dali.iojbl.cn/Article/details/gt2wnjtzrkl.html

Java: User(String name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2rjiuqadl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hammf.cn/Article/details/gt2pxxtamkp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cdnleiting.top/Article/details/gt2hemmslvx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gt2vfipxpps.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gt2wevfibqb.html

Py:   self.name = "x"
来源：http://dali.fengsongda.top/Article/details/gt2pwqrmvax.html

PHP:  public string $name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2tytnpscg.html


<!-- 参考信息 -->