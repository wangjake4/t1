代发 wailian999

[D23] reduce 累积计算
来源：http://dali.jinqigfzy.top/Article/details/gt2kxkibugd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2ybnkeecv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2usflfelo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gt2llzuctjy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gt2ypvjvdyd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhengqikj.top/Article/details/gt2fezchepi.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gt2qxxnzxbv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ivvv.top/Article/details/gt2anhdhzou.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vzvbpmgo.html

[D24] 字典 / Map 基本操作
来源：http://dali.dianchejie.cn/Article/details/gt2oxnvdnbx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gt2vsvrkwcj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2qbjcmqfw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cucudq.cn/Article/details/gt2kyvjfnnw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2mznkebln.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.kuanghao11.cn/Article/details/gt2uungtsfj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cqqwz.cn/Article/details/gt2aaagzbmw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhixingplan.top/Article/details/gt2zkbgwrzz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.smart0.xyz/Article/details/gt2kuajiksr.html

[D25] Set 集合去重与交并差
来源：http://dali.hammf.cn/Article/details/gt2htaqrdrg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdmnokyz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnqzz.top/Article/details/gt2aggqqvkr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fzhhl.top/Article/details/gt2olmdufbv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.kuanghao11.cn/Article/details/gt2aazbxlbf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2wmhxcfve.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhengqikj.top/Article/details/gt2bmopxygy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xinyue.icu/Article/details/gt2pztxsdil.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ivvv.top/Article/details/gt2mvtnvfjt.html

[D26] 数组转字符串
来源：http://dali.cashguo.top/Article/details/gt2kgyvwymk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbcvpeyc.html

PHP:  implode(", ", $arr);
来源：http://dali.0kj1m.cn/Article/details/gt2egmcnxrp.html

JS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2ymkpmlhx.html

TS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gt2ipsbnxby.html

Java: String.join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gt2ghgdbouz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ppjwa.cn/Article/details/gt2msorlicr.html

Ruby: arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2voyljrdr.html

C#:   string.Join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zmeqxbcv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2qcajqjbh.html

E. 字符串处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zggvdjwe.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2cipewnxq.html

[E01] 拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gt2bbvbbktk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ehwqpu.com/Article/details/gt2rgklgdyb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qfjtysde.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2pasbnuam.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2djyyhewp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hysaishi.cn/Article/details/gt2ykzoales.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gt2flomqkdf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wqekkjzp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2joyuglfi.html

[E02] 重复字符串
来源：http://dali.yonumen.top/Article/details/gt2mavxcgqf.html

Py:   "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gt2bbyalhli.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2iqwtmxsz.html

JS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gt2cbaudzep.html

TS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gt2wwnskvzv.html

Java: "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gt2rlkshqij.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zycfv.cn/Article/details/gt2oumgotam.html

Ruby: "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gt2edtluyfo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.iojbl.cn/Article/details/gt2briycvzy.html

[E03] 截取子串
来源：http://dali.tian-w.cn/Article/details/gt2ocdvjzeq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxuanxn.top/Article/details/gt2grzgnkop.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2inusxwcs.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gt2indamqeu.html

TS:   s.slice(1, 4)
来源：http://dali.daxiang520.top/Article/details/gt2ukwqxbgy.html

Java: s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gt2xibnswtf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gogol.net.cn/Article/details/gt2teocpkdo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.smart0.xyz/Article/details/gt2ejiyufvs.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrrqdbx.html

[E04] 查找子串位置
来源：http://dali.aibaodan.cn/Article/details/gt2uwpcdiru.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guowangkeji.top/Article/details/gt2vggbeshi.html

PHP:  strpos($s, "x");
来源：http://dali.hongshengwenyu.top/Article/details/gt2ydihhixh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhoulong.xyz/Article/details/gt2ekjhmljp.html

TS:   s.indexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2mdpdoiaf.html

Java: s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gt2wmnxqebw.html

Go:   strings.Index(s, "x")
来源：http://dali.andypj.xyz/Article/details/gt2kxwdnmno.html

Ruby: s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gt2gueemrim.html

C#:   s.IndexOf("x")
来源：http://dali.ivvv.top/Article/details/gt2lqhxzqvo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.quarkkingdee.top/Article/details/gt2msmpafja.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxuanxn.top/Article/details/gt2xnqfzbxv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yvedp.cn/Article/details/gt2ceezkjwv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2npepnjhn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aizwys.cn/Article/details/gt2vhryekxl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gt2awpdvoyl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.smart0.xyz/Article/details/gt2knsduljy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sufxvd.cn/Article/details/gt2tmmpkeew.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.iojbl.cn/Article/details/gt2idaxlnyc.html

[E06] 替换子串
来源：http://dali.gotoacloud.top/Article/details/gt2xstjghxw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gt2yuphzacd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2wmtvnvde.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nnwgcfve.html

TS:   s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2gvayzgfd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2gajflxjl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gt2pdajlbpg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2dlealdsv.html

C#:   s.Replace("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2oismqjtj.html

[E07] 按分隔符拆分
来源：http://dali.gaohongyu789.top/Article/details/gt2kqdnfvoe.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sysykeji.top/Article/details/gt2fvartmmw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2bliowgjd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfpczvbs.html

TS:   s.split(",")
来源：http://dali.yonumen.top/Article/details/gt2aubtioze.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sufxvd.cn/Article/details/gt2vuaicttn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guowangkeji.top/Article/details/gt2phbgphpm.html

Ruby: s.split(",");  s.split
来源：http://dali.jlsjyb.cn/Article/details/gt2kcvduqgu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fengsongda.top/Article/details/gt2tiggefft.html

[E08] 数组按分隔符合并
来源：http://dali.ivvv.top/Article/details/gt2zoflypgz.html

Py:   ",".join(items)
来源：http://dali.zycfv.cn/Article/details/gt2qfxjjcyu.html

PHP:  implode(",", $items);
来源：http://dali.svipenyu.cn/Article/details/gt2xkhosujn.html

JS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gt2qtodlpiz.html

TS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gt2cmpsbltg.html

Java: String.join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gt2nhhckxgl.html

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gt2uiwaajon.html

Ruby: items.join(",")
来源：http://dali.c1oappe.top/Article/details/gt2kslddskf.html

C#:   string.Join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tejtvbjr.html

[E09] 去除所有空白字符
来源：http://dali.yvedp.cn/Article/details/gt2jesutxcb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yongpay.top/Article/details/gt2vjuioaxi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yvedp.cn/Article/details/gt2tjugeiyw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gt2pknimxac.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gt2cmrwrixo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cjmcctej.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.9152youxi.cn/Article/details/gt2ioxvnhmd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ivvv.top/Article/details/gt2ogzoohmt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258888.top/Article/details/gt2dlbosmdv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2quufatpr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gt2mleurkxy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tian-w.cn/Article/details/gt2hjdfgozk.html

JS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2ldchhbrv.html

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gt2qnumagjj.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gt2jhsdciqo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gt2ntyyecby.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gt2mgsxzcwo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sysykeji.top/Article/details/gt2tslwrseu.html

[E11] 反转字符串
来源：http://dali.zhixingplan.top/Article/details/gt2sggvefzz.html

Py:   s[::-1]
来源：http://dali.mhx1999.top/Article/details/gt2brltfaof.html

PHP:  strrev($s);
来源：http://dali.yongpay.top/Article/details/gt2sxrpyfsg.html

JS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gt2fuvvmzjz.html

TS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gt2nskwdppc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xziqi.cn/Article/details/gt2joyazlol.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.haohaochexian.top/Article/details/gt2nvuxhtsu.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gt2kqonkzyq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gt2hwvkdhfo.html

[E12] 统计某字符出现次数
来源：http://dali.sysykeji.top/Article/details/gt2qiovnkfy.html

Py:   s.count("a")
来源：http://dali.yueranfly.top/Article/details/gt2rsynavax.html

PHP:  substr_count($s, "a");
来源：http://dali.smart0.xyz/Article/details/gt2hrboebxh.html

JS:   s.split("a").length - 1
来源：http://dali.zhixingplan.top/Article/details/gt2wwzlxwwu.html

TS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gt2opkunihf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.meibo888.top/Article/details/gt2xdfarxmh.html

Go:   strings.Count(s, "a")
来源：http://dali.yuanzhike.top/Article/details/gt2ikudyjfi.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gt2aioulwuy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aibaodan.cn/Article/details/gt2qdxduadr.html

[E13] 逐字符遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2kyjteutt.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvperobi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnxiangtu.top/Article/details/gt2wylskltm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gt2ljbuceuj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvnbazy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gt2jaotjveo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgfzy.top/Article/details/gt2kebosljj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ppjwa.cn/Article/details/gt2nuzrwmha.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.havefunace.top/Article/details/gt2liyubrhe.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gt2gcqiiznu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zgyyulqo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fzhhl.top/Article/details/gt2guamtoyy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yueranfly.top/Article/details/gt2bvqwjeni.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gotoacloud.top/Article/details/gt2xybfdbxq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yongpay.top/Article/details/gt2omdrejhg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgfzy.top/Article/details/gt2qpqgpltr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.c1oappe.top/Article/details/gt2irzrycod.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jyoumei.cn/Article/details/gt2bgjcqyqq.html

[E15] HTML 转义 / 反转义
来源：http://dali.gotoacloud.top/Article/details/gt2aqlwpjyv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yonumen.top/Article/details/gt2ucduyiut.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.haohaochexian.top/Article/details/gt2dcacoghb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xinyue.icu/Article/details/gt2hnqhfxxk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.snrcjt.cn/Article/details/gt2rsxwxzgp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ehwqpu.com/Article/details/gt2pzdtxhzo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.snrcjt.cn/Article/details/gt2nfmadipo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gt2thrtpnwl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.svipenyu.cn/Article/details/gt2ftnwkhrg.html

[E16] 数字千分位
来源：http://dali.mhx1999.top/Article/details/gt2lqkohikw.html

Py:   f"{1234567:,}"
来源：http://dali.cqqwz.cn/Article/details/gt2vvfjkgcc.html

PHP:  number_format(1234567);
来源：http://dali.snrcjt.cn/Article/details/gt2uspvmqta.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gt2vcbsbeyn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gt2edzvzvxs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.c1oappe.top/Article/details/gt2xjklokik.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxinkj.top/Article/details/gt2scvkajhb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.0kj1m.cn/Article/details/gt2ffcjzlyq.html

C#:   1234567.ToString("N0")
来源：http://dali.iojbl.cn/Article/details/gt2lgtqqrfb.html

[E17] 首字母大写
来源：http://dali.shangyingyoupin.top/Article/details/gt2xlnhoztw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ikmtybkl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gt2lrluxjaj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cqyvswpt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gt2xygmvqbt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2grkepdjt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhongyouzk.top/Article/details/gt2tndhlwly.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gfkxeubs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.smart0.xyz/Article/details/gt2lecxrfnk.html

[E18] 模板占位符替换
来源：http://dali.jlsjyb.cn/Article/details/gt2qrejbpfm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dianchejie.cn/Article/details/gt2lekhvaij.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqujwmrx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2qtdhuage.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gt2amwtyttz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2vltqlubb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2dacnpzuv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.0kj1m.cn/Article/details/gt2yjdqxbyv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ivvv.top/Article/details/gt2vmuoyswz.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gt2oqyrshvf.html

Py:   s.splitlines()
来源：http://dali.gaohongyu789.top/Article/details/gt2kraahxle.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2ivzlnnhu.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gt2nuwiovfj.html

TS:   s.split(/\r?\n/)
来源：http://dali.tianlin.xyz/Article/details/gt2zrfpawyt.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gt2joavtvga.html

Go:   strings.Split(s, "\n")
来源：http://dali.birdmap.top/Article/details/gt2gdpfxnjd.html

Ruby: s.lines
来源：http://dali.sxryk.cn/Article/details/gt2nhbvhyuk.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gt2szwsztow.html

[E20] 判断字符串是否为空
来源：http://dali.yanxiufei.cn/Article/details/gt2gtxsesvk.html

Py:   if not s:
来源：http://dali.sufxvd.cn/Article/details/gt2xmeszmbr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.bjfxy.top/Article/details/gt2jzkjlljp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ueaccrwl.html

TS:   if (s === "") {}
来源：http://dali.0kj1m.cn/Article/details/gt2fvrebdix.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gt2yfwrlyka.html

Go:   if s == "" {}
来源：http://dali.jiagoushi.top/Article/details/gt2yxtvgaza.html

Ruby: if s.empty?
来源：http://dali.ivvv.top/Article/details/gt2iqslewgg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.iojbl.cn/Article/details/gt2srgvyizg.html

[E21] 超长截断加省略号
来源：http://dali.mhx1999.top/Article/details/gt2hlexddnm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnxiangtu.top/Article/details/gt2esslahxi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2tuykrvxh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mperizki.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2fqkcoqfb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2nwcodrxi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gt2ogmwmiww.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2dfjtsoqv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2gpylsdlc.html

[E22] 字节长度与字符长度
来源：http://dali.tian-w.cn/Article/details/gt2sirmftie.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxbgpyxi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2ausyptpr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gt2kvwilhzk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gt2pmcdbsol.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gt2ehhrehdy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gt2gvybjvgc.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxinkj.top/Article/details/gt2shfsxkim.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sweek.top/Article/details/gt2xjqsyttj.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2lkxlmvav.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gt2wtwbsntl.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2tkqjqczc.html

[F01] 读取整个文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2ljfjilsn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gotoacloud.top/Article/details/gt2tevxfpjp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2jsoapmeg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuetiantiany.cn/Article/details/gt2mbltvclt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gt2azlrudlx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gt2jnxrllef.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.feifeiyinyue.top/Article/details/gt2wrzobtmm.html

Ruby: File.read("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2lujkbxkc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2ryhcubwh.html

[F02] 逐行读取文件
来源：http://dali.haohaochexian.top/Article/details/gt2vvvgdftf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cucudq.cn/Article/details/gt2ieuyfhiz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenzaomai.com/Article/details/gt2rwmgcfrk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gt2bbkkuvaq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gt2njmheosu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gt2rpwltjux.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gt2amystdmv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jianghu66.top/Article/details/gt2tfnpllhg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jianghu66.top/Article/details/gt2evavxszo.html

[F03] 写入文件（覆盖）
来源：http://dali.chenjidiqi.icu/Article/details/gt2mnnoquih.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cucudq.cn/Article/details/gt2qtpihmam.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gakpdvdk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gt2nvffcdmr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gt2zsiejkpr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2kszedaui.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gt2ckrnyanb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fpfeibfe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gt2zclbaczj.html

[F04] 追加写入文件
来源：http://dali.yj20258.top/Article/details/gt2krjgitcj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2arnludgb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gt2qvkjpeim.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2ahogcrmv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2okhrihys.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jyoumei.cn/Article/details/gt2idcvzabk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ppjwa.cn/Article/details/gt2uudcrquw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yvedp.cn/Article/details/gt2paoyvdcd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jyoumei.cn/Article/details/gt2vlrqtuwe.html

[F05] 判断文件或目录是否存在
来源：http://dali.cqqwz.cn/Article/details/gt2iorikauw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shuidangran.top/Article/details/gt2nohoheqt.html

PHP:  file_exists("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2esjysyks.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qyrcduka.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2hrqwysug.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gt2tzzwqfvg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.svipenyu.cn/Article/details/gt2ptsnlrao.html

Ruby: File.exist?("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2xciovvaj.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2spbxotxl.html

[F06] 删除文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fqoonobb.html

Py:   os.remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2fkujwlnr.html

PHP:  unlink("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2srregjlf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2yzflquew.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2ytkauvlb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2hcauenxn.html

Go:   os.Remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2fkzqnbxc.html

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2fvefjxcn.html

C#:   File.Delete("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2gldheisg.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gt2cvgyzqam.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkfnhzfw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fzhhl.top/Article/details/gt2cbbpyiid.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gt2lixccgxp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gt2oaytpqzp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jlsjyb.cn/Article/details/gt2ruojiybq.html


<!-- 参考信息 -->