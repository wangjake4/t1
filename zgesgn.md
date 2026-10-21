代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yanxiufei.cn/Article/details/gtwnarioxo.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtveqbhcol.html

[D17] 最大值与最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtfthcadil.html

Py:   max(arr);  min(arr)
来源：http://dali.daxiang520.top/Article/details/gtnsipjbts.html

PHP:  max($arr);  min($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtucxneflu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxslfedw.html

TS:   Math.max(...arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtdqoczbxb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tanke756.top/Article/details/gthzoqcrcw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aibaodan.cn/Article/details/gtyllvhjrx.html

Ruby: arr.max;  arr.min
来源：http://dali.aizwys.cn/Article/details/gtiztulobp.html

C#:   list.Max();  list.Min()
来源：http://dali.daria6918.cn/Article/details/gtrssltlhg.html

[D18] 扁平化嵌套数组
来源：http://dali.bjfxy.top/Article/details/gtrdmnpwgu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258888.top/Article/details/gtanjmpivv.html

PHP:  array_merge(...$nested);
来源：http://dali.chenjidiqi.icu/Article/details/gtmqvlfwyo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sweek.top/Article/details/gtcpgjvzgz.html

TS:   nested.flat();
来源：http://dali.yvedp.cn/Article/details/gtdcaofvra.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xziqi.cn/Article/details/gtouzlynga.html

Go:   // 手写双层循环
来源：http://dali.cdnleiting.top/Article/details/gtxkpquqog.html

Ruby: nested.flatten
来源：http://dali.yonumen.top/Article/details/gtmpdabgtg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shuidangran.top/Article/details/gtugztzxyj.html

[D19] 按字段分组
来源：http://dali.zhoulong.xyz/Article/details/gthgcqwfiu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.iojbl.cn/Article/details/gtyizijkgk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hysaishi.cn/Article/details/gtdhhwathu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzffdujet.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gtdzbwoiaj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ybcxt.top/Article/details/gtpxgivwek.html

Go:   // 手写 map[string][]T
来源：http://dali.hfpthk.cn/Article/details/gtrgnbpkka.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.mhx1999.top/Article/details/gtalfbolvb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.kuanghao11.cn/Article/details/gtrcfwaxys.html

[D20] 统计每个元素出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gtknhjisvj.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtzaipmneg.html

PHP:  array_count_values($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gterbwcnye.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtuwmhqhja.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sweek.top/Article/details/gtkusqwdaw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tanke756.top/Article/details/gthsxoyqyi.html

Go:   // 手写 map[T]int
来源：http://dali.zhiwuduotai.top/Article/details/gtxriuzshq.html

Ruby: arr.tally
来源：http://dali.yuxming.cn/Article/details/gtdojggxgy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ydzc1.top/Article/details/gtlasgqgfq.html

[D21] 判断是否包含某元素
来源：http://dali.nanxuanxn.top/Article/details/gtonejvnub.html

Py:   x in arr
来源：http://dali.jyoumei.cn/Article/details/gtreddddwh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtzcaswzfi.html

JS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtcyxktsxz.html

TS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gtazehhlgd.html

Java: list.contains(x)
来源：http://dali.gzhubu.top/Article/details/gtkrkjbvfk.html

Go:   slices.Contains(arr, x)
来源：http://dali.cheryme.top/Article/details/gtjvguthpx.html

Ruby: arr.include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtxiuwkhby.html

C#:   list.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gtgiamohcb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aizwys.cn/Article/details/gtogvqqprj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefttlijs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.birdmap.top/Article/details/gtynarypct.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ydzc1.top/Article/details/gtdrivvltj.html

TS:   [...arr];
来源：http://dali.yonumen.top/Article/details/gtystnvowm.html

Java: new ArrayList<>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfulwdok.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xinyue.icu/Article/details/gtpqtjnthm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.meibo888.top/Article/details/gteyuwfiim.html

C#:   new List<int>(list);
来源：http://dali.hnxiangtu.top/Article/details/gtchfobydo.html

[D23] reduce 累积计算
来源：http://dali.tian-w.cn/Article/details/gtsapisalh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtqieveway.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtpbaipopz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gthifnzptk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gtpuzasnfn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangdashe.top/Article/details/gtestphugq.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gttiognsfc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sysykeji.top/Article/details/gtzqzkzjns.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gtgcruidhl.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuxming.cn/Article/details/gtsnfldbhx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gtyopkhmkr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gtefpbaoct.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtlvgyozqw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258.top/Article/details/gtqcpojlgm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guannengcc.top/Article/details/gtmgobwsxj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ehwqpu.com/Article/details/gtonvqcfvl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.bjfxy.top/Article/details/gtyhefvnjc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnxiangtu.top/Article/details/gtofpekzrw.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgfzy.top/Article/details/gtxqgecbna.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangtech.top/Article/details/gtedveotmx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sufxvd.cn/Article/details/gtljgihkbd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gaohongyu789.top/Article/details/gtkjwxlpnh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gtufhjghln.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tanke756.top/Article/details/gtqoanowne.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gtzyrhieag.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gtfnlqxmgw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdpihvwj.html

[D26] 数组转字符串
来源：http://dali.jinqigufen.top/Article/details/gtqysuqzbe.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jiagoushi.top/Article/details/gtbtefsace.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhkozxkd.html

JS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtehhcpfyd.html

TS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtgfdhqmmo.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdaocmowf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangdashe.top/Article/details/gthqqxcfnd.html

Ruby: arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtdfnjxafa.html

C#:   string.Join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gtnchepgaf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrqwkyhom.html

E. 字符串处理
来源：http://dali.vqdsnc.cn/Article/details/gtcfskziqg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtryegwhlt.html

[E01] 拼接字符串
来源：http://dali.birdmap.top/Article/details/gtltvjjzlk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xylfe.cn/Article/details/gtnfazcvkt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yvedp.cn/Article/details/gtqsfatvpr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gtzbjrrggv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gtioykpaoa.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.mhx1999.top/Article/details/gtoywdpdke.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gtizudfqnx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hammf.cn/Article/details/gtkezupchd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtsfkxfrvb.html

[E02] 重复字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsfacaqb.html

Py:   "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtmcqkvyaq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sufxvd.cn/Article/details/gtadslsxci.html

JS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtmxufatyp.html

TS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtjsrrwnis.html

Java: "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtaongdbrx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ybcxt.top/Article/details/gtivbuhisx.html

Ruby: "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gturxvknwa.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xinyue.icu/Article/details/gtvsknvpib.html

[E03] 截取子串
来源：http://dali.yuxming.cn/Article/details/gtbkdyecfa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cqqwz.cn/Article/details/gtmnghxtdd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtwypjiofw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.smart0.xyz/Article/details/gtmnyrnwwi.html

TS:   s.slice(1, 4)
来源：http://dali.ivvv.top/Article/details/gtirbfiyxo.html

Java: s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtuunqghbt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnybdfivh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gaohongyu789.top/Article/details/gteqggpnir.html

C#:   s.Substring(1, 3)
来源：http://dali.fzhhl.top/Article/details/gtlaknebio.html

[E04] 查找子串位置
来源：http://dali.aizwys.cn/Article/details/gtufqowrge.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cashguo.top/Article/details/gtkunpmqck.html

PHP:  strpos($s, "x");
来源：http://dali.xuetiantiany.cn/Article/details/gthdldmilw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sysykeji.top/Article/details/gtwblgwklj.html

TS:   s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtccvyfgcx.html

Java: s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtuxxmmysf.html

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gtsebltwlw.html

Ruby: s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gtllhotvga.html

C#:   s.IndexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtgjjbjaya.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenjidiqi.icu/Article/details/gtbkqgnytg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yvedp.cn/Article/details/gtbifjlgny.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.daria6918.cn/Article/details/gtrplnmgcn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtukgbdwaz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnqzz.top/Article/details/gtcldyqlok.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ybcxt.top/Article/details/gtiqyckulf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.svipenyu.cn/Article/details/gtnibbxzos.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluclbzdc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtvbjnztoh.html

[E06] 替换子串
来源：http://dali.redwolf501.top/Article/details/gtosiaufvt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gtyuntermm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbarfeyzg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtrpblfxye.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtbfenbouc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtpzdymtiv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gtolcrlopx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtfkuxjwcd.html

C#:   s.Replace("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtcenjavvk.html

[E07] 按分隔符拆分
来源：http://dali.yueranfly.top/Article/details/gtumujrrlt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.9152youxi.cn/Article/details/gtqqsdoitn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ybcxt.top/Article/details/gteiyobvcn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.vqdsnc.cn/Article/details/gtnghfucjz.html

TS:   s.split(",")
来源：http://dali.yj202588.top/Article/details/gtvyvtrgbh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zycfv.cn/Article/details/gtyaulvzgc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenlongwang.top/Article/details/gtnkniombh.html

Ruby: s.split(",");  s.split
来源：http://dali.dianchejie.cn/Article/details/gtjfwkksdr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hongshengwenyu.top/Article/details/gtdvsmhict.html

[E08] 数组按分隔符合并
来源：http://dali.cqqwz.cn/Article/details/gtmhechnrt.html

Py:   ",".join(items)
来源：http://dali.hfpthk.cn/Article/details/gtjlxwvrdg.html

PHP:  implode(",", $items);
来源：http://dali.yueranfly.top/Article/details/gtuwzwdgzy.html

JS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtfcvnvqnt.html

TS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtirbvqhxf.html

Java: String.join(",", items)
来源：http://dali.ivvv.top/Article/details/gtgvrrydiq.html

Go:   strings.Join(items, ",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtriaxbnwf.html

Ruby: items.join(",")
来源：http://dali.cheryme.top/Article/details/gtjsedjzxn.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgefzzqq.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gthfofpcbc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gtdadtruko.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xylfe.cn/Article/details/gtxxsvwfdd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gtbvledndd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gtqrwjjlim.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtrucpewmn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.svipenyu.cn/Article/details/gtkxodygor.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gtwlufjiir.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gtwkffdira.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yongpay.top/Article/details/gtuacexnqq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pycfn.com/Article/details/gtysbqerql.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xinyue.icu/Article/details/gtxaepxvml.html

JS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtizenpbiy.html

TS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtwmbxjwjd.html

Java: String.format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtmxnnhrga.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtystevdje.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtabvmdsww.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sxryk.cn/Article/details/gtridqagwr.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gtqlgqdpqk.html

Py:   s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gtlxeawmdq.html

PHP:  strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtcfrhmzom.html

JS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtdbqghhrk.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtiaaokurf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.smart0.xyz/Article/details/gtttfnxhqi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhixingplan.top/Article/details/gtnuwztiyw.html

Ruby: s.reverse
来源：http://dali.daria6918.cn/Article/details/gtrovpjndg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gtxyqcgblh.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigufen.top/Article/details/gtbjbmdoyg.html

Py:   s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gttukfnpfq.html

PHP:  substr_count($s, "a");
来源：http://dali.tanke756.top/Article/details/gtgtfpublg.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtxjskvbxp.html

TS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gtdtkrqaca.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xziqi.cn/Article/details/gtpgngmkna.html

Go:   strings.Count(s, "a")
来源：http://dali.shangyingyoupin.top/Article/details/gtxyzfvhpa.html

Ruby: s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gtziwjxuaf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ydzc1.top/Article/details/gtxxaanqtq.html

[E13] 逐字符遍历
来源：http://dali.sufxvd.cn/Article/details/gtuzbvwhmr.html

Py:   for ch in s: print(ch)
来源：http://dali.sufxvd.cn/Article/details/gteodgzppy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ybcxt.top/Article/details/gtoeyafupz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtbfjkmqha.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtxbrpopjg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtxnysapgm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.havefunace.top/Article/details/gttwgozken.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gtryvreunr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtghtcqyjd.html

[E14] URL 编码与 Base64
来源：http://dali.kuanghao11.cn/Article/details/gtrsgjvhgb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gtgpzigzay.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigufen.top/Article/details/gtxdyuvvmu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnxiangtu.top/Article/details/gtkfyfrfgm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ppjwa.cn/Article/details/gtqahhhjpj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ydzc1.top/Article/details/gtrhduupbw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.havefunace.top/Article/details/gttfuhzffa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigfzy.top/Article/details/gtscccixgk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtptucsgoa.html

[E15] HTML 转义 / 反转义
来源：http://dali.tanke756.top/Article/details/gtrrdqonta.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xinyue.icu/Article/details/gtjhjbovla.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtlzsuhgcx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtrdydruin.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gtwtbwajtg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tian-w.cn/Article/details/gtatbhtpwe.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gteojgsbtz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.haohaochexian.top/Article/details/gtjeosspff.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvupxkzdx.html

[E16] 数字千分位
来源：http://dali.yuxming.cn/Article/details/gtwozfqtqc.html

Py:   f"{1234567:,}"
来源：http://dali.nanxuanxn.top/Article/details/gtxswcoyer.html

PHP:  number_format(1234567);
来源：http://dali.wangdashe.top/Article/details/gtbquxcnbe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gthuzsgcyo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdvmkmvz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yanxiufei.cn/Article/details/gtbaltkhzb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cqqwz.cn/Article/details/gtykeqzxhc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gaohongyu789.top/Article/details/gtjlfjmeqy.html

C#:   1234567.ToString("N0")
来源：http://dali.xziqi.cn/Article/details/gtiprxouos.html

[E17] 首字母大写
来源：http://dali.mhx1999.top/Article/details/gthdtsozjy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj202588.top/Article/details/gttjnrtjqk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhoulong.xyz/Article/details/gtgnuqpezc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gtqvfogzws.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtuwijcv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenlongwang.top/Article/details/gteintcebw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ppjwa.cn/Article/details/gttyowtiet.html

Ruby: s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqpgwrns.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ydzc1.top/Article/details/gthztxhdmf.html

[E18] 模板占位符替换
来源：http://dali.smart0.xyz/Article/details/gtfojovpwo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.birdmap.top/Article/details/gtxjccxnmu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pycfn.com/Article/details/gtnbrhbieu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtcdwjscxw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtxxkcalfv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtfspcypqh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtydmwaodt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenlongwang.top/Article/details/gtvsbbveoc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sxryk.cn/Article/details/gtbowstlxf.html

[E19] 多行文本按行拆分
来源：http://dali.hysaishi.cn/Article/details/gtcwhifakb.html

Py:   s.splitlines()
来源：http://dali.zhongyouzk.top/Article/details/gtrfzcsoyk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtoughsvko.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtsrarolbg.html

TS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gtulsfklzp.html

Java: s.lines().toList()
来源：http://dali.yanxiufei.cn/Article/details/gthrqaqazx.html

Go:   strings.Split(s, "\n")
来源：http://dali.ydzc1.top/Article/details/gtoorzdapy.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gtcaubjnki.html

C#:   s.Split('\n')
来源：http://dali.cqqwz.cn/Article/details/gtibcoockj.html

[E20] 判断字符串是否为空
来源：http://dali.shzxlz.cn/Article/details/gtoaybojdx.html

Py:   if not s:
来源：http://dali.yueranfly.top/Article/details/gtxsjaajct.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dianchejie.cn/Article/details/gtdtfmpuzm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhoulong.xyz/Article/details/gthhizzxji.html

TS:   if (s === "") {}
来源：http://dali.jinqigfzy.top/Article/details/gtqktwespv.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gtkvdgyvtc.html

Go:   if s == "" {}
来源：http://dali.shangyingyoupin.top/Article/details/gtdhoqqfgk.html

Ruby: if s.empty?
来源：http://dali.hammf.cn/Article/details/gtslphfeeb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ybcxt.top/Article/details/gtbuqlyfur.html

[E21] 超长截断加省略号
来源：http://dali.haohaochexian.top/Article/details/gtsusujkrx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhengqikj.top/Article/details/gtvcuvsegi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtvwqfqvuw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtlvqhlycv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtdpchwdar.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtzqllmqxp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.andypj.xyz/Article/details/gtrilevtkq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gtdgdimjca.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtquntfobz.html

[E22] 字节长度与字符长度
来源：http://dali.nanxuanxn.top/Article/details/gtddvplgwx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhongyouzk.top/Article/details/gtbaayzqca.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtjtqrjwnj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtucptoodd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtvkeihqmm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtfiyixxob.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cashguo.top/Article/details/gtcplirzrx.html

Ruby: s.bytesize;  s.length
来源：http://dali.sysykeji.top/Article/details/gtttycliqq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ivvv.top/Article/details/gtlvftwixl.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtsidfhvme.html

F. 文件与目录
来源：http://dali.yvedp.cn/Article/details/gtzqgwgekd.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxrtspoyt.html

[F01] 读取整个文件
来源：http://dali.xuanzx.com/Article/details/gtatpbasgz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guannengcc.top/Article/details/gttalwndhq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtclxrjsbr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aizwys.cn/Article/details/gtaxtwfaxk.html


<!-- 参考信息 -->