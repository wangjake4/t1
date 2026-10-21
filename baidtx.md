代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gtyqqeukuy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangshuangyany.cn/Article/details/gtkhycrhhl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.quarkkingdee.top/Article/details/gttrepqthg.html

Ruby: arr.uniq
来源：http://dali.haohaochexian.top/Article/details/gtookjdmtr.html

C#:   list.Distinct().ToList()
来源：http://dali.sufxvd.cn/Article/details/gttmevtytr.html

[D16] 求和与平均值
来源：http://dali.haohaochexian.top/Article/details/gtalpjjgnd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxetwgmod.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.andypj.xyz/Article/details/gtewsyauwa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gtsleozdga.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gtlkcgumnh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgufenzy.top/Article/details/gtbdhpmcmy.html

Go:   // 手写循环累加
来源：http://dali.chenjidiqi.icu/Article/details/gteolxgwmx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sysykeji.top/Article/details/gtxymbmvdt.html

C#:   list.Sum();  list.Average()
来源：http://dali.redwolf501.top/Article/details/gtqxhklgwp.html

[D17] 最大值与最小值
来源：http://dali.chenzaomai.com/Article/details/gtgodagpno.html

Py:   max(arr);  min(arr)
来源：http://dali.yvedp.cn/Article/details/gtqzmdnndx.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnqzz.top/Article/details/gtvhvrrcay.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.smart0.xyz/Article/details/gtnfvfdeen.html

TS:   Math.max(...arr);
来源：http://dali.smart0.xyz/Article/details/gtkibrmfhd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hywenlv.cn/Article/details/gtdsnxqzyv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tian-w.cn/Article/details/gtaaatagno.html

Ruby: arr.max;  arr.min
来源：http://dali.chenlongwang.top/Article/details/gthccprsvd.html

C#:   list.Max();  list.Min()
来源：http://dali.daria6918.cn/Article/details/gtlaggvrzd.html

[D18] 扁平化嵌套数组
来源：http://dali.sufxvd.cn/Article/details/gtdpoycbnl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxuanxn.top/Article/details/gtqjasojij.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycmwsqmz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.andypj.xyz/Article/details/gtnkopklrs.html

TS:   nested.flat();
来源：http://dali.cqqwz.cn/Article/details/gtzmabqhqv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daria6918.cn/Article/details/gtatjsaxsz.html

Go:   // 手写双层循环
来源：http://dali.shzxlz.cn/Article/details/gtatoeodai.html

Ruby: nested.flatten
来源：http://dali.vqdsnc.cn/Article/details/gtijcuoofz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtidruhwye.html

[D19] 按字段分组
来源：http://dali.feifeiyinyue.top/Article/details/gtnkmhltmr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtnwwyjkwk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyqzcfce.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuetiantiany.cn/Article/details/gtvmuimzjy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gtndrozptx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangtech.top/Article/details/gtsubsmrwn.html

Go:   // 手写 map[string][]T
来源：http://dali.iojbl.cn/Article/details/gtkaazndbb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zdqjudy.top/Article/details/gtmcnvmwil.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.0kj1m.cn/Article/details/gtmyxyyywy.html

[D20] 统计每个元素出现次数
来源：http://dali.hnxiangtu.top/Article/details/gtbkoolshu.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtoovnjqft.html

PHP:  array_count_values($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtcuuhsqqx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gturjojbjf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sweek.top/Article/details/gtmjidbheu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shzxlz.cn/Article/details/gtftdvujge.html

Go:   // 手写 map[T]int
来源：http://dali.iojbl.cn/Article/details/gtsuqijbzq.html

Ruby: arr.tally
来源：http://dali.yuanzhike.top/Article/details/gtxtmcpguq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gotoacloud.top/Article/details/gtedocrpcm.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gtyglelihl.html

Py:   x in arr
来源：http://dali.zdqjudy.top/Article/details/gtsjobgejz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmfkpava.html

JS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gtntuiyosa.html

TS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtqnecdkgj.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtvsqgrwdn.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtoymjsnfn.html

Ruby: arr.include?(x)
来源：http://dali.havefunace.top/Article/details/gtigzmscqn.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuglpuzss.html

[D22] 复制数组（避免共享引用）
来源：http://dali.svipenyu.cn/Article/details/gtwybvkggn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gtxanbnuva.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hfpthk.cn/Article/details/gtmqgmwpwm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhixingplan.top/Article/details/gtcgmojjko.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gtqfjscicl.html

Java: new ArrayList<>(list);
来源：http://dali.jqgfzy.top/Article/details/gtmlbfitmx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yonumen.top/Article/details/gthyzajhoz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yvedp.cn/Article/details/gtiircynno.html

C#:   new List<int>(list);
来源：http://dali.ydzc1.top/Article/details/gtnpzkckbg.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gtiiqarlqo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daxiang520.top/Article/details/gtqfymxfhy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cashguo.top/Article/details/gtatzyphzj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gtymywkzwq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gtzwkaosqg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodxjsowe.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gtxsuahwch.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yangfankeji.com/Article/details/gtopqwrbsx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gtjanmmyjz.html

[D24] 字典 / Map 基本操作
来源：http://dali.meibo888.top/Article/details/gtkbhkamit.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jiagoushi.top/Article/details/gtbzauqxuw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sxryk.cn/Article/details/gtjsmylypf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yueranfly.top/Article/details/gtplwqnmhy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtdvxqfuqr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenzaomai.com/Article/details/gtesjgothv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258.top/Article/details/gtzmecnaep.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shzxlz.cn/Article/details/gtrxezrqxh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gtsieustef.html

[D25] Set 集合去重与交并差
来源：http://dali.ybcxt.top/Article/details/gtahtihmsm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cashguo.top/Article/details/gtjqaodlan.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.iojbl.cn/Article/details/gtmlzddxuj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiihxhrcn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdoauvpag.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nwbrower.top/Article/details/gtkirkjfcs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sweek.top/Article/details/gtxmibwqjg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xziqi.cn/Article/details/gttwrbdafy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj202588.top/Article/details/gtwhodxvvu.html

[D26] 数组转字符串
来源：http://dali.hywenlv.cn/Article/details/gtxdofmkyj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtsexnlzjp.html

PHP:  implode(", ", $arr);
来源：http://dali.sweek.top/Article/details/gtsqmzmkfn.html

JS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtvuthllbq.html

TS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gthcxikunx.html

Java: String.join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gtrzcteiyt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhixingplan.top/Article/details/gtlstcptxk.html

Ruby: arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtybfjwend.html

C#:   string.Join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gttfohbzui.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtytjgzdor.html

E. 字符串处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxyocpyx.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtkyynojrc.html

[E01] 拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gthdrglftj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsrsyhgj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenzaomai.com/Article/details/gtikxglhuv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtjocjpnxy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtvoountxk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnqzz.top/Article/details/gtadfryawg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhoulong.xyz/Article/details/gtahkvycpn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ehwqpu.com/Article/details/gtqmnlgrwu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258.top/Article/details/gtjznlterv.html

[E02] 重复字符串
来源：http://dali.jinqigufen.top/Article/details/gtchfvppmt.html

Py:   "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwjowuqj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cqqwz.cn/Article/details/gtmxoghzer.html

JS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gticgdrbqb.html

TS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtxtxbjkuj.html

Java: "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtmqystvgr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gthdcpwopx.html

Ruby: "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gtlxlviixu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fengsongda.top/Article/details/gtcwmevjal.html

[E03] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gthtgtrocg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cqqwz.cn/Article/details/gtxbcoskqc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtbipwedem.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtculormhm.html

TS:   s.slice(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtosczyjii.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtleabhdrd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daria6918.cn/Article/details/gtscbdhwdg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhiwuduotai.top/Article/details/gtzisjubec.html

C#:   s.Substring(1, 3)
来源：http://dali.fengsongda.top/Article/details/gtagehevcu.html

[E04] 查找子串位置
来源：http://dali.jinqigfzy.top/Article/details/gtymtzizog.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gtksskcejv.html

PHP:  strpos($s, "x");
来源：http://dali.vqdsnc.cn/Article/details/gtezvkrcbd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sufxvd.cn/Article/details/gtowfmffth.html

TS:   s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtpnqjwqbe.html

Java: s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpsevxix.html

Go:   strings.Index(s, "x")
来源：http://dali.daria6918.cn/Article/details/gtimfpmayb.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gttbemlcnr.html

C#:   s.IndexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtsrfbhreu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ppjwa.cn/Article/details/gtdzpfhdrk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.mhx1999.top/Article/details/gteufukypp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwysbfbyp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gttiuhcogq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ybcxt.top/Article/details/gtijopmrah.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtzhcqremc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jianghu66.top/Article/details/gtvjrzwxbg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenzaomai.com/Article/details/gtkotsjqxv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtucpvofcy.html

[E06] 替换子串
来源：http://dali.daria6918.cn/Article/details/gtwfkumwwt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gtffwcjqaj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ehwqpu.com/Article/details/gtrhnjnqya.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtjdxkizjr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtazsuzowa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtoygvbfre.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtuigktymv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gttqbejsqe.html

C#:   s.Replace("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtpietufdp.html

[E07] 按分隔符拆分
来源：http://dali.yueranfly.top/Article/details/gtoowfafgb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cashguo.top/Article/details/gtbhhwudbf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258.top/Article/details/gtemwfppuk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yanxiufei.cn/Article/details/gtfdxotrwm.html

TS:   s.split(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtkqnymlig.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuanzhike.top/Article/details/gtfyozrwsk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.aizwys.cn/Article/details/gtuqidcdym.html

Ruby: s.split(",");  s.split
来源：http://dali.gotoacloud.top/Article/details/gtjkjdyjeq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cdnleiting.top/Article/details/gtrgrzccbm.html

[E08] 数组按分隔符合并
来源：http://dali.316326.xyz/Article/details/gtvrifteim.html

Py:   ",".join(items)
来源：http://dali.fengsongda.top/Article/details/gtpscvkgfx.html

PHP:  implode(",", $items);
来源：http://dali.9152youxi.cn/Article/details/gtvjphebqa.html

JS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtzkoapbgy.html

TS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gtonpjvopz.html

Java: String.join(",", items)
来源：http://dali.hywenlv.cn/Article/details/gtvufqiiuh.html

Go:   strings.Join(items, ",")
来源：http://dali.haohaochexian.top/Article/details/gtesmkapqb.html

Ruby: items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtcniicigg.html

C#:   string.Join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gtxhaamxqb.html

[E09] 去除所有空白字符
来源：http://dali.haohaochexian.top/Article/details/gtzodjpjth.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.svipenyu.cn/Article/details/gtxqkplczb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hywenlv.cn/Article/details/gtireqwzap.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gtthkijolx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gtzgwqxhju.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtnngodyld.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ydzc1.top/Article/details/gtdkmxgzkh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sweek.top/Article/details/gtgknkgkky.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gzhubu.top/Article/details/gtsffwdufy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwbnsnyv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtjkitkwml.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gttjuuwvgr.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtgcktdsrq.html

TS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxvtcjex.html

Java: String.format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtqgkcjkdc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtbegqaouf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtebobebxl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.andypj.xyz/Article/details/gtkwkzgazy.html

[E11] 反转字符串
来源：http://dali.ybcxt.top/Article/details/gtvytxuzir.html

Py:   s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gtguwshqvf.html

PHP:  strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gthkkwclqa.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcoampbpi.html

TS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtdgvatlhp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtonsfrkjn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyeqzzoi.html

Ruby: s.reverse
来源：http://dali.guannengcc.top/Article/details/gtwatmmksx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gthzvzbgvz.html

[E12] 统计某字符出现次数
来源：http://dali.jqgfzy.top/Article/details/gtnfgmywaa.html

Py:   s.count("a")
来源：http://dali.bjfxy.top/Article/details/gtxfppeohz.html

PHP:  substr_count($s, "a");
来源：http://dali.yuanzhike.top/Article/details/gtabqlbckc.html

JS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gtfnrvegtv.html

TS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gtwbfustto.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.vqdsnc.cn/Article/details/gtuvqpapwm.html

Go:   strings.Count(s, "a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdteehcri.html

Ruby: s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gtrpbbwrqz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.feifeiyinyue.top/Article/details/gtyjvqupoc.html

[E13] 逐字符遍历
来源：http://dali.kuanghao11.cn/Article/details/gtfonjxxnz.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258.top/Article/details/gtdneckmbx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cqqwz.cn/Article/details/gtjnkxadxe.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtgufsubxb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtinixjutr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtczhdnyeb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuukikfch.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258888.top/Article/details/gtlijwtubq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.bjfxy.top/Article/details/gtekzdwoqw.html

[E14] URL 编码与 Base64
来源：http://dali.haohaochexian.top/Article/details/gtmdlrvgjn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258.top/Article/details/gtmxqymftu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nwbrower.top/Article/details/gtmrhufvhr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yueranfly.top/Article/details/gtrrbxfdgd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtbvsevxbx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuanzx.com/Article/details/gtejdqgzif.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cashguo.top/Article/details/gtzzkizyhd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xinyue.icu/Article/details/gtzxiqctpx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sxryk.cn/Article/details/gtgayfwlwb.html

[E15] HTML 转义 / 反转义
来源：http://dali.cashguo.top/Article/details/gteoswmczk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xziqi.cn/Article/details/gtlnmoybsm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cqqwz.cn/Article/details/gtpubgzlly.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.316326.xyz/Article/details/gtkkheqopq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ybcxt.top/Article/details/gtfegihczm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gtkiiejcqh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gtdlrqnela.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ybcxt.top/Article/details/gtzcjsbyfp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj202588.top/Article/details/gtsftdtwiv.html

[E16] 数字千分位
来源：http://dali.sufxvd.cn/Article/details/gtxwqmcvwo.html

Py:   f"{1234567:,}"
来源：http://dali.birdmap.top/Article/details/gtvdcfxmud.html

PHP:  number_format(1234567);
来源：http://dali.xziqi.cn/Article/details/gtqrebzjzd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gtqgsgjcaw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhdyjnqd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenlongwang.top/Article/details/gttldqfvjf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gtygrurcws.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.svipenyu.cn/Article/details/gtgjsboisy.html

C#:   1234567.ToString("N0")
来源：http://dali.fengsongda.top/Article/details/gtjijegako.html

[E17] 首字母大写
来源：http://dali.pengpengdd.cyou/Article/details/gttotnkxoq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuetiantiany.cn/Article/details/gtxfpnlnwr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.quarkkingdee.top/Article/details/gtiwyolnqv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gtdphrpzsm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gtyyrjrgon.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gtjduzpimb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pycfn.com/Article/details/gtxsepxllp.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gtdxgzevqr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shangyingyoupin.top/Article/details/gtsfgxqsrv.html

[E18] 模板占位符替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtectejxqw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cucudq.cn/Article/details/gtddrkfysh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gtoawiebzk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtavvmdkto.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtphccuoyj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtzqcsdgvu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtjqjjlgpi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cashguo.top/Article/details/gtxaspbexk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gtfsozhsco.html

[E19] 多行文本按行拆分
来源：http://dali.hongshengwenyu.top/Article/details/gttdebdcnd.html

Py:   s.splitlines()
来源：http://dali.cucudq.cn/Article/details/gtcyhduran.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojflolsr.html

JS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gtglvkjnsd.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtkpmgamgi.html

Java: s.lines().toList()
来源：http://dali.316326.xyz/Article/details/gtkmupzngl.html

Go:   strings.Split(s, "\n")
来源：http://dali.hywenlv.cn/Article/details/gtkackupap.html

Ruby: s.lines
来源：http://dali.quarkkingdee.top/Article/details/gtlvlrljuo.html

C#:   s.Split('\n')
来源：http://dali.tanke756.top/Article/details/gtnkxuidkf.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gtlzkerxyw.html

Py:   if not s:
来源：http://dali.c1oappe.top/Article/details/gtmutqxfic.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xziqi.cn/Article/details/gtyqucqhyv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cdnleiting.top/Article/details/gtxokgdtac.html

TS:   if (s === "") {}
来源：http://dali.aizwys.cn/Article/details/gtfpremgrb.html

Java: if (s.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gtufyikbpu.html

Go:   if s == "" {}
来源：http://dali.chenlongwang.top/Article/details/gtzxgoluho.html

Ruby: if s.empty?
来源：http://dali.ivvv.top/Article/details/gttkgvelen.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtykqfmelq.html

[E21] 超长截断加省略号
来源：http://dali.ydzc1.top/Article/details/gtscmoetel.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhoulong.xyz/Article/details/gtkupklssz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtuqfrmsqh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtxqwctkwj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtvquthuyf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtujmwfkdx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjjixnbd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtbbonavmr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtdvlhzgor.html

[E22] 字节长度与字符长度
来源：http://dali.dashuyun.cn/Article/details/gtedmdgbnj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gtopeszmfg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtubgxvmwy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtqvkojvsu.html


<!-- 参考信息 -->