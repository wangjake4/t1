代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.tianlin.xyz/Article/details/gtjziwfikn.html

[D16] 求和与平均值
来源：http://dali.zhengqikj.top/Article/details/gtbiofosbr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.bjfxy.top/Article/details/gtbaeoloeu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtuzelufvm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtjfyzlcqt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gtzamfdrlq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcikaxvyl.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gtjovqljpf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqmfefor.html

C#:   list.Sum();  list.Average()
来源：http://dali.sufxvd.cn/Article/details/gtfrlfowgb.html

[D17] 最大值与最小值
来源：http://dali.sysykeji.top/Article/details/gtsmhbuqra.html

Py:   max(arr);  min(arr)
来源：http://dali.sufxvd.cn/Article/details/gtdnuvkmfd.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhixingplan.top/Article/details/gtiyztxaho.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnxiangtu.top/Article/details/gtqqluzxha.html

TS:   Math.max(...arr);
来源：http://dali.pycfn.com/Article/details/gtwspcoykw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtvybbkzne.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgfzy.top/Article/details/gtlmwxqpli.html

Ruby: arr.max;  arr.min
来源：http://dali.havefunace.top/Article/details/gtupjcwpwb.html

C#:   list.Max();  list.Min()
来源：http://dali.yj202588.top/Article/details/gtqtkynscr.html

[D18] 扁平化嵌套数组
来源：http://dali.nwbrower.top/Article/details/gtsxspzaat.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zdqjudy.top/Article/details/gtimugytuj.html

PHP:  array_merge(...$nested);
来源：http://dali.gotoacloud.top/Article/details/gtowqxreju.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aizwys.cn/Article/details/gthzqslvzu.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gtfstrqphv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwiasidn.html

Go:   // 手写双层循环
来源：http://dali.feifeiyinyue.top/Article/details/gtzpgvzmgi.html

Ruby: nested.flatten
来源：http://dali.jinqigufen.top/Article/details/gtomuwtams.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yongpay.top/Article/details/gtnenzertg.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gtaupvyuew.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ppjwa.cn/Article/details/gtemrqnjsu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hongshengwenyu.top/Article/details/gtbyzxgkda.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.havefunace.top/Article/details/gtrpxybynf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yvedp.cn/Article/details/gtsbfhaoeh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dashuyun.cn/Article/details/gtpgualunm.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlahutcm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fengsongda.top/Article/details/gthvhdikhp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.andypj.xyz/Article/details/gtysmausyq.html

[D20] 统计每个元素出现次数
来源：http://dali.ydzc1.top/Article/details/gttbhachqm.html

Py:   Counter(arr)
来源：http://dali.cucudq.cn/Article/details/gtarfzhyxq.html

PHP:  array_count_values($arr);
来源：http://dali.bjfxy.top/Article/details/gtukqqdodo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gtbscszsdv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvrxarff.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzrggsdk.html

Go:   // 手写 map[T]int
来源：http://dali.birdmap.top/Article/details/gtreykthjy.html

Ruby: arr.tally
来源：http://dali.ydzc1.top/Article/details/gtemriafel.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gtwjonvsxd.html

[D21] 判断是否包含某元素
来源：http://dali.hnqzz.top/Article/details/gtygifyknx.html

Py:   x in arr
来源：http://dali.sysykeji.top/Article/details/gttocyfpsf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgufenzy.top/Article/details/gtvgyjgimb.html

JS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gtjfidomxp.html

TS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtvsjlmcxo.html

Java: list.contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtjlqushge.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtjymbsrin.html

Ruby: arr.include?(x)
来源：http://dali.hysaishi.cn/Article/details/gtulquddyn.html

C#:   list.Contains(x)
来源：http://dali.fengsongda.top/Article/details/gtkzthuaek.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmcaothb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.birdmap.top/Article/details/gtqjzztaow.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbkkeyiz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.svipenyu.cn/Article/details/gtqjdixxyf.html

TS:   [...arr];
来源：http://dali.chenlongwang.top/Article/details/gtlehwouny.html

Java: new ArrayList<>(list);
来源：http://dali.cucudq.cn/Article/details/gtlelosufb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gtxzdsclei.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shzxlz.cn/Article/details/gtlraxcpto.html

C#:   new List<int>(list);
来源：http://dali.cashguo.top/Article/details/gttprurrho.html

[D23] reduce 累积计算
来源：http://dali.9152youxi.cn/Article/details/gtznxfehoo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tanke756.top/Article/details/gtncsdxtkc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtkyjbdnjj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gtpvnmipdf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gtvjytpevz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangdashe.top/Article/details/gtvxuclefr.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gtdzcjcqrh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fzhhl.top/Article/details/gtpwmqsmmi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gtmtqapxvq.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenlongwang.top/Article/details/gtcwicuqij.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxuanxn.top/Article/details/gtzpeztmkz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.9152youxi.cn/Article/details/gtvivzumdc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cqqwz.cn/Article/details/gtnjqldevo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtfdovtruf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhiwuduotai.top/Article/details/gtucppbvfu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yangfankeji.com/Article/details/gtipkqhgzp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shzxlz.cn/Article/details/gtnxdxflzw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.haohaochexian.top/Article/details/gtttxtxrfo.html

[D25] Set 集合去重与交并差
来源：http://dali.redwolf501.top/Article/details/gtkwzqgxnq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yanxiufei.cn/Article/details/gtykrbztkq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yueranfly.top/Article/details/gtrkqdcyzc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.quarkkingdee.top/Article/details/gtxpxjtqkc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpxrusye.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hywenlv.cn/Article/details/gttmszjonm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.vqdsnc.cn/Article/details/gtujcuskbh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.haohaochexian.top/Article/details/gtdqmtsgez.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhengqikj.top/Article/details/gtftwaswhl.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gtbkpipmvl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj202588.top/Article/details/gtzhynpueq.html

PHP:  implode(", ", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtxzjzkzyd.html

JS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtcvhtxoeb.html

TS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gtlggawzpd.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gtxcsofqce.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtufensiim.html

Ruby: arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtmjflssdu.html

C#:   string.Join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gtpyadpunv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtsahnmbuk.html

E. 字符串处理
来源：http://dali.daxiang520.top/Article/details/gtijgputjv.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtjfolpjil.html

[E01] 拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtyhwewdsl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hfpthk.cn/Article/details/gtjantjecd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gzhubu.top/Article/details/gtevgapifu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovuvvznh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gtlizcpvyl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhongyouzk.top/Article/details/gtfjkhjorh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pengpengdd.cyou/Article/details/gthlnvlovq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aizwys.cn/Article/details/gtyyycdacn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtghpswbnw.html

[E02] 重复字符串
来源：http://dali.guannengcc.top/Article/details/gtszqidelz.html

Py:   "ab" * 3
来源：http://dali.hammf.cn/Article/details/gtopypmwdk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.kuanghao11.cn/Article/details/gtplqpfrvr.html

JS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtgclcramv.html

TS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtzfhybpml.html

Java: "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtwsbihlex.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.vqdsnc.cn/Article/details/gtezppsqgq.html

Ruby: "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gtrzsddizk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtaggsptfi.html

[E03] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gtiflrhqpn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cqqwz.cn/Article/details/gtaogzfkmf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtxxiwqojn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.smart0.xyz/Article/details/gtidxurktl.html

TS:   s.slice(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtfnojdywi.html

Java: s.substring(1, 4)
来源：http://dali.aizwys.cn/Article/details/gtbdufxlis.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwwqfnwt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhengqikj.top/Article/details/gtyyforsse.html

C#:   s.Substring(1, 3)
来源：http://dali.jlsjyb.cn/Article/details/gtnwizowxf.html

[E04] 查找子串位置
来源：http://dali.yj20258.top/Article/details/gtsvaeblfw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtddxoxpqq.html

PHP:  strpos($s, "x");
来源：http://dali.daria6918.cn/Article/details/gtufnulqwv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shangyingyoupin.top/Article/details/gtqjfilvfx.html

TS:   s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtjwnbvcrn.html

Java: s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtpxfrlwov.html

Go:   strings.Index(s, "x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzvulfpm.html

Ruby: s.index("x")
来源：http://dali.guannengcc.top/Article/details/gtfkfzzeda.html

C#:   s.IndexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtxpmoazjn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daria6918.cn/Article/details/gtyfvercor.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ybcxt.top/Article/details/gtedmqaxjz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jyoumei.cn/Article/details/gtnxbmoqsm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqkapfdr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cheryme.top/Article/details/gtvgkmzret.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gtdemjyudk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gtterggxnv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.mhx1999.top/Article/details/gtkiepthuf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gthqxbedyq.html

[E06] 替换子串
来源：http://dali.hfpthk.cn/Article/details/gtzkvsncek.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtdztyychc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258888.top/Article/details/gtpvhworxq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtohjmfoen.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtpqrdmupm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtvcnkqurh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gtwuafkczy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtrkuzehao.html

C#:   s.Replace("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtuglvhvyc.html

[E07] 按分隔符拆分
来源：http://dali.tian-w.cn/Article/details/gtyecjsskw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sysykeji.top/Article/details/gtkhkkdmhi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shuidangran.top/Article/details/gtbysvbxvb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuanzhike.top/Article/details/gtvntbbgpr.html

TS:   s.split(",")
来源：http://dali.birdmap.top/Article/details/gtutaysrfz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258.top/Article/details/gtmxhszsrt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tian-w.cn/Article/details/gtdiyfmgoh.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxinkj.top/Article/details/gtcwshojpt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258888.top/Article/details/gtpfofwxby.html

[E08] 数组按分隔符合并
来源：http://dali.gotoacloud.top/Article/details/gtrpvctaoa.html

Py:   ",".join(items)
来源：http://dali.wangshuangyany.cn/Article/details/gtouwyfrcw.html

PHP:  implode(",", $items);
来源：http://dali.meibo888.top/Article/details/gtyajijadk.html

JS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtidgzknip.html

TS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtsleqhgwi.html

Java: String.join(",", items)
来源：http://dali.sysykeji.top/Article/details/gttmfdlmmj.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgufenzy.top/Article/details/gtafutoluz.html

Ruby: items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtbucpqucc.html

C#:   string.Join(",", items)
来源：http://dali.dianchejie.cn/Article/details/gthlmlteae.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gtfbamyfqy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yangfankeji.com/Article/details/gtdbvtrebs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ppjwa.cn/Article/details/gtqadnuwsq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gtroandmwb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtttrkjryj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ivvv.top/Article/details/gtpwkjrico.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gaohongyu789.top/Article/details/gttjsjsiuf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tianlin.xyz/Article/details/gtqqsngnlm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gtedovxwsh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gotoacloud.top/Article/details/gtybrypimg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtnrwibiwl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ydzc1.top/Article/details/gtbtvoydaa.html

JS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gthmagtucf.html

TS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtznnddfpv.html

Java: String.format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtplaupyte.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtkjegvgim.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtaevgudhm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.kuanghao11.cn/Article/details/gtafqvxtbc.html

[E11] 反转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtilzbjtzm.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gtdrnzuhhc.html

PHP:  strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gtdtsnumut.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgyidcjp.html

TS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtdykhupcj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gzhubu.top/Article/details/gtwmzifhsz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwnbmhxb.html

Ruby: s.reverse
来源：http://dali.0kj1m.cn/Article/details/gtpksmbhfn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gthibzrarg.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gtxdpawhzq.html

Py:   s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtraharblv.html

PHP:  substr_count($s, "a");
来源：http://dali.zdqjudy.top/Article/details/gtqgznuvdv.html

JS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gtjlzilkhk.html

TS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gtuenfhzhm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.kuanghao11.cn/Article/details/gtsrhbemvj.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gtlzkhhuho.html

Ruby: s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gtojoharrr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gtltzzluat.html

[E13] 逐字符遍历
来源：http://dali.yongpay.top/Article/details/gtpphcofkr.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gthhuifkhm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gzhubu.top/Article/details/gttxbiyznt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gteddjpngj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtotehdruy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gttrpeszza.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cqqwz.cn/Article/details/gtielfcgbb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.9152youxi.cn/Article/details/gtnpwqsmfp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtxfhidgdr.html

[E14] URL 编码与 Base64
来源：http://dali.yongpay.top/Article/details/gttqjpnnqi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guowangkeji.top/Article/details/gtprftfjql.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.316326.xyz/Article/details/gtyqehurbr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gtwtdwlwel.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtoqrdnciu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtaxiagbkq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xylfe.cn/Article/details/gtmarulaob.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shangyingyoupin.top/Article/details/gtbbuolunm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxmyodcw.html

[E15] HTML 转义 / 反转义
来源：http://dali.bjfxy.top/Article/details/gtqytufavz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aizwys.cn/Article/details/gttbxzkfni.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqoqnyhqy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yueranfly.top/Article/details/gtksyzzrqr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fzhhl.top/Article/details/gtxbjhmeaz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hammf.cn/Article/details/gtpjwwhfaw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.svipenyu.cn/Article/details/gtxawduhix.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ybcxt.top/Article/details/gtdammlucx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gaohongyu789.top/Article/details/gtnqjtdwxe.html

[E16] 数字千分位
来源：http://dali.havefunace.top/Article/details/gtanqzxump.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gtyerdigpe.html

PHP:  number_format(1234567);
来源：http://dali.cucudq.cn/Article/details/gtdeapdnpd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtierkdvyk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gtmrkjexrf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cheryme.top/Article/details/gtnkyfqmus.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.316326.xyz/Article/details/gttcqgqldz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtslndgctm.html

C#:   1234567.ToString("N0")
来源：http://dali.yuxming.cn/Article/details/gtezpxyflx.html

[E17] 首字母大写
来源：http://dali.yueranfly.top/Article/details/gtfwiympdo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gtkzohzmpv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gtnoqmjsqx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gthvaucwpr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxglobmn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhixingplan.top/Article/details/gtrnfoeguc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtcdnrpaov.html

Ruby: s.capitalize
来源：http://dali.zhixingplan.top/Article/details/gtvenjbcxs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.meibo888.top/Article/details/gthswvjnld.html

[E18] 模板占位符替换
来源：http://dali.0kj1m.cn/Article/details/gtfccdzqdm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsztgfszu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pengpengdd.cyou/Article/details/gtmotyzfvz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtzsbhdhpk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtsyizkwei.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gteetsrrfj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtriugtdqh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gtumqkjrlt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yanxiufei.cn/Article/details/gtvfruzvoq.html

[E19] 多行文本按行拆分
来源：http://dali.hywenlv.cn/Article/details/gtuhjpckxi.html

Py:   s.splitlines()
来源：http://dali.ppjwa.cn/Article/details/gtnlnjgwcw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.c1oappe.top/Article/details/gtbbpyiqql.html

JS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gtmxsoyzxn.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtqwofdzap.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtfgdyphjk.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgfzy.top/Article/details/gthdknqkhj.html

Ruby: s.lines
来源：http://dali.redwolf501.top/Article/details/gtwdqsdrij.html

C#:   s.Split('\n')
来源：http://dali.yj20258.top/Article/details/gtcuuthxeq.html

[E20] 判断字符串是否为空
来源：http://dali.yonumen.top/Article/details/gtdorjwbai.html

Py:   if not s:
来源：http://dali.sweek.top/Article/details/gtwkmqvwdj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gzhubu.top/Article/details/gtstbjsjbo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ppjwa.cn/Article/details/gtciakmmke.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gtspihrppz.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtknitodps.html

Go:   if s == "" {}
来源：http://dali.shuidangran.top/Article/details/gtadiecihu.html

Ruby: if s.empty?
来源：http://dali.9152youxi.cn/Article/details/gtifmucjlo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gtavfpjnxv.html

[E21] 超长截断加省略号
来源：http://dali.nanxuanxn.top/Article/details/gtxtpkrhph.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hongshengwenyu.top/Article/details/gtolqxullj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtvocvscky.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtxudkgflw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtwurtyimg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtvojfgyvt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hywenlv.cn/Article/details/gtluiytaux.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtvukjhruv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtvtxomwvd.html

[E22] 字节长度与字符长度
来源：http://dali.chenzaomai.com/Article/details/gtogodadqt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hywenlv.cn/Article/details/gtxymgyjco.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtxdrqoypd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gtqmjrlqfv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gtwxvrwipt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yangfankeji.com/Article/details/gtscgclyiu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gaohongyu789.top/Article/details/gthbprntea.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtbfnqxlgd.html


<!-- 参考信息 -->