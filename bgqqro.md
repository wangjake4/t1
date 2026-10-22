代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jyoumei.cn/Article/details/gtnphdniaf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.c1oappe.top/Article/details/gtfshgdocs.html

[D25] Set 集合去重与交并差
来源：http://dali.hnxiangtu.top/Article/details/gtjjbmprhf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigfzy.top/Article/details/gtwefseudf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cashguo.top/Article/details/gtldjwwbpo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xylfe.cn/Article/details/gtbcbkquhd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.9152youxi.cn/Article/details/gtdrzuebrw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.redwolf501.top/Article/details/gtqfptlrot.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnngualbn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigufen.top/Article/details/gtxlnkzvir.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sufxvd.cn/Article/details/gtgpcuagbz.html

[D26] 数组转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtfuqvzfuv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pycfn.com/Article/details/gtlnrdcsga.html

PHP:  implode(", ", $arr);
来源：http://dali.xinyue.icu/Article/details/gtaxwkaryq.html

JS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gtwpbimrfs.html

TS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtipvnqjqp.html

Java: String.join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gtgcykamht.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daxiang520.top/Article/details/gtccbnodyu.html

Ruby: arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtvarcqexj.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpaiyiwog.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtvngjbcsm.html

E. 字符串处理
来源：http://dali.cqqwz.cn/Article/details/gtsmuwtgqt.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtdyoofhie.html

[E01] 拼接字符串
来源：http://dali.tanke756.top/Article/details/gtnhkcedkj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258.top/Article/details/gtpcjyvnjv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.mhx1999.top/Article/details/gtqdadubfz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gtrxxjcybg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ehwqpu.com/Article/details/gtawuojmpd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuanzhike.top/Article/details/gtjvtlrmxb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.bjfxy.top/Article/details/gtpbbzxvcn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhengqikj.top/Article/details/gtuhodkdek.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtclqjbexc.html

[E02] 重复字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtsmnjbgqj.html

Py:   "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gtenankmdj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.mhx1999.top/Article/details/gtinwtzjmp.html

JS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtuiupmovr.html

TS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtcpfylvmq.html

Java: "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtzruzwtrb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtawmiqqrw.html

Ruby: "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gtltludyyx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guannengcc.top/Article/details/gtyesrndws.html

[E03] 截取子串
来源：http://dali.mhx1999.top/Article/details/gtxcdlyvib.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ehwqpu.com/Article/details/gtnwvoohuc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxpkaxqk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtmlgnxdub.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtypclzidr.html

Java: s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtygrnutpp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gzhubu.top/Article/details/gtusxeqpso.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dianchejie.cn/Article/details/gthlujaned.html

C#:   s.Substring(1, 3)
来源：http://dali.yuanzhike.top/Article/details/gteoahsbeo.html

[E04] 查找子串位置
来源：http://dali.yvedp.cn/Article/details/gtdtlnxuzu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gtmtheijnh.html

PHP:  strpos($s, "x");
来源：http://dali.hnxiangtu.top/Article/details/gtbyeyotnw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xziqi.cn/Article/details/gtjueiljjb.html

TS:   s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtwkojeabc.html

Java: s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtngkrygnb.html

Go:   strings.Index(s, "x")
来源：http://dali.xuetiantiany.cn/Article/details/gtturgcfmk.html

Ruby: s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gtyslopxca.html

C#:   s.IndexOf("x")
来源：http://dali.hammf.cn/Article/details/gtzsejtvwo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cucudq.cn/Article/details/gtpjxsocep.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fengsongda.top/Article/details/gtvavsqwmy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tianlin.xyz/Article/details/gtclmdpyyy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtsvhbdwme.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ivvv.top/Article/details/gtsekbbcrl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtkbjghquf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hammf.cn/Article/details/gtavbdpcnp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnxiangtu.top/Article/details/gtrdrvuvsj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ivvv.top/Article/details/gtjzxbpahc.html

[E06] 替换子串
来源：http://dali.sufxvd.cn/Article/details/gtqgssiwui.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtkxxrgptu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqxzbqpt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudhmfold.html

TS:   s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtozhraqgm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtquqrwjnm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gtbmmerhxy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtlgxqktbv.html

C#:   s.Replace("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtkunurgcl.html

[E07] 按分隔符拆分
来源：http://dali.nanxuanxn.top/Article/details/gtsnszfdmm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cqqwz.cn/Article/details/gtutsiiukk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtwyzowuxn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ehwqpu.com/Article/details/gturzudorc.html

TS:   s.split(",")
来源：http://dali.jyoumei.cn/Article/details/gtlfpapkmn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.meibo888.top/Article/details/gtxcdnjalc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.smart0.xyz/Article/details/gtmtsbacbu.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigfzy.top/Article/details/gtvdcuuvpa.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jlsjyb.cn/Article/details/gtatbcyzvx.html

[E08] 数组按分隔符合并
来源：http://dali.gzhubu.top/Article/details/gtfndvlpbr.html

Py:   ",".join(items)
来源：http://dali.jiagoushi.top/Article/details/gtxkaznbps.html

PHP:  implode(",", $items);
来源：http://dali.ivvv.top/Article/details/gtxkcwgkhj.html

JS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gthakshjrb.html

TS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtqwtxfuqe.html

Java: String.join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtaqvkqlsp.html

Go:   strings.Join(items, ",")
来源：http://dali.gogol.net.cn/Article/details/gtkloboefq.html

Ruby: items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtuwpyojne.html

C#:   string.Join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtjsrlhqqe.html

[E09] 去除所有空白字符
来源：http://dali.daxiang520.top/Article/details/gtfsmrfznl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hnqzz.top/Article/details/gtamexyhou.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtknvropxb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gtvcyxdftc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gtmvnudloy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gtgoisegxl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jianghu66.top/Article/details/gtiikioztr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtiprbudpa.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cucudq.cn/Article/details/gtkxgwebms.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daxiang520.top/Article/details/gtjmnljkck.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtktdegswb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xziqi.cn/Article/details/gtpgomteun.html

JS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gtxnzcgnzl.html

TS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtonxadzxs.html

Java: String.format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gthbaitqfb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gthwtlzgsh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gtktxtnnaw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenlongwang.top/Article/details/gtservukjh.html

[E11] 反转字符串
来源：http://dali.gzhubu.top/Article/details/gtmgiffudj.html

Py:   s[::-1]
来源：http://dali.yueranfly.top/Article/details/gthxjfwrdj.html

PHP:  strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtvsuvrles.html

JS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtntliushv.html

TS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtrcswjhmt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwipddsoz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ivvv.top/Article/details/gtfbzlvgbp.html

Ruby: s.reverse
来源：http://dali.sysykeji.top/Article/details/gtgaocojyk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gtyeefefud.html

[E12] 统计某字符出现次数
来源：http://dali.kuanghao11.cn/Article/details/gtyjwvdijs.html

Py:   s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtoqnnstwk.html

PHP:  substr_count($s, "a");
来源：http://dali.yangfankeji.com/Article/details/gtokmkhgcb.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gtufxviwdi.html

TS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gtgjpmrets.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxuanxn.top/Article/details/gtzshttfoi.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigfzy.top/Article/details/gtsgzbnwwf.html

Ruby: s.count("a")
来源：http://dali.birdmap.top/Article/details/gtydxdvvvm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.316326.xyz/Article/details/gtrebqdbpw.html

[E13] 逐字符遍历
来源：http://dali.kuanghao11.cn/Article/details/gthvbfndcv.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gtsjtowqcp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guannengcc.top/Article/details/gttwgqfhek.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gtbpegilak.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gtdrlxkpkw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258888.top/Article/details/gtrswudtwm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvvbtwhq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gtawvgtzwj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ybcxt.top/Article/details/gtqhhiifzm.html

[E14] URL 编码与 Base64
来源：http://dali.shzxlz.cn/Article/details/gthcyqovsj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yvedp.cn/Article/details/gtutjgzzzh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtugsrmxue.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuxming.cn/Article/details/gtzdkrfkcn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gzhubu.top/Article/details/gtsyakqyka.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtcsiswyfk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cheryme.top/Article/details/gtueexeuhz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gogol.net.cn/Article/details/gtqviwxsrf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtfsxdjdxa.html

[E15] HTML 转义 / 反转义
来源：http://dali.xylfe.cn/Article/details/gtscgyyxdp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigfzy.top/Article/details/gtdnbvagrl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.9152youxi.cn/Article/details/gtabfytpjf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fzhhl.top/Article/details/gtoqbfnxxs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gttecffrff.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gtafaeurov.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgfzy.top/Article/details/gtipnfxagn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.quarkkingdee.top/Article/details/gtxnmmfjju.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtklttqmko.html

[E16] 数字千分位
来源：http://dali.yongpay.top/Article/details/gtqliarvnu.html

Py:   f"{1234567:,}"
来源：http://dali.zhoulong.xyz/Article/details/gtrihqqbyw.html

PHP:  number_format(1234567);
来源：http://dali.c1oappe.top/Article/details/gtvndulmaa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjnexanw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gtdyngffeo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gtnjbfaufy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.mhx1999.top/Article/details/gtvkaugckr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cucudq.cn/Article/details/gtavekxkac.html

C#:   1234567.ToString("N0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvhtwlzh.html

[E17] 首字母大写
来源：http://dali.shangyingyoupin.top/Article/details/gtdnjfhzda.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hfpthk.cn/Article/details/gtqjfwiano.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tian-w.cn/Article/details/gtzysyhhxq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtswlzzpgu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gtprgxsxhb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.9152youxi.cn/Article/details/gtlaxjbmrl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jiagoushi.top/Article/details/gteycurjki.html

Ruby: s.capitalize
来源：http://dali.shangyingyoupin.top/Article/details/gtxemxlksp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ybcxt.top/Article/details/gtqlmnwfow.html

[E18] 模板占位符替换
来源：http://dali.cashguo.top/Article/details/gtmafgpoud.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhengqikj.top/Article/details/gtdvthghmg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yongpay.top/Article/details/gtjgzucgwd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtstczvjbc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtvbwaxqpt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sweek.top/Article/details/gtgjkqmbhr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtvzxsmaln.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zycfv.cn/Article/details/gtezkmgmtv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yangfankeji.com/Article/details/gtgptcrbyt.html

[E19] 多行文本按行拆分
来源：http://dali.cheryme.top/Article/details/gtqwshadvo.html

Py:   s.splitlines()
来源：http://dali.daxiang520.top/Article/details/gtogtfusol.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtqfiqqdst.html

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gterdmeujg.html

TS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gtgptoyfur.html

Java: s.lines().toList()
来源：http://dali.yj202588.top/Article/details/gtottjyjfp.html

Go:   strings.Split(s, "\n")
来源：http://dali.aizwys.cn/Article/details/gtzoyoljwz.html

Ruby: s.lines
来源：http://dali.hongshengwenyu.top/Article/details/gtiqbsyrvk.html

C#:   s.Split('\n')
来源：http://dali.redwolf501.top/Article/details/gtxvavdnle.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gtrmutszaw.html

Py:   if not s:
来源：http://dali.ybcxt.top/Article/details/gtymhyczew.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aizwys.cn/Article/details/gtpnbutrxi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tian-w.cn/Article/details/gthdjwzksw.html

TS:   if (s === "") {}
来源：http://dali.daria6918.cn/Article/details/gtpyrtyewi.html

Java: if (s.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gtompqornk.html

Go:   if s == "" {}
来源：http://dali.dianchejie.cn/Article/details/gtiiwfdtmb.html

Ruby: if s.empty?
来源：http://dali.yvedp.cn/Article/details/gtbbwguqjw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guannengcc.top/Article/details/gtavjpqmsc.html

[E21] 超长截断加省略号
来源：http://dali.zhengqikj.top/Article/details/gtdsxvkxzx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tianlin.xyz/Article/details/gtuzgpnjjl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtxhwoeuss.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtygokuxdk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtyimmmhll.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtbnxlcags.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tianlin.xyz/Article/details/gtfoeyuaqc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvtncdif.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtccolwoof.html

[E22] 字节长度与字符长度
来源：http://dali.xuetiantiany.cn/Article/details/gthfyeoylr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yangfankeji.com/Article/details/gttwgnkmrg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfsigjxk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtbiginfoz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtudgxcdic.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuxming.cn/Article/details/gtxagcllbu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gtljwbmfwu.html

Ruby: s.bytesize;  s.length
来源：http://dali.pycfn.com/Article/details/gtijllcmqa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gotoacloud.top/Article/details/gtjlknwjkj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtybmhlsiw.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzyyxowp.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gttctgrzoq.html

[F01] 读取整个文件
来源：http://dali.meibo888.top/Article/details/gtuhulesfv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigfzy.top/Article/details/gtexemfhty.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzutuqofa.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fzhhl.top/Article/details/gtiavbkmsx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.bjfxy.top/Article/details/gtibltvund.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtabcovpae.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhengqikj.top/Article/details/gtffoclbtw.html

Ruby: File.read("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiupkovza.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ivvv.top/Article/details/gtvdjbstry.html

[F02] 逐行读取文件
来源：http://dali.jlsjyb.cn/Article/details/gthteodydv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gaohongyu789.top/Article/details/gthbprdqrs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.0kj1m.cn/Article/details/gtkzyijlzs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gtkoqgdjzo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtnzogwehx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtvfubhtww.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.c1oappe.top/Article/details/gtysidodtq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhoulong.xyz/Article/details/gthreemvkk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hammf.cn/Article/details/gtzjlxiajq.html

[F03] 写入文件（覆盖）
来源：http://dali.xuetiantiany.cn/Article/details/gtzhkreojw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gtptmbvfvl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtwncmjkal.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gtdxziomeu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtzqxuwxag.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtcrjucmnw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zycfv.cn/Article/details/gtgnpycqnl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgfzy.top/Article/details/gtgnagwcsg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtmwlclpld.html

[F04] 追加写入文件
来源：http://dali.xziqi.cn/Article/details/gtbdwthcef.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cucudq.cn/Article/details/gtdzdqmxlc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gtbaedldxc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gttsphmtso.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtvppslnjk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ehwqpu.com/Article/details/gtlqglvkqa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gtuhmnxfzh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gtqdlszoze.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenzaomai.com/Article/details/gtuyoecdtf.html

[F05] 判断文件或目录是否存在
来源：http://dali.sweek.top/Article/details/gtalvdjien.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pengpengdd.cyou/Article/details/gtmuhtthsi.html

PHP:  file_exists("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gteumlyhoc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtapmbksnp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtupyqosxu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtyyxmokaz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.kuanghao11.cn/Article/details/gtiknilrqp.html

Ruby: File.exist?("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtdanjykmh.html

C#:   File.Exists("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtlfdlvhoo.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gtwqiwjlzg.html

Py:   os.remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gtrthgobwb.html

PHP:  unlink("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbypnvzvt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gttjqftzdc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtifcqyefj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtgfjtiirg.html

Go:   os.Remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtyaqovsfu.html

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtayzhtrrs.html

C#:   File.Delete("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtwxzmbjar.html

[F07] 创建目录（含多级）
来源：http://dali.yonumen.top/Article/details/gtrskgszsd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gtilqlvsft.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cucudq.cn/Article/details/gtswhlovdj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfamejgm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtvstvspkn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jyoumei.cn/Article/details/gtkrlftwao.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jlsjyb.cn/Article/details/gtewweomjw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gtazqjuuax.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gtafjbuvfh.html

[F08] 遍历目录
来源：http://dali.shuidangran.top/Article/details/gtfkjydeax.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gtbwhasrhl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvixpuxag.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtyjormfcl.html

TS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gtbgooovkd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtwkjxgwjs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sufxvd.cn/Article/details/gthjubfigf.html

Ruby: Dir.children("dir")
来源：http://dali.nanxuanxn.top/Article/details/gthhrnvhgr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtstjouopn.html

[F09] 获取文件大小
来源：http://dali.daria6918.cn/Article/details/gtfrxfltbd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtkduvqrsw.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtioucnvpy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gtmkvuofgk.html


<!-- 参考信息 -->