代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.snrcjt.cn/Article/details/gt2txskpqjx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuanzhike.top/Article/details/gt2cztthtdq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gt2nuceogxa.html

[D26] 数组转字符串
来源：http://dali.9152youxi.cn/Article/details/gt2ebvzozxc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nwbrower.top/Article/details/gt2rlgxyavf.html

PHP:  implode(", ", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sbgedjnr.html

JS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gt2kyifdwhh.html

TS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gt2detlqbcb.html

Java: String.join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2elfzprpd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.mhx1999.top/Article/details/gt2nxgddtcm.html

Ruby: arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rjthwnxu.html

C#:   string.Join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gt2gljgfise.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2lhqletpo.html

E. 字符串处理
来源：http://dali.hnqzz.top/Article/details/gt2mrmqzkyw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2qxdmzakz.html

[E01] 拼接字符串
来源：http://dali.birdmap.top/Article/details/gt2twiyzags.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxinkj.top/Article/details/gt2xvqeyllr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jnvadksz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gt2uouhcstv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2podflnyg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gt2nijpdppm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.316326.xyz/Article/details/gt2ranfzywm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tanke756.top/Article/details/gt2vysyfyap.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dgeiklma.html

[E02] 重复字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oibgmmcg.html

Py:   "ab" * 3
来源：http://dali.nwbrower.top/Article/details/gt2qxnvwacz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenzaomai.com/Article/details/gt2wqkibarz.html

JS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gt2zhleflgv.html

TS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gt2vbxkugwt.html

Java: "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gt2dlhjrtne.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.iojbl.cn/Article/details/gt2wlcfcnlv.html

Ruby: "ab" * 3
来源：http://dali.ivvv.top/Article/details/gt2luoozxwc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.vqdsnc.cn/Article/details/gt2vrczqqnk.html

[E03] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gt2fiqipino.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yonumen.top/Article/details/gt2fjrsubxy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gnvnkqkr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gt2ubvputpg.html

TS:   s.slice(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2pcvyirqi.html

Java: s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gt2cyaridbg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gt2tkljbohx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dashuyun.cn/Article/details/gt2pymviuss.html

C#:   s.Substring(1, 3)
来源：http://dali.sufxvd.cn/Article/details/gt2ddeuoqqo.html

[E04] 查找子串位置
来源：http://dali.andypj.xyz/Article/details/gt2xlmydhgh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gt2rmseheky.html

PHP:  strpos($s, "x");
来源：http://dali.gzhubu.top/Article/details/gt2gnfdcuit.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uravtxvv.html

TS:   s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ttnpljhf.html

Java: s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gt2vdowpygf.html

Go:   strings.Index(s, "x")
来源：http://dali.xinyue.icu/Article/details/gt2wflzlnsu.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gt2dbpzfykr.html

C#:   s.IndexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gt2acvivqgt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gogol.net.cn/Article/details/gt2lmqkvxgq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhengqikj.top/Article/details/gt2guwynxfd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldbtisny.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zbwghpvb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.haohaochexian.top/Article/details/gt2pluetpbf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2lzkplkem.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangshuangyany.cn/Article/details/gt2aceyxlah.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj202588.top/Article/details/gt2bkmhxqcw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gt2dgvwnzcb.html

[E06] 替换子串
来源：http://dali.xziqi.cn/Article/details/gt2cvkrbsgx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kcepygrn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gt2ixbaptcm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2deiddqyd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2csoaaqlt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2dtxeojtb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2risqhcks.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2bobkcmmf.html

C#:   s.Replace("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2rckcthdv.html

[E07] 按分隔符拆分
来源：http://dali.sysykeji.top/Article/details/gt2bozqxwxr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xziqi.cn/Article/details/gt2ntkcljhy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2erftjksb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2enubdrye.html

TS:   s.split(",")
来源：http://dali.hywenlv.cn/Article/details/gt2avkfeifh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.9152youxi.cn/Article/details/gt2xdifygud.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.snrcjt.cn/Article/details/gt2jikuxgbs.html

Ruby: s.split(",");  s.split
来源：http://dali.xziqi.cn/Article/details/gt2vchqgqgr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zycfv.cn/Article/details/gt2wvxscldh.html

[E08] 数组按分隔符合并
来源：http://dali.hnxiangtu.top/Article/details/gt2eitquwpb.html

Py:   ",".join(items)
来源：http://dali.0kj1m.cn/Article/details/gt2uphbldwe.html

PHP:  implode(",", $items);
来源：http://dali.chenjidiqi.icu/Article/details/gt2nfhrotkx.html

JS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gt2bwtqirtq.html

TS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2cqzpnmjz.html

Java: String.join(",", items)
来源：http://dali.sweek.top/Article/details/gt2nvkgmrok.html

Go:   strings.Join(items, ",")
来源：http://dali.tanke756.top/Article/details/gt2yamqwcyk.html

Ruby: items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qozsvdus.html

C#:   string.Join(",", items)
来源：http://dali.wangdashe.top/Article/details/gt2zfncubpm.html

[E09] 去除所有空白字符
来源：http://dali.yonumen.top/Article/details/gt2rmanopnv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xziqi.cn/Article/details/gt2cosgpbvv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuanzx.com/Article/details/gt2mwxrmfzb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2upbdfzuc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gt2ebzwgmpc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yvedp.cn/Article/details/gt2zcovohbw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqaemtmi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.birdmap.top/Article/details/gt2eigwqxmy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gt2jtpkhjid.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ydzc1.top/Article/details/gt2hjgghsdb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2gfhyhpmb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zycfv.cn/Article/details/gt2romsmfry.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gt2qhqynkde.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yooyaqnu.html

Java: String.format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ktfxpewm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2wpkhwzye.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bpyaogyx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.quarkkingdee.top/Article/details/gt2kvnrgwkt.html

[E11] 反转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eafewpfe.html

Py:   s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gt2anqoorrr.html

PHP:  strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gt2fzbfamsu.html

JS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2mjjqznlu.html

TS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gt2ucfkpefe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tanke756.top/Article/details/gt2onnmhbah.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenzaomai.com/Article/details/gt2rhtfpjqd.html

Ruby: s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gt2ntqnqzgk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gt2lxlcnufp.html

[E12] 统计某字符出现次数
来源：http://dali.bjfxy.top/Article/details/gt2podpugtx.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gt2ccyzpjsu.html

PHP:  substr_count($s, "a");
来源：http://dali.cdnleiting.top/Article/details/gt2zurhssge.html

JS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gt2nolhhdaf.html

TS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gt2jnbludaa.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jyoumei.cn/Article/details/gt2qqudehtg.html

Go:   strings.Count(s, "a")
来源：http://dali.birdmap.top/Article/details/gt2qjbpcyjl.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gt2uapluucy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuanzhike.top/Article/details/gt2czwdojvr.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gt2jskwtdmh.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gt2vlrwcxoa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ljrbegqs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gt2yepwwiej.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gt2gwkadsto.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gt2sgcatdiq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guannengcc.top/Article/details/gt2spjvcwdk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangshuangyany.cn/Article/details/gt2syahfrap.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ybcxt.top/Article/details/gt2fmwmpajg.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258.top/Article/details/gt2qsamqjch.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.svipenyu.cn/Article/details/gt2fvjruung.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj202588.top/Article/details/gt2mcuukipa.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuanzhike.top/Article/details/gt2kgatiajs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2badgmlsm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcircep.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hfpthk.cn/Article/details/gt2wulbtzav.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhixingplan.top/Article/details/gt2quqqbxes.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258888.top/Article/details/gt2jmttsvmg.html

[E15] HTML 转义 / 反转义
来源：http://dali.gzhubu.top/Article/details/gt2eywksjms.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzkfxiua.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dopoesuv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zycfv.cn/Article/details/gt2kuyqsvlr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxinkj.top/Article/details/gt2oeyvunur.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nwbrower.top/Article/details/gt2pglkcdrz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovefjcle.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daria6918.cn/Article/details/gt2vgppcoth.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zdqjudy.top/Article/details/gt2uvxroxfs.html

[E16] 数字千分位
来源：http://dali.yuxming.cn/Article/details/gt2ptehuftv.html

Py:   f"{1234567:,}"
来源：http://dali.gaohongyu789.top/Article/details/gt2owcjzaar.html

PHP:  number_format(1234567);
来源：http://dali.jqgufenzy.top/Article/details/gt2yanhrxpw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gt2zptzdqxn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gt2gmoeszaq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jyoumei.cn/Article/details/gt2wzcfcndw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cashguo.top/Article/details/gt2efkxvbgm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.9152youxi.cn/Article/details/gt2leresbww.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgfzy.top/Article/details/gt2qkqdcovy.html

[E17] 首字母大写
来源：http://dali.birdmap.top/Article/details/gt2djajaxph.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jianghu66.top/Article/details/gt2shaubrkx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxinkj.top/Article/details/gt2dljslnxo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gt2mwcipsme.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lutyugcu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aibaodan.cn/Article/details/gt2srnxgvbe.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuanzhike.top/Article/details/gt2dlggmyxd.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gt2ivkvxpbf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shuidangran.top/Article/details/gt2sqvxbrje.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tbzgaosv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gt2cienohmh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yueranfly.top/Article/details/gt2qakfaaoo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gt2asiqcnkb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gt2cdfcstcy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2pukawswz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gt2zmzycgcj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoesxzu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gt2fxfjuzmj.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gt2fnxquzrg.html

Py:   s.splitlines()
来源：http://dali.dashuyun.cn/Article/details/gt2ajrneilr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2wqevxjxo.html

JS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gt2aroqbwwf.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fkirvuqa.html

Java: s.lines().toList()
来源：http://dali.meibo888.top/Article/details/gt2jkerrqtj.html

Go:   strings.Split(s, "\n")
来源：http://dali.cucudq.cn/Article/details/gt2hpqeduwm.html

Ruby: s.lines
来源：http://dali.redwolf501.top/Article/details/gt2ltyauqee.html

C#:   s.Split('\n')
来源：http://dali.zhoulong.xyz/Article/details/gt2jhqusedm.html

[E20] 判断字符串是否为空
来源：http://dali.xuanzx.com/Article/details/gt2ixgfucfh.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gt2uybgbjyb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hysaishi.cn/Article/details/gt2efvjnpbl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2kgwhuafq.html

TS:   if (s === "") {}
来源：http://dali.gaohongyu789.top/Article/details/gt2wfirdkny.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gt2qxvpmmlz.html

Go:   if s == "" {}
来源：http://dali.aizwys.cn/Article/details/gt2strdwxie.html

Ruby: if s.empty?
来源：http://dali.jqgfzy.top/Article/details/gt2vhczsjmo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zdqjudy.top/Article/details/gt2wnvsexke.html

[E21] 超长截断加省略号
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxijrqni.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxinkj.top/Article/details/gt2sfquntiq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2hadoklbm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2efhyuoxv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2pxexjcbk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gt2sfcpueny.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lgdsevnj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tyebkfxo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2jjpliprz.html

[E22] 字节长度与字符长度
来源：http://dali.zhoulong.xyz/Article/details/gt2bvydfufu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zycfv.cn/Article/details/gt2dszzcwbt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gt2fehrzaxe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gt2gxlyojwy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gt2zyouekae.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.316326.xyz/Article/details/gt2brmwgmlo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daria6918.cn/Article/details/gt2lroxyqys.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gt2esnnddyi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gt2lncjbygw.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2lalypxsv.html

F. 文件与目录
来源：http://dali.xuetiantiany.cn/Article/details/gt2vkcwqmtz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2vjfefwhg.html

[F01] 读取整个文件
来源：http://dali.jyoumei.cn/Article/details/gt2ykzcuohx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgbgypcq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2jmhpnmwe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gt2zzzogrjg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj202588.top/Article/details/gt2zrcjaxjr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2epzyozbv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yongpay.top/Article/details/gt2kdlfokrv.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2vgklguup.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2doeepocr.html

[F02] 逐行读取文件
来源：http://dali.cdnleiting.top/Article/details/gt2ytweutyt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gt2vaguaxbu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eebjjnrl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gt2eradkhwu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gt2ytgystcd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gt2pxyiliue.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfzpnblh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dfkukmtm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vczztaln.html

[F03] 写入文件（覆盖）
来源：http://dali.c1oappe.top/Article/details/gt2pugcjoca.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tianlin.xyz/Article/details/gt2unlcgcvx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gt2rwcfgakf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gt2fcsluqfe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2ecbueped.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sweek.top/Article/details/gt2hgyptgul.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sufxvd.cn/Article/details/gt2brwpdqsu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2pcihavrn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gt2oszteras.html

[F04] 追加写入文件
来源：http://dali.316326.xyz/Article/details/gt2nrfnvmsz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yonumen.top/Article/details/gt2xyzvrbnf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dashuyun.cn/Article/details/gt2nnvfqlrl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2dqnbbmkg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2ezphphnk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xinyue.icu/Article/details/gt2bplyxzew.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2uuyqovay.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uxnhrhjh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pengpengdd.cyou/Article/details/gt2trvmmvox.html

[F05] 判断文件或目录是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2syuxnukl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gt2nfbrvjea.html

PHP:  file_exists("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2svgfeeaq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2papfcobo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2tvhmkbdw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2kpuylete.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.316326.xyz/Article/details/gt2qlehpnfo.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2psnsouln.html

C#:   File.Exists("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2alruaios.html

[F06] 删除文件
来源：http://dali.yj20258.top/Article/details/gt2lsvgooql.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2dmauigfp.html

PHP:  unlink("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2xvoobrkj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2sgfwdkpd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2cginqcoo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iqaawqdn.html

Go:   os.Remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2oyhidque.html

Ruby: File.delete("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2vphctakz.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2qmfulugh.html

[F07] 创建目录（含多级）
来源：http://dali.tanke756.top/Article/details/gt2hsxnkfos.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xinyue.icu/Article/details/gt2aqqddmxl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jlsjyb.cn/Article/details/gt2mbcbgvqj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gt2vihudvmh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gt2eblzcxqw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jlsjyb.cn/Article/details/gt2gojdhpyo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.smart0.xyz/Article/details/gt2wpmmrlez.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cucudq.cn/Article/details/gt2srmweeud.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aibaodan.cn/Article/details/gt2waskrkor.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gt2ugvagjyg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gzhubu.top/Article/details/gt2sldpcymw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.haohaochexian.top/Article/details/gt2whkzvdgm.html

JS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2yvpovnsu.html

TS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gt2lubhqxib.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gt2gylnkxdn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2nyesobob.html

Ruby: Dir.children("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2vfvfokwr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yvedp.cn/Article/details/gt2gpksopos.html

[F09] 获取文件大小
来源：http://dali.gogol.net.cn/Article/details/gt2zuvazfkj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjfakyxp.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2tcwzkvrj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gt2ormkilrm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gt2dpesdmgo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2yzoxrgue.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gt2bgabozuz.html

Ruby: File.size("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2nqubdrmp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jyoumei.cn/Article/details/gt2jbisjrrx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangshuangyany.cn/Article/details/gt2jejhknev.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2chfztcdj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gt2dntkhloo.html


<!-- 参考信息 -->