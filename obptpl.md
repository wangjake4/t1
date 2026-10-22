代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.quarkkingdee.top/Article/details/gt2sykkeumx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zycfv.cn/Article/details/gt2jdijgjov.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gt2vpkfohao.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gt2sevrzmip.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gotoacloud.top/Article/details/gt2ovnksgiz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sysykeji.top/Article/details/gt2ovwuztse.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuanzhike.top/Article/details/gt2btoxjkjc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2kotxcrhb.html

[E02] 重复字符串
来源：http://dali.aizwys.cn/Article/details/gt2jdhhwdfp.html

Py:   "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gt2zovjocii.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hammf.cn/Article/details/gt2dqhybhul.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gt2qslfhkka.html

TS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2ojeeegdq.html

Java: "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gt2ddyapofh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sweek.top/Article/details/gt2zskecowv.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gt2foxvhomn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.bjfxy.top/Article/details/gt2yfuctebn.html

[E03] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gt2hfharspo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ivvv.top/Article/details/gt2kxjnbqur.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2btnkeixl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2uyevuzbm.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258888.top/Article/details/gt2rpgowdnq.html

Java: s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2mrpljikg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zycfv.cn/Article/details/gt2mhcxrmbp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxtanspz.html

C#:   s.Substring(1, 3)
来源：http://dali.zdqjudy.top/Article/details/gt2jwusbgey.html

[E04] 查找子串位置
来源：http://dali.chenlongwang.top/Article/details/gt2qlpbttqh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kopstdsd.html

PHP:  strpos($s, "x");
来源：http://dali.fzhhl.top/Article/details/gt2vyqxbciq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hnopwjij.html

TS:   s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gt2sfibpocs.html

Java: s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gt2ilpwbxis.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258888.top/Article/details/gt2nrlqhxsy.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gmzfnors.html

C#:   s.IndexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gt2fcuzakth.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rqlsggum.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzytvbtk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.redwolf501.top/Article/details/gt2fmcrvmqi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gt2evxfybni.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sweek.top/Article/details/gt2icbewtja.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gt2fgmchymr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shuidangran.top/Article/details/gt2ocupmpul.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lntjbobb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ivvv.top/Article/details/gt2yxpfrzqf.html

[E06] 替换子串
来源：http://dali.shangyingyoupin.top/Article/details/gt2sbphuttp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gt2suqrpeiz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlnjfkv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2goalbmfd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2tovnlxle.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2ksoynoln.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gt2tmyahcyf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2sycrixpj.html

C#:   s.Replace("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2vcxnzdnf.html

[E07] 按分隔符拆分
来源：http://dali.gogol.net.cn/Article/details/gt2pmepkdlk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sxryk.cn/Article/details/gt2xyjlymaa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj202588.top/Article/details/gt2eldbqzhg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aizwys.cn/Article/details/gt2jszzeqxv.html

TS:   s.split(",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmrnvypj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dtwoctwp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2scshuohn.html

Ruby: s.split(",");  s.split
来源：http://dali.ydzc1.top/Article/details/gt2vxfcymad.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.svipenyu.cn/Article/details/gt2jnimwpip.html

[E08] 数组按分隔符合并
来源：http://dali.zdqjudy.top/Article/details/gt2lxnrgunq.html

Py:   ",".join(items)
来源：http://dali.quarkkingdee.top/Article/details/gt2gklnzwrp.html

PHP:  implode(",", $items);
来源：http://dali.jlsjyb.cn/Article/details/gt2gqcgfanm.html

JS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gt2sbazjizw.html

TS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gt2nsxptkcu.html

Java: String.join(",", items)
来源：http://dali.xylfe.cn/Article/details/gt2pdfvizwz.html

Go:   strings.Join(items, ",")
来源：http://dali.ehwqpu.com/Article/details/gt2dtoujabi.html

Ruby: items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mlsnbdpy.html

C#:   string.Join(",", items)
来源：http://dali.c1oappe.top/Article/details/gt2djunjudq.html

[E09] 去除所有空白字符
来源：http://dali.aizwys.cn/Article/details/gt2hodxytsh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xylfe.cn/Article/details/gt2tfunkury.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ybcxt.top/Article/details/gt2fzttmsky.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gt2graoccmi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwcyqrbk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.andypj.xyz/Article/details/gt2cukjdqvj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gogol.net.cn/Article/details/gt2apusljzi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gotoacloud.top/Article/details/gt2ewvouyko.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gt2mrxwxzqq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jlsjyb.cn/Article/details/gt2cvnjqgho.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gt2cfkrunol.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.smart0.xyz/Article/details/gt2jahquspt.html

JS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gt2lnopirhd.html

TS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gt2dnceqyps.html

Java: String.format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gt2umpkxuhq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjlfizkj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gt2rbxiepqy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigfzy.top/Article/details/gt2psaigsuj.html

[E11] 反转字符串
来源：http://dali.wangdashe.top/Article/details/gt2siiuuejd.html

Py:   s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2mizefrqg.html

PHP:  strrev($s);
来源：http://dali.ydzc1.top/Article/details/gt2ipprolvm.html

JS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2ujlhppmm.html

TS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2odjatghx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.bjfxy.top/Article/details/gt2euasgwjr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.mhx1999.top/Article/details/gt2wnecnpqu.html

Ruby: s.reverse
来源：http://dali.yvedp.cn/Article/details/gt2wbuzgcyp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gt2gowpehfk.html

[E12] 统计某字符出现次数
来源：http://dali.chenzaomai.com/Article/details/gt2qnvbuhml.html

Py:   s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gt2mwjyqfxg.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigfzy.top/Article/details/gt2irdvwqsw.html

JS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gt2iwgyabwb.html

TS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gt2rhkjbyox.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.c1oappe.top/Article/details/gt2zaliawnj.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gt2rcpahdhm.html

Ruby: s.count("a")
来源：http://dali.sxryk.cn/Article/details/gt2imiqdfxk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuanzhike.top/Article/details/gt2eoebjmip.html

[E13] 逐字符遍历
来源：http://dali.c1oappe.top/Article/details/gt2zsyzuhqf.html

Py:   for ch in s: print(ch)
来源：http://dali.xylfe.cn/Article/details/gt2vleyaffp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuanzhike.top/Article/details/gt2xyslgysv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vvimyoya.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2teuuyhad.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2fblitfze.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhengqikj.top/Article/details/gt2xzkuslxx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.daria6918.cn/Article/details/gt2aivynucp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2flaqvczf.html

[E14] URL 编码与 Base64
来源：http://dali.feifeiyinyue.top/Article/details/gt2quskmyvb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cdnleiting.top/Article/details/gt2blkwkswh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gt2bibahzpt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhixingplan.top/Article/details/gt2amghmakl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cucudq.cn/Article/details/gt2zkvvesow.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgfzy.top/Article/details/gt2kujeozmo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jyoumei.cn/Article/details/gt2pownddxt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sysykeji.top/Article/details/gt2mgegtfvv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gt2itdjaxii.html

[E15] HTML 转义 / 反转义
来源：http://dali.cucudq.cn/Article/details/gt2xwdfmsss.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mqfygfia.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehjkshgi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxinkj.top/Article/details/gt2yrqlevqc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2ergxdymu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pengpengdd.cyou/Article/details/gt2jnlghhls.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2iakqhbfe.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gt2nogjwfwj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nwbrower.top/Article/details/gt2cejdyqmd.html

[E16] 数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gt2mtiwuxdv.html

Py:   f"{1234567:,}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvydzyve.html

PHP:  number_format(1234567);
来源：http://dali.yonumen.top/Article/details/gt2olcldbem.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gt2ziocdbcf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gt2epgsqiyf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yvedp.cn/Article/details/gt2qdinnlpx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenlongwang.top/Article/details/gt2joxiicku.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gotoacloud.top/Article/details/gt2dhetjfwl.html

C#:   1234567.ToString("N0")
来源：http://dali.hnxiangtu.top/Article/details/gt2olijtvsv.html

[E17] 首字母大写
来源：http://dali.dianchejie.cn/Article/details/gt2epdyzkxi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cheryme.top/Article/details/gt2afccdqnc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuanzhike.top/Article/details/gt2dpvyxezi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qvxbmjtx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gt2bkidaeno.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yueranfly.top/Article/details/gt2senkpthh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2iryxragj.html

Ruby: s.capitalize
来源：http://dali.xuanzx.com/Article/details/gt2sdqbyikx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cashguo.top/Article/details/gt2nogwdylp.html

[E18] 模板占位符替换
来源：http://dali.hfpthk.cn/Article/details/gt2awwqdohv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ydzc1.top/Article/details/gt2hglnpyjx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.9152youxi.cn/Article/details/gt2kwimwotf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2fxhsiznm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2spoolsfb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2bjndclff.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2esqhlguj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2icfrxzpi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yongpay.top/Article/details/gt2gvuwscqn.html

[E19] 多行文本按行拆分
来源：http://dali.pycfn.com/Article/details/gt2nwwmdzwz.html

Py:   s.splitlines()
来源：http://dali.xylfe.cn/Article/details/gt2hsxabknq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2jtdcknwr.html

JS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gt2xljsmesj.html

TS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gt2lqlpmpdl.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gt2fkudrsxk.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gt2oabxbwtu.html

Ruby: s.lines
来源：http://dali.yj20258.top/Article/details/gt2pnayaygt.html

C#:   s.Split('\n')
来源：http://dali.9152youxi.cn/Article/details/gt2ifkbhixj.html

[E20] 判断字符串是否为空
来源：http://dali.hfpthk.cn/Article/details/gt2pmoxdihv.html

Py:   if not s:
来源：http://dali.jqgufenzy.top/Article/details/gt2zzevlhlr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.mhx1999.top/Article/details/gt2etpofbea.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gogol.net.cn/Article/details/gt2nphslvjt.html

TS:   if (s === "") {}
来源：http://dali.316326.xyz/Article/details/gt2womtoprv.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvydjxqf.html

Go:   if s == "" {}
来源：http://dali.hywenlv.cn/Article/details/gt2xsnybter.html

Ruby: if s.empty?
来源：http://dali.birdmap.top/Article/details/gt2caulrfar.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigufen.top/Article/details/gt2gcjxyvio.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcjcqey.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhiwuduotai.top/Article/details/gt2xamxnuxl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gt2zrfnaamc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2gjjqffdd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2uftnoxdk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2tlyquwwb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ppjwa.cn/Article/details/gt2ryinnccl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2gntatfcz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2qdcpbxde.html

[E22] 字节长度与字符长度
来源：http://dali.pycfn.com/Article/details/gt2iewypyas.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jyoumei.cn/Article/details/gt2ncrnhwuz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2mdceaxho.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2latzfmyy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gt2qxonfviv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gt2tfybicsc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.0kj1m.cn/Article/details/gt2cavyycri.html

Ruby: s.bytesize;  s.length
来源：http://dali.sysykeji.top/Article/details/gt2ddboefwz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tian-w.cn/Article/details/gt2amvkjxdx.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xaqhwwkg.html

F. 文件与目录
来源：http://dali.jinqigfzy.top/Article/details/gt2zdzrdwiz.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2corhxjpx.html

[F01] 读取整个文件
来源：http://dali.shzxlz.cn/Article/details/gt2bspfrdfu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yanxiufei.cn/Article/details/gt2liwofett.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2cxzldpek.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yueranfly.top/Article/details/gt2xgagctny.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gt2ckahgjzo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gt2mnmrqibw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gt2tpzmgayu.html

Ruby: File.read("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2wdlhdqrz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqhpvdlg.html

[F02] 逐行读取文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2orbhmidf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.smart0.xyz/Article/details/gt2zjkzfzfq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.quarkkingdee.top/Article/details/gt2qmnbenlx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tnkjvrnn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gt2afpqsddf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gt2tfvoomvq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gaohongyu789.top/Article/details/gt2kvaigtfs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.bjfxy.top/Article/details/gt2zlkkckjw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hysaishi.cn/Article/details/gt2nqsldqav.html

[F03] 写入文件（覆盖）
来源：http://dali.xinyue.icu/Article/details/gt2vvuloxmn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.havefunace.top/Article/details/gt2gsxsvuaa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gt2cfkujkkl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gt2rwdusiry.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gt2kagckrdd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fengsongda.top/Article/details/gt2mfkyxcgh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.snrcjt.cn/Article/details/gt2yvsnqrzu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.snrcjt.cn/Article/details/gt2tcyrxeod.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gt2eljnxtpi.html

[F04] 追加写入文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2qqqhhjsu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258.top/Article/details/gt2iazhkiph.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gt2qbrdxger.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gt2nvmwothj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gt2qinukign.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shzxlz.cn/Article/details/gt2mfzxwotg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2umjfsvnj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aizwys.cn/Article/details/gt2nidyodak.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qgbllqjf.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gt2mlprzghw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmqyhqar.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2sxwtkonh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2hnzkflaf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2rkqdpgtv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2nmcgyzuy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.0kj1m.cn/Article/details/gt2cwnuikuk.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2xxczibit.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2hrmfswof.html

[F06] 删除文件
来源：http://dali.yonumen.top/Article/details/gt2qzwrwndq.html

Py:   os.remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2tegdniuv.html

PHP:  unlink("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2zfnzrgao.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2ceeeiqib.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2zvvlampa.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2hyalguxl.html

Go:   os.Remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2rhzycgxo.html

Ruby: File.delete("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2yuuqayfz.html

C#:   File.Delete("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2fyeonvom.html

[F07] 创建目录（含多级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qcbupkwg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjredqob.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.smart0.xyz/Article/details/gt2gjsbpakc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gt2dyuuebsy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gt2yscylzmf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gotoacloud.top/Article/details/gt2pfpyvesx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guannengcc.top/Article/details/gt2clqwwadt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jnathmwi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cheryme.top/Article/details/gt2ffqsaunv.html

[F08] 遍历目录
来源：http://dali.nanxinkj.top/Article/details/gt2iznfzwno.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hammf.cn/Article/details/gt2yghtluch.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnqzz.top/Article/details/gt2zqxfzfgo.html

JS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gt2qgofpfhm.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2shtyhmse.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gt2iyxsmocf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2hqxlmonf.html

Ruby: Dir.children("dir")
来源：http://dali.meibo888.top/Article/details/gt2kkyvahkt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xinyue.icu/Article/details/gt2yxyzmdqn.html

[F09] 获取文件大小
来源：http://dali.chenzaomai.com/Article/details/gt2pnykvtzx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2qhfaoujm.html

PHP:  filesize("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2hbnngohh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gt2uglozxoq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gt2luddahmf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2ckbcpwam.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gt2sdklqqkc.html

Ruby: File.size("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2dbnsbvns.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsxliae.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jianghu66.top/Article/details/gt2pfivlatc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2iftnycoz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2skxauejj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wfexwtoa.html

TS:   path.extname("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2xnkztqgb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shuidangran.top/Article/details/gt2pczlirzt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2egabwoqn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2atxopmhe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2bgokpwgj.html

[F11] 复制与移动文件
来源：http://dali.shzxlz.cn/Article/details/gt2hccarbru.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2bgrswria.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2omodoetq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2botpzemh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2xhgickyu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cqqwz.cn/Article/details/gt2kdpcaida.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.9152youxi.cn/Article/details/gt2ytvaqhbp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2hlluqfnx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gt2uxdynmce.html

[F12] CSV 读写
来源：http://dali.cqqwz.cn/Article/details/gt2wncquyqs.html


<!-- 参考信息 -->