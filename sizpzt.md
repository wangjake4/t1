代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.dianchejie.cn/Article/details/gtymiyfddw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtizsxeypr.html

TS:   Math.max(...arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtzeftnikq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258.top/Article/details/gtrrluhisu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shzxlz.cn/Article/details/gtdwcsmnol.html

Ruby: arr.max;  arr.min
来源：http://dali.yangfankeji.com/Article/details/gtggksntyh.html

C#:   list.Max();  list.Min()
来源：http://dali.shuidangran.top/Article/details/gtcvvbcexs.html

[D18] 扁平化嵌套数组
来源：http://dali.cashguo.top/Article/details/gtvobelugl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhoulong.xyz/Article/details/gtahwzybwj.html

PHP:  array_merge(...$nested);
来源：http://dali.bjfxy.top/Article/details/gtixeiqmlc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigufen.top/Article/details/gtktlvtajh.html

TS:   nested.flat();
来源：http://dali.redwolf501.top/Article/details/gtkugelzey.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guowangkeji.top/Article/details/gtznxxivkx.html

Go:   // 手写双层循环
来源：http://dali.9152youxi.cn/Article/details/gtapmifftf.html

Ruby: nested.flatten
来源：http://dali.jlsjyb.cn/Article/details/gtqlidhybv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtyvaeklle.html

[D19] 按字段分组
来源：http://dali.cucudq.cn/Article/details/gtbgsoohqt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtibpijjnn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xinyue.icu/Article/details/gtatyxnqgt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gotoacloud.top/Article/details/gtywzvetrk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.9152youxi.cn/Article/details/gtitvcpwxd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gtjffktlar.html

Go:   // 手写 map[string][]T
来源：http://dali.sufxvd.cn/Article/details/gtlgahzocv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj202588.top/Article/details/gtfosvmgoy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ehwqpu.com/Article/details/gtrgtjepon.html

[D20] 统计每个元素出现次数
来源：http://dali.c1oappe.top/Article/details/gtswyemmxm.html

Py:   Counter(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuffvzevc.html

PHP:  array_count_values($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtfrdsgrnm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gtgwombdfl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gtsijprpff.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cashguo.top/Article/details/gtohnpcnwn.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangtech.top/Article/details/gtiinbfqma.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gtqymufkub.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxinkj.top/Article/details/gtcoaoibok.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangtech.top/Article/details/gteseswric.html

Py:   x in arr
来源：http://dali.jqgfzy.top/Article/details/gtzocfeyng.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ybcxt.top/Article/details/gtiavtmbfq.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtvomsncdq.html

TS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtkcjyuqqi.html

Java: list.contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtslvewbyb.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdvlbywt.html

Ruby: arr.include?(x)
来源：http://dali.c1oappe.top/Article/details/gtwahmmows.html

C#:   list.Contains(x)
来源：http://dali.pycfn.com/Article/details/gtgigchxzi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangdashe.top/Article/details/gtcyggzqyh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecqgceme.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gtuxugkbwq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenzaomai.com/Article/details/gtwiyzvgpt.html

TS:   [...arr];
来源：http://dali.dianchejie.cn/Article/details/gtxcpxbbxi.html

Java: new ArrayList<>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtxphuphuf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.svipenyu.cn/Article/details/gtagztfspi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xinyue.icu/Article/details/gtorbiwoel.html

C#:   new List<int>(list);
来源：http://dali.aizwys.cn/Article/details/gtkgqnbudz.html

[D23] reduce 累积计算
来源：http://dali.nwbrower.top/Article/details/gtimpgzjab.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtfxzjzqbs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guannengcc.top/Article/details/gtlplmtxcy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gtwepuhtij.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gttyyljckg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.meibo888.top/Article/details/gtokrwvvrs.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtbnrxkxnn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinghuilouyu.cn/Article/details/gtnksoaovs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.9152youxi.cn/Article/details/gtvzhvgqfv.html

[D24] 字典 / Map 基本操作
来源：http://dali.ivvv.top/Article/details/gtvjbvmrpo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenlongwang.top/Article/details/gtjhwfamuz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jianghu66.top/Article/details/gtgjouvnhx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.meibo888.top/Article/details/gtkksvjrbw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtqbobgypw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tian-w.cn/Article/details/gtesigxakt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aizwys.cn/Article/details/gtxjvfcggj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xinyue.icu/Article/details/gtrtblvksp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zdqjudy.top/Article/details/gtdhrpliis.html

[D25] Set 集合去重与交并差
来源：http://dali.jianghu66.top/Article/details/gtewgailvi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyyqthxx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aizwys.cn/Article/details/gtzzihlheb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jiagoushi.top/Article/details/gtsqkpgmfb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gaohongyu789.top/Article/details/gtjkecpkbi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daria6918.cn/Article/details/gtucsbtwso.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hfpthk.cn/Article/details/gtaowftbpf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fengsongda.top/Article/details/gthtzaudvh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hnxiangtu.top/Article/details/gtipibpddw.html

[D26] 数组转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfqcpzjt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aibaodan.cn/Article/details/gtrhebqdmc.html

PHP:  implode(", ", $arr);
来源：http://dali.redwolf501.top/Article/details/gthrilxyqn.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtotpsgxgl.html

TS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtyykttlbk.html

Java: String.join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gtghtyajqs.html

Go:   strings.Join(strs, ", ")
来源：http://dali.birdmap.top/Article/details/gtoepvzqxd.html

Ruby: arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtmrnsyddp.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwphzjqyl.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtjsfnjuqv.html

E. 字符串处理
来源：http://dali.daria6918.cn/Article/details/gtesddilrm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtvtnyxvbv.html

[E01] 拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtdjdbvjxw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ehwqpu.com/Article/details/gtnwjebkkc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gthnncrvke.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gtpqyycalq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gtriegdqjn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gtujnthifh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gtbpfwxdoo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenzaomai.com/Article/details/gtvzqoqbfi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtapgbkxvo.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gtfnehklap.html

Py:   "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtsvcnfhid.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aibaodan.cn/Article/details/gtyzdpxnbt.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtegdgokcn.html

TS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtudwtvqlq.html

Java: "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtcrmymuea.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqeclnkgt.html

Ruby: "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtpopoemwb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gtelylvkit.html

[E03] 截取子串
来源：http://dali.ydzc1.top/Article/details/gtlrweontl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxbajmby.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtikflgjjz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtbhkmsjoz.html

TS:   s.slice(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtcppmiakk.html

Java: s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gtjtfmsvpt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258888.top/Article/details/gtjhxbazpc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgfzy.top/Article/details/gtpkuvyvdl.html

C#:   s.Substring(1, 3)
来源：http://dali.cashguo.top/Article/details/gtjahwqljp.html

[E04] 查找子串位置
来源：http://dali.xylfe.cn/Article/details/gtdrwthiun.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtrvlhgtvj.html

PHP:  strpos($s, "x");
来源：http://dali.yj202588.top/Article/details/gtvhmoutnj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sufxvd.cn/Article/details/gtusrhrowz.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtjuujvyge.html

Java: s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtgoafiban.html

Go:   strings.Index(s, "x")
来源：http://dali.fengsongda.top/Article/details/gtcbnoznuf.html

Ruby: s.index("x")
来源：http://dali.bjfxy.top/Article/details/gtwmdzscrv.html

C#:   s.IndexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtlwappcfw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.bjfxy.top/Article/details/gtjjbmoiek.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aibaodan.cn/Article/details/gthvrcylsn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.andypj.xyz/Article/details/gtpiknzzff.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtqyhbwhty.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.havefunace.top/Article/details/gtlbykyeax.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtjbxmazgt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jianghu66.top/Article/details/gtgpcoroji.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.snrcjt.cn/Article/details/gtetzogclv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yongpay.top/Article/details/gtptwghepf.html

[E06] 替换子串
来源：http://dali.wangdashe.top/Article/details/gtglfcodot.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtdulokepb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hammf.cn/Article/details/gtynafjrqo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtszvfhhyu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtbffqdyop.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtgoamvmwr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtsfmblvtl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tanke756.top/Article/details/gtfavopenk.html

C#:   s.Replace("a", "b")
来源：http://dali.pycfn.com/Article/details/gttjcfoknq.html

[E07] 按分隔符拆分
来源：http://dali.aibaodan.cn/Article/details/gtdzfebnds.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shuidangran.top/Article/details/gtkusfowzm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sweek.top/Article/details/gtxqvokcii.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gaohongyu789.top/Article/details/gtbbjpdtoq.html

TS:   s.split(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxldobngi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.snrcjt.cn/Article/details/gtavxrkcak.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jiagoushi.top/Article/details/gtwauuswoo.html

Ruby: s.split(",");  s.split
来源：http://dali.wangshuangyany.cn/Article/details/gtzcykjkib.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.9152youxi.cn/Article/details/gtwdrvkuwx.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258888.top/Article/details/gtgzwafcwf.html

Py:   ",".join(items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbhmusmd.html

PHP:  implode(",", $items);
来源：http://dali.pengpengdd.cyou/Article/details/gthiwwzqyq.html

JS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gtsgbfvxpt.html

TS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gtgsykcnja.html

Java: String.join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gtrpptbvws.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gtyqruunia.html

Ruby: items.join(",")
来源：http://dali.hammf.cn/Article/details/gtyetidybq.html

C#:   string.Join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtbetnbdec.html

[E09] 去除所有空白字符
来源：http://dali.redwolf501.top/Article/details/gtoboyipok.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fzhhl.top/Article/details/gtpsjhtofk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gtkcamepil.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoayngxmz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gtysaezjtj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sxryk.cn/Article/details/gtzvfomaus.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zdqjudy.top/Article/details/gtdvwyypes.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tian-w.cn/Article/details/gtnwmrjpdm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gtjuecjdxu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.9152youxi.cn/Article/details/gtfacfkyxf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.316326.xyz/Article/details/gtptxsjion.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258888.top/Article/details/gtodqdprkx.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsoyoxbd.html

TS:   "7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtbunfaerd.html

Java: String.format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gtdzldcgvj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtptzxjmqn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtkobzcdub.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.feifeiyinyue.top/Article/details/gtonywltmy.html

[E11] 反转字符串
来源：http://dali.zycfv.cn/Article/details/gtevwbrayw.html

Py:   s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtyfgkollm.html

PHP:  strrev($s);
来源：http://dali.xuanzx.com/Article/details/gtawlsvywg.html

JS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtooeusdhk.html

TS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtarvnltft.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtyhrdcwmg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guowangkeji.top/Article/details/gtonxdmvmq.html

Ruby: s.reverse
来源：http://dali.nanxinkj.top/Article/details/gtgbzxnkrw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gtlaupcbbi.html

[E12] 统计某字符出现次数
来源：http://dali.yangfankeji.com/Article/details/gttmekszoo.html

Py:   s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtspcvsujt.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gtqlbyoekl.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtwvqonveq.html

TS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gtggjkakkn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gtabzkqhqo.html

Go:   strings.Count(s, "a")
来源：http://dali.jianghu66.top/Article/details/gtravfvazm.html

Ruby: s.count("a")
来源：http://dali.nwbrower.top/Article/details/gtruzpvbtc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhiwuduotai.top/Article/details/gtnkppmiow.html

[E13] 逐字符遍历
来源：http://dali.zycfv.cn/Article/details/gterfqzcwm.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgufenzy.top/Article/details/gtspohvvfq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fengsongda.top/Article/details/gtwejipgrp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtqbiifepu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtxdnuexwj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtlzsrysgp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tian-w.cn/Article/details/gtqduyqrkb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fzhhl.top/Article/details/gttdqafspw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtawdvsurr.html

[E14] URL 编码与 Base64
来源：http://dali.jianghu66.top/Article/details/gtyynzxeep.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cashguo.top/Article/details/gtewiuhidi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtmcmcjvdt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sweek.top/Article/details/gtovgbnjxw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gteoinaecm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hammf.cn/Article/details/gtwjyvhdui.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jianghu66.top/Article/details/gtjhylfzsf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gtemdbswce.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258888.top/Article/details/gtrtbjctnk.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gtownodxay.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.kuanghao11.cn/Article/details/gtgwgzyjid.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ehwqpu.com/Article/details/gtpysplown.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtdxvdrkrf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtezjirilh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.redwolf501.top/Article/details/gtjuxxtias.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shzxlz.cn/Article/details/gtibywngcb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyntuwsu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgfzy.top/Article/details/gtzrrpnpci.html

[E16] 数字千分位
来源：http://dali.fzhhl.top/Article/details/gthdwohegm.html

Py:   f"{1234567:,}"
来源：http://dali.yanxiufei.cn/Article/details/gtuojvlghg.html

PHP:  number_format(1234567);
来源：http://dali.sxryk.cn/Article/details/gtlppjhtht.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gtcfrvgjce.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtthfaleqz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gtafynhkyv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tian-w.cn/Article/details/gtvjbdrjnn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumakqsft.html

C#:   1234567.ToString("N0")
来源：http://dali.yuxming.cn/Article/details/gtwcxxjgcs.html

[E17] 首字母大写
来源：http://dali.gaohongyu789.top/Article/details/gtsakmqbus.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenjidiqi.icu/Article/details/gtrjjfanru.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sweek.top/Article/details/gtmtewtznx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtlbjjmufz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtpncfhdin.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangdashe.top/Article/details/gtrrvxycfl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtaaozwymz.html

Ruby: s.capitalize
来源：http://dali.wangdashe.top/Article/details/gtgybjwpvl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jyoumei.cn/Article/details/gtdhgwnoxw.html

[E18] 模板占位符替换
来源：http://dali.meibo888.top/Article/details/gtioxaxewa.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sufxvd.cn/Article/details/gtujrtdswh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.snrcjt.cn/Article/details/gtkjjqkwcj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtbiovyrmt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtqizmksnv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtyahxrvlo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrumaqlv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hongshengwenyu.top/Article/details/gtauyuoelz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.9152youxi.cn/Article/details/gtrlhsyypm.html

[E19] 多行文本按行拆分
来源：http://dali.hnqzz.top/Article/details/gtadcudhfv.html

Py:   s.splitlines()
来源：http://dali.yueranfly.top/Article/details/gtoshkvenc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtkoimhphp.html

JS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gtrqarvotd.html

TS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtrgmqcfml.html

Java: s.lines().toList()
来源：http://dali.yvedp.cn/Article/details/gtugngnule.html

Go:   strings.Split(s, "\n")
来源：http://dali.feifeiyinyue.top/Article/details/gttgizuqix.html

Ruby: s.lines
来源：http://dali.xuetiantiany.cn/Article/details/gtctsoenwt.html

C#:   s.Split('\n')
来源：http://dali.sxryk.cn/Article/details/gtjzgfxlio.html

[E20] 判断字符串是否为空
来源：http://dali.yuxming.cn/Article/details/gthrzfrcex.html

Py:   if not s:
来源：http://dali.zhixingplan.top/Article/details/gttuvqfdbb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tanke756.top/Article/details/gtxbojgylp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258888.top/Article/details/gtwqghokix.html

TS:   if (s === "") {}
来源：http://dali.cqqwz.cn/Article/details/gtljqtfvzr.html

Java: if (s.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gteyxdjrux.html

Go:   if s == "" {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvyenwqip.html

Ruby: if s.empty?
来源：http://dali.wangdashe.top/Article/details/gtdymceqvq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtimymdrvw.html

[E21] 超长截断加省略号
来源：http://dali.fzhhl.top/Article/details/gtquxcgjpq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhoulong.xyz/Article/details/gtdzuvqhxk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtlwtzvbkh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gttvftrfgt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtpwmuswqt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtnnibftkt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.iojbl.cn/Article/details/gtdyraobjz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gteyytsqej.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtydplhzpb.html

[E22] 字节长度与字符长度
来源：http://dali.hammf.cn/Article/details/gtnrwnhipc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sxryk.cn/Article/details/gtzwmeqcmk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtijckklar.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gthhnwwpbx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gtgvwpyjtw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtkrznvgve.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sufxvd.cn/Article/details/gtomdodxbl.html

Ruby: s.bytesize;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtangbqsrh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtoaustpqi.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtksfpdzci.html

F. 文件与目录
来源：http://dali.tanke756.top/Article/details/gtfwuuyfxn.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtfyspcbvv.html

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gtshuptgit.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gotoacloud.top/Article/details/gtmwkqohqs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtfhwczeqe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.meibo888.top/Article/details/gtlwujswov.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj202588.top/Article/details/gtjmmvuthk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjcfyzpw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsnwxqfw.html

Ruby: File.read("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtbdpxqzfp.html


<!-- 参考信息 -->