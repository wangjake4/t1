代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gtxpxqraty.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tianlin.xyz/Article/details/gtbzynrole.html

TS:   Math.max(...arr);
来源：http://dali.yuanzhike.top/Article/details/gtltuynyqg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yonumen.top/Article/details/gtfctaquih.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fengsongda.top/Article/details/gtceqvolvs.html

Ruby: arr.max;  arr.min
来源：http://dali.hongshengwenyu.top/Article/details/gtprednzmw.html

C#:   list.Max();  list.Min()
来源：http://dali.iojbl.cn/Article/details/gtomtpdtxg.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258.top/Article/details/gtumcxivlt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aibaodan.cn/Article/details/gterasesww.html

PHP:  array_merge(...$nested);
来源：http://dali.sweek.top/Article/details/gtykwaxodi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yangfankeji.com/Article/details/gtiuekllok.html

TS:   nested.flat();
来源：http://dali.aizwys.cn/Article/details/gtyojasdef.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.svipenyu.cn/Article/details/gthacdyhvt.html

Go:   // 手写双层循环
来源：http://dali.ydzc1.top/Article/details/gtntuwqgko.html

Ruby: nested.flatten
来源：http://dali.jyoumei.cn/Article/details/gtnwrcqwfg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtmsenucaa.html

[D19] 按字段分组
来源：http://dali.9152youxi.cn/Article/details/gtvtpcvmvw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.redwolf501.top/Article/details/gtrtbyeofx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sufxvd.cn/Article/details/gtpjzlfeyf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zycfv.cn/Article/details/gtdvldlwrk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gtaezqcdei.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.kuanghao11.cn/Article/details/gtjzxosynh.html

Go:   // 手写 map[string][]T
来源：http://dali.xylfe.cn/Article/details/gtvsnnmezf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hywenlv.cn/Article/details/gtojxyzifk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuetiantiany.cn/Article/details/gtbbasyrhc.html

[D20] 统计每个元素出现次数
来源：http://dali.jiagoushi.top/Article/details/gtrnawssxs.html

Py:   Counter(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtvvxqdkup.html

PHP:  array_count_values($arr);
来源：http://dali.yueranfly.top/Article/details/gtpqurtexq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gtecrmbnre.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gtwfndwkei.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgefjdbil.html

Go:   // 手写 map[T]int
来源：http://dali.nanxuanxn.top/Article/details/gtfowthcyt.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gtpzyzkdch.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.kuanghao11.cn/Article/details/gtqpuejjzg.html

[D21] 判断是否包含某元素
来源：http://dali.wangshuangyany.cn/Article/details/gtwklsymtn.html

Py:   x in arr
来源：http://dali.jlsjyb.cn/Article/details/gtxsaeixls.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnqzz.top/Article/details/gtraietmyn.html

JS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gttuvoaygi.html

TS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtmzyqkyyd.html

Java: list.contains(x)
来源：http://dali.c1oappe.top/Article/details/gtlzpdoqau.html

Go:   slices.Contains(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtudopiahs.html

Ruby: arr.include?(x)
来源：http://dali.jqgfzy.top/Article/details/gtiytszdin.html

C#:   list.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtvkwgtetp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xinyue.icu/Article/details/gtsaqdgqio.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gteuihmkdv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj202588.top/Article/details/gtcbuawmxr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jiagoushi.top/Article/details/gtspbdewfg.html

TS:   [...arr];
来源：http://dali.jinqigfzy.top/Article/details/gtvgpvnwnu.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigufen.top/Article/details/gtkfndghjb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cashguo.top/Article/details/gtbjuyafue.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncnrolnm.html

C#:   new List<int>(list);
来源：http://dali.zhengqikj.top/Article/details/gtwlmqjusx.html

[D23] reduce 累积计算
来源：http://dali.zhoulong.xyz/Article/details/gtziyzrgdl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cdnleiting.top/Article/details/gtryfsovoo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtupfrscac.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gtgjfzeyei.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtccgkxkmp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shzxlz.cn/Article/details/gtzbwlcems.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gtqxaatjlu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yueranfly.top/Article/details/gtyisctdtg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gtpwwrfubn.html

[D24] 字典 / Map 基本操作
来源：http://dali.jyoumei.cn/Article/details/gtcylegyim.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuxming.cn/Article/details/gthujajraj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhiwuduotai.top/Article/details/gttsmaqpcd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtsbpjtyfn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtgklshlsw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cqqwz.cn/Article/details/gtcsplkfda.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yangfankeji.com/Article/details/gtcarcvzhv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.c1oappe.top/Article/details/gttecltryb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzdsoepz.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxinkj.top/Article/details/gtebhqskdg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gtgyjogxft.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gtcsmjqlco.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guowangkeji.top/Article/details/gtdgsiduhg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.bjfxy.top/Article/details/gtixmouyus.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrlbsmzb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gtozzpolly.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.birdmap.top/Article/details/gtcxntltie.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cheryme.top/Article/details/gtkcaecbgd.html

[D26] 数组转字符串
来源：http://dali.hysaishi.cn/Article/details/gtwfpfawym.html

Py:   ", ".join(map(str, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtjenwfagq.html

PHP:  implode(", ", $arr);
来源：http://dali.sweek.top/Article/details/gtcqndqajb.html

JS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gttbwiexuw.html

TS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtruftzxrh.html

Java: String.join(", ", list)
来源：http://dali.tanke756.top/Article/details/gtvrqldiel.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xylfe.cn/Article/details/gtwgjgbkhx.html

Ruby: arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtfhvgmxzl.html

C#:   string.Join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gtjumoaikm.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtlwolsypg.html

E. 字符串处理
来源：http://dali.yj20258.top/Article/details/gtvztrvntu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtkxywwvpn.html

[E01] 拼接字符串
来源：http://dali.ivvv.top/Article/details/gtleiapugb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.svipenyu.cn/Article/details/gtnaczxzqv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sweek.top/Article/details/gtwtftlube.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gthzhsvcaf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gtreveocxy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnxiangtu.top/Article/details/gtwhlrepus.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangdashe.top/Article/details/gtgktwwgjt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.quarkkingdee.top/Article/details/gtgxokiigw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gteezhiqdx.html

[E02] 重复字符串
来源：http://dali.birdmap.top/Article/details/gtsvmoqvdq.html

Py:   "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gtgcflcjja.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gogol.net.cn/Article/details/gtdklaccta.html

JS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gtrsgwgthe.html

TS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtnztikwqm.html

Java: "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gtlkxekbia.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgfzy.top/Article/details/gtrduuuidp.html

Ruby: "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtctjibwrn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtxefbralt.html

[E03] 截取子串
来源：http://dali.pycfn.com/Article/details/gtscqzosvm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yongpay.top/Article/details/gtrwdrytid.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtnvgcooxb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtparbidou.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtelvekiwe.html

Java: s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteoxhbzag.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtcczhwajb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hnxiangtu.top/Article/details/gtqlhoibht.html

C#:   s.Substring(1, 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkihlvcz.html

[E04] 查找子串位置
来源：http://dali.nwbrower.top/Article/details/gtsciasriz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gtnxysymra.html

PHP:  strpos($s, "x");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnecscwl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ydzc1.top/Article/details/gttixdgyar.html

TS:   s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gtugfqmzqb.html

Java: s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gthzlsyvwn.html

Go:   strings.Index(s, "x")
来源：http://dali.birdmap.top/Article/details/gtxxrgjwho.html

Ruby: s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gtzgjoraoc.html

C#:   s.IndexOf("x")
来源：http://dali.fzhhl.top/Article/details/gthroncvfr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgufenzy.top/Article/details/gtehfirmet.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj202588.top/Article/details/gtzwsmaafw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxinkj.top/Article/details/gtomamcvrn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtskbibumr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zdqjudy.top/Article/details/gtccuvwwqa.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gtjqrgluam.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuanzx.com/Article/details/gtprjhdohf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenlongwang.top/Article/details/gtjzmimpmg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtfnayjhby.html

[E06] 替换子串
来源：http://dali.wangshuangyany.cn/Article/details/gtkimyoyqe.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtplgsapyh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tianlin.xyz/Article/details/gtfvvdjsqu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtasrzcyex.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtfcwbzbsq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gtsedutscx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dashuyun.cn/Article/details/gtsrprkvtl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hammf.cn/Article/details/gtjdfxqbdu.html

C#:   s.Replace("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtrymruytw.html

[E07] 按分隔符拆分
来源：http://dali.ybcxt.top/Article/details/gtwbphdpid.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cheryme.top/Article/details/gtkojcbufa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtuswosdpw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tianlin.xyz/Article/details/gtwjmidgoz.html

TS:   s.split(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtwmmsoxbw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xylfe.cn/Article/details/gtuuvhnshn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cqqwz.cn/Article/details/gtazhzufek.html

Ruby: s.split(",");  s.split
来源：http://dali.pengpengdd.cyou/Article/details/gtjkolhvqh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgufenzy.top/Article/details/gtowiosiox.html

[E08] 数组按分隔符合并
来源：http://dali.hammf.cn/Article/details/gtjfikbmlh.html

Py:   ",".join(items)
来源：http://dali.yj20258.top/Article/details/gtdeciyprl.html

PHP:  implode(",", $items);
来源：http://dali.hongshengwenyu.top/Article/details/gtptpucexs.html

JS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtyybwllfp.html

TS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtkmmnzkes.html

Java: String.join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtxygwmboy.html

Go:   strings.Join(items, ",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqvuwenm.html

Ruby: items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuyjsmhuo.html

C#:   string.Join(",", items)
来源：http://dali.tian-w.cn/Article/details/gthjebhzmy.html

[E09] 去除所有空白字符
来源：http://dali.gotoacloud.top/Article/details/gtupzseept.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.quarkkingdee.top/Article/details/gtxouvoctn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwggznwm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gtdlztowjj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtdikqvhih.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtxytxrvbc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ivvv.top/Article/details/gtlywbsqlh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.svipenyu.cn/Article/details/gtefdrelwo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gtkkvytcwn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ehwqpu.com/Article/details/gtkjlrurfz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtudarnptc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ybcxt.top/Article/details/gtdgmlqzoy.html

JS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtjvqstqrj.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtwlmlewvh.html

Java: String.format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtyqaoymnk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gtfulelwwb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtsetitbpw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cdnleiting.top/Article/details/gtlqjqxlny.html

[E11] 反转字符串
来源：http://dali.gzhubu.top/Article/details/gtuxdmhvsl.html

Py:   s[::-1]
来源：http://dali.havefunace.top/Article/details/gtdpkehzyg.html

PHP:  strrev($s);
来源：http://dali.yuxming.cn/Article/details/gtbxrmbmjp.html

JS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtguhaqpcj.html

TS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtxtnfxbjj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jyoumei.cn/Article/details/gtxcvxfzmr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.meibo888.top/Article/details/gtwcdozqmo.html

Ruby: s.reverse
来源：http://dali.birdmap.top/Article/details/gtaargbdgr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gtpkfpzzqz.html

[E12] 统计某字符出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuolezfq.html

Py:   s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gtljbcnyac.html

PHP:  substr_count($s, "a");
来源：http://dali.vqdsnc.cn/Article/details/gtdqxbufnw.html

JS:   s.split("a").length - 1
来源：http://dali.hammf.cn/Article/details/gtvqjmizrx.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzongrqel.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gttphammqp.html

Go:   strings.Count(s, "a")
来源：http://dali.shuidangran.top/Article/details/gtplispein.html

Ruby: s.count("a")
来源：http://dali.smart0.xyz/Article/details/gtejaftzhb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yangfankeji.com/Article/details/gtojifkqgu.html

[E13] 逐字符遍历
来源：http://dali.gzhubu.top/Article/details/gttrsnyogf.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gtigxnyzpo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gtdqnritnb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gtibzuiutv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtevovewfb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zycfv.cn/Article/details/gtbuvnbutn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtoynvbzdj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hywenlv.cn/Article/details/gtjevpsmxs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ybcxt.top/Article/details/gtruixudrd.html

[E14] URL 编码与 Base64
来源：http://dali.aibaodan.cn/Article/details/gtdrqwvela.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvrtatnv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gtitpwoqxi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sxryk.cn/Article/details/gtoybfxpts.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nwbrower.top/Article/details/gtcaesczmg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtcfvlhfgo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guannengcc.top/Article/details/gtmzeuggqk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqjrwedz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtldceyuua.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gtiabadvwf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jlsjyb.cn/Article/details/gtgpfnodbq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ydzc1.top/Article/details/gtlrbqygqm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jiagoushi.top/Article/details/gtvrnwacxs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxydwekv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jyoumei.cn/Article/details/gtbpyxmjha.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yueranfly.top/Article/details/gtrfcestav.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.kuanghao11.cn/Article/details/gtbbzjmset.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guannengcc.top/Article/details/gtvbgrbrfe.html

[E16] 数字千分位
来源：http://dali.nwbrower.top/Article/details/gtzjiwqsvz.html

Py:   f"{1234567:,}"
来源：http://dali.zhongyouzk.top/Article/details/gtmzqogxsu.html

PHP:  number_format(1234567);
来源：http://dali.yj20258888.top/Article/details/gtuztblysb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvypncqp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtpxrljaoa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gteavrlzbx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sxryk.cn/Article/details/gtvwzctttz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daxiang520.top/Article/details/gtiuonfdkx.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgfzy.top/Article/details/gtbdcpkwip.html

[E17] 首字母大写
来源：http://dali.c1oappe.top/Article/details/gtranyjmhs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gtmbupbdrw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtepultnil.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gthamingll.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gteilsxwpg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuanzx.com/Article/details/gtpaedhoaf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yonumen.top/Article/details/gtcvrugbrb.html

Ruby: s.capitalize
来源：http://dali.shuidangran.top/Article/details/gtyobvyitu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuanzhike.top/Article/details/gtrcehcfzt.html

[E18] 模板占位符替换
来源：http://dali.sysykeji.top/Article/details/gtimutscpe.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cucudq.cn/Article/details/gtofcmmykg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.snrcjt.cn/Article/details/gtcayecvzt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtzmkclciw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtlwdlegfp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtxlbxywbp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtrapbcddi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dashuyun.cn/Article/details/gthpabeehk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.iojbl.cn/Article/details/gtdnkvlkqb.html

[E19] 多行文本按行拆分
来源：http://dali.cucudq.cn/Article/details/gtxxtadzvx.html

Py:   s.splitlines()
来源：http://dali.jlsjyb.cn/Article/details/gtvitjhrxj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.mhx1999.top/Article/details/gtdvctlshl.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwgkroog.html

TS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtcbickakc.html

Java: s.lines().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtxayzpsjn.html

Go:   strings.Split(s, "\n")
来源：http://dali.kuanghao11.cn/Article/details/gtxukfmuxk.html

Ruby: s.lines
来源：http://dali.pycfn.com/Article/details/gtcecceeua.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gtfhwerghh.html

[E20] 判断字符串是否为空
来源：http://dali.gzhubu.top/Article/details/gtsdejhwza.html

Py:   if not s:
来源：http://dali.gzhubu.top/Article/details/gthzzeckxy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gtcwabewtb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shzxlz.cn/Article/details/gtqhxrbeed.html

TS:   if (s === "") {}
来源：http://dali.nanxinkj.top/Article/details/gtagehqxyv.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtngaeptky.html

Go:   if s == "" {}
来源：http://dali.snrcjt.cn/Article/details/gtbzopacxi.html

Ruby: if s.empty?
来源：http://dali.jinqigfzy.top/Article/details/gtmisffrlm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shuidangran.top/Article/details/gtbhvryvhx.html

[E21] 超长截断加省略号
来源：http://dali.chenzaomai.com/Article/details/gtlykqifxz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhengqikj.top/Article/details/gtbbkzjqhj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtwvldjxol.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtbrkandra.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtqcuphqsz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvierrsxz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yueranfly.top/Article/details/gtpadhqewx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtwsnfjpbx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtiqpnkxms.html

[E22] 字节长度与字符长度
来源：http://dali.smart0.xyz/Article/details/gtkbnuapcw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.316326.xyz/Article/details/gtamemroxy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtdbkcuuue.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntxpncki.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkkbnvut.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gtdmybfzya.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xziqi.cn/Article/details/gtbosvqzdq.html

Ruby: s.bytesize;  s.length
来源：http://dali.tian-w.cn/Article/details/gtpyfhvill.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtnyfjaewo.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtwvuvrkmv.html

F. 文件与目录
来源：http://dali.quarkkingdee.top/Article/details/gtgcphumls.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtwkxhzhaz.html

[F01] 读取整个文件
来源：http://dali.ppjwa.cn/Article/details/gtcfglulwv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.vqdsnc.cn/Article/details/gtyyeaavct.html

PHP:  file_get_contents("a.txt");
来源：http://dali.316326.xyz/Article/details/gtgtihpznd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswiltcem.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtnisesoio.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtnefujcxl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shuidangran.top/Article/details/gtupjdbdoe.html

Ruby: File.read("a.txt")
来源：http://dali.havefunace.top/Article/details/gtfzfjackd.html


<!-- 参考信息 -->