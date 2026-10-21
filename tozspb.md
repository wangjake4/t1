代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.xziqi.cn/Article/details/gtmgawtrhd.html

[D16] 求和与平均值
来源：http://dali.zhiwuduotai.top/Article/details/gtmmglergh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmozxpslu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtgxraczbf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gtihbxwdtp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gtttfyxowo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhongyouzk.top/Article/details/gtatdrrgfz.html

Go:   // 手写循环累加
来源：http://dali.xziqi.cn/Article/details/gtbipwtbzx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tanke756.top/Article/details/gtxawbvslv.html

C#:   list.Sum();  list.Average()
来源：http://dali.snrcjt.cn/Article/details/gtlefzqgpr.html

[D17] 最大值与最小值
来源：http://dali.iojbl.cn/Article/details/gtrwtuergr.html

Py:   max(arr);  min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtfvythyrf.html

PHP:  max($arr);  min($arr);
来源：http://dali.jianghu66.top/Article/details/gtdivayeeg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtlskwkfzz.html

TS:   Math.max(...arr);
来源：http://dali.jlsjyb.cn/Article/details/gtqqnyxsmb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sxryk.cn/Article/details/gtahmficdj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwesbcwws.html

Ruby: arr.max;  arr.min
来源：http://dali.cashguo.top/Article/details/gtxrexvqct.html

C#:   list.Max();  list.Min()
来源：http://dali.yanxiufei.cn/Article/details/gtnuobnach.html

[D18] 扁平化嵌套数组
来源：http://dali.xylfe.cn/Article/details/gtpywfvfpk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhongyouzk.top/Article/details/gtipnbxbyr.html

PHP:  array_merge(...$nested);
来源：http://dali.nwbrower.top/Article/details/gtodosmbkw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhengqikj.top/Article/details/gtnuxipwaq.html

TS:   nested.flat();
来源：http://dali.hnqzz.top/Article/details/gtqijbvtmh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nwbrower.top/Article/details/gtxiiospzf.html

Go:   // 手写双层循环
来源：http://dali.zhixingplan.top/Article/details/gtmpldzgmh.html

Ruby: nested.flatten
来源：http://dali.xinyue.icu/Article/details/gthureravv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtgaqvkfjh.html

[D19] 按字段分组
来源：http://dali.sufxvd.cn/Article/details/gtkltvccxf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aizwys.cn/Article/details/gtplkbiupm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gaohongyu789.top/Article/details/gtktvjradc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xylfe.cn/Article/details/gtvslacpwe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gtaguqygmk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yvedp.cn/Article/details/gttweimqzh.html

Go:   // 手写 map[string][]T
来源：http://dali.chenlongwang.top/Article/details/gtitwypxlf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cucudq.cn/Article/details/gtiwzqqdsv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigfzy.top/Article/details/gttnqoskex.html

[D20] 统计每个元素出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gtkmovottt.html

Py:   Counter(arr)
来源：http://dali.zhengqikj.top/Article/details/gtaghyrhrb.html

PHP:  array_count_values($arr);
来源：http://dali.9152youxi.cn/Article/details/gtmllvagsv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gtordcbcpn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gtjfcabcqs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.meibo888.top/Article/details/gtovgzhbqf.html

Go:   // 手写 map[T]int
来源：http://dali.jianghu66.top/Article/details/gtottwraij.html

Ruby: arr.tally
来源：http://dali.fengsongda.top/Article/details/gtodsqfuue.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigufen.top/Article/details/gtpytciuls.html

[D21] 判断是否包含某元素
来源：http://dali.xuetiantiany.cn/Article/details/gtylvtrpti.html

Py:   x in arr
来源：http://dali.cdnleiting.top/Article/details/gtpjdmjkgs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.quarkkingdee.top/Article/details/gtpobgjjdh.html

JS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gtenkbekan.html

TS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtqinlsgkt.html

Java: list.contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtsxasehof.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtjmnajfhz.html

Ruby: arr.include?(x)
来源：http://dali.xziqi.cn/Article/details/gtluqyqcob.html

C#:   list.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtaebebfke.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zdqjudy.top/Article/details/gtydwgxsqz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cdnleiting.top/Article/details/gtvxafminq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yvedp.cn/Article/details/gtorowwffj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gthgewupzd.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhdnever.html

Java: new ArrayList<>(list);
来源：http://dali.aibaodan.cn/Article/details/gtgecsftzf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbtfjqpo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cheryme.top/Article/details/gtoalnubuk.html

C#:   new List<int>(list);
来源：http://dali.mhx1999.top/Article/details/gtxjnsfocy.html

[D23] reduce 累积计算
来源：http://dali.hysaishi.cn/Article/details/gtwfzdjpin.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.haohaochexian.top/Article/details/gttlpikvws.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cdnleiting.top/Article/details/gtepwkmogy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gttwexydjd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gtbbvgavtg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ivvv.top/Article/details/gteieflycn.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gtkjmswwwg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daria6918.cn/Article/details/gtvcwnnypk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gtzmmvorjb.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuxming.cn/Article/details/gtooheutbn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhengqikj.top/Article/details/gtrkenools.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yvedp.cn/Article/details/gtcwbprtqv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jiagoushi.top/Article/details/gtodfejhra.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtugcxigio.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gtwarbxkwu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dianchejie.cn/Article/details/gtthjrtpxx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258.top/Article/details/gtdsvvzdmo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgufenzy.top/Article/details/gtkcgfdgag.html

[D25] Set 集合去重与交并差
来源：http://dali.aibaodan.cn/Article/details/gtmgqhuyrc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangtech.top/Article/details/gtstmanosn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangdashe.top/Article/details/gtghrwkwne.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.birdmap.top/Article/details/gtwavzcgij.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cqqwz.cn/Article/details/gtbdwrlkpq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xylfe.cn/Article/details/gthumqradj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gtnowjkfaq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dianchejie.cn/Article/details/gtkeozorla.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ybcxt.top/Article/details/gtdafgkvgk.html

[D26] 数组转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtatszxqnp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yonumen.top/Article/details/gtdhphhlkx.html

PHP:  implode(", ", $arr);
来源：http://dali.yonumen.top/Article/details/gtnthchltk.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxumyuwx.html

TS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtbyqfegwt.html

Java: String.join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gtwoaphibd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jianghu66.top/Article/details/gtaphvilmd.html

Ruby: arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtystmgvhq.html

C#:   string.Join(", ", list)
来源：http://dali.yj202588.top/Article/details/gtcqxknxws.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkbztmej.html

E. 字符串处理
来源：http://dali.zhixingplan.top/Article/details/gtogieiyvv.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtsiabvqff.html

[E01] 拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtkshiyaci.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yvedp.cn/Article/details/gtrhybzdsn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtkquffllh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyrlugxq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gtsiafpeqr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sufxvd.cn/Article/details/gtamvlgboq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daxiang520.top/Article/details/gtvdugyctx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gogol.net.cn/Article/details/gtzhumoydw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtzzfonutf.html

[E02] 重复字符串
来源：http://dali.gaohongyu789.top/Article/details/gtjrlhzmft.html

Py:   "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gtccpmrxyq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shzxlz.cn/Article/details/gtjiqgdhoi.html

JS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtyeocaiev.html

TS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtxqtjwqlx.html

Java: "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtdyonpdhp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fzhhl.top/Article/details/gtarbjobpx.html

Ruby: "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gtwyolguws.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hammf.cn/Article/details/gtwecqsaeh.html

[E03] 截取子串
来源：http://dali.iojbl.cn/Article/details/gthidokefq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pycfn.com/Article/details/gtiwxbpcwq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtdyoazleb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtsoeysvie.html

TS:   s.slice(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtivqurvbq.html

Java: s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gthfjxucgk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gtvajegpwk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuxming.cn/Article/details/gtubkgwylo.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258.top/Article/details/gtefrvbvap.html

[E04] 查找子串位置
来源：http://dali.pycfn.com/Article/details/gtjnybducg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtwsyvmahe.html

PHP:  strpos($s, "x");
来源：http://dali.xziqi.cn/Article/details/gtmraxjwmr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbotuijb.html

TS:   s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtyqaiwrrq.html

Java: s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gtdgzdbgky.html

Go:   strings.Index(s, "x")
来源：http://dali.chenjidiqi.icu/Article/details/gttmgbyldc.html

Ruby: s.index("x")
来源：http://dali.havefunace.top/Article/details/gtcvqgraac.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtrhpluttr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dianchejie.cn/Article/details/gtytqvsgbe.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtdiwzcrnv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntjgtjzz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtbtrvqxxn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cheryme.top/Article/details/gtfomunths.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokxubohu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gtuvlgmmnd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hfpthk.cn/Article/details/gtrvqvzjar.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtdyisdvkv.html

[E06] 替换子串
来源：http://dali.quarkkingdee.top/Article/details/gtgdjcumll.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gtcxwdxmfd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.c1oappe.top/Article/details/gtopzhzflg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtgnylnipz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtotpvsuss.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtsrebavee.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtfmutsevu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtgwawjkxd.html

C#:   s.Replace("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtbdbjhkkw.html

[E07] 按分隔符拆分
来源：http://dali.gzhubu.top/Article/details/gttemvymxo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fengsongda.top/Article/details/gteokbvjkq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gttjohewpl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.haohaochexian.top/Article/details/gtwrsczrmy.html

TS:   s.split(",")
来源：http://dali.yuanzhike.top/Article/details/gtpvrteeky.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cqqwz.cn/Article/details/gtcqlpxzql.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cqqwz.cn/Article/details/gttarycbxz.html

Ruby: s.split(",");  s.split
来源：http://dali.iojbl.cn/Article/details/gtnqxckkap.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gtiiwdvnun.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgantwwuy.html

Py:   ",".join(items)
来源：http://dali.c1oappe.top/Article/details/gtepjmjumg.html

PHP:  implode(",", $items);
来源：http://dali.yvedp.cn/Article/details/gtygnhucst.html

JS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtdearlwpa.html

TS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtcxzotztc.html

Java: String.join(",", items)
来源：http://dali.tanke756.top/Article/details/gtrgrvwljf.html

Go:   strings.Join(items, ",")
来源：http://dali.ydzc1.top/Article/details/gtegsmepjz.html

Ruby: items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtzocabxmw.html

C#:   string.Join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapzddrnt.html

[E09] 去除所有空白字符
来源：http://dali.zdqjudy.top/Article/details/gtezkipkep.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tianlin.xyz/Article/details/gtliewhqkz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hysaishi.cn/Article/details/gtueutnzbd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtrzpcxcak.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gtjmhmolcl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yonumen.top/Article/details/gtxinjmwwu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.snrcjt.cn/Article/details/gtdvmxetyl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gaohongyu789.top/Article/details/gtfpsmjbwo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xziqi.cn/Article/details/gtlovlrbke.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmupmjync.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtoqdghncs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gaohongyu789.top/Article/details/gtfxlxtjgs.html

JS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtfbpljbmw.html

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtyneffueg.html

Java: String.format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtvckbzbhl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtidccdrkz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gtbvojxnfg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guannengcc.top/Article/details/gtexfyyzqy.html

[E11] 反转字符串
来源：http://dali.0kj1m.cn/Article/details/gtqjknjnwz.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gtlfmtbcaf.html

PHP:  strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbwxljsc.html

JS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gttbyqfbhf.html

TS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtnwwqvcor.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthklsbyav.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtrwgloqmp.html

Ruby: s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtvokqkfhm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gttwvzwkhc.html

[E12] 统计某字符出现次数
来源：http://dali.aizwys.cn/Article/details/gtdbdgrfzd.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtrntogznr.html

PHP:  substr_count($s, "a");
来源：http://dali.andypj.xyz/Article/details/gtrpnsarjw.html

JS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtewdhkraf.html

TS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtnlnnijfr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tanke756.top/Article/details/gtjpaiavcx.html

Go:   strings.Count(s, "a")
来源：http://dali.chenjidiqi.icu/Article/details/gtmhfmucjb.html

Ruby: s.count("a")
来源：http://dali.andypj.xyz/Article/details/gtqbwhrmck.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shzxlz.cn/Article/details/gtofcljbws.html

[E13] 逐字符遍历
来源：http://dali.guannengcc.top/Article/details/gtjavxdxpz.html

Py:   for ch in s: print(ch)
来源：http://dali.aibaodan.cn/Article/details/gtbsdstegt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jianghu66.top/Article/details/gttkhegeff.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtdpoulrqb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtyhkyqvbo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnqzz.top/Article/details/gtssqvyigg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenlongwang.top/Article/details/gtcpfzlqen.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tanke756.top/Article/details/gtljywbwmz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfszlfekn.html

[E14] URL 编码与 Base64
来源：http://dali.meibo888.top/Article/details/gtsdxhcqbd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dianchejie.cn/Article/details/gtwcmkltzz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtihpeljii.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.havefunace.top/Article/details/gtuihdhbam.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yonumen.top/Article/details/gtoxxyzjhq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gtoclrndpf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnqzz.top/Article/details/gtszrmgzeq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aizwys.cn/Article/details/gtyjevlrre.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258.top/Article/details/gtizpcrfgz.html

[E15] HTML 转义 / 反转义
来源：http://dali.birdmap.top/Article/details/gtzhdtbhku.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sysykeji.top/Article/details/gtkcjrbhja.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hywenlv.cn/Article/details/gtbmmmwdby.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dianchejie.cn/Article/details/gtofwahkbg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.andypj.xyz/Article/details/gtrtuzljup.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cheryme.top/Article/details/gtkxvkqeff.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangdashe.top/Article/details/gtyjuczait.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.mhx1999.top/Article/details/gtxftyuoru.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gtkinavgyw.html

[E16] 数字千分位
来源：http://dali.daxiang520.top/Article/details/gtzasvhqda.html

Py:   f"{1234567:,}"
来源：http://dali.yonumen.top/Article/details/gtzydomcwl.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gtdggqlgvi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtmkwjpbbb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gtlwebkueo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtdnovmaay.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ehwqpu.com/Article/details/gtyepiqpyq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yonumen.top/Article/details/gtautiipqk.html

C#:   1234567.ToString("N0")
来源：http://dali.daxiang520.top/Article/details/gtggzwaiir.html

[E17] 首字母大写
来源：http://dali.redwolf501.top/Article/details/gtxavktjdm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.snrcjt.cn/Article/details/gtvexgpljf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhengqikj.top/Article/details/gtsbcrgreq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gtngnvycpk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gtbfzhzooy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tianlin.xyz/Article/details/gtkjalfuxg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtvpixyzsp.html

Ruby: s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gtqbagrdms.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gtnbbdacxo.html

[E18] 模板占位符替换
来源：http://dali.nanxuanxn.top/Article/details/gtxeqyuapi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cashguo.top/Article/details/gtwujenpfm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aibaodan.cn/Article/details/gtrlsxxqwm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtcitmcdbr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfdlgxmr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtmumaluta.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtovyptskf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shuidangran.top/Article/details/gtvutljbzx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cdnleiting.top/Article/details/gtgmauewuo.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gtsfwfdpoc.html

Py:   s.splitlines()
来源：http://dali.yj202588.top/Article/details/gtkveyptzy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtbvwtmryh.html

JS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtzusfjutn.html

TS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gtbpjbbqyw.html

Java: s.lines().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmelqtsj.html

Go:   strings.Split(s, "\n")
来源：http://dali.haohaochexian.top/Article/details/gtasulgjtg.html

Ruby: s.lines
来源：http://dali.nanxuanxn.top/Article/details/gtwxhorsre.html

C#:   s.Split('\n')
来源：http://dali.hammf.cn/Article/details/gtlpgyfvhf.html

[E20] 判断字符串是否为空
来源：http://dali.iojbl.cn/Article/details/gtdbolkfof.html

Py:   if not s:
来源：http://dali.sysykeji.top/Article/details/gtlskxqhgg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhixingplan.top/Article/details/gtcglqtbmj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgufenzy.top/Article/details/gtdkkgrhgp.html

TS:   if (s === "") {}
来源：http://dali.havefunace.top/Article/details/gtzldudnok.html

Java: if (s.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gtquelwjpu.html

Go:   if s == "" {}
来源：http://dali.xylfe.cn/Article/details/gtkeikklmi.html

Ruby: if s.empty?
来源：http://dali.snrcjt.cn/Article/details/gtcjnvpyen.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yongpay.top/Article/details/gthjlrtxnt.html

[E21] 超长截断加省略号
来源：http://dali.cdnleiting.top/Article/details/gtbdxufqlp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.andypj.xyz/Article/details/gtzqkobgln.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtosgffoqq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtehauawnh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtztgwvjox.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtnbwgpfav.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.redwolf501.top/Article/details/gtbbctszjb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtkgefgrwi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtxgmcglhn.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258888.top/Article/details/gthpwcvotz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxuanxn.top/Article/details/gtwormxclp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtrepojpcn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gtxodeennc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtxytrvoys.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtnhgegmep.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yvedp.cn/Article/details/gtewyqukje.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj202588.top/Article/details/gtnfweghie.html


<!-- 参考信息 -->