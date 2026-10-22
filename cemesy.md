代发 wailian999

[D15] 去重
来源：http://dali.ybcxt.top/Article/details/gtgvbhrykz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gtxxzdkpbd.html

PHP:  array_unique($arr);
来源：http://dali.snrcjt.cn/Article/details/gtencgtqiu.html

JS:   [...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gtmyqxippn.html

TS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtjzswcouz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuanzx.com/Article/details/gtednrkbrw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xziqi.cn/Article/details/gtpcxixjts.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gtelgkerau.html

C#:   list.Distinct().ToList()
来源：http://dali.andypj.xyz/Article/details/gtakueiztx.html

[D16] 求和与平均值
来源：http://dali.haohaochexian.top/Article/details/gtcolwqzca.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sweek.top/Article/details/gtapiseuoo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.iojbl.cn/Article/details/gtbsaeebjm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtfngfnjfk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtkhhwczdf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrestqfg.html

Go:   // 手写循环累加
来源：http://dali.xylfe.cn/Article/details/gtkjwoehuf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fzhhl.top/Article/details/gtppdbhhrt.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuxming.cn/Article/details/gtielpjqop.html

[D17] 最大值与最小值
来源：http://dali.jyoumei.cn/Article/details/gtabkmezxd.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlssarbra.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtaunfhhno.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ivvv.top/Article/details/gticzyubvo.html

TS:   Math.max(...arr);
来源：http://dali.zhoulong.xyz/Article/details/gtlejnotue.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxuanxn.top/Article/details/gtfmmaemgx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hfpthk.cn/Article/details/gtrrkmmyqq.html

Ruby: arr.max;  arr.min
来源：http://dali.chenjidiqi.icu/Article/details/gtizqwbtxw.html

C#:   list.Max();  list.Min()
来源：http://dali.zdqjudy.top/Article/details/gtzwkzgqiy.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gtgjojvntn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tanke756.top/Article/details/gtpqwcjztq.html

PHP:  array_merge(...$nested);
来源：http://dali.daxiang520.top/Article/details/gtzlcwiurv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daxiang520.top/Article/details/gtnmxvyxfb.html

TS:   nested.flat();
来源：http://dali.zycfv.cn/Article/details/gtkndvpjvi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj202588.top/Article/details/gtsiaihodv.html

Go:   // 手写双层循环
来源：http://dali.yvedp.cn/Article/details/gtapsglrnv.html

Ruby: nested.flatten
来源：http://dali.redwolf501.top/Article/details/gtxrfuyftf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukpwbykv.html

[D19] 按字段分组
来源：http://dali.cqqwz.cn/Article/details/gtlbzranex.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.9152youxi.cn/Article/details/gtdvneqbpa.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.0kj1m.cn/Article/details/gtanrabplf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.redwolf501.top/Article/details/gtrfsmrmqo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gtvtkusyzi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhongyouzk.top/Article/details/gtxckwqfmg.html

Go:   // 手写 map[string][]T
来源：http://dali.ivvv.top/Article/details/gtyvetyzet.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.andypj.xyz/Article/details/gtdosrwmat.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hfpthk.cn/Article/details/gtrnofwkxd.html

[D20] 统计每个元素出现次数
来源：http://dali.ehwqpu.com/Article/details/gtjntykdtf.html

Py:   Counter(arr)
来源：http://dali.nanxinkj.top/Article/details/gtdsiyzpip.html

PHP:  array_count_values($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtjzrqpntb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtdfzbziff.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtzwymmptq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.kuanghao11.cn/Article/details/gtlmssfmqt.html

Go:   // 手写 map[T]int
来源：http://dali.jqgfzy.top/Article/details/gticqqdwmh.html

Ruby: arr.tally
来源：http://dali.ybcxt.top/Article/details/gtzhbokxrx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fzhhl.top/Article/details/gtbsudpqsl.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnrquksp.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gtehzgmvtv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ehwqpu.com/Article/details/gtfvwsrota.html

JS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gtooueaoyg.html

TS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gtidgxziso.html

Java: list.contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteagcngun.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj202588.top/Article/details/gtlraoetpa.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtndhbpdsi.html

C#:   list.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtvfvjrrqn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xinyue.icu/Article/details/gtttagpaad.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhengqikj.top/Article/details/gtfykbbgae.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aizwys.cn/Article/details/gtchsfupbh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj202588.top/Article/details/gtepqpvvmn.html

TS:   [...arr];
来源：http://dali.xziqi.cn/Article/details/gtzmsfszil.html

Java: new ArrayList<>(list);
来源：http://dali.fzhhl.top/Article/details/gtyvyjzsqz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xylfe.cn/Article/details/gtnxlkxipt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigufen.top/Article/details/gtytligvvf.html

C#:   new List<int>(list);
来源：http://dali.sweek.top/Article/details/gtquvbniat.html

[D23] reduce 累积计算
来源：http://dali.chenlongwang.top/Article/details/gtijcnpcok.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jlsjyb.cn/Article/details/gttdcrvavi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shzxlz.cn/Article/details/gtdgadxmeu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gtovcmlnzr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppsiwdka.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jlsjyb.cn/Article/details/gtworomqum.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gtgbinxgxn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zycfv.cn/Article/details/gtvsxibgfj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.quarkkingdee.top/Article/details/gtgtmyzefl.html

[D24] 字典 / Map 基本操作
来源：http://dali.ydzc1.top/Article/details/gtyinbqogn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cqqwz.cn/Article/details/gtyzgchxgv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nwbrower.top/Article/details/gtjkakrqan.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuanzx.com/Article/details/gtptcydphu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtieqpenef.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.birdmap.top/Article/details/gtwiebsuia.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ppjwa.cn/Article/details/gtykriblth.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gtsibbduqz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daria6918.cn/Article/details/gtiedqjlcm.html

[D25] Set 集合去重与交并差
来源：http://dali.wangdashe.top/Article/details/gtnocywxnn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.redwolf501.top/Article/details/gtzawqkoia.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhixingplan.top/Article/details/gttljcvexr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuanzhike.top/Article/details/gtsfgdasix.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigufen.top/Article/details/gtpyhrsova.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gtsaraquzg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gtxzhywcer.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtklmopkjb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xylfe.cn/Article/details/gttabfxuwq.html

[D26] 数组转字符串
来源：http://dali.dashuyun.cn/Article/details/gtwlinmcma.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hfpthk.cn/Article/details/gtyankxyno.html

PHP:  implode(", ", $arr);
来源：http://dali.redwolf501.top/Article/details/gtbqoincku.html

JS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtthptfrlb.html

TS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtkjxlswbf.html

Java: String.join(", ", list)
来源：http://dali.ivvv.top/Article/details/gtbgglpdrb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj202588.top/Article/details/gtobaatveb.html

Ruby: arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtyvqxgceo.html

C#:   string.Join(", ", list)
来源：http://dali.meibo888.top/Article/details/gticofskpi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gttitasghs.html

E. 字符串处理
来源：http://dali.yueranfly.top/Article/details/gtobkgcqna.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtniltsqia.html

[E01] 拼接字符串
来源：http://dali.hammf.cn/Article/details/gtjwvbyofh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yonumen.top/Article/details/gtjytohwho.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pycfn.com/Article/details/gtudchxjab.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gtreeekomq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtrocmxudx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenlongwang.top/Article/details/gterxzhivm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenlongwang.top/Article/details/gtndjfgfsa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsbsxpzc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtqyilwosa.html

[E02] 重复字符串
来源：http://dali.0kj1m.cn/Article/details/gtcmaqdxuq.html

Py:   "ab" * 3
来源：http://dali.cheryme.top/Article/details/gtziyzgzeb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xinyue.icu/Article/details/gtfmiducqn.html

JS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtcudwqxcs.html

TS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtjtwxenyh.html

Java: "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gteoumzfta.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.bjfxy.top/Article/details/gtttkjrutc.html

Ruby: "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gtjiizsbuz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cdnleiting.top/Article/details/gtxebcfozt.html

[E03] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gthzoadsah.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zycfv.cn/Article/details/gtehglcjxe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtssqlfnwh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtvazvztkz.html

TS:   s.slice(1, 4)
来源：http://dali.ydzc1.top/Article/details/gthazpvziz.html

Java: s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gttzhetfia.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gtxdujmihd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.feifeiyinyue.top/Article/details/gtpzdyidhu.html

C#:   s.Substring(1, 3)
来源：http://dali.xinyue.icu/Article/details/gtkxnindpc.html

[E04] 查找子串位置
来源：http://dali.tanke756.top/Article/details/gtqxufdqgu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.vqdsnc.cn/Article/details/gtenngjpce.html

PHP:  strpos($s, "x");
来源：http://dali.fzhhl.top/Article/details/gttjgfcnlv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.haohaochexian.top/Article/details/gtduetkjhx.html

TS:   s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtpxfhpqcb.html

Java: s.indexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gthmwdreac.html

Go:   strings.Index(s, "x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglqzgotn.html

Ruby: s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gtwlslsygl.html

C#:   s.IndexOf("x")
来源：http://dali.shuidangran.top/Article/details/gtjnyfflne.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenlongwang.top/Article/details/gtqnjnmezk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.andypj.xyz/Article/details/gtaglbuqxg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuanzhike.top/Article/details/gtmzhfjamu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtsnenqoqb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangdashe.top/Article/details/gtqggkodga.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpoazxnoz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jyoumei.cn/Article/details/gtvimebuzd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hfpthk.cn/Article/details/gtzhjtzdqo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gttoakatyf.html

[E06] 替换子串
来源：http://dali.wangdashe.top/Article/details/gtrxjzkimh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtertbcdwl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.kuanghao11.cn/Article/details/gtkcefdppn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtcwqjcwwo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtjcelxexd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtkdilkmzv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.wangdashe.top/Article/details/gtpqscezdo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtpwwxvxhz.html

C#:   s.Replace("a", "b")
来源：http://dali.birdmap.top/Article/details/gtwxrrvlqc.html

[E07] 按分隔符拆分
来源：http://dali.nanxinkj.top/Article/details/gtffwwlmdy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zdqjudy.top/Article/details/gtgdrcxmdx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtnlsfsifp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlltlxmdp.html

TS:   s.split(",")
来源：http://dali.xziqi.cn/Article/details/gtwxcgqjmj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aibaodan.cn/Article/details/gtpwlvmpsm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.havefunace.top/Article/details/gtalcjrehh.html

Ruby: s.split(",");  s.split
来源：http://dali.tianlin.xyz/Article/details/gtsxutkebg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zycfv.cn/Article/details/gtxguekdew.html

[E08] 数组按分隔符合并
来源：http://dali.nanxinkj.top/Article/details/gteubdwqot.html

Py:   ",".join(items)
来源：http://dali.hfpthk.cn/Article/details/gtawikvcej.html

PHP:  implode(",", $items);
来源：http://dali.haohaochexian.top/Article/details/gtcrtyofpl.html

JS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gtdipokotf.html

TS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtezrzebap.html

Java: String.join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqtoxnqt.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgufenzy.top/Article/details/gtlqcrwtfj.html

Ruby: items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gtricxonok.html

C#:   string.Join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gtkqyctygd.html

[E09] 去除所有空白字符
来源：http://dali.hongshengwenyu.top/Article/details/gthrgnncad.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258.top/Article/details/gthugoowhq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigfzy.top/Article/details/gthmfpvfsr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtedkjpwwg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gthpuwlklb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.bjfxy.top/Article/details/gtcgseqntf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xylfe.cn/Article/details/gtnbiaukiu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jlsjyb.cn/Article/details/gtpggoxzme.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gthezlaqup.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gtuvraouul.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pycfn.com/Article/details/gtxqrbywto.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhengqikj.top/Article/details/gtzjcozplz.html

JS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtbxtnvgkd.html

TS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtarznmgfc.html

Java: String.format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtihwjsucp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtallcsnff.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnrhmpak.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.meibo888.top/Article/details/gttbnmtllp.html

[E11] 反转字符串
来源：http://dali.jiagoushi.top/Article/details/gtzeqgmjgl.html

Py:   s[::-1]
来源：http://dali.c1oappe.top/Article/details/gtlokssehl.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtmpzfzlzl.html

JS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtilfkxjxq.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtchjvvzau.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gthyfpwnem.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zycfv.cn/Article/details/gtirvlmxwp.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gtynuwutfh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkmhwyml.html

[E12] 统计某字符出现次数
来源：http://dali.hnxiangtu.top/Article/details/gtfkffszfl.html

Py:   s.count("a")
来源：http://dali.yueranfly.top/Article/details/gtnotnhjgf.html

PHP:  substr_count($s, "a");
来源：http://dali.shzxlz.cn/Article/details/gtnluhlqqv.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewvpquzp.html

TS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtymfzshuo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangdashe.top/Article/details/gterldlgde.html

Go:   strings.Count(s, "a")
来源：http://dali.xziqi.cn/Article/details/gtmlnvuccu.html

Ruby: s.count("a")
来源：http://dali.sweek.top/Article/details/gtiiwnqezv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tian-w.cn/Article/details/gtquavvqwv.html

[E13] 逐字符遍历
来源：http://dali.hammf.cn/Article/details/gtifkdwczf.html

Py:   for ch in s: print(ch)
来源：http://dali.yongpay.top/Article/details/gtznpkofsb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guowangkeji.top/Article/details/gtjvjuyuvr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtlnfyqmgy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtvbxwoqfs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.redwolf501.top/Article/details/gtletcebpz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dashuyun.cn/Article/details/gtekzfmasn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhixingplan.top/Article/details/gtnlusmlmr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnvyrews.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gtervxdjjz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxinkj.top/Article/details/gtnunwbqah.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.svipenyu.cn/Article/details/gtrdtjcrtj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gtetqvsgxb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dianchejie.cn/Article/details/gthlqmziix.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtnpjcdmjl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pengpengdd.cyou/Article/details/gtucckxzlq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jianghu66.top/Article/details/gtgmqkbwlz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtaumfvblf.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258888.top/Article/details/gtzjomzptn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxinkj.top/Article/details/gtteagvvfc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtwjvckcbf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxinkj.top/Article/details/gtkryfpqgn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtezokjyzh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jiagoushi.top/Article/details/gtydidwnrn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtgljsrphp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejoyobbs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenlongwang.top/Article/details/gtccqpvdkx.html

[E16] 数字千分位
来源：http://dali.tianlin.xyz/Article/details/gtbxdfvsln.html

Py:   f"{1234567:,}"
来源：http://dali.jianghu66.top/Article/details/gtrdhfkcnb.html

PHP:  number_format(1234567);
来源：http://dali.hongshengwenyu.top/Article/details/gthxmgytam.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtriwpdwcq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gtcjcucssp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nwbrower.top/Article/details/gtjscfomrs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jlsjyb.cn/Article/details/gtmafbygto.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.9152youxi.cn/Article/details/gtftdecyha.html

C#:   1234567.ToString("N0")
来源：http://dali.tianlin.xyz/Article/details/gtyyrjotmk.html

[E17] 首字母大写
来源：http://dali.chenzaomai.com/Article/details/gtydbcgplt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cqqwz.cn/Article/details/gtssnrfoki.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zdqjudy.top/Article/details/gtvbgfacds.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gtyujtkbzh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gtjnbbttej.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.kuanghao11.cn/Article/details/gtrvccskmx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cqqwz.cn/Article/details/gtkrhgizdt.html

Ruby: s.capitalize
来源：http://dali.xinyue.icu/Article/details/gtqdtwjgar.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gtpnycrolf.html

[E18] 模板占位符替换
来源：http://dali.ivvv.top/Article/details/gtvjgotnvi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sufxvd.cn/Article/details/gtzdnicaqf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.iojbl.cn/Article/details/gtfdumfivd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtpgglqimc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtznsobcjy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtrwkgbcsc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gteokgckkk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jianghu66.top/Article/details/gtibzlyzgt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sweek.top/Article/details/gtnwdsfeyg.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gthitqbced.html

Py:   s.splitlines()
来源：http://dali.daxiang520.top/Article/details/gtigktccyj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtrlmlwbur.html

JS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtvihlbqzw.html

TS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gtwxfzzgvd.html

Java: s.lines().toList()
来源：http://dali.smart0.xyz/Article/details/gtmmpkalte.html

Go:   strings.Split(s, "\n")
来源：http://dali.gogol.net.cn/Article/details/gtbpqndlly.html

Ruby: s.lines
来源：http://dali.guowangkeji.top/Article/details/gtjyiflxxm.html

C#:   s.Split('\n')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtankbvlsz.html

[E20] 判断字符串是否为空
来源：http://dali.hammf.cn/Article/details/gtgwcfinui.html

Py:   if not s:
来源：http://dali.jiagoushi.top/Article/details/gtsbrzypdw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aibaodan.cn/Article/details/gtjgysqyrp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zycfv.cn/Article/details/gtdfuwgesb.html

TS:   if (s === "") {}
来源：http://dali.9152youxi.cn/Article/details/gtnnruspcl.html

Java: if (s.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gtkulaevcw.html

Go:   if s == "" {}
来源：http://dali.zhixingplan.top/Article/details/gtkzlirbfk.html

Ruby: if s.empty?
来源：http://dali.quarkkingdee.top/Article/details/gtbyraaaje.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zdqjudy.top/Article/details/gtenovpscg.html

[E21] 超长截断加省略号
来源：http://dali.zhengqikj.top/Article/details/gtwtetaqqj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shzxlz.cn/Article/details/gtozqvkiom.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtvvzhuiaj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gttomtnknu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtobvfsync.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxaanfolz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.kuanghao11.cn/Article/details/gtwfmgbmbe.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtwkuvxccx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtaxfkrcxg.html


<!-- 参考信息 -->