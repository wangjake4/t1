代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xziqi.cn/Article/details/gtawxiocqz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhixingplan.top/Article/details/gtyvaavqek.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtjiifzace.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hysaishi.cn/Article/details/gtifpatino.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jianghu66.top/Article/details/gtgduoxxwu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cqqwz.cn/Article/details/gtujjtybia.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtnabxbetb.html

TS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtldcuhfaw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jyoumei.cn/Article/details/gtzstahdws.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gtcpvzchyy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdatiswd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sweek.top/Article/details/gtsyquswfx.html

[D15] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtggtzxgzo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gttygtqmnd.html

PHP:  array_unique($arr);
来源：http://dali.shuidangran.top/Article/details/gttpevlfjm.html

JS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtgtclgwmx.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuazidyde.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.smart0.xyz/Article/details/gtffjdoesj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dashuyun.cn/Article/details/gtkyidmnyb.html

Ruby: arr.uniq
来源：http://dali.dashuyun.cn/Article/details/gtrmaxyuhp.html

C#:   list.Distinct().ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtqdsuapbt.html

[D16] 求和与平均值
来源：http://dali.chenzaomai.com/Article/details/gtvugyukpk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dashuyun.cn/Article/details/gtvvwqdxua.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zdqjudy.top/Article/details/gtjwzheqmu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtyzdvxgjn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gtyhulzqle.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tianlin.xyz/Article/details/gtbhfdcvat.html

Go:   // 手写循环累加
来源：http://dali.tanke756.top/Article/details/gtxvkmehtr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.316326.xyz/Article/details/gthnmapadu.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuetiantiany.cn/Article/details/gtqmwsraxg.html

[D17] 最大值与最小值
来源：http://dali.hfpthk.cn/Article/details/gtuscwtcos.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gtgezlevha.html

PHP:  max($arr);  min($arr);
来源：http://dali.yueranfly.top/Article/details/gtmuqoukgh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.birdmap.top/Article/details/gtfikvsppr.html

TS:   Math.max(...arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtpahksnkf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtxtrglwkp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xylfe.cn/Article/details/gtjjfjzkrx.html

Ruby: arr.max;  arr.min
来源：http://dali.quarkkingdee.top/Article/details/gtzaqsiiop.html

C#:   list.Max();  list.Min()
来源：http://dali.hysaishi.cn/Article/details/gtbtkzqaaq.html

[D18] 扁平化嵌套数组
来源：http://dali.vqdsnc.cn/Article/details/gttdfpjqze.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tianlin.xyz/Article/details/gtxhppwhxz.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxinkj.top/Article/details/gtqlvwbkxt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pycfn.com/Article/details/gtddjaygim.html

TS:   nested.flat();
来源：http://dali.cucudq.cn/Article/details/gtjysvcgio.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yvedp.cn/Article/details/gtxphbrpri.html

Go:   // 手写双层循环
来源：http://dali.jlsjyb.cn/Article/details/gtasqyqjhq.html

Ruby: nested.flatten
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcjtjxaq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zycfv.cn/Article/details/gtvulqvkoo.html

[D19] 按字段分组
来源：http://dali.hysaishi.cn/Article/details/gtogmxwrxr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtlwiabzst.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shangyingyoupin.top/Article/details/gtkycqbncw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gtuvnaxnun.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gthiexihmb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gtdtsxpqll.html

Go:   // 手写 map[string][]T
来源：http://dali.daria6918.cn/Article/details/gtunzhrqwb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ydzc1.top/Article/details/gtdhrdrnfo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.feifeiyinyue.top/Article/details/gtoqhrrjtz.html

[D20] 统计每个元素出现次数
来源：http://dali.quarkkingdee.top/Article/details/gtmngjrzqc.html

Py:   Counter(arr)
来源：http://dali.svipenyu.cn/Article/details/gtavusqypu.html

PHP:  array_count_values($arr);
来源：http://dali.yongpay.top/Article/details/gtnxhsaaxn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gtriyyimbg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtccdwitga.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jyoumei.cn/Article/details/gtkkenqcip.html

Go:   // 手写 map[T]int
来源：http://dali.birdmap.top/Article/details/gtajyqyuli.html

Ruby: arr.tally
来源：http://dali.haohaochexian.top/Article/details/gtjkwdgymw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvjnszzw.html

[D21] 判断是否包含某元素
来源：http://dali.ehwqpu.com/Article/details/gtitprilfy.html

Py:   x in arr
来源：http://dali.xuanzx.com/Article/details/gtplrigqtd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xinyue.icu/Article/details/gtnhqowovr.html

JS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gtszxbmkuy.html

TS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtrdbiqujo.html

Java: list.contains(x)
来源：http://dali.ybcxt.top/Article/details/gtnaxyzldt.html

Go:   slices.Contains(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtxwimckuu.html

Ruby: arr.include?(x)
来源：http://dali.chenzaomai.com/Article/details/gtvvrclrbu.html

C#:   list.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtszgdfqub.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ydzc1.top/Article/details/gtvtjeltvz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gtwknrxpvs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yonumen.top/Article/details/gtuxtnndvj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gthifdzgzh.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gtyiohsaci.html

Java: new ArrayList<>(list);
来源：http://dali.xuanzx.com/Article/details/gtlkzgtwdl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cucudq.cn/Article/details/gthuwfgdps.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shuidangran.top/Article/details/gtmszjkahj.html

C#:   new List<int>(list);
来源：http://dali.cucudq.cn/Article/details/gtjmxdunli.html

[D23] reduce 累积计算
来源：http://dali.zdqjudy.top/Article/details/gtretmpopx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ydzc1.top/Article/details/gtuaprrxlk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtjmozvebb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtwrszuuls.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gtouyfrrjj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.vqdsnc.cn/Article/details/gtqiciydfj.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gtpymzwqkp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj202588.top/Article/details/gtwznrqaxx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhoulong.xyz/Article/details/gtnibbiogg.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhixingplan.top/Article/details/gtaygbmqhx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tianlin.xyz/Article/details/gttiiyfeoo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigfzy.top/Article/details/gtfyrojyhr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigufen.top/Article/details/gtuuynzfrj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtyhmnhssl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gaohongyu789.top/Article/details/gtlwgwxrbe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258888.top/Article/details/gtqdxrhbdk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gtfzjlmcer.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxuanxn.top/Article/details/gtbwkxmtsv.html

[D25] Set 集合去重与交并差
来源：http://dali.hnxiangtu.top/Article/details/gtpsmcldpu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shuidangran.top/Article/details/gtitibclkz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gotoacloud.top/Article/details/gthtcqlcfy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.havefunace.top/Article/details/gtrqdurqpn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dianchejie.cn/Article/details/gtrtvcibxn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtvelwlycn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbqtjbqy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ydzc1.top/Article/details/gthpdgbcbl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtbstegc.html

[D26] 数组转字符串
来源：http://dali.haohaochexian.top/Article/details/gteealfaqb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.birdmap.top/Article/details/gtxwennbyv.html

PHP:  implode(", ", $arr);
来源：http://dali.guannengcc.top/Article/details/gtmlvcwnkp.html

JS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtxbyvaixf.html

TS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtzqhvuvye.html

Java: String.join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gthgofqpks.html

Go:   strings.Join(strs, ", ")
来源：http://dali.redwolf501.top/Article/details/gtmkrnjdom.html

Ruby: arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtzszwpltn.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtizxhxpwz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtlnrlkylj.html

E. 字符串处理
来源：http://dali.meibo888.top/Article/details/gthzayxehy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtqvkinuxb.html

[E01] 拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtlprlyvps.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.feifeiyinyue.top/Article/details/gtfsroccgt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydjyppik.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gtagndcsar.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtpyscivyp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cheryme.top/Article/details/gtrimskkce.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yonumen.top/Article/details/gtpimjgozx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuxming.cn/Article/details/gteounibto.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtzglolxwz.html

[E02] 重复字符串
来源：http://dali.nanxuanxn.top/Article/details/gtpblgbjwe.html

Py:   "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gtpxwuloah.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yueranfly.top/Article/details/gtobuuvmmu.html

JS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gtgnizphsk.html

TS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtcjlvuznt.html

Java: "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtebsewxjr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gzhubu.top/Article/details/gtqsajiemq.html

Ruby: "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtaxqyehnr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xziqi.cn/Article/details/gtbuaizpux.html

[E03] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gtpxxywera.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fengsongda.top/Article/details/gtmqinyblp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtlfgspsdc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtuvykwzce.html

TS:   s.slice(1, 4)
来源：http://dali.havefunace.top/Article/details/gtvrgypoqx.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtohwqfvhq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xziqi.cn/Article/details/gtatjjbpho.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jlsjyb.cn/Article/details/gtwkqfgdgz.html

C#:   s.Substring(1, 3)
来源：http://dali.iojbl.cn/Article/details/gtunjnojro.html

[E04] 查找子串位置
来源：http://dali.yongpay.top/Article/details/gttvmiezhl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangdashe.top/Article/details/gtqtokekcj.html

PHP:  strpos($s, "x");
来源：http://dali.bjfxy.top/Article/details/gtjljldjbs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenzaomai.com/Article/details/gtzzhgshly.html

TS:   s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtezxhfxlw.html

Java: s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gthezebhpu.html

Go:   strings.Index(s, "x")
来源：http://dali.jinqigfzy.top/Article/details/gtvouichem.html

Ruby: s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gtirfuihtd.html

C#:   s.IndexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtepgpckvg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhoulong.xyz/Article/details/gtokefadds.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtadrjekqp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuxming.cn/Article/details/gthflqgdkz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtflvrnpfr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.pycfn.com/Article/details/gtustamdhm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtisjpxrxb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hfpthk.cn/Article/details/gteowvgpat.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jianghu66.top/Article/details/gtzshptoui.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtoovewxoq.html

[E06] 替换子串
来源：http://dali.pengpengdd.cyou/Article/details/gtaengzcrg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtfchqdkbo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnqzz.top/Article/details/gtnbggmhin.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtqpzbsgvp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtlaisaios.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtwckwxyoc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.birdmap.top/Article/details/gtzjmauxuv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtmmlwtmid.html

C#:   s.Replace("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtrnyllbcj.html

[E07] 按分隔符拆分
来源：http://dali.andypj.xyz/Article/details/gtcrcxzthg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgufenzy.top/Article/details/gtqkdfhios.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.bjfxy.top/Article/details/gtfgvhyulq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gaohongyu789.top/Article/details/gtbgrxqunm.html

TS:   s.split(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpimbvaq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jiagoushi.top/Article/details/gtehxhzchv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenlongwang.top/Article/details/gtdpbbklob.html

Ruby: s.split(",");  s.split
来源：http://dali.0kj1m.cn/Article/details/gtfncdazir.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.feifeiyinyue.top/Article/details/gtwtrojzqk.html

[E08] 数组按分隔符合并
来源：http://dali.bjfxy.top/Article/details/gtlykspnjw.html

Py:   ",".join(items)
来源：http://dali.wangshuangyany.cn/Article/details/gtvtogzyps.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibvbstvg.html

JS:   items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtyencuwgv.html

TS:   items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtwovponga.html

Java: String.join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gtthheckwg.html

Go:   strings.Join(items, ",")
来源：http://dali.yvedp.cn/Article/details/gttwwkteqz.html

Ruby: items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtwtrodepv.html

C#:   string.Join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gtwfelpgvg.html

[E09] 去除所有空白字符
来源：http://dali.guannengcc.top/Article/details/gtaamffkss.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.birdmap.top/Article/details/gtkgikrgma.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenlongwang.top/Article/details/gtlmwxwsmv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtezomobay.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtfrhnkymy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gtboicgrih.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthngzliqz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxuanxn.top/Article/details/gtldgopani.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtwyagpgtc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jianghu66.top/Article/details/gthuptbogf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.birdmap.top/Article/details/gttalvwdso.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuetiantiany.cn/Article/details/gttsyavdwa.html

JS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtvlydurss.html

TS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtuziyilok.html

Java: String.format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtmksszbux.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtmteapadp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtmoqhuvmn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrylwgyj.html

[E11] 反转字符串
来源：http://dali.ivvv.top/Article/details/gtsnwwhdvc.html

Py:   s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtizgtiqnn.html

PHP:  strrev($s);
来源：http://dali.316326.xyz/Article/details/gtujwhzljh.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtgaiptxek.html

TS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtvfgcflui.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gtyffromoc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovqjmauv.html

Ruby: s.reverse
来源：http://dali.cqqwz.cn/Article/details/gtrliqzzdr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gttpnlklpv.html

[E12] 统计某字符出现次数
来源：http://dali.hnqzz.top/Article/details/gtiqqalaof.html

Py:   s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdysokuse.html

PHP:  substr_count($s, "a");
来源：http://dali.ehwqpu.com/Article/details/gtnascxtnu.html

JS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gttighylse.html

TS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gtnpgzviwe.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zdqjudy.top/Article/details/gtnmpamrpa.html

Go:   strings.Count(s, "a")
来源：http://dali.xuanzx.com/Article/details/gtqcrxdmhj.html

Ruby: s.count("a")
来源：http://dali.xziqi.cn/Article/details/gtgrwjpoub.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gtpnjjdpcd.html

[E13] 逐字符遍历
来源：http://dali.zhengqikj.top/Article/details/gtpoipudue.html

Py:   for ch in s: print(ch)
来源：http://dali.iojbl.cn/Article/details/gtehojnown.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yvedp.cn/Article/details/gtduavwasu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gtzmgrjnei.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtsmajepme.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xylfe.cn/Article/details/gtzxceovgu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yongpay.top/Article/details/gthrqziynz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aizwys.cn/Article/details/gtudhhjkuq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aizwys.cn/Article/details/gtuyobvtmr.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gtmyoxknln.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ppjwa.cn/Article/details/gtwrswrcoz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuanzhike.top/Article/details/gtqkofnpdf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtystgnefy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gogol.net.cn/Article/details/gttjnhardo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtvpjeyyfg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shuidangran.top/Article/details/gtxzqfqhxh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnqzz.top/Article/details/gtekpjiftt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtqdyntyfw.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gtdzajejav.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtavavzxsg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hysaishi.cn/Article/details/gtcxqjpgym.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hfpthk.cn/Article/details/gtsyxjauzg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yonumen.top/Article/details/gthupidxbv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cucudq.cn/Article/details/gtivximbdr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tian-w.cn/Article/details/gtsgolxzpv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzckiohq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ydzc1.top/Article/details/gtgpcdnbfk.html

[E16] 数字千分位
来源：http://dali.hysaishi.cn/Article/details/gtexgedkap.html

Py:   f"{1234567:,}"
来源：http://dali.gaohongyu789.top/Article/details/gtpkqmcgqf.html

PHP:  number_format(1234567);
来源：http://dali.pycfn.com/Article/details/gthhrxbwkh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gtuypbvkcn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtysokuabf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwjdywri.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ivvv.top/Article/details/gtpakieejb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fengsongda.top/Article/details/gthetjspbu.html

C#:   1234567.ToString("N0")
来源：http://dali.hnqzz.top/Article/details/gtifmmzapt.html

[E17] 首字母大写
来源：http://dali.hfpthk.cn/Article/details/gttxatasmj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gtjqbvczek.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sufxvd.cn/Article/details/gtjygoxohe.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtqbquthjb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtoocitvww.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guannengcc.top/Article/details/gteefmoohp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pycfn.com/Article/details/gtvgoodgbg.html

Ruby: s.capitalize
来源：http://dali.yuxming.cn/Article/details/gtifdrgjvb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hammf.cn/Article/details/gthqkyhgzh.html

[E18] 模板占位符替换
来源：http://dali.yj20258.top/Article/details/gtjbfzbbls.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hywenlv.cn/Article/details/gtmtyclzco.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dashuyun.cn/Article/details/gtqntholiu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtnpuplkia.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtjgizogtl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtycgrbktn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cheryme.top/Article/details/gtfzunajeo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnxiangtu.top/Article/details/gtjtprnhmj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuetiantiany.cn/Article/details/gtszevxdoe.html

[E19] 多行文本按行拆分
来源：http://dali.hnqzz.top/Article/details/gtkzzfaztq.html

Py:   s.splitlines()
来源：http://dali.cdnleiting.top/Article/details/gtahpftmpe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tianlin.xyz/Article/details/gthochgqhd.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtyzqciera.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtxvrgqllc.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gtwxcclksx.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsqbiejs.html

Ruby: s.lines
来源：http://dali.xuanzx.com/Article/details/gttvumsrib.html

C#:   s.Split('\n')
来源：http://dali.jyoumei.cn/Article/details/gtywlppcru.html

[E20] 判断字符串是否为空
来源：http://dali.aizwys.cn/Article/details/gtrdsawymu.html

Py:   if not s:
来源：http://dali.0kj1m.cn/Article/details/gtxxivvluf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tian-w.cn/Article/details/gthlltbmex.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tanke756.top/Article/details/gtgffpjtkt.html

TS:   if (s === "") {}
来源：http://dali.jinqigfzy.top/Article/details/gtbygvmnfw.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gtzaiktzfm.html


<!-- 参考信息 -->