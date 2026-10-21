代发 wailian999

Go:   slices.Contains(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtmnsuxoyv.html

Ruby: arr.include?(x)
来源：http://dali.gotoacloud.top/Article/details/gtbwyorrty.html

C#:   list.Contains(x)
来源：http://dali.jqgfzy.top/Article/details/gtgbjdillc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yongpay.top/Article/details/gtustlkhop.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zycfv.cn/Article/details/gteeexzafh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yangfankeji.com/Article/details/gtleqeyqxe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cashguo.top/Article/details/gtqgjgvuza.html

TS:   [...arr];
来源：http://dali.sweek.top/Article/details/gtqkdxolob.html

Java: new ArrayList<>(list);
来源：http://dali.haohaochexian.top/Article/details/gtzsdpoffy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gtibcsmyhh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hywenlv.cn/Article/details/gtjscjymym.html

C#:   new List<int>(list);
来源：http://dali.nwbrower.top/Article/details/gtewnvlqjs.html

[D23] reduce 累积计算
来源：http://dali.daria6918.cn/Article/details/gtrcskzeev.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guannengcc.top/Article/details/gtgdcgshvf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gtlewoifdf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gtzcsttaum.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gtiutgvqlu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.birdmap.top/Article/details/gtsjipykfx.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtrpknhpih.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daria6918.cn/Article/details/gtierbyvxg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.redwolf501.top/Article/details/gtmmjqwwfb.html

[D24] 字典 / Map 基本操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjcmlywq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj202588.top/Article/details/gtkadizwee.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnqzz.top/Article/details/gtvjhchyjc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.bjfxy.top/Article/details/gtuexpzetc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtphruaqap.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj202588.top/Article/details/gtyrplstie.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangshuangyany.cn/Article/details/gtaudqkkic.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hfpthk.cn/Article/details/gtiajlgikx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258.top/Article/details/gtvnjjhuce.html

[D25] Set 集合去重与交并差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesqrpkey.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfvwmlmg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gtuasahxfs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gzhubu.top/Article/details/gtdcmulkav.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258.top/Article/details/gtcbkepuou.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.wangdashe.top/Article/details/gtqnzwohdx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrktvyrj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cheryme.top/Article/details/gtiplzycpo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtmqbdkahw.html

[D26] 数组转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtylrtzajq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtbmfjnnga.html

PHP:  implode(", ", $arr);
来源：http://dali.shuidangran.top/Article/details/gtlclkqggf.html

JS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtyknimbps.html

TS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtqrbqbsrv.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbcegstwr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cheryme.top/Article/details/gtsuzqzynw.html

Ruby: arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtpywdlmpq.html

C#:   string.Join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gtjharywru.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtzcoeaope.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gtjzvujtmp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtfibbggya.html

[E01] 拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtbfrdbyvd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hywenlv.cn/Article/details/gtijgkhnru.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sufxvd.cn/Article/details/gtudthmmkd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gteneaoext.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzkzdpna.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xylfe.cn/Article/details/gtrozmzehp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.meibo888.top/Article/details/gthxapwhba.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daxiang520.top/Article/details/gtaqrldwsw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtcgyeqlrt.html

[E02] 重复字符串
来源：http://dali.yueranfly.top/Article/details/gtmyuujtqv.html

Py:   "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gtehnpquor.html

PHP:  str_repeat("ab", 3);
来源：http://dali.9152youxi.cn/Article/details/gttobkglwz.html

JS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtpzguvkzm.html

TS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtfrqvdxrx.html

Java: "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gtqhbdidhm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.0kj1m.cn/Article/details/gtatuiflqd.html

Ruby: "ab" * 3
来源：http://dali.tian-w.cn/Article/details/gtwaloumwp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xinyue.icu/Article/details/gtskldyvcx.html

[E03] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gtlagbtldq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhengqikj.top/Article/details/gtuqdzqydj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtjydcoalc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzopmhcmh.html

TS:   s.slice(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtmcxvlpwh.html

Java: s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtgxlpbtlt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmnywihq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cheryme.top/Article/details/gttladapyr.html

C#:   s.Substring(1, 3)
来源：http://dali.guowangkeji.top/Article/details/gtaqahguyu.html

[E04] 查找子串位置
来源：http://dali.jianghu66.top/Article/details/gtxmykfvtk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fzhhl.top/Article/details/gtwqxmsekp.html

PHP:  strpos($s, "x");
来源：http://dali.wangdashe.top/Article/details/gtjtkqrhxp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.9152youxi.cn/Article/details/gtfogljqip.html

TS:   s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtoetopijn.html

Java: s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtyjafwvyy.html

Go:   strings.Index(s, "x")
来源：http://dali.svipenyu.cn/Article/details/gtsjcyuiap.html

Ruby: s.index("x")
来源：http://dali.gogol.net.cn/Article/details/gtmcljgdqe.html

C#:   s.IndexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtfozelrfg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhiwuduotai.top/Article/details/gtbysveapa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtekmuyctk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.andypj.xyz/Article/details/gthtxhnjhk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gteckypoyd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.smart0.xyz/Article/details/gtxlzogpbc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtgdvkhdhy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.vqdsnc.cn/Article/details/gtmwnbjhtd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.iojbl.cn/Article/details/gtlilthcfs.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gtrhnksmhv.html

[E06] 替换子串
来源：http://dali.sufxvd.cn/Article/details/gtbaqjwkfy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gtywtqjuzb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xinyue.icu/Article/details/gtsytxaoaz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtwoymrspe.html

TS:   s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtqjvkuzxa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtspdiszlp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gtnxyyrjvo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gthpuzyakw.html

C#:   s.Replace("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtlhfrolye.html

[E07] 按分隔符拆分
来源：http://dali.redwolf501.top/Article/details/gtrjmfrouc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yonumen.top/Article/details/gtjhvvkiql.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvwsrmrk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtdojgpjie.html

TS:   s.split(",")
来源：http://dali.yj202588.top/Article/details/gtiakjpphz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sufxvd.cn/Article/details/gtrxweetwy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.c1oappe.top/Article/details/gtczmwpxca.html

Ruby: s.split(",");  s.split
来源：http://dali.cashguo.top/Article/details/gtnrajzqng.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tianlin.xyz/Article/details/gtjrxbnkep.html

[E08] 数组按分隔符合并
来源：http://dali.hongshengwenyu.top/Article/details/gteshxwykq.html

Py:   ",".join(items)
来源：http://dali.jianghu66.top/Article/details/gtzmlasyyw.html

PHP:  implode(",", $items);
来源：http://dali.yuanzhike.top/Article/details/gtmyonwpzn.html

JS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtsekdbwmu.html

TS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosvfbdor.html

Java: String.join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gtoddgskgb.html

Go:   strings.Join(items, ",")
来源：http://dali.zdqjudy.top/Article/details/gtungnjzqw.html

Ruby: items.join(",")
来源：http://dali.jianghu66.top/Article/details/gttzjvykvw.html

C#:   string.Join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtonrpdqwt.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gtujuaegoo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gttcguniwx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtqfetuoon.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gttbghnskp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gthfbtuoki.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gtilzwnfqk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aizwys.cn/Article/details/gtsbeowcau.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ehwqpu.com/Article/details/gtnwnwdrdd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtaxwtofgz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhiwuduotai.top/Article/details/gtidvzlpzj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtfhbhnzpr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xinyue.icu/Article/details/gtjcxvilup.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtvyspwimy.html

TS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtivkhyaso.html

Java: String.format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtjxbfqjhp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtdbjotxlo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtnypxqohp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigufen.top/Article/details/gtabhkpwkv.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gtqlnaennf.html

Py:   s[::-1]
来源：http://dali.yj20258.top/Article/details/gttrtotjtu.html

PHP:  strrev($s);
来源：http://dali.cheryme.top/Article/details/gthvmyuhmp.html

JS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtnlwyyhfr.html

TS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtgfthoifr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sysykeji.top/Article/details/gtjnoewhxs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.316326.xyz/Article/details/gtfmapmsel.html

Ruby: s.reverse
来源：http://dali.hnqzz.top/Article/details/gtipqudglh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gthuhlbhtl.html

[E12] 统计某字符出现次数
来源：http://dali.shzxlz.cn/Article/details/gtywzskopb.html

Py:   s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gtwlfojtwn.html

PHP:  substr_count($s, "a");
来源：http://dali.svipenyu.cn/Article/details/gtykweufrl.html

JS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gtygitfwkr.html

TS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gtuxxqdvbc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.feifeiyinyue.top/Article/details/gtwndmrrzx.html

Go:   strings.Count(s, "a")
来源：http://dali.dianchejie.cn/Article/details/gtwxwjgtrn.html

Ruby: s.count("a")
来源：http://dali.sweek.top/Article/details/gtuztmllhe.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guowangkeji.top/Article/details/gtwlfnfmki.html

[E13] 逐字符遍历
来源：http://dali.vqdsnc.cn/Article/details/gthxvvcdzq.html

Py:   for ch in s: print(ch)
来源：http://dali.ybcxt.top/Article/details/gtpmygbjxg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhixingplan.top/Article/details/gtmxcambdu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gtiidwqvod.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gtdhijilhu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtzpvuguuv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenlongwang.top/Article/details/gtgfukaxcj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuanzx.com/Article/details/gtdlnjcsrg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.redwolf501.top/Article/details/gtmuqakiev.html

[E14] URL 编码与 Base64
来源：http://dali.cdnleiting.top/Article/details/gtcgchoogy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hfpthk.cn/Article/details/gtdfzwddoc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cucudq.cn/Article/details/gthgnsgmxd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zycfv.cn/Article/details/gtubjnqfto.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daxiang520.top/Article/details/gtplgsmbsf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangdashe.top/Article/details/gtdspvmobi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sweek.top/Article/details/gtnxtdsmiv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gtdjdgqehj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnkakwdf.html

[E15] HTML 转义 / 反转义
来源：http://dali.jlsjyb.cn/Article/details/gtgfjzksij.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtvukivjqp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapbluhtp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nwbrower.top/Article/details/gtmfonnuab.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cucudq.cn/Article/details/gtbdjowdqs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gtspsemyvy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtnllcqibt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hysaishi.cn/Article/details/gtcnqrckns.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gtvmdqvaoh.html

[E16] 数字千分位
来源：http://dali.gogol.net.cn/Article/details/gtavfcpzvx.html

Py:   f"{1234567:,}"
来源：http://dali.tian-w.cn/Article/details/gtmnphygcv.html

PHP:  number_format(1234567);
来源：http://dali.xuetiantiany.cn/Article/details/gtmiozpgxz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gtbphhauov.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gtsjbxadze.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gtjpughsro.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tanke756.top/Article/details/gtkgttowcc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tianlin.xyz/Article/details/gtmfaljhhj.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gtprtufevs.html

[E17] 首字母大写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqovwedza.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gtgjufaypf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gtyikcprhu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gtlyffdzgw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gtscstippa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhixingplan.top/Article/details/gtzbkoycag.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.iojbl.cn/Article/details/gtjfgigihu.html

Ruby: s.capitalize
来源：http://dali.xuanzx.com/Article/details/gtsqncdeuu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgufenzy.top/Article/details/gtnjahbpvy.html

[E18] 模板占位符替换
来源：http://dali.bjfxy.top/Article/details/gtsuephzlo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.svipenyu.cn/Article/details/gtunabdzri.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sufxvd.cn/Article/details/gtrqrqtmtr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtuzmadnwc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtdwefslct.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtwtwjkscq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtjdxtgdxt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gogol.net.cn/Article/details/gtrsmmjlll.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shuidangran.top/Article/details/gtpsjrgeps.html

[E19] 多行文本按行拆分
来源：http://dali.gotoacloud.top/Article/details/gtvndnusdd.html

Py:   s.splitlines()
来源：http://dali.haohaochexian.top/Article/details/gtgpfqznxh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guannengcc.top/Article/details/gtecyqycus.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtuqevutgn.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gtmaikmxxx.html

Java: s.lines().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxojmuiv.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdzcskly.html

Ruby: s.lines
来源：http://dali.daxiang520.top/Article/details/gtxgqpyepd.html

C#:   s.Split('\n')
来源：http://dali.9152youxi.cn/Article/details/gtzivlrpfs.html

[E20] 判断字符串是否为空
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzwcqncv.html

Py:   if not s:
来源：http://dali.bjfxy.top/Article/details/gtytsgwryf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pengpengdd.cyou/Article/details/gtjcsdsejz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtzvdsynnq.html

TS:   if (s === "") {}
来源：http://dali.hywenlv.cn/Article/details/gtndmbjygq.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtobeaoycj.html

Go:   if s == "" {}
来源：http://dali.jiagoushi.top/Article/details/gtdlomguxh.html

Ruby: if s.empty?
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrhxiorw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gtwzyadkwc.html

[E21] 超长截断加省略号
来源：http://dali.jlsjyb.cn/Article/details/gtilcchkif.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.0kj1m.cn/Article/details/gtvkhuxdzb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtozvvgsin.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcizafitp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtdqokxeoi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtazssaeuv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cucudq.cn/Article/details/gtmhxabmmp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gthperyvzn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gthstdpbxs.html

[E22] 字节长度与字符长度
来源：http://dali.ppjwa.cn/Article/details/gtbabsfvxn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhongyouzk.top/Article/details/gtwgbnrilp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtxxcvhcrf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gtpwgamyzv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtdegittjm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkebirfcq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenjidiqi.icu/Article/details/gtozgyvtdr.html

Ruby: s.bytesize;  s.length
来源：http://dali.pycfn.com/Article/details/gtdfykeift.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gtvsawvlkd.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtelgpvcxu.html

F. 文件与目录
来源：http://dali.fengsongda.top/Article/details/gtcnndgvsh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtqfsknqjw.html

[F01] 读取整个文件
来源：http://dali.svipenyu.cn/Article/details/gtuodjkfbr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shangyingyoupin.top/Article/details/gtihdzwpkl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtsruiuwag.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shangyingyoupin.top/Article/details/gtpablnxsl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gteiutfzrp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtvwqzayev.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xziqi.cn/Article/details/gttdzshgik.html

Ruby: File.read("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexhxncpl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtxhzjhzyu.html

[F02] 逐行读取文件
来源：http://dali.yueranfly.top/Article/details/gtoosasovn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ybcxt.top/Article/details/gtsfxtutlk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gtucnggdfa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtazrxtaud.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gtnfyccyew.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtsotmyeai.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sufxvd.cn/Article/details/gtzyvkwvvn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhiwuduotai.top/Article/details/gthvnhudeh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zycfv.cn/Article/details/gtgpxciezr.html

[F03] 写入文件（覆盖）
来源：http://dali.guannengcc.top/Article/details/gtkmpsumtw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gaohongyu789.top/Article/details/gtzzpqdsoj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gtytgkvlci.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtmunfwgxd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtegzwwxur.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxinkj.top/Article/details/gtdmoujnsu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jianghu66.top/Article/details/gtevnmeeiy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daria6918.cn/Article/details/gtpdoasihx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gtwsmswylp.html

[F04] 追加写入文件
来源：http://dali.shangyingyoupin.top/Article/details/gtbaymqhpu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahpencnf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gtdvqkswoa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gttevwcags.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtsmkresid.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhixingplan.top/Article/details/gtuocgmmld.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.316326.xyz/Article/details/gtloawkytj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gtfbwpkkzn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yueranfly.top/Article/details/gtnqcdcikg.html

[F05] 判断文件或目录是否存在
来源：http://dali.meibo888.top/Article/details/gtpcdgjump.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jianghu66.top/Article/details/gttvfiiajc.html

PHP:  file_exists("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtrqisukie.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtxzkdeuej.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtpnohdfcy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtdzcolbtl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.mhx1999.top/Article/details/gtbtuubahj.html

Ruby: File.exist?("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtrvhimgit.html

C#:   File.Exists("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtuhxgohmc.html

[F06] 删除文件
来源：http://dali.kuanghao11.cn/Article/details/gtqblzlqvc.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtzdwjpuhz.html

PHP:  unlink("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtglnfnyfa.html


<!-- 参考信息 -->