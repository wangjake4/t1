代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gt2xvqryoxx.html

[D24] 字典 / Map 基本操作
来源：http://dali.jiagoushi.top/Article/details/gt2yareiiml.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guowangkeji.top/Article/details/gt2qacgpsel.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gt2beasjwsn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj202588.top/Article/details/gt2csiohkyo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2jfbhwzfp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hfpthk.cn/Article/details/gt2kxxboumd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nanjrzmd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yuanzhike.top/Article/details/gt2aqdyrenu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhengqikj.top/Article/details/gt2unjltdae.html

[D25] Set 集合去重与交并差
来源：http://dali.mhx1999.top/Article/details/gt2rlkctisy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ybcxt.top/Article/details/gt2gmzpxoux.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aizwys.cn/Article/details/gt2ynhwdyhs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xziqi.cn/Article/details/gt2cmyodwex.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gaohongyu789.top/Article/details/gt2izgzrcvd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nanxinkj.top/Article/details/gt2xmoogkyc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tian-w.cn/Article/details/gt2vnoartqm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yangfankeji.com/Article/details/gt2sxqhqnsj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dianchejie.cn/Article/details/gt2uglygxqm.html

[D26] 数组转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2tupqlntc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2hltxpqpt.html

PHP:  implode(", ", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2smfzvcck.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gt2iwkgdrjg.html

TS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gt2plumxcnr.html

Java: String.join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gt2xblkilyr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhengqikj.top/Article/details/gt2dtsqnywz.html

Ruby: arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yzkzwjjs.html

C#:   string.Join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gt2eeiczrfp.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2bjooswcm.html

E. 字符串处理
来源：http://dali.pycfn.com/Article/details/gt2ptmmkdfd.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ahnbafbn.html

[E01] 拼接字符串
来源：http://dali.nwbrower.top/Article/details/gt2bgykrnmq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gotoacloud.top/Article/details/gt2qemdfhxy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.9152youxi.cn/Article/details/gt2lcadkujt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gt2cgqsqwyb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gt2mmpxclgb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yonumen.top/Article/details/gt2vmtryeqq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nwbrower.top/Article/details/gt2grimsphl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnxiangtu.top/Article/details/gt2gcxobehp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2gtvbraya.html

[E02] 重复字符串
来源：http://dali.yvedp.cn/Article/details/gt2zgdnbgil.html

Py:   "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gt2lcmkkdlb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zycfv.cn/Article/details/gt2dzyrnghd.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gt2cdfcvpbd.html

TS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gt2dhhhdvme.html

Java: "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2aphxvvsp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tgqoqgwy.html

Ruby: "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gt2uwtckbbk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daxiang520.top/Article/details/gt2zrmqpbke.html

[E03] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gt2tqzwqfjn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.kuanghao11.cn/Article/details/gt2goozjqke.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2ohyiydvt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2mvqqcsyo.html

TS:   s.slice(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2eenrmeee.html

Java: s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqgygdau.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bwbgwbaa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.316326.xyz/Article/details/gt2cufdqcmj.html

C#:   s.Substring(1, 3)
来源：http://dali.gzhubu.top/Article/details/gt2rcorogzw.html

[E04] 查找子串位置
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbinrvht.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnqzz.top/Article/details/gt2ozqbwreg.html

PHP:  strpos($s, "x");
来源：http://dali.zhongyouzk.top/Article/details/gt2ibwimgbz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sysykeji.top/Article/details/gt2cpwcycfa.html

TS:   s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2qqktljue.html

Java: s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wvpzsktz.html

Go:   strings.Index(s, "x")
来源：http://dali.xziqi.cn/Article/details/gt2zbmnsuwy.html

Ruby: s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2joqxspvq.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipfzogkg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.vqdsnc.cn/Article/details/gt2cvogwhma.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gt2pkkxktjr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.snrcjt.cn/Article/details/gt2vrnxsmxr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gt2bhsvrcna.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2lxwddrpo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gt2cechuexi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhengqikj.top/Article/details/gt2qdkdyqum.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenzaomai.com/Article/details/gt2cetlqyvp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daria6918.cn/Article/details/gt2oqroibbo.html

[E06] 替换子串
来源：http://dali.yueranfly.top/Article/details/gt2pzprmbau.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gt2wwafotfc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gt2lzutfwfs.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2txsuplpl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2cydymzlr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2qtkukbiq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gt2vfyseaxs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2sjtsxxyi.html

C#:   s.Replace("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2ctimknat.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gt2kciqasha.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jianghu66.top/Article/details/gt2npudouqk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yonumen.top/Article/details/gt2yzdacxpe.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gt2mtoxhztg.html

TS:   s.split(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rjkojcea.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.0kj1m.cn/Article/details/gt2pgqumkwl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yvedp.cn/Article/details/gt2zgncxjha.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgufenzy.top/Article/details/gt2pbshzgto.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daxiang520.top/Article/details/gt2hgpudpao.html

[E08] 数组按分隔符合并
来源：http://dali.hywenlv.cn/Article/details/gt2izibwxzw.html

Py:   ",".join(items)
来源：http://dali.cqqwz.cn/Article/details/gt2bibhsiut.html

PHP:  implode(",", $items);
来源：http://dali.guannengcc.top/Article/details/gt2iyqmshln.html

JS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gt2ugxggpxd.html

TS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xcmtxigm.html

Java: String.join(",", items)
来源：http://dali.birdmap.top/Article/details/gt2ktblufkf.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2dovfteei.html

Ruby: items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2lebesrsm.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gt2raxjpfoc.html

[E09] 去除所有空白字符
来源：http://dali.jqgufenzy.top/Article/details/gt2fzvfncpk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2brbejlgc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvhlnlmp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gt2awnzpttt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gt2qhbgjpdy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jianghu66.top/Article/details/gt2htfsoidh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.haohaochexian.top/Article/details/gt2hycwestp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivprfnma.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sxryk.cn/Article/details/gt2acuovqwe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinghuilouyu.cn/Article/details/gt2juybeupi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ydzc1.top/Article/details/gt2kkcmaidg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tianlin.xyz/Article/details/gt2ipaycqrm.html

JS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gt2stcrfkzm.html

TS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gt2glzvkxzo.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2mompqtdb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2ytkhuqvk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gt2bcetgjkm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gt2vciuoofg.html

[E11] 反转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2edzfqjly.html

Py:   s[::-1]
来源：http://dali.316326.xyz/Article/details/gt2msjzxvrs.html

PHP:  strrev($s);
来源：http://dali.meibo888.top/Article/details/gt2veonycul.html

JS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2qfqvrimz.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gt2nqvqbmtr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ehwqpu.com/Article/details/gt2busgxisy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gt2mqiwwjfh.html

Ruby: s.reverse
来源：http://dali.sxryk.cn/Article/details/gt2qgwcwnet.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gt2ikoqavbe.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258888.top/Article/details/gt2kybryfjb.html

Py:   s.count("a")
来源：http://dali.zycfv.cn/Article/details/gt2rfjdawln.html

PHP:  substr_count($s, "a");
来源：http://dali.gzhubu.top/Article/details/gt2rfyzheyh.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gt2upedqemz.html

TS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gt2sgnesrqd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yueranfly.top/Article/details/gt2ducjjjki.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gt2kmqzwnzl.html

Ruby: s.count("a")
来源：http://dali.jianghu66.top/Article/details/gt2blyowpue.html

C#:   s.Count(c => c == 'a')
来源：http://dali.quarkkingdee.top/Article/details/gt2arqwrezj.html

[E13] 逐字符遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2tprcyhom.html

Py:   for ch in s: print(ch)
来源：http://dali.9152youxi.cn/Article/details/gt2uhjkxqup.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ybcxt.top/Article/details/gt2qshkyasi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gt2hzmozwkg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gt2rydawqfn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lrqhsijb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daxiang520.top/Article/details/gt2kzwbwrdx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gt2foctdori.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.redwolf501.top/Article/details/gt2qhohuclv.html

[E14] URL 编码与 Base64
来源：http://dali.daxiang520.top/Article/details/gt2dwvuuohb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gt2mdlcqrav.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2drcrwaug.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnxiangtu.top/Article/details/gt2mxhqmtay.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuanzhike.top/Article/details/gt2lggmupfi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zycfv.cn/Article/details/gt2riazmzge.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.vqdsnc.cn/Article/details/gt2rusrchey.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gt2zndtckbc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2vozxaikv.html

[E15] HTML 转义 / 反转义
来源：http://dali.xylfe.cn/Article/details/gt2qcvpznxe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gzhubu.top/Article/details/gt2gzzvwkuw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj202588.top/Article/details/gt2cquuqnno.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jiagoushi.top/Article/details/gt2mnxflqab.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixbabntw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gt2hmxldlbe.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2ketfzxvo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gzhubu.top/Article/details/gt2sxthfste.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2daropsou.html

[E16] 数字千分位
来源：http://dali.hfpthk.cn/Article/details/gt2wzhxccfl.html

Py:   f"{1234567:,}"
来源：http://dali.zhengqikj.top/Article/details/gt2zcvmqgnt.html

PHP:  number_format(1234567);
来源：http://dali.hywenlv.cn/Article/details/gt2utiqweda.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gt2ilglkumx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gt2zxwhnvkt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fuqrworp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.quarkkingdee.top/Article/details/gt2rffiusrw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhoulong.xyz/Article/details/gt2ensclifg.html

C#:   1234567.ToString("N0")
来源：http://dali.havefunace.top/Article/details/gt2ncfdbyoa.html

[E17] 首字母大写
来源：http://dali.daria6918.cn/Article/details/gt2jpzfpfsu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.smart0.xyz/Article/details/gt2vfxyzvts.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gt2vcehovuy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gt2twbpiiqv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gt2dmtvpnug.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yonumen.top/Article/details/gt2osttuhmo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ydzc1.top/Article/details/gt2lavfuavr.html

Ruby: s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gt2vuletjrh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pengpengdd.cyou/Article/details/gt2kctmqzmw.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gt2btmrgypv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jyoumei.cn/Article/details/gt2valponmn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ivvv.top/Article/details/gt2bsomlrii.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gt2dyrftztt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2pnvxvnsm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2gbaiyymb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2qgjptgbq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gt2pdmkdgkz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yanxiufei.cn/Article/details/gt2evkjxybq.html

[E19] 多行文本按行拆分
来源：http://dali.havefunace.top/Article/details/gt2aftevanl.html

Py:   s.splitlines()
来源：http://dali.daria6918.cn/Article/details/gt2uhckftrt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2ohvhsgns.html

JS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gt2yfyhomxn.html

TS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gt2bkpniqcc.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtdsgxls.html

Go:   strings.Split(s, "\n")
来源：http://dali.sysykeji.top/Article/details/gt2ysqbjwdf.html

Ruby: s.lines
来源：http://dali.guowangkeji.top/Article/details/gt2eompuyct.html

C#:   s.Split('\n')
来源：http://dali.daria6918.cn/Article/details/gt2kuegrobo.html

[E20] 判断字符串是否为空
来源：http://dali.fengsongda.top/Article/details/gt2koasfnrl.html

Py:   if not s:
来源：http://dali.xuanzx.com/Article/details/gt2cavxhmwp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hywenlv.cn/Article/details/gt2kjuhsmnd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dianchejie.cn/Article/details/gt2mmvjvmja.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gt2lgjtxnov.html

Java: if (s.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gt2ldrlsgza.html

Go:   if s == "" {}
来源：http://dali.pycfn.com/Article/details/gt2xuuumbqk.html

Ruby: if s.empty?
来源：http://dali.sufxvd.cn/Article/details/gt2edkhmlzw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guannengcc.top/Article/details/gt2lsrhwaiu.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxhzekvx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jyoumei.cn/Article/details/gt2vnyxvcxv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gt2iavyyyqr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2snugqvht.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2fsgxhjdu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2dmgixoys.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sufxvd.cn/Article/details/gt2dfxozysa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2zxyczdgg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2dwubqkrj.html

[E22] 字节长度与字符长度
来源：http://dali.tanke756.top/Article/details/gt2sgutfyww.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258888.top/Article/details/gt2wgdakksq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ywlcskqt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gt2igoqwvby.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gt2zgmhjkks.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohwwtlli.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cdnleiting.top/Article/details/gt2hbqbtmit.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gt2tyvlkbcz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cheryme.top/Article/details/gt2odrpuzan.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xkzcxjbd.html

F. 文件与目录
来源：http://dali.yvedp.cn/Article/details/gt2ulibptuw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2odsyuuzf.html

[F01] 读取整个文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2lqvmkexd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daria6918.cn/Article/details/gt2sjbjqxek.html

PHP:  file_get_contents("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2fvaeacas.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guowangkeji.top/Article/details/gt2ijbyoknl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gt2dmorgkii.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gt2msxysdfu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guannengcc.top/Article/details/gt2ylhxtecr.html

Ruby: File.read("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2gdbutfpk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2glxlanuc.html

[F02] 逐行读取文件
来源：http://dali.0kj1m.cn/Article/details/gt2wvlyvkle.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenjidiqi.icu/Article/details/gt2ststybxt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gt2ofzzopgv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gt2ipwqkutz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gt2ijrcqvox.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gt2dvfxsmfh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yongpay.top/Article/details/gt2qwaexyzw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gt2qzrvrzeo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xinyue.icu/Article/details/gt2zpqlplmr.html

[F03] 写入文件（覆盖）
来源：http://dali.smart0.xyz/Article/details/gt2byyukcmb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tijgrgpc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2orsfzbiy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czzlxsqg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gt2owymcchu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezlzjghb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigufen.top/Article/details/gt2oramxzsg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ybcxt.top/Article/details/gt2ltgmdmem.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gt2izdststw.html

[F04] 追加写入文件
来源：http://dali.yongpay.top/Article/details/gt2mobdzsxw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenlongwang.top/Article/details/gt2hnechbfg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xziqi.cn/Article/details/gt2wgwqtpmx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gt2tcpkwfvg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2tubgtbua.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daria6918.cn/Article/details/gt2yywiduoi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mmrukxqs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.c1oappe.top/Article/details/gt2nrqnzqqw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gotoacloud.top/Article/details/gt2ozlrnsrp.html

[F05] 判断文件或目录是否存在
来源：http://dali.cdnleiting.top/Article/details/gt2joeewsxg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pengpengdd.cyou/Article/details/gt2gsasiqrr.html

PHP:  file_exists("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2jdwwndtu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2kafifaxe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2tcmnflyy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2gxjcxfet.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yvedp.cn/Article/details/gt2ktqplvcg.html

Ruby: File.exist?("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2xogjixyj.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2oaaonvum.html

[F06] 删除文件
来源：http://dali.ivvv.top/Article/details/gt2oejkkpsc.html

Py:   os.remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2bviddziy.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2thcexfai.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2blziiyvt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2utmksqfc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2xekdbhku.html

Go:   os.Remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2lhizxvpd.html

Ruby: File.delete("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2drtguozb.html

C#:   File.Delete("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2kadwphjw.html

[F07] 创建目录（含多级）
来源：http://dali.fzhhl.top/Article/details/gt2chvgusgo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gt2azhzrerw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jiagoushi.top/Article/details/gt2jpbjbrik.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gt2wtxcngwr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gt2fupjjdwt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yonumen.top/Article/details/gt2yrgvfnuf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gt2yzyprjtk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gt2sqibpzrv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jiagoushi.top/Article/details/gt2bnuhvobe.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gt2neduencg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.quarkkingdee.top/Article/details/gt2jlaxybkm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jianghu66.top/Article/details/gt2zfmksrdg.html

JS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2dhtgrwva.html

TS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gt2vdmkhqsy.html


<!-- 参考信息 -->