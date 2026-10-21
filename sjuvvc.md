代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gtpyfbgkdc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gaohongyu789.top/Article/details/gtmzrgwzms.html

Go:   // 手写 map[string][]T
来源：http://dali.aibaodan.cn/Article/details/gtzifqbweh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ppjwa.cn/Article/details/gtjfthzmei.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.0kj1m.cn/Article/details/gthauldscj.html

[D20] 统计每个元素出现次数
来源：http://dali.gotoacloud.top/Article/details/gttrscfere.html

Py:   Counter(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbyyrahx.html

PHP:  array_count_values($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxxcwkfh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gtwdhukpqz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gthpourcae.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gtsdwaqrza.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gtwbhposza.html

Ruby: arr.tally
来源：http://dali.jlsjyb.cn/Article/details/gtyctqtcce.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gtqqwjfytn.html

[D21] 判断是否包含某元素
来源：http://dali.0kj1m.cn/Article/details/gtqsjaoeef.html

Py:   x in arr
来源：http://dali.andypj.xyz/Article/details/gtgvinflks.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jianghu66.top/Article/details/gtghienuif.html

JS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gtpjsuovaw.html

TS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtqbykldno.html

Java: list.contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtdztzvrfl.html

Go:   slices.Contains(arr, x)
来源：http://dali.cashguo.top/Article/details/gtqgdzyhnu.html

Ruby: arr.include?(x)
来源：http://dali.tianlin.xyz/Article/details/gtrwhwwmyr.html

C#:   list.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtbmweffgf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guowangkeji.top/Article/details/gtrgzanldz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258.top/Article/details/gtasoqojhn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnxiangtu.top/Article/details/gtsomgchaq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xziqi.cn/Article/details/gtgzypwvob.html

TS:   [...arr];
来源：http://dali.316326.xyz/Article/details/gtacpzpfha.html

Java: new ArrayList<>(list);
来源：http://dali.hnxiangtu.top/Article/details/gtnwpqlvjp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sufxvd.cn/Article/details/gtyoggeskc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cheryme.top/Article/details/gtqcksyvml.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdaksgeog.html

[D23] reduce 累积计算
来源：http://dali.havefunace.top/Article/details/gtapfkywaq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gtfvsetvwd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgfzy.top/Article/details/gtrkiszoka.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gtlipiaals.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtsexszubh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nwbrower.top/Article/details/gtnujsvojo.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtemmrblfw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangshuangyany.cn/Article/details/gtkrpbkthn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cashguo.top/Article/details/gtwwrchcgq.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuanzx.com/Article/details/gtremsahsg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sweek.top/Article/details/gthdllwwuv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gthpqtximv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtlmsusial.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gthhcollcp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ehwqpu.com/Article/details/gtglxmxopd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.smart0.xyz/Article/details/gtygebcdpd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhengqikj.top/Article/details/gtxuphifnv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.quarkkingdee.top/Article/details/gtiienqetu.html

[D25] Set 集合去重与交并差
来源：http://dali.ybcxt.top/Article/details/gtuawspukk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.smart0.xyz/Article/details/gtdjzrdmsj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ppjwa.cn/Article/details/gttwrhdhtg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guannengcc.top/Article/details/gtuwyzqbsg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrckmibpz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hysaishi.cn/Article/details/gtmvjlklvq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jianghu66.top/Article/details/gtutgitjff.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yanxiufei.cn/Article/details/gtjhrxifef.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ybcxt.top/Article/details/gtvewlxijl.html

[D26] 数组转字符串
来源：http://dali.xylfe.cn/Article/details/gtwdunevgv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtqxthjnwt.html

PHP:  implode(", ", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvquoteta.html

JS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtecllqcmk.html

TS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gtqfezvncf.html

Java: String.join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gtblngiejh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigufen.top/Article/details/gtkgrxsxrb.html

Ruby: arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtsockrkpg.html

C#:   string.Join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gtjjvcrkbj.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtwwrjvvaf.html

E. 字符串处理
来源：http://dali.fengsongda.top/Article/details/gtgvpykkdm.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtuljsrvhy.html

[E01] 拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtcgbkkdgm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.andypj.xyz/Article/details/gtuwdvkufw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zycfv.cn/Article/details/gtcdkgniei.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtkolmtlcn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtmckdtpcx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shangyingyoupin.top/Article/details/gtnisclagd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yvedp.cn/Article/details/gthyymzutu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hywenlv.cn/Article/details/gtlvkfifms.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gthjaldnag.html

[E02] 重复字符串
来源：http://dali.jinqigufen.top/Article/details/gtfsgdedrl.html

Py:   "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gtbowkdupu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangdashe.top/Article/details/gtiunqgctl.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtvghretcw.html

TS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtrxwsbzkb.html

Java: "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtioioquzr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtsmnmrwcx.html

Ruby: "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gtwihclriw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyapbvlt.html

[E03] 截取子串
来源：http://dali.xziqi.cn/Article/details/gtbliygjor.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhongyouzk.top/Article/details/gtqwfdgaiy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcrbdggi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gtbtavvydv.html

TS:   s.slice(1, 4)
来源：http://dali.hammf.cn/Article/details/gtmbsjobgb.html

Java: s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtpafrvava.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenzaomai.com/Article/details/gtbeeqxrau.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gtsnhamswd.html

C#:   s.Substring(1, 3)
来源：http://dali.zycfv.cn/Article/details/gtoahpcpcx.html

[E04] 查找子串位置
来源：http://dali.jyoumei.cn/Article/details/gtcvtcqwtv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gtnqaxvlbi.html

PHP:  strpos($s, "x");
来源：http://dali.zhongyouzk.top/Article/details/gtvuvotlsi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guannengcc.top/Article/details/gtasptfvdu.html

TS:   s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gtuzsjfqlf.html

Java: s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gthmvgbsiu.html

Go:   strings.Index(s, "x")
来源：http://dali.zhixingplan.top/Article/details/gtgutzxwmn.html

Ruby: s.index("x")
来源：http://dali.smart0.xyz/Article/details/gtwzukiufe.html

C#:   s.IndexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtxsgypnbl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.andypj.xyz/Article/details/gttmjxmivi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ybcxt.top/Article/details/gtarynyzte.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dashuyun.cn/Article/details/gtgfalinfe.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtktcczkoz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cucudq.cn/Article/details/gtoxbpaxos.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtlaitgjat.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daxiang520.top/Article/details/gtvmwgimqq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhoulong.xyz/Article/details/gtdlxxshnw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtuqsxpwjs.html

[E06] 替换子串
来源：http://dali.cdnleiting.top/Article/details/gtlvyfuhkw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gtjsljbzwr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hywenlv.cn/Article/details/gtlqzwhnmh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtratrcwpx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtlmeqqksj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtvmaryibx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gtoacarwhq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtsimidqot.html

C#:   s.Replace("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtqhxbvmtc.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gtlpphsdso.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.guowangkeji.top/Article/details/gtakzvfiea.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxscmtzm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fengsongda.top/Article/details/gtefafjsqg.html

TS:   s.split(",")
来源：http://dali.vqdsnc.cn/Article/details/gtrjvdxgec.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.vqdsnc.cn/Article/details/gtjijyavot.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.9152youxi.cn/Article/details/gtpplslxuk.html

Ruby: s.split(",");  s.split
来源：http://dali.pycfn.com/Article/details/gtwuiaadyx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gtrqdruczp.html

[E08] 数组按分隔符合并
来源：http://dali.zhongyouzk.top/Article/details/gtteialkgf.html

Py:   ",".join(items)
来源：http://dali.xuanzx.com/Article/details/gtqfdzidgj.html

PHP:  implode(",", $items);
来源：http://dali.jiagoushi.top/Article/details/gtoervqrtk.html

JS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtkryjsdmj.html

TS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gtavnktfvo.html

Java: String.join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gtqlevujqb.html

Go:   strings.Join(items, ",")
来源：http://dali.jiagoushi.top/Article/details/gttrbywirq.html

Ruby: items.join(",")
来源：http://dali.yongpay.top/Article/details/gtlugilkiv.html

C#:   string.Join(",", items)
来源：http://dali.havefunace.top/Article/details/gtynoqhprq.html

[E09] 去除所有空白字符
来源：http://dali.gogol.net.cn/Article/details/gtdegqjzpv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.bjfxy.top/Article/details/gtgvdoffnb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtbqkcryme.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gtrajybhrh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gttmbvcgdk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gtbdfjlkvt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhongyouzk.top/Article/details/gtmahdkpqf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cucudq.cn/Article/details/gtbuvcdcph.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gteferpifh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhengqikj.top/Article/details/gtatxwexxd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtcvoljomj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yvedp.cn/Article/details/gtnmjcvepe.html

JS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtygnkmlxj.html

TS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtfammvidm.html

Java: String.format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtiygllnzl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gtrkqdufiu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtuhromgja.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnxiangtu.top/Article/details/gtomqyypfo.html

[E11] 反转字符串
来源：http://dali.wangdashe.top/Article/details/gtwrirhsjp.html

Py:   s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gtlwycfffi.html

PHP:  strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtkweisjao.html

JS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtqqhvosda.html

TS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhzcpxxh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwczhifk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrldhayeu.html

Ruby: s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gttzschbne.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gtuvctohjx.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigufen.top/Article/details/gtxumltdpj.html

Py:   s.count("a")
来源：http://dali.316326.xyz/Article/details/gthbjhqdow.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgufenzy.top/Article/details/gtjfwhugjr.html

JS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gtqgdlkvet.html

TS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gtirpeingq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cucudq.cn/Article/details/gtnamwxfoy.html

Go:   strings.Count(s, "a")
来源：http://dali.nwbrower.top/Article/details/gtevkimcyg.html

Ruby: s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtznvzcend.html

C#:   s.Count(c => c == 'a')
来源：http://dali.andypj.xyz/Article/details/gthfpfqdbb.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gtozjvgzlq.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxuanxn.top/Article/details/gtliicaghs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.bjfxy.top/Article/details/gthfzjsujr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gtkooxmocb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gtykwztbyk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yongpay.top/Article/details/gtwexrjuce.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtephfiiof.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ybcxt.top/Article/details/gtpxjawvhb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gtrxhzylly.html

[E14] URL 编码与 Base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmujvetpr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtmachpmac.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tianlin.xyz/Article/details/gtfrhbipsj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ivvv.top/Article/details/gthbpeytwc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.snrcjt.cn/Article/details/gtilqdphnu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.birdmap.top/Article/details/gtiwgqyxys.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aibaodan.cn/Article/details/gtbfpbqwul.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplmqtoxg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtqgnwjnof.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gtusogqkky.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jyoumei.cn/Article/details/gtbwryawzv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hammf.cn/Article/details/gtzxkjxjod.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.9152youxi.cn/Article/details/gtcruseqlk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guowangkeji.top/Article/details/gtkfumbsnb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tanke756.top/Article/details/gtvcjzpduk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnxiangtu.top/Article/details/gtrgpcffqs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtezuunwrn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yanxiufei.cn/Article/details/gtuepfisqs.html

[E16] 数字千分位
来源：http://dali.jinqigufen.top/Article/details/gtirshzuwf.html

Py:   f"{1234567:,}"
来源：http://dali.sxryk.cn/Article/details/gtnxkejszd.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gtjtjqvegu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gtwohvxicq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaifsjegp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjkddhff.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cashguo.top/Article/details/gtexwkviwj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guannengcc.top/Article/details/gtdduzgydm.html

C#:   1234567.ToString("N0")
来源：http://dali.quarkkingdee.top/Article/details/gtqocroemt.html

[E17] 首字母大写
来源：http://dali.chenlongwang.top/Article/details/gtaocmdulg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj202588.top/Article/details/gtooumppke.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gtzgtvdsvp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gtyotpqpit.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gtteskasgl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fengsongda.top/Article/details/gtiwatibxo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cdnleiting.top/Article/details/gtgdqqpptc.html

Ruby: s.capitalize
来源：http://dali.daxiang520.top/Article/details/gtdiwjotkq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.c1oappe.top/Article/details/gtxtyiprbo.html

[E18] 模板占位符替换
来源：http://dali.nanxinkj.top/Article/details/gtooxdgxsq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.meibo888.top/Article/details/gtufgecmja.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sysykeji.top/Article/details/gtbjljuqxc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtybltnbvz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtdzcohhcj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtutzdiotv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtuttfkehk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.bjfxy.top/Article/details/gtplhmmkfp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.iojbl.cn/Article/details/gtybakfslw.html

[E19] 多行文本按行拆分
来源：http://dali.yangfankeji.com/Article/details/gtpelkblgg.html

Py:   s.splitlines()
来源：http://dali.fengsongda.top/Article/details/gtakhivdpv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pycfn.com/Article/details/gtienfjroo.html

JS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtzyvybahc.html

TS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gtumrasipr.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gtyputsaua.html

Go:   strings.Split(s, "\n")
来源：http://dali.jianghu66.top/Article/details/gtzypwsony.html

Ruby: s.lines
来源：http://dali.redwolf501.top/Article/details/gteuqzcykt.html

C#:   s.Split('\n')
来源：http://dali.zhixingplan.top/Article/details/gtqtbagldb.html

[E20] 判断字符串是否为空
来源：http://dali.jqgfzy.top/Article/details/gtngjhhrsg.html

Py:   if not s:
来源：http://dali.ehwqpu.com/Article/details/gtzogwkdiw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tian-w.cn/Article/details/gtdmdgeale.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gttkhlkmgy.html

TS:   if (s === "") {}
来源：http://dali.redwolf501.top/Article/details/gtupcaddxr.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gtkepvogde.html

Go:   if s == "" {}
来源：http://dali.zhoulong.xyz/Article/details/gtasgobnol.html

Ruby: if s.empty?
来源：http://dali.ppjwa.cn/Article/details/gtlzrtjwsf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtnsghbrxv.html

[E21] 超长截断加省略号
来源：http://dali.zycfv.cn/Article/details/gtfaskcngk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangdashe.top/Article/details/gtltjrzjfh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtubsofddg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtksbvihad.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtqqeuawjf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtzbdckbnw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gzhubu.top/Article/details/gteastcwgf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtqmuzdhmg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtfbexdwle.html

[E22] 字节长度与字符长度
来源：http://dali.fengsongda.top/Article/details/gtqazoviwm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gtbyxnabpy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtznpfbide.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gtijvsxfdu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gtirbljdfk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tianlin.xyz/Article/details/gtpmjjhtkm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gzhubu.top/Article/details/gtcnotbptx.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtueftehch.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sxryk.cn/Article/details/gtkfhztheu.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtdszwmmdl.html

F. 文件与目录
来源：http://dali.wangdashe.top/Article/details/gthcrmqwmx.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtdpdqjbkl.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gtudtzubkh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.redwolf501.top/Article/details/gtcusytvgw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtmdnetyju.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdeegooqg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtkmhmocow.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtlgguejft.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtseklzrcp.html

Ruby: File.read("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gttgjobdkw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cashguo.top/Article/details/gthvmxkllf.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gtvasoajgb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cheryme.top/Article/details/gtiesyzclq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gogol.net.cn/Article/details/gtyxtvhzmj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gtuqoutunx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gttwqqnjnj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtujtvhdpo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daxiang520.top/Article/details/gtgrkwybne.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gtypayiktv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jyoumei.cn/Article/details/gtitcntaxl.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gtdcchfetz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuanzx.com/Article/details/gtvvzzlfnb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gthabdidgx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtsytoepib.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtsyjxkvld.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sysykeji.top/Article/details/gthafykwur.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.iojbl.cn/Article/details/gtyumhszci.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gtdnwdigab.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtbsadwogs.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gtvuotzmlt.html


<!-- 参考信息 -->