代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gttyhyoknh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gtwsdkfnuy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cashguo.top/Article/details/gtvyurwrtk.html

Go:   slices.Index(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtvbwombkp.html

Ruby: arr.index(x)
来源：http://dali.zycfv.cn/Article/details/gtpoyzcksp.html

C#:   list.IndexOf(x);
来源：http://dali.gogol.net.cn/Article/details/gtadpxgtdj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangshuangyany.cn/Article/details/gtyziyewqw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhixingplan.top/Article/details/gtoajqhmva.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.316326.xyz/Article/details/gtqxhcaoav.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gtynopywir.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gtyqfvpttz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yongpay.top/Article/details/gtdntdvxmd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sufxvd.cn/Article/details/gtxfavjmzg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gotoacloud.top/Article/details/gtntixkyyb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258888.top/Article/details/gtnvwedegn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shuidangran.top/Article/details/gthzviiowr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fengsongda.top/Article/details/gtwtiqiujr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258888.top/Article/details/gtapgfhimu.html

JS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gtsbxrofoq.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gthdmyttmd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.316326.xyz/Article/details/gtdiykhhsf.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gtvmhrkanq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtvlejbieq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtbgpofpox.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtcinagvvf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aizwys.cn/Article/details/gtxxitfgqc.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gttitaudha.html

JS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtjkxhhcnl.html

TS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gtpjwmspoj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tianlin.xyz/Article/details/gtdjuzodbi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zycfv.cn/Article/details/gtrladhsfe.html

Ruby: arr.uniq
来源：http://dali.andypj.xyz/Article/details/gtuxwvomim.html

C#:   list.Distinct().ToList()
来源：http://dali.hammf.cn/Article/details/gtgjmfelzw.html

[D16] 求和与平均值
来源：http://dali.zhiwuduotai.top/Article/details/gtzuslsrzh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aizwys.cn/Article/details/gtayodpmls.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258.top/Article/details/gtcticsuqh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtaesojryp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtqhmyeovx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tian-w.cn/Article/details/gtqrfuruyx.html

Go:   // 手写循环累加
来源：http://dali.zdqjudy.top/Article/details/gtbqkiftfk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgufenzy.top/Article/details/gtpemaauxq.html

C#:   list.Sum();  list.Average()
来源：http://dali.ydzc1.top/Article/details/gtadqqwzzs.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gtiasszkuj.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gtkhaneleb.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtbzrrigtb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ydzc1.top/Article/details/gtebpsdhqf.html

TS:   Math.max(...arr);
来源：http://dali.yanxiufei.cn/Article/details/gtxbbmpkqx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daxiang520.top/Article/details/gtycuztpqk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtzbmbznco.html

Ruby: arr.max;  arr.min
来源：http://dali.zhengqikj.top/Article/details/gtjzaukyva.html

C#:   list.Max();  list.Min()
来源：http://dali.hywenlv.cn/Article/details/gtzhjarzkg.html

[D18] 扁平化嵌套数组
来源：http://dali.dashuyun.cn/Article/details/gtwfgotjqp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tian-w.cn/Article/details/gtenkomiiv.html

PHP:  array_merge(...$nested);
来源：http://dali.gaohongyu789.top/Article/details/gttncxhunm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenzaomai.com/Article/details/gtxqwkuctl.html

TS:   nested.flat();
来源：http://dali.hywenlv.cn/Article/details/gtclebkeoc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtzzlpejwu.html

Go:   // 手写双层循环
来源：http://dali.wangshuangyany.cn/Article/details/gtnovoldjg.html

Ruby: nested.flatten
来源：http://dali.sysykeji.top/Article/details/gtqommofah.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtagxvbfoj.html

[D19] 按字段分组
来源：http://dali.xuanzx.com/Article/details/gtthregnup.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fzhhl.top/Article/details/gtvmukhuaj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jiagoushi.top/Article/details/gtkxcjvhcc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hammf.cn/Article/details/gtkedcskqp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gtqbsugykb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangshuangyany.cn/Article/details/gtgdvxmpqn.html

Go:   // 手写 map[string][]T
来源：http://dali.sweek.top/Article/details/gtisihjsrv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tian-w.cn/Article/details/gtovavrkqq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.316326.xyz/Article/details/gtwpqoywvo.html

[D20] 统计每个元素出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtabfzfmpt.html

Py:   Counter(arr)
来源：http://dali.nwbrower.top/Article/details/gtkifbjpey.html

PHP:  array_count_values($arr);
来源：http://dali.hywenlv.cn/Article/details/gtelbldgic.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtfpnxqoyo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtmyvdenrr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xziqi.cn/Article/details/gtvpcmmxiw.html

Go:   // 手写 map[T]int
来源：http://dali.ivvv.top/Article/details/gtwtdfvpgz.html

Ruby: arr.tally
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsdguwbo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gttttvgjqt.html

[D21] 判断是否包含某元素
来源：http://dali.hammf.cn/Article/details/gtlhnqekzs.html

Py:   x in arr
来源：http://dali.zhixingplan.top/Article/details/gtfgbjsjvy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aizwys.cn/Article/details/gtyxctyfyi.html

JS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtghqylhhb.html

TS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtvwqwpcfg.html

Java: list.contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtiqjdhhbx.html

Go:   slices.Contains(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtyktpgyub.html

Ruby: arr.include?(x)
来源：http://dali.hysaishi.cn/Article/details/gtyibwercq.html

C#:   list.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gthwuhoilo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gtnamjkxjc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tianlin.xyz/Article/details/gttxfynttv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ivvv.top/Article/details/gtoaqdpmxm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtbqomwnwu.html

TS:   [...arr];
来源：http://dali.chenjidiqi.icu/Article/details/gttobjwooc.html

Java: new ArrayList<>(list);
来源：http://dali.xziqi.cn/Article/details/gtspxyumvz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fengsongda.top/Article/details/gtodcvhpch.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonofveac.html

C#:   new List<int>(list);
来源：http://dali.smart0.xyz/Article/details/gtbaaxvkzj.html

[D23] reduce 累积计算
来源：http://dali.aizwys.cn/Article/details/gtgzonfsog.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jianghu66.top/Article/details/gtrpgzrekv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuanzhike.top/Article/details/gtjtpcdynz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gtspzkwdmb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gtcvkzmrwn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sweek.top/Article/details/gtnijlijrs.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gtaqkxgkmp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.iojbl.cn/Article/details/gtnnlyffxz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gtoqswqoyp.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhengqikj.top/Article/details/gtvnjwaeoc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gtenezoxvp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.birdmap.top/Article/details/gtwbqkxynk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtizslsuig.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtvknacqip.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.andypj.xyz/Article/details/gtvgxlkvtj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.316326.xyz/Article/details/gtdpdtjqzp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gtaseoduxx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvmkawkh.html

[D25] Set 集合去重与交并差
来源：http://dali.c1oappe.top/Article/details/gtewslrwba.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258.top/Article/details/gtfcybvpjr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.redwolf501.top/Article/details/gtvnmtuxpn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gotoacloud.top/Article/details/gtcmbnjoow.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sxryk.cn/Article/details/gtmehncsau.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtfviqnjzh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.kuanghao11.cn/Article/details/gthhklgzsk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.andypj.xyz/Article/details/gttyjernvm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuxming.cn/Article/details/gtamkupsxj.html

[D26] 数组转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtnnstcjeg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ydzc1.top/Article/details/gtilhzssis.html

PHP:  implode(", ", $arr);
来源：http://dali.shzxlz.cn/Article/details/gticqorpsb.html

JS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtfmapjigp.html

TS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtehslqhtg.html

Java: String.join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gtqpgxfbdt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hysaishi.cn/Article/details/gtkmlprzml.html

Ruby: arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtcwcjsxfy.html

C#:   string.Join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gtzaarqxfu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtnbejejyw.html

E. 字符串处理
来源：http://dali.nanxuanxn.top/Article/details/gtikjufsqz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtnacepypv.html

[E01] 拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtcmoauyvx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nwbrower.top/Article/details/gtjpdtwuew.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xylfe.cn/Article/details/gtxifjgwpp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gtbsedelva.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtjpxlefar.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ivvv.top/Article/details/gtzkonbouz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.quarkkingdee.top/Article/details/gtbckidipl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sweek.top/Article/details/gtfvpnbjlf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtzxdfjkkp.html

[E02] 重复字符串
来源：http://dali.tanke756.top/Article/details/gtfccmpicg.html

Py:   "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gtsyznbpxb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigfzy.top/Article/details/gtnxjixorh.html

JS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gttxowhruq.html

TS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtnleaguqq.html

Java: "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtxcbihsbw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.iojbl.cn/Article/details/gtublkehrh.html

Ruby: "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gtkiaxaalv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yuxming.cn/Article/details/gttpkaposi.html

[E03] 截取子串
来源：http://dali.havefunace.top/Article/details/gtpcziamox.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.smart0.xyz/Article/details/gtjjgdtaob.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sweek.top/Article/details/gtvvyiwysr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtjrjfpqpy.html

TS:   s.slice(1, 4)
来源：http://dali.cheryme.top/Article/details/gtahjmwjsr.html

Java: s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtapdktrgp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gtjawedugt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jianghu66.top/Article/details/gtjhlzvwti.html

C#:   s.Substring(1, 3)
来源：http://dali.kuanghao11.cn/Article/details/gtcomvlxcp.html

[E04] 查找子串位置
来源：http://dali.aizwys.cn/Article/details/gttwzmunbz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gtijnpijpa.html

PHP:  strpos($s, "x");
来源：http://dali.hnqzz.top/Article/details/gthjrbtunh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zycfv.cn/Article/details/gttszhzrtj.html

TS:   s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtrwzglqrz.html

Java: s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gteczqohmc.html

Go:   strings.Index(s, "x")
来源：http://dali.xuetiantiany.cn/Article/details/gtcdktvucd.html

Ruby: s.index("x")
来源：http://dali.pycfn.com/Article/details/gtaxbdaslr.html

C#:   s.IndexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtgcbcgkgl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cqqwz.cn/Article/details/gtepisiubo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cucudq.cn/Article/details/gtxuvlljsb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yongpay.top/Article/details/gtwifxftve.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gtnglxxywp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zdqjudy.top/Article/details/gtmtqddbjk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtmchxpacf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenlongwang.top/Article/details/gtvtlrbinn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yonumen.top/Article/details/gtgahtjoty.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtdjcyosvd.html

[E06] 替换子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyadorigj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtqqzmxgsk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnqzz.top/Article/details/gtriketbnh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtoxtmjjdh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtmuojwmrb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtnupuyvko.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gtywqbbueo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtmxwhwdsm.html

C#:   s.Replace("a", "b")
来源：http://dali.tanke756.top/Article/details/gtyququdjt.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gtfpfyslhn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqczaikck.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cheryme.top/Article/details/gtbtldexjh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.bjfxy.top/Article/details/gtboknwkqz.html

TS:   s.split(",")
来源：http://dali.yuanzhike.top/Article/details/gtyzccauat.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pycfn.com/Article/details/gtloaygurd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxinkj.top/Article/details/gtiarjswkl.html

Ruby: s.split(",");  s.split
来源：http://dali.quarkkingdee.top/Article/details/gthmwywnpi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gtlnwdseni.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzmbwmig.html

Py:   ",".join(items)
来源：http://dali.9152youxi.cn/Article/details/gtfwvghckk.html

PHP:  implode(",", $items);
来源：http://dali.redwolf501.top/Article/details/gteaxtsoqx.html

JS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtzzdrjxlr.html

TS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gtfjejuhpw.html

Java: String.join(",", items)
来源：http://dali.xziqi.cn/Article/details/gtytgqlbhu.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gtqoithaoc.html

Ruby: items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtchijkvzw.html

C#:   string.Join(",", items)
来源：http://dali.yongpay.top/Article/details/gtokceswgu.html

[E09] 去除所有空白字符
来源：http://dali.gaohongyu789.top/Article/details/gtmgvvxiqz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxuanxn.top/Article/details/gtfpsqraos.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gzhubu.top/Article/details/gtzywqkrag.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gtvlqmqcuz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtqrrerpuh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gtbaxezqex.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aibaodan.cn/Article/details/gtqqvkxbki.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hysaishi.cn/Article/details/gtososfbtt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gtfvvpxwzd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.vqdsnc.cn/Article/details/gtrooeeymv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtbjxrvzsg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.316326.xyz/Article/details/gtzrzczjcp.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gteilzjeqf.html

TS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtatdmsqrq.html

Java: String.format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtsrvbpyjy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtxrzolhes.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtmbyujhhw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.vqdsnc.cn/Article/details/gttgnanwhh.html

[E11] 反转字符串
来源：http://dali.xuanzx.com/Article/details/gtmndzgddp.html

Py:   s[::-1]
来源：http://dali.ybcxt.top/Article/details/gttvejgmqu.html

PHP:  strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gtbmejbnuw.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtujxytljo.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtdxitnslg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtevtrqahw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtcywebbkh.html

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtbhdqbtka.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gthumzbexh.html

[E12] 统计某字符出现次数
来源：http://dali.chenzaomai.com/Article/details/gtmxhuzopp.html

Py:   s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gtgcwegfom.html

PHP:  substr_count($s, "a");
来源：http://dali.xuanzx.com/Article/details/gtcnhljups.html

JS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gtbvseyswc.html

TS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gtilyxscce.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shangyingyoupin.top/Article/details/gtzktvegpc.html

Go:   strings.Count(s, "a")
来源：http://dali.redwolf501.top/Article/details/gtbpssuydw.html

Ruby: s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gtnsrdpbid.html

C#:   s.Count(c => c == 'a')
来源：http://dali.svipenyu.cn/Article/details/gthryrohmn.html

[E13] 逐字符遍历
来源：http://dali.hywenlv.cn/Article/details/gtbooenwds.html

Py:   for ch in s: print(ch)
来源：http://dali.zhongyouzk.top/Article/details/gtfqqremqs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ppjwa.cn/Article/details/gtwrgmayxl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gthvihrukm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtlwpofzbb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtuuvugqpp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gtsoufzomq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.andypj.xyz/Article/details/gtdrtwlaxp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tian-w.cn/Article/details/gtegkeickp.html

[E14] URL 编码与 Base64
来源：http://dali.xinyue.icu/Article/details/gtbdzpyfod.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenjidiqi.icu/Article/details/gtzybxabgq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xylfe.cn/Article/details/gtclygjhpt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.9152youxi.cn/Article/details/gtgrbcvjej.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtrxqkhall.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yueranfly.top/Article/details/gtjyjsuekk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nwbrower.top/Article/details/gttwqwuway.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gtgcqzttqn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sweek.top/Article/details/gtrvazbdeg.html

[E15] HTML 转义 / 反转义
来源：http://dali.svipenyu.cn/Article/details/gtqmfakhsq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.birdmap.top/Article/details/gtqlwbdcsj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cucudq.cn/Article/details/gtpjoshtvu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tianlin.xyz/Article/details/gtebanfcpg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.c1oappe.top/Article/details/gtlidqiuwd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yanxiufei.cn/Article/details/gtbnfmpqvr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tianlin.xyz/Article/details/gtnhcqiobf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsvdezua.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.9152youxi.cn/Article/details/gtimxbfiku.html

[E16] 数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gtuginrsom.html

Py:   f"{1234567:,}"
来源：http://dali.yuanzhike.top/Article/details/gthecimzii.html

PHP:  number_format(1234567);
来源：http://dali.hnqzz.top/Article/details/gtvxwgoexe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gtnviziomh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gtmjsfmkdt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.smart0.xyz/Article/details/gtyjfuuwif.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgfzy.top/Article/details/gtcgczhfda.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xziqi.cn/Article/details/gtagujmtsr.html

C#:   1234567.ToString("N0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsslcpgzu.html

[E17] 首字母大写
来源：http://dali.0kj1m.cn/Article/details/gtpotbdahg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnxiangtu.top/Article/details/gtivxjjmgj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hammf.cn/Article/details/gtcsjnjuua.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtiafczxra.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtrrqqkvkn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yongpay.top/Article/details/gtwajfzxwp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgfzy.top/Article/details/gtcsqntqer.html

Ruby: s.capitalize
来源：http://dali.dashuyun.cn/Article/details/gtavievvbo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigfzy.top/Article/details/gtxqiskugr.html

[E18] 模板占位符替换
来源：http://dali.cqqwz.cn/Article/details/gtlaaqhnvy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.svipenyu.cn/Article/details/gtmvskermk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigufen.top/Article/details/gtzwmrkjhz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gttsuvobma.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtxohiswor.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtdiftztcn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtagogpsqc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.birdmap.top/Article/details/gtvjipidgd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gtfwpqcgep.html

[E19] 多行文本按行拆分
来源：http://dali.birdmap.top/Article/details/gtodugkusd.html

Py:   s.splitlines()
来源：http://dali.daria6918.cn/Article/details/gtfombeghm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtzegzpyah.html


<!-- 参考信息 -->