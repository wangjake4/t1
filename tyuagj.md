代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.gotoacloud.top/Article/details/gtnmrmedzf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcotztvaa.html

TS:   Math.max(...arr);
来源：http://dali.pycfn.com/Article/details/gtekxndkkk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sweek.top/Article/details/gtznbmuvbu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuanzx.com/Article/details/gtdbpyroxt.html

Ruby: arr.max;  arr.min
来源：http://dali.xuanzx.com/Article/details/gtlbuuqraj.html

C#:   list.Max();  list.Min()
来源：http://dali.hnqzz.top/Article/details/gtoexwlpwv.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigufen.top/Article/details/gtexmvllko.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shzxlz.cn/Article/details/gtzmktjrto.html

PHP:  array_merge(...$nested);
来源：http://dali.cucudq.cn/Article/details/gtnwyjqsxj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.haohaochexian.top/Article/details/gtflppiskx.html

TS:   nested.flat();
来源：http://dali.cucudq.cn/Article/details/gtkaoyyyfq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtocwoucrb.html

Go:   // 手写双层循环
来源：http://dali.yj202588.top/Article/details/gtlzccdqfn.html

Ruby: nested.flatten
来源：http://dali.xinyue.icu/Article/details/gtuutbyhjx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtfdpseuyn.html

[D19] 按字段分组
来源：http://dali.jinqigfzy.top/Article/details/gtlykuuwrf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ehwqpu.com/Article/details/gtpiedaqiw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.kuanghao11.cn/Article/details/gtdkrgtzvf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jqgufenzy.top/Article/details/gtjsdocrkx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenjidiqi.icu/Article/details/gterwzprbe.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.mhx1999.top/Article/details/gtdzqzqumg.html

Go:   // 手写 map[string][]T
来源：http://dali.yangfankeji.com/Article/details/gtvaqbppmz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrdokgjc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ivvv.top/Article/details/gtgvjpiyov.html

[D20] 统计每个元素出现次数
来源：http://dali.aizwys.cn/Article/details/gtzlaspwgg.html

Py:   Counter(arr)
来源：http://dali.chenlongwang.top/Article/details/gtdkkoovgr.html

PHP:  array_count_values($arr);
来源：http://dali.jiagoushi.top/Article/details/gtxxhblanw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gtncellvaq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gtoldudqfw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxuanxn.top/Article/details/gtxnotlyex.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gtvkjvbfpy.html

Ruby: arr.tally
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpeynpmn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fengsongda.top/Article/details/gtoanzapgz.html

[D21] 判断是否包含某元素
来源：http://dali.sweek.top/Article/details/gteqhbsmgf.html

Py:   x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gtbcudthfw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydqkztyb.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjohflhac.html

TS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtfxwsistg.html

Java: list.contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtuuxvrqeq.html

Go:   slices.Contains(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtodbeyjuf.html

Ruby: arr.include?(x)
来源：http://dali.ivvv.top/Article/details/gtrtqopydu.html

C#:   list.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtxjclorck.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gtxrvzjgov.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcjmciqw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jlsjyb.cn/Article/details/gtgigoruru.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aibaodan.cn/Article/details/gtuilqpojh.html

TS:   [...arr];
来源：http://dali.xylfe.cn/Article/details/gtihybtdul.html

Java: new ArrayList<>(list);
来源：http://dali.ppjwa.cn/Article/details/gtsnfltvgy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gtuzetmnhy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.vqdsnc.cn/Article/details/gthnqwlaas.html

C#:   new List<int>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gteumokaxt.html

[D23] reduce 累积计算
来源：http://dali.sweek.top/Article/details/gtkecalzmh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtwaqhnglm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cucudq.cn/Article/details/gtfqofmbou.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtdhlhnsul.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gtygmwgwkk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jlsjyb.cn/Article/details/gtdktdievx.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gtmildnkag.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhengqikj.top/Article/details/gtmcglvggb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gtizkodnni.html

[D24] 字典 / Map 基本操作
来源：http://dali.nwbrower.top/Article/details/gtbtpsbbau.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xinyue.icu/Article/details/gthxdlimrb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgfzy.top/Article/details/gthevpuakt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ybcxt.top/Article/details/gtzcypticx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yonumen.top/Article/details/gtbfwvvxap.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhixingplan.top/Article/details/gtgtavppyy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258888.top/Article/details/gtlbsvoivo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuanzx.com/Article/details/gtqwdaggrx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.andypj.xyz/Article/details/gtueqmsqel.html

[D25] Set 集合去重与交并差
来源：http://dali.guannengcc.top/Article/details/gtfhznnege.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhiwuduotai.top/Article/details/gthsmuajhm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnqzz.top/Article/details/gtyefalhmz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxuanxn.top/Article/details/gtkshqkxml.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhoulong.xyz/Article/details/gtbiafqxwq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtszlgyumn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tianlin.xyz/Article/details/gtqezjcjnl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aibaodan.cn/Article/details/gtzxarinba.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtszbzokxf.html

[D26] 数组转字符串
来源：http://dali.yj20258888.top/Article/details/gtltpinmir.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aibaodan.cn/Article/details/gtndljpjvn.html

PHP:  implode(", ", $arr);
来源：http://dali.ybcxt.top/Article/details/gtnptoybmz.html

JS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtzckmrhkx.html

TS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtvquowgnv.html

Java: String.join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gtsdigvttb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.316326.xyz/Article/details/gthkewiwtf.html

Ruby: arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtxgseardk.html

C#:   string.Join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gtqpdxeoim.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtwecenpqe.html

E. 字符串处理
来源：http://dali.nwbrower.top/Article/details/gtnppommjr.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtgznsqjat.html

[E01] 拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtfdprpgpa.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aizwys.cn/Article/details/gtmrimocdq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhzdkzju.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gtjqcsqtek.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gtpwekukny.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daxiang520.top/Article/details/gtpzqpoyes.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.c1oappe.top/Article/details/gtwlnluhwo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shzxlz.cn/Article/details/gtpbwqfmjt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtfvyjotsv.html

[E02] 重复字符串
来源：http://dali.c1oappe.top/Article/details/gtnyznepvh.html

Py:   "ab" * 3
来源：http://dali.pycfn.com/Article/details/gtnqeknoph.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sweek.top/Article/details/gthztvnnzt.html

JS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtogvvlnho.html

TS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtbwserdic.html

Java: "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtjbnvrcur.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.vqdsnc.cn/Article/details/gtnxhpnvxx.html

Ruby: "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtikmiervk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gtfovcjfxg.html

[E03] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gtdeukfyyj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnxiangtu.top/Article/details/gtrxdufehm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtrcnkqvlz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gtukcbcbxa.html

TS:   s.slice(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtmfggmahi.html

Java: s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gtffpinlll.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenzaomai.com/Article/details/gtjufsqzqn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cucudq.cn/Article/details/gttciwlrlu.html

C#:   s.Substring(1, 3)
来源：http://dali.tian-w.cn/Article/details/gtqczrmeqt.html

[E04] 查找子串位置
来源：http://dali.aizwys.cn/Article/details/gtzwsiouvn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gtbkoguvon.html

PHP:  strpos($s, "x");
来源：http://dali.cheryme.top/Article/details/gtusoqjrpd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxuanxn.top/Article/details/gtbhmnenum.html

TS:   s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gtstgzitwd.html

Java: s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtjpchcnub.html

Go:   strings.Index(s, "x")
来源：http://dali.ydzc1.top/Article/details/gtivjkmswi.html

Ruby: s.index("x")
来源：http://dali.yonumen.top/Article/details/gtuwdfnijv.html

C#:   s.IndexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtixjybomv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gzhubu.top/Article/details/gtocyetumy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aibaodan.cn/Article/details/gthqgwimwd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgfzy.top/Article/details/gtvwhesksz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtygjofloa.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shuidangran.top/Article/details/gtaxfjboyy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtcyojehxw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ivvv.top/Article/details/gtynonerjp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xylfe.cn/Article/details/gtothxnpky.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtfdiszzew.html

[E06] 替换子串
来源：http://dali.sufxvd.cn/Article/details/gtnahkmifz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gtozlvxqev.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tianlin.xyz/Article/details/gticokhugz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gthqbkihqu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtbdlmqciw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gttrnrfyvz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtnmcfnhwr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtenpvojdj.html

C#:   s.Replace("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtbxdwpbwh.html

[E07] 按分隔符拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtbigvkxbr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tanke756.top/Article/details/gthrfzxhoz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yonumen.top/Article/details/gtjynpkrjq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yanxiufei.cn/Article/details/gtwxboiwwn.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gtmfbjkiru.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuxming.cn/Article/details/gtbjmjzczp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnxiangtu.top/Article/details/gthaicbafw.html

Ruby: s.split(",");  s.split
来源：http://dali.daxiang520.top/Article/details/gttdllpnfy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhengqikj.top/Article/details/gtdigertcl.html

[E08] 数组按分隔符合并
来源：http://dali.tanke756.top/Article/details/gtdyoxrlhd.html

Py:   ",".join(items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtifpkibvf.html

PHP:  implode(",", $items);
来源：http://dali.yanxiufei.cn/Article/details/gttxdyihxi.html

JS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtnoeilaen.html

TS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtxkocgtzs.html

Java: String.join(",", items)
来源：http://dali.ydzc1.top/Article/details/gtliwcrxak.html

Go:   strings.Join(items, ",")
来源：http://dali.gotoacloud.top/Article/details/gtnkaiftwn.html

Ruby: items.join(",")
来源：http://dali.hammf.cn/Article/details/gtokwyqhsj.html

C#:   string.Join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gtejlqmqct.html

[E09] 去除所有空白字符
来源：http://dali.hysaishi.cn/Article/details/gtfxdovtqg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guowangkeji.top/Article/details/gtsxiuxrzp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ivvv.top/Article/details/gtqjnqfsjb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtxehkiocs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gtnhipbaok.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovcevouc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ydzc1.top/Article/details/gtdjqimlcw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258888.top/Article/details/gtwijtkwtl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gtznyxudde.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hongshengwenyu.top/Article/details/gtkezmxvzw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtyjhqzfng.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daxiang520.top/Article/details/gtzlnyxusq.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtfmuaytnh.html

TS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtiitcutdo.html

Java: String.format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtvqponmqn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtskqseekq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtbihllehi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yvedp.cn/Article/details/gtlrjistry.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gtxmiybcwr.html

Py:   s[::-1]
来源：http://dali.fengsongda.top/Article/details/gtrcvpyyvq.html

PHP:  strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gtgebnzfev.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdnjrsyu.html

TS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtxmmotgew.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yueranfly.top/Article/details/gtvgzgsyxr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.haohaochexian.top/Article/details/gtvcnvmylt.html

Ruby: s.reverse
来源：http://dali.jqgfzy.top/Article/details/gtxdnvkhhl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gtfyhrnjzj.html

[E12] 统计某字符出现次数
来源：http://dali.guannengcc.top/Article/details/gtwbhyaawd.html

Py:   s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtqfaruxcz.html

PHP:  substr_count($s, "a");
来源：http://dali.ehwqpu.com/Article/details/gthlmhiens.html

JS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gtcgfqcaqf.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtqmfkusrq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zycfv.cn/Article/details/gtydgixava.html

Go:   strings.Count(s, "a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpthpammm.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtbuhhclgo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shangyingyoupin.top/Article/details/gtmdfpexdm.html

[E13] 逐字符遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmizpskg.html

Py:   for ch in s: print(ch)
来源：http://dali.snrcjt.cn/Article/details/gttvdraqwx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwpzwdul.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gthyoliuxq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtlabbbqvk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guannengcc.top/Article/details/gtckjnjzaj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fzhhl.top/Article/details/gtpuwoxflu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yongpay.top/Article/details/gtfcvkexan.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtavixnqgh.html

[E14] URL 编码与 Base64
来源：http://dali.gogol.net.cn/Article/details/gtvhbjbbli.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gtrjcpdhzh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hfpthk.cn/Article/details/gturmmpjkw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jyoumei.cn/Article/details/gtdajrzime.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hysaishi.cn/Article/details/gtsczvgnna.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpaxvaxd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.iojbl.cn/Article/details/gtbncaqocx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pengpengdd.cyou/Article/details/gtaffwtdzp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtdqvkjrek.html

[E15] HTML 转义 / 反转义
来源：http://dali.yueranfly.top/Article/details/gtifjpbjbo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258888.top/Article/details/gtbngypkgy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenlongwang.top/Article/details/gtlefkkoac.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxihcvzpa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sysykeji.top/Article/details/gtnaltrcbc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aibaodan.cn/Article/details/gtboabpivd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.meibo888.top/Article/details/gtrlqhhbnj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fzhhl.top/Article/details/gtfqgggzkj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sweek.top/Article/details/gtbwqvtefb.html

[E16] 数字千分位
来源：http://dali.cqqwz.cn/Article/details/gtcxptzyvj.html

Py:   f"{1234567:,}"
来源：http://dali.hnqzz.top/Article/details/gthawdzpbn.html

PHP:  number_format(1234567);
来源：http://dali.nanxuanxn.top/Article/details/gtghtlinms.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtvrbmmygy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtvgtojjsa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gtmdinlgbb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jiagoushi.top/Article/details/gttqmfzerp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gzhubu.top/Article/details/gtvzkbbuht.html

C#:   1234567.ToString("N0")
来源：http://dali.zdqjudy.top/Article/details/gtsdtucdep.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gtrotwfabr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gtbjfdhymi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgfzy.top/Article/details/gtwlvyznzq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yueranfly.top/Article/details/gtvmzwgvio.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gthwfuwzrh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxuanxn.top/Article/details/gtgsnhjtja.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sweek.top/Article/details/gtslbnbnec.html

Ruby: s.capitalize
来源：http://dali.yuanzhike.top/Article/details/gtqarbqexb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxuanxn.top/Article/details/gtoamxcisx.html

[E18] 模板占位符替换
来源：http://dali.havefunace.top/Article/details/gtbljxehbb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.mhx1999.top/Article/details/gtifkxnldm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xinyue.icu/Article/details/gtuqiamvdq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtuvdbbwqz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtsqutvpku.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtsvrxqtxx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gteelpdeyb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hongshengwenyu.top/Article/details/gtdiwssqwl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258888.top/Article/details/gtriygaqod.html

[E19] 多行文本按行拆分
来源：http://dali.nwbrower.top/Article/details/gtvameaqvj.html

Py:   s.splitlines()
来源：http://dali.jinqigufen.top/Article/details/gtanuciljq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtwgpyhrkr.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtdagokjlr.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gtvnvfmeew.html

Java: s.lines().toList()
来源：http://dali.xuanzx.com/Article/details/gtakpuuzvp.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj202588.top/Article/details/gtdxzwxhne.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gthxfghbhj.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtuzxuzqpm.html

[E20] 判断字符串是否为空
来源：http://dali.guowangkeji.top/Article/details/gtoayftizp.html

Py:   if not s:
来源：http://dali.aizwys.cn/Article/details/gtcocudurk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgfzy.top/Article/details/gtujwlrkmu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cdnleiting.top/Article/details/gtrcwdlazw.html

TS:   if (s === "") {}
来源：http://dali.cdnleiting.top/Article/details/gtachvhimo.html

Java: if (s.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gtylqfzvsz.html

Go:   if s == "" {}
来源：http://dali.pengpengdd.cyou/Article/details/gttvpufyoz.html

Ruby: if s.empty?
来源：http://dali.sysykeji.top/Article/details/gtkpdotdht.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.0kj1m.cn/Article/details/gtqhwqgtvk.html

[E21] 超长截断加省略号
来源：http://dali.jqgufenzy.top/Article/details/gtfewbhlkl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gtfdgoctgk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtjfwgjeqs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtpwnymyjz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtnjtxadcv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgtidvos.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gttjfraqbg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtdqflaqdt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtfglokswa.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gtairbuzpi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dianchejie.cn/Article/details/gtzqtswjem.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtitlvudus.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtxfuzuask.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtekplvray.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.havefunace.top/Article/details/gtaafwteir.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenjidiqi.icu/Article/details/gtdsuicrjq.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gtoikwoijb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.bjfxy.top/Article/details/gtovzrrtqu.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtpuubelcg.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gtlfvmztak.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtknffnjvh.html

[F01] 读取整个文件
来源：http://dali.tian-w.cn/Article/details/gtpdovmqbd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nwbrower.top/Article/details/gtfleziidv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtclmlherk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnxiangtu.top/Article/details/gtrkmiizya.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtlrmbvumf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtjdmndmfl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxuanxn.top/Article/details/gtexofqtrj.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gttwnqoqhb.html


<!-- 参考信息 -->