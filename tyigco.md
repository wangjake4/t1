代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sweek.top/Article/details/gtnnwmgiym.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtbticepjt.html

JS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gtduqbjvda.html

TS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtogunbkbg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtkkaespve.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gtpjgatrsh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtcaitwmxp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aizwys.cn/Article/details/gtzxyhpodn.html

[D15] 去重
来源：http://dali.sweek.top/Article/details/gtzwjmnkwo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gogol.net.cn/Article/details/gturtkknro.html

PHP:  array_unique($arr);
来源：http://dali.yangfankeji.com/Article/details/gtudbsnijn.html

JS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtsiuktpkn.html

TS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqyrslyso.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ivvv.top/Article/details/gtmabepism.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgfzy.top/Article/details/gtcesduosr.html

Ruby: arr.uniq
来源：http://dali.cashguo.top/Article/details/gtwyzekaae.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258.top/Article/details/gteprgzpsd.html

[D16] 求和与平均值
来源：http://dali.pycfn.com/Article/details/gtznrwnxoe.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtahxlnkga.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tianlin.xyz/Article/details/gtlmydirwj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtvfxnjsxm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtimzsesov.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtguugwooh.html

Go:   // 手写循环累加
来源：http://dali.jinqigfzy.top/Article/details/gtanavfxyt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sufxvd.cn/Article/details/gteftpufgr.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxuanxn.top/Article/details/gtusmvlwlf.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gtrvdueoeh.html

Py:   max(arr);  min(arr)
来源：http://dali.yvedp.cn/Article/details/gttqippuil.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258.top/Article/details/gtjmintrhx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj202588.top/Article/details/gtgpwhtdik.html

TS:   Math.max(...arr);
来源：http://dali.xinyue.icu/Article/details/gtijmqczrx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfwxoblu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daria6918.cn/Article/details/gtpwkwxxyl.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gtihgeraxu.html

C#:   list.Max();  list.Min()
来源：http://dali.wangshuangyany.cn/Article/details/gtaisdolfu.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gtiwygfuvm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.bjfxy.top/Article/details/gtlhebbwzo.html

PHP:  array_merge(...$nested);
来源：http://dali.birdmap.top/Article/details/gtqgdkbvho.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckpshtij.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gtrprplxgp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dianchejie.cn/Article/details/gtkwmkxvoy.html

Go:   // 手写双层循环
来源：http://dali.gotoacloud.top/Article/details/gthzckseru.html

Ruby: nested.flatten
来源：http://dali.aibaodan.cn/Article/details/gtmlpugljc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtttjyyuaz.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdejelbcz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenzaomai.com/Article/details/gtdjphtgej.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhixingplan.top/Article/details/gtyrqvacwr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xziqi.cn/Article/details/gtzufcaukl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gtfxhnhoaa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hammf.cn/Article/details/gtwiydxevs.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258.top/Article/details/gtlzlprkmh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangdashe.top/Article/details/gtzjveeift.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangdashe.top/Article/details/gtpizpgndg.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gtcaiojpvm.html

Py:   Counter(arr)
来源：http://dali.aibaodan.cn/Article/details/gtgxtntaon.html

PHP:  array_count_values($arr);
来源：http://dali.tanke756.top/Article/details/gtkeomprbd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gthygzxabc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gtyftgzpyw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtmedzpm.html

Go:   // 手写 map[T]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrudfyoe.html

Ruby: arr.tally
来源：http://dali.yueranfly.top/Article/details/gtrduvonuv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuanzx.com/Article/details/gtfumbmeyf.html

[D21] 判断是否包含某元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhrwrarz.html

Py:   x in arr
来源：http://dali.sxryk.cn/Article/details/gtkluuidyh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gtgvfihgad.html

JS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtrrmzugua.html

TS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gtibqpzjrk.html

Java: list.contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtpszzvlzm.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtbzrcoj.html

Ruby: arr.include?(x)
来源：http://dali.ydzc1.top/Article/details/gtocpreree.html

C#:   list.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gtyaouoelp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhongyouzk.top/Article/details/gtjycojtcz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gturjoprup.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.havefunace.top/Article/details/gtflykarrm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cashguo.top/Article/details/gtkfgexfeg.html

TS:   [...arr];
来源：http://dali.yonumen.top/Article/details/gtvooahjfm.html

Java: new ArrayList<>(list);
来源：http://dali.dianchejie.cn/Article/details/gttdboqxar.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.9152youxi.cn/Article/details/gtvfuafrbs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.andypj.xyz/Article/details/gtekveqsbu.html

C#:   new List<int>(list);
来源：http://dali.jiagoushi.top/Article/details/gtwmulcrgn.html

[D23] reduce 累积计算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqyttayyf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gtneirxama.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtwgdnihjz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gtmkrspeqd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gtzqomrbjb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.snrcjt.cn/Article/details/gtezuubhmv.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gtbosrxuvd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pycfn.com/Article/details/gtonynnjor.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guowangkeji.top/Article/details/gtmjefvmej.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhengqikj.top/Article/details/gtktyvcomh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.svipenyu.cn/Article/details/gtaxsjzrcg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hfpthk.cn/Article/details/gtwlsgjimw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gtcpcauqbc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtycuilknn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuanzx.com/Article/details/gtmfzoqjgj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shuidangran.top/Article/details/gtxdukhkgi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangdashe.top/Article/details/gtpncydkvx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhongyouzk.top/Article/details/gtcniqlaqb.html

[D25] Set 集合去重与交并差
来源：http://dali.tanke756.top/Article/details/gtyqpzyvsn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuanzhike.top/Article/details/gtnynranrx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.vqdsnc.cn/Article/details/gtooxrzorr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenlongwang.top/Article/details/gtsyvnwvpz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gogol.net.cn/Article/details/gthbustzbq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gtptvgzssi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangtech.top/Article/details/gtgehskjnl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gaohongyu789.top/Article/details/gtwlqqxlrx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aizwys.cn/Article/details/gtnmyrwnjd.html

[D26] 数组转字符串
来源：http://dali.sxryk.cn/Article/details/gtmqdfmpni.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenzaomai.com/Article/details/gtwvxacjpv.html

PHP:  implode(", ", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtclvrlkbh.html

JS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtlaqrxses.html

TS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gtbokgpvyg.html

Java: String.join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gtzhyhwyii.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslqunejk.html

Ruby: arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtcbkmxuqq.html

C#:   string.Join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gtanbhogfs.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtqqozihhw.html

E. 字符串处理
来源：http://dali.xylfe.cn/Article/details/gtqavznnrn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtfhefdowf.html

[E01] 拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gteilfsgde.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shuidangran.top/Article/details/gtezqenuoc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gotoacloud.top/Article/details/gtloxvbfig.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtswjmojjv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gtxgfynsvn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuanzx.com/Article/details/gtrlaonrsc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dianchejie.cn/Article/details/gtufnjughu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ivvv.top/Article/details/gtdbeyxddx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtvdjesmic.html

[E02] 重复字符串
来源：http://dali.gotoacloud.top/Article/details/gtfhmgjkbi.html

Py:   "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gtsuaeikze.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jyoumei.cn/Article/details/gtwmamiqhi.html

JS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtiakvxbjb.html

TS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtzezmrzmb.html

Java: "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtywxpvtzg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtylfaudvy.html

Ruby: "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gtptqqxvlp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shzxlz.cn/Article/details/gtenkijspr.html

[E03] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcjdmvhb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yueranfly.top/Article/details/gtutjjggan.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtjzmsitnu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtznpsmimq.html

TS:   s.slice(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gtwaqbdlgd.html

Java: s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtmadwyenz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tianlin.xyz/Article/details/gtjcqyfszw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ehwqpu.com/Article/details/gtmljnkrvc.html

C#:   s.Substring(1, 3)
来源：http://dali.hywenlv.cn/Article/details/gtufxnligi.html

[E04] 查找子串位置
来源：http://dali.c1oappe.top/Article/details/gtjhrxshjq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtadpblfeb.html

PHP:  strpos($s, "x");
来源：http://dali.yj202588.top/Article/details/gtjuienzcr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dianchejie.cn/Article/details/gtuxowsxir.html

TS:   s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gttxlffpru.html

Java: s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gttfflbybb.html

Go:   strings.Index(s, "x")
来源：http://dali.jyoumei.cn/Article/details/gthihwfzpr.html

Ruby: s.index("x")
来源：http://dali.yongpay.top/Article/details/gtmsljgcbk.html

C#:   s.IndexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtxadtoiiq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnqzz.top/Article/details/gtsminnufu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwgazezi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhuptmen.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtxdgexlav.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jlsjyb.cn/Article/details/gthinyfymm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtcbwjplry.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.kuanghao11.cn/Article/details/gtsrpgykkh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gtfpmdjuth.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcriadtt.html

[E06] 替换子串
来源：http://dali.316326.xyz/Article/details/gtyahdisoe.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gtvbidlufn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtbsgqoauj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtejhqjjnz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtmvoggjqd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtfybsekcn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gtmsjlwpgt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtnkcylfyt.html

C#:   s.Replace("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtqaqptgyh.html

[E07] 按分隔符拆分
来源：http://dali.cdnleiting.top/Article/details/gtpopcnvbg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sweek.top/Article/details/gtwjisauxs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtidnsvzfw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgufenzy.top/Article/details/gtigrjrjzs.html

TS:   s.split(",")
来源：http://dali.feifeiyinyue.top/Article/details/gteacidjwz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aibaodan.cn/Article/details/gtekatsxsp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.kuanghao11.cn/Article/details/gtobpreida.html

Ruby: s.split(",");  s.split
来源：http://dali.yuanzhike.top/Article/details/gtnxfalswp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daxiang520.top/Article/details/gtyoyntzsh.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gtdmwcxlwl.html

Py:   ",".join(items)
来源：http://dali.jqgfzy.top/Article/details/gtdojowtfx.html

PHP:  implode(",", $items);
来源：http://dali.0kj1m.cn/Article/details/gtmnwkkecz.html

JS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtxrnaspcy.html

TS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtolbhhwoe.html

Java: String.join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gtyiccghtq.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gtdffhchoe.html

Ruby: items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtefmnvcfl.html

C#:   string.Join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gtielmdctd.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gtasyrnvcc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tian-w.cn/Article/details/gtolewcpqw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cucudq.cn/Article/details/gtgwnrklbi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gtlouebdjr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gtmfnwgjjd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gtyqnfeiwp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhongyouzk.top/Article/details/gtkspjtnui.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnxiangtu.top/Article/details/gtpnzqbvzk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aizwys.cn/Article/details/gtcumnewdm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sweek.top/Article/details/gtejppufqy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258.top/Article/details/gtvmfutvpr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.havefunace.top/Article/details/gtxrtmrllv.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtatogcpkb.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtorpkzxio.html

Java: String.format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtfoohkkhp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gtphblgskn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtgllthsft.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guannengcc.top/Article/details/gteipfzqnc.html

[E11] 反转字符串
来源：http://dali.iojbl.cn/Article/details/gtdmwhbecs.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtxuvmpelt.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtxmaegwes.html

JS:   [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtttknikqd.html

TS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtxahpfbhu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gtkdmvqasq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtjvivufod.html

Ruby: s.reverse
来源：http://dali.andypj.xyz/Article/details/gtgfdnglzz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gtzknuqqat.html

[E12] 统计某字符出现次数
来源：http://dali.daria6918.cn/Article/details/gtlficjfsc.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtubqoafqv.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gtulrwmtsg.html

JS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gtfagdfpte.html

TS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gttsbeqzjz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fengsongda.top/Article/details/gtoxwdylxp.html

Go:   strings.Count(s, "a")
来源：http://dali.chenlongwang.top/Article/details/gtkcqwmqsf.html

Ruby: s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gtfysxusyw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pengpengdd.cyou/Article/details/gtfiulkjsx.html

[E13] 逐字符遍历
来源：http://dali.mhx1999.top/Article/details/gtjovpzilt.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgufenzy.top/Article/details/gtptqsgiyf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.bjfxy.top/Article/details/gtcoacczuj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtcgghhxsx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtpwkzombp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtyxeapwbi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hfpthk.cn/Article/details/gtaxzkdmed.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sysykeji.top/Article/details/gtoaoiaxlx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvwiryvq.html

[E14] URL 编码与 Base64
来源：http://dali.hnxiangtu.top/Article/details/gtfdnxrgpy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yonumen.top/Article/details/gtvpfhsshe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gtstrpvmnk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dianchejie.cn/Article/details/gtcnponhax.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yanxiufei.cn/Article/details/gtcegkgvav.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangdashe.top/Article/details/gtkaqijfiu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hysaishi.cn/Article/details/gtxidwraaz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zycfv.cn/Article/details/gtnyiujdxx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.havefunace.top/Article/details/gtlsueozsg.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gthstncfyo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.kuanghao11.cn/Article/details/gtmdocszmx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuanzx.com/Article/details/gtwnxdrheo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxuanxn.top/Article/details/gtptetwhjk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuanzx.com/Article/details/gtologzzeq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sufxvd.cn/Article/details/gthcihdwvu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dashuyun.cn/Article/details/gtaihthxdo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sysykeji.top/Article/details/gtcrgaaarf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hammf.cn/Article/details/gtekprajvt.html

[E16] 数字千分位
来源：http://dali.guannengcc.top/Article/details/gtpbqpzlxw.html

Py:   f"{1234567:,}"
来源：http://dali.jqgufenzy.top/Article/details/gtsoktalch.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gtkxvqqxkz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gtxnfrdddz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtucdiwxfq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtqpqrxhvf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fengsongda.top/Article/details/gtfjnsdviq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yvedp.cn/Article/details/gtofdbyatj.html

C#:   1234567.ToString("N0")
来源：http://dali.ydzc1.top/Article/details/gtobkptses.html

[E17] 首字母大写
来源：http://dali.daxiang520.top/Article/details/gtzsukpkqw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.kuanghao11.cn/Article/details/gtaizlumzp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoydyncii.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtimcbxfoc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gtbzwtcsyz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijrwewnl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtgprdaqyk.html

Ruby: s.capitalize
来源：http://dali.hywenlv.cn/Article/details/gteuypzdip.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cdnleiting.top/Article/details/gtbqudhipe.html

[E18] 模板占位符替换
来源：http://dali.guannengcc.top/Article/details/gtqyzolbso.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhongyouzk.top/Article/details/gtdymojktr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gtkdfjapza.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtgffumbwl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtolcvsgkv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtouadxkxd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtzmaesljs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yangfankeji.com/Article/details/gtlcxsjmjw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pengpengdd.cyou/Article/details/gtcjddbgck.html

[E19] 多行文本按行拆分
来源：http://dali.yj202588.top/Article/details/gtqqnflmvw.html

Py:   s.splitlines()
来源：http://dali.sxryk.cn/Article/details/gtgtjvwjem.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuanzx.com/Article/details/gtudztyame.html

JS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gtixekbldt.html

TS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtcpzzjxto.html

Java: s.lines().toList()
来源：http://dali.nwbrower.top/Article/details/gtmsubdlxy.html

Go:   strings.Split(s, "\n")
来源：http://dali.cashguo.top/Article/details/gthlzlwjfy.html

Ruby: s.lines
来源：http://dali.gzhubu.top/Article/details/gtjyfwroqm.html

C#:   s.Split('\n')
来源：http://dali.wangshuangyany.cn/Article/details/gtqgmizter.html

[E20] 判断字符串是否为空
来源：http://dali.hfpthk.cn/Article/details/gtkwfbgrcb.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gtjwiqzcmx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tianlin.xyz/Article/details/gtkfazbhhl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daria6918.cn/Article/details/gtixnzkstq.html

TS:   if (s === "") {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgwohwkj.html

Java: if (s.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gtbhhmefum.html

Go:   if s == "" {}
来源：http://dali.nwbrower.top/Article/details/gteojyopty.html

Ruby: if s.empty?
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbclhdgf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tianlin.xyz/Article/details/gttkhqiuzl.html

[E21] 超长截断加省略号
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvwergtv.html


<!-- 参考信息 -->