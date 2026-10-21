代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtjsngnxul.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258888.top/Article/details/gtxmomywpd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.redwolf501.top/Article/details/gtfrhqkctp.html

Ruby: arr.uniq
来源：http://dali.jiagoushi.top/Article/details/gtzctxwceu.html

C#:   list.Distinct().ToList()
来源：http://dali.bjfxy.top/Article/details/gtkfjlzrjk.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gtbkuhmevs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zycfv.cn/Article/details/gtkvcspkkr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xziqi.cn/Article/details/gtngbxdhia.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvshmwyrv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gtgvthxtqo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gtymjwnttm.html

Go:   // 手写循环累加
来源：http://dali.yongpay.top/Article/details/gtxouusgkb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gtttmameay.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangshuangyany.cn/Article/details/gtmmnglney.html

[D17] 最大值与最小值
来源：http://dali.tanke756.top/Article/details/gtymncplig.html

Py:   max(arr);  min(arr)
来源：http://dali.xuanzx.com/Article/details/gtvyztchwj.html

PHP:  max($arr);  min($arr);
来源：http://dali.smart0.xyz/Article/details/gtjewjyguq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sweek.top/Article/details/gtyezvjkkn.html

TS:   Math.max(...arr);
来源：http://dali.dianchejie.cn/Article/details/gtjksgglrf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenlongwang.top/Article/details/gtzxcsiawy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.svipenyu.cn/Article/details/gtkycocxmd.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgufenzy.top/Article/details/gtbndyefor.html

C#:   list.Max();  list.Min()
来源：http://dali.meibo888.top/Article/details/gtyyymllpy.html

[D18] 扁平化嵌套数组
来源：http://dali.gogol.net.cn/Article/details/gttuxzsizn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ivvv.top/Article/details/gtlwkpzgwb.html

PHP:  array_merge(...$nested);
来源：http://dali.wangshuangyany.cn/Article/details/gtkjndyrym.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jyoumei.cn/Article/details/gtdvigbeuh.html

TS:   nested.flat();
来源：http://dali.tian-w.cn/Article/details/gtigrvnptm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnqzz.top/Article/details/gtbosbcvnr.html

Go:   // 手写双层循环
来源：http://dali.chenjidiqi.icu/Article/details/gtvkdzirkw.html

Ruby: nested.flatten
来源：http://dali.gzhubu.top/Article/details/gtxdtzezuw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtttgrzgea.html

[D19] 按字段分组
来源：http://dali.fzhhl.top/Article/details/gthzifyznk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hywenlv.cn/Article/details/gtqkjqmexu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmmctjuj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gtxmzcfxfd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gtwhzkhugq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangkeji.top/Article/details/gthttamjci.html

Go:   // 手写 map[string][]T
来源：http://dali.zdqjudy.top/Article/details/gtaslhwyiw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.meibo888.top/Article/details/gtifcpadjn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tianlin.xyz/Article/details/gtlqjlfoms.html

[D20] 统计每个元素出现次数
来源：http://dali.havefunace.top/Article/details/gtzshkibru.html

Py:   Counter(arr)
来源：http://dali.jiagoushi.top/Article/details/gtpcgqghyh.html

PHP:  array_count_values($arr);
来源：http://dali.yangfankeji.com/Article/details/gtatizyauw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gtwklyaizm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhiwuduotai.top/Article/details/gtqaynbaqn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sweek.top/Article/details/gtghowcwzh.html

Go:   // 手写 map[T]int
来源：http://dali.smart0.xyz/Article/details/gtjvanrmmf.html

Ruby: arr.tally
来源：http://dali.xylfe.cn/Article/details/gtoastitvu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvukgbxj.html

[D21] 判断是否包含某元素
来源：http://dali.pycfn.com/Article/details/gthqczerez.html

Py:   x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqwkbulg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dashuyun.cn/Article/details/gtoecucmoi.html

JS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtpkoddmuf.html

TS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtlbbrzrmk.html

Java: list.contains(x)
来源：http://dali.wangdashe.top/Article/details/gtachsvbgi.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gtgeivvvqg.html

Ruby: arr.include?(x)
来源：http://dali.iojbl.cn/Article/details/gtioqrotbc.html

C#:   list.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtlkwcmivc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.andypj.xyz/Article/details/gtqmahjzla.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dianchejie.cn/Article/details/gtlwjdmwwc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmrpzkiy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tian-w.cn/Article/details/gtbwkwkfcn.html

TS:   [...arr];
来源：http://dali.aizwys.cn/Article/details/gtjntalchd.html

Java: new ArrayList<>(list);
来源：http://dali.svipenyu.cn/Article/details/gthtbvhfko.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gzhubu.top/Article/details/gtnkxzplch.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sxryk.cn/Article/details/gtqejugoyi.html

C#:   new List<int>(list);
来源：http://dali.hysaishi.cn/Article/details/gttonokeqv.html

[D23] reduce 累积计算
来源：http://dali.pycfn.com/Article/details/gtrlqgxdsa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigufen.top/Article/details/gtxkxkhavz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jianghu66.top/Article/details/gtdtfrhmsb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdfhnhpg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gtchjbidqc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cheryme.top/Article/details/gtfcskewhi.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gtbypwuobk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gzhubu.top/Article/details/gtupdogexx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ppjwa.cn/Article/details/gtvlksuwqx.html

[D24] 字典 / Map 基本操作
来源：http://dali.gogol.net.cn/Article/details/gtouvvpkat.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cucudq.cn/Article/details/gttkjwpljk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gtwnyjmxmu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ydzc1.top/Article/details/gtdjtoihuj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtxqllwaxx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shuidangran.top/Article/details/gtdholexno.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhongyouzk.top/Article/details/gtorotqzyp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtklpfylvp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sweek.top/Article/details/gtyfjwawzf.html

[D25] Set 集合去重与交并差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulhbouay.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.redwolf501.top/Article/details/gtvscvubkt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jyoumei.cn/Article/details/gtogvhiyyl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenlongwang.top/Article/details/gturedzbld.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtasrpkqrk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtgfgdhgli.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gtncqtufqc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gtavkvqbrs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.svipenyu.cn/Article/details/gtqdnywzyp.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gtlhykfwmx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuxming.cn/Article/details/gtwbcyuuqu.html

PHP:  implode(", ", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtumrthoxl.html

JS:   arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtglzocpsp.html

TS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtconokeme.html

Java: String.join(", ", list)
来源：http://dali.ybcxt.top/Article/details/gtfhwzoynd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.andypj.xyz/Article/details/gtrcipjflk.html

Ruby: arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtemkclqxp.html

C#:   string.Join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gtabekaknz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtbpfbiezl.html

E. 字符串处理
来源：http://dali.gotoacloud.top/Article/details/gtebnkrobh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtnwdzqipl.html

[E01] 拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtjevbbzmx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.iojbl.cn/Article/details/gtkgrwvaql.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxuanxn.top/Article/details/gtldempxtf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gtyplojrrg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gtpfcodlbl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgfzy.top/Article/details/gtfpbmrwoz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zycfv.cn/Article/details/gtfebqhspw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnqzz.top/Article/details/gtlpsmpfwb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtwghmdaec.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gtvmilkxop.html

Py:   "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gtkmxrtpmq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fengsongda.top/Article/details/gtfyzilbwr.html

JS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtgieeztne.html

TS:   "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtvpsootzp.html

Java: "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtnorjkakl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xziqi.cn/Article/details/gtdgqtofco.html

Ruby: "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gtidvbufje.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhiwuduotai.top/Article/details/gtloghuqqs.html

[E03] 截取子串
来源：http://dali.pycfn.com/Article/details/gtlzlhsuhl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daxiang520.top/Article/details/gtgvbypyay.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtpcxfjnae.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtemiaberz.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gttogoebdq.html

Java: s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtjwbybflz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.havefunace.top/Article/details/gtmkxlokbs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pycfn.com/Article/details/gtoxpkwmip.html

C#:   s.Substring(1, 3)
来源：http://dali.guowangkeji.top/Article/details/gtpvbixnuk.html

[E04] 查找子串位置
来源：http://dali.cucudq.cn/Article/details/gtraveisef.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtojzubbxp.html

PHP:  strpos($s, "x");
来源：http://dali.gzhubu.top/Article/details/gtdjtekcbg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.snrcjt.cn/Article/details/gtmgauhfmf.html

TS:   s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtmsgummih.html

Java: s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtyhtqrbax.html

Go:   strings.Index(s, "x")
来源：http://dali.fengsongda.top/Article/details/gtwcryguby.html

Ruby: s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteflbcsys.html

C#:   s.IndexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtxatnylge.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangdashe.top/Article/details/gtujykbeuj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.316326.xyz/Article/details/gtncaqasmh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hysaishi.cn/Article/details/gtepdapylc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gtdpbujxre.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sufxvd.cn/Article/details/gtxvascxrv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gtuxysuguk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.havefunace.top/Article/details/gtckfiqawo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.andypj.xyz/Article/details/gtrknqysep.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gtrbbvogau.html

[E06] 替换子串
来源：http://dali.redwolf501.top/Article/details/gtjvknzjii.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gtwwhytodh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dashuyun.cn/Article/details/gtnadliujw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtilhwggho.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtwxuycpiz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtwmqxwbhw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbifxape.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtnnbgqwwi.html

C#:   s.Replace("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtaqsgemwi.html

[E07] 按分隔符拆分
来源：http://dali.meibo888.top/Article/details/gtbpleauot.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuetiantiany.cn/Article/details/gtatkonuke.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj202588.top/Article/details/gtzuocuhmr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.havefunace.top/Article/details/gtkjondxjd.html

TS:   s.split(",")
来源：http://dali.gzhubu.top/Article/details/gtdgraypir.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jyoumei.cn/Article/details/gtlnobczsb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cqqwz.cn/Article/details/gtijmokfsu.html

Ruby: s.split(",");  s.split
来源：http://dali.ppjwa.cn/Article/details/gtpcwccgqh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuxming.cn/Article/details/gtuyaovbbm.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigufen.top/Article/details/gtlwgymthr.html

Py:   ",".join(items)
来源：http://dali.bjfxy.top/Article/details/gtqdthftbq.html

PHP:  implode(",", $items);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxldvpbvm.html

JS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtwifxiswf.html

TS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtiaymwskl.html

Java: String.join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gtcvpjehrf.html

Go:   strings.Join(items, ",")
来源：http://dali.jlsjyb.cn/Article/details/gtvrsjhrim.html

Ruby: items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtzehlzayn.html

C#:   string.Join(",", items)
来源：http://dali.cashguo.top/Article/details/gtqiznzfcg.html

[E09] 去除所有空白字符
来源：http://dali.chenlongwang.top/Article/details/gtrdupbedl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.smart0.xyz/Article/details/gthurjzruv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hywenlv.cn/Article/details/gtbitamgnp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gaohongyu789.top/Article/details/gtkdekysen.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtorjoxfwy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cheryme.top/Article/details/gtqeeaslxt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jyoumei.cn/Article/details/gtpktivbja.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xziqi.cn/Article/details/gtbncolsyl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nwbrower.top/Article/details/gtlciewyvz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.9152youxi.cn/Article/details/gtkpxhfjyh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gttdiajytr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aizwys.cn/Article/details/gtarmblhvm.html

JS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtfzgwznnl.html

TS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtbvhqtbld.html

Java: String.format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtetpbwhiu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gthnurnfzu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtknnvpgkm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guannengcc.top/Article/details/gtfhgrqsmj.html

[E11] 反转字符串
来源：http://dali.snrcjt.cn/Article/details/gtdbmikfsb.html

Py:   s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtdxhnfexl.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtvwxkumte.html

JS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtozuxmrve.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtamvczkrz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuanzhike.top/Article/details/gtnmsdtnej.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cdnleiting.top/Article/details/gtkwroryxy.html

Ruby: s.reverse
来源：http://dali.aizwys.cn/Article/details/gtrftbbosd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtmishhjyk.html

[E12] 统计某字符出现次数
来源：http://dali.ehwqpu.com/Article/details/gtoxloxgiu.html

Py:   s.count("a")
来源：http://dali.sxryk.cn/Article/details/gtitsmoqsw.html

PHP:  substr_count($s, "a");
来源：http://dali.tianlin.xyz/Article/details/gtyylftwaz.html

JS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gthccksygg.html

TS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gtcmrijrsp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dashuyun.cn/Article/details/gtpbqhbyes.html

Go:   strings.Count(s, "a")
来源：http://dali.sufxvd.cn/Article/details/gtsibqmglq.html

Ruby: s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtpogawvan.html

C#:   s.Count(c => c == 'a')
来源：http://dali.snrcjt.cn/Article/details/gtbkkyuhxi.html

[E13] 逐字符遍历
来源：http://dali.redwolf501.top/Article/details/gtylveauaj.html

Py:   for ch in s: print(ch)
来源：http://dali.hnqzz.top/Article/details/gtkbqpmawz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hammf.cn/Article/details/gthkzamgdw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gtylwbbift.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrejhzmlg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtcndfebag.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jianghu66.top/Article/details/gtuhwtxnny.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xylfe.cn/Article/details/gtnxzuvfhw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangdashe.top/Article/details/gtfpncwmvd.html

[E14] URL 编码与 Base64
来源：http://dali.shzxlz.cn/Article/details/gtkmdzilcq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.iojbl.cn/Article/details/gtgpxaxoad.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xziqi.cn/Article/details/gtgojyhipg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.kuanghao11.cn/Article/details/gtgirdhlhp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.0kj1m.cn/Article/details/gtrcxqsphr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhmitqrc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxuanxn.top/Article/details/gtqihljshu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sxryk.cn/Article/details/gtmiuebehu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yueranfly.top/Article/details/gtidogpftn.html

[E15] HTML 转义 / 反转义
来源：http://dali.zdqjudy.top/Article/details/gtjmbnfxio.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.quarkkingdee.top/Article/details/gtrnuaauxx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258888.top/Article/details/gtozavhmnq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gtiaakuekr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dianchejie.cn/Article/details/gtanhufxec.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jiagoushi.top/Article/details/gtzvajepcr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hammf.cn/Article/details/gtscrfvhkl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yonumen.top/Article/details/gtnzshtfqt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zdqjudy.top/Article/details/gtdmcksuht.html

[E16] 数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gtkjhsioam.html

Py:   f"{1234567:,}"
来源：http://dali.dianchejie.cn/Article/details/gtywanmxlu.html

PHP:  number_format(1234567);
来源：http://dali.zycfv.cn/Article/details/gtgqzmnvkr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gtqbuubfuv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.birdmap.top/Article/details/gtavqyuwvx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gtfzetcnhh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj202588.top/Article/details/gtulcobyon.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gtwrbhwnzi.html

C#:   1234567.ToString("N0")
来源：http://dali.smart0.xyz/Article/details/gtmnvnsmkb.html

[E17] 首字母大写
来源：http://dali.snrcjt.cn/Article/details/gtujxirciq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gtxgpuwiwb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zycfv.cn/Article/details/gtieaaxtwe.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtmmaqaqpz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gtrymxmslr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.vqdsnc.cn/Article/details/gtliplmudh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xinyue.icu/Article/details/gtgglnrecq.html

Ruby: s.capitalize
来源：http://dali.redwolf501.top/Article/details/gtippocjwl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.9152youxi.cn/Article/details/gtjddkksrj.html

[E18] 模板占位符替换
来源：http://dali.snrcjt.cn/Article/details/gtjeqwxxmx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhixingplan.top/Article/details/gtbaskdmrz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sufxvd.cn/Article/details/gtogcbmvqq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtxxsxsozd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtowipewnr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtsnrqhxwr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258.top/Article/details/gtrgqsasrr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.quarkkingdee.top/Article/details/gttbppwecm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ppjwa.cn/Article/details/gturzphagf.html

[E19] 多行文本按行拆分
来源：http://dali.bjfxy.top/Article/details/gtanldckux.html

Py:   s.splitlines()
来源：http://dali.sweek.top/Article/details/gtbwqvgsty.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtuuedblyq.html

JS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtaanwockl.html

TS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gthiknyehr.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtecqekocj.html

Go:   strings.Split(s, "\n")
来源：http://dali.fengsongda.top/Article/details/gtbtmfbffo.html

Ruby: s.lines
来源：http://dali.gotoacloud.top/Article/details/gtfomggxct.html

C#:   s.Split('\n')
来源：http://dali.chenjidiqi.icu/Article/details/gtaljmelkn.html

[E20] 判断字符串是否为空
来源：http://dali.cashguo.top/Article/details/gtuvdvehbh.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlydblqls.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gtntnfnsik.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxuanxn.top/Article/details/gtnmfvzxfc.html

TS:   if (s === "") {}
来源：http://dali.xuetiantiany.cn/Article/details/gtiveuidwx.html

Java: if (s.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtgevzbzoa.html

Go:   if s == "" {}
来源：http://dali.aibaodan.cn/Article/details/gtwbxfkdcj.html

Ruby: if s.empty?
来源：http://dali.bjfxy.top/Article/details/gtkrmgkgna.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gtxxwelmrv.html

[E21] 超长截断加省略号
来源：http://dali.hnqzz.top/Article/details/gtuxzubbwm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhixingplan.top/Article/details/gtjntlvqcr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtcbgyfhiq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtrodcttmm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtmdqasoij.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtbpzjlbqo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gthkqaegqb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtynfjmalz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtdlvmznbi.html

[E22] 字节长度与字符长度
来源：http://dali.nanxinkj.top/Article/details/gtxsuhospw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gtxybvlxni.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtittuiuoj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtpohjhmvd.html


<!-- 参考信息 -->