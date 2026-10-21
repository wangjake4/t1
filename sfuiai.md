代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuxming.cn/Article/details/gtilnlysgp.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gtelguatum.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gzhubu.top/Article/details/gtmasaqzzs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtfxgdaukt.html

[D15] 去重
来源：http://dali.cheryme.top/Article/details/gtgmafppyr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shzxlz.cn/Article/details/gtwywkonrz.html

PHP:  array_unique($arr);
来源：http://dali.haohaochexian.top/Article/details/gtkubjzdon.html

JS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gttgbsgozd.html

TS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtznprcugy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sweek.top/Article/details/gttcqfbzgh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sweek.top/Article/details/gtdckycdoa.html

Ruby: arr.uniq
来源：http://dali.tian-w.cn/Article/details/gtumqaszxc.html

C#:   list.Distinct().ToList()
来源：http://dali.birdmap.top/Article/details/gtsycjmiqo.html

[D16] 求和与平均值
来源：http://dali.vqdsnc.cn/Article/details/gtwpliwdyv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gtiilpqupl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yongpay.top/Article/details/gtavbjwjll.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gtvphytjzf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gtsitvqkag.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pycfn.com/Article/details/gtnmeskgsi.html

Go:   // 手写循环累加
来源：http://dali.xziqi.cn/Article/details/gtmlaoynnl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.c1oappe.top/Article/details/gtytymffme.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhoulong.xyz/Article/details/gtzjnefint.html

[D17] 最大值与最小值
来源：http://dali.hammf.cn/Article/details/gthcsmflux.html

Py:   max(arr);  min(arr)
来源：http://dali.gotoacloud.top/Article/details/gtmvifrgsn.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gtnjuasbmd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazbsaezm.html

TS:   Math.max(...arr);
来源：http://dali.hysaishi.cn/Article/details/gtkwpeaspm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangdashe.top/Article/details/gtvrurwjkv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258.top/Article/details/gtyynnqmyt.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gtnfhiohjw.html

C#:   list.Max();  list.Min()
来源：http://dali.gaohongyu789.top/Article/details/gtjhuwlyei.html

[D18] 扁平化嵌套数组
来源：http://dali.hysaishi.cn/Article/details/gtlqqeuhrg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.redwolf501.top/Article/details/gtwtmtljac.html

PHP:  array_merge(...$nested);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmxnolbz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sxryk.cn/Article/details/gtdscodhfz.html

TS:   nested.flat();
来源：http://dali.andypj.xyz/Article/details/gtzgfdtkpl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnqzz.top/Article/details/gtbsvwysbx.html

Go:   // 手写双层循环
来源：http://dali.jiagoushi.top/Article/details/gtqusdfuko.html

Ruby: nested.flatten
来源：http://dali.0kj1m.cn/Article/details/gtgpwtyqyl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tanke756.top/Article/details/gtpvkjpxvo.html

[D19] 按字段分组
来源：http://dali.ppjwa.cn/Article/details/gteteergpa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtsvyswpqx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.iojbl.cn/Article/details/gtccmnidcd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuanzhike.top/Article/details/gtlfmndbql.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnxiangtu.top/Article/details/gtebhmivhc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhongyouzk.top/Article/details/gtktntjbwa.html

Go:   // 手写 map[string][]T
来源：http://dali.aizwys.cn/Article/details/gthirfzfxg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ivvv.top/Article/details/gtdwefhyyc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gtjwiapvkp.html

[D20] 统计每个元素出现次数
来源：http://dali.nwbrower.top/Article/details/gtxgbewfzn.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmqomjyf.html

PHP:  array_count_values($arr);
来源：http://dali.zhixingplan.top/Article/details/gtjelgzsfh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gtcusxfhne.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gtlbpqzswh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gtasxlblpg.html

Go:   // 手写 map[T]int
来源：http://dali.yuanzhike.top/Article/details/gtyolkhmmo.html

Ruby: arr.tally
来源：http://dali.jqgfzy.top/Article/details/gtlsaroybg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tanke756.top/Article/details/gtvqoqmzhq.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtqesuccps.html

Py:   x in arr
来源：http://dali.316326.xyz/Article/details/gtihqounso.html

PHP:  in_array($x, $arr, true);
来源：http://dali.quarkkingdee.top/Article/details/gtgqwithpv.html

JS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gteltlcwjo.html

TS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gttmpktibh.html

Java: list.contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewnblhaq.html

Go:   slices.Contains(arr, x)
来源：http://dali.yongpay.top/Article/details/gtwwsmcoqi.html

Ruby: arr.include?(x)
来源：http://dali.zycfv.cn/Article/details/gticjviskj.html

C#:   list.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gttgeewftm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.quarkkingdee.top/Article/details/gtoykcsxhq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxinkj.top/Article/details/gtbvamngkg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xziqi.cn/Article/details/gtinieihbl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shuidangran.top/Article/details/gtgvugwigx.html

TS:   [...arr];
来源：http://dali.dianchejie.cn/Article/details/gtmckwqtcm.html

Java: new ArrayList<>(list);
来源：http://dali.chenzaomai.com/Article/details/gtmojycvhc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gtjcibffvw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.birdmap.top/Article/details/gtewwnpmxc.html

C#:   new List<int>(list);
来源：http://dali.guowangkeji.top/Article/details/gtskjkpeld.html

[D23] reduce 累积计算
来源：http://dali.smart0.xyz/Article/details/gtyprseuwq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigufen.top/Article/details/gtwrllbcoe.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aizwys.cn/Article/details/gtpehekxdl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtvtavjpcr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpedsdtuf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tanke756.top/Article/details/gtlsaiqhjp.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gtjcavrgog.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxuanxn.top/Article/details/gtnqvyhtsb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gtmaffewpk.html

[D24] 字典 / Map 基本操作
来源：http://dali.dianchejie.cn/Article/details/gtstjhpaic.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpvvsuqb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gthbgpuxlx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aizwys.cn/Article/details/gtwxrrdajk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtffnjgzcn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yonumen.top/Article/details/gttyusxybo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sweek.top/Article/details/gtrfcsypwg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.bjfxy.top/Article/details/gtmnhvkfoa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gtyiibrlyb.html

[D25] Set 集合去重与交并差
来源：http://dali.hammf.cn/Article/details/gtkavhirgx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgufenzy.top/Article/details/gtnemqhzgi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shangyingyoupin.top/Article/details/gtbopsmzvp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258.top/Article/details/gtwlmjmjco.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zdqjudy.top/Article/details/gtulpggqhr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gttyifjtap.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxuswwfn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgfzy.top/Article/details/gtpskgbzoz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtivoaaqok.html

[D26] 数组转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtnmysedoj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pycfn.com/Article/details/gtbsaytcyu.html

PHP:  implode(", ", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtemmviqpr.html

JS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtrioiefhb.html

TS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtmgzoedfg.html

Java: String.join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gtfxfwfbit.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dianchejie.cn/Article/details/gtvewqhyyn.html

Ruby: arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtvwuiwydl.html

C#:   string.Join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gtqksaqrnm.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtlslhdmxw.html

E. 字符串处理
来源：http://dali.316326.xyz/Article/details/gtluztdriz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtklwtinyv.html

[E01] 拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtrarfawhv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.mhx1999.top/Article/details/gtkbmfzqxb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sysykeji.top/Article/details/gtdjrfkuxj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gtxbsgonby.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gticwygypr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tian-w.cn/Article/details/gtvbgxezyt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigufen.top/Article/details/gtnzhnbxhv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pycfn.com/Article/details/gtnfshqpgw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtjlxssles.html

[E02] 重复字符串
来源：http://dali.0kj1m.cn/Article/details/gtfytbojjn.html

Py:   "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gtqdzxelwx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shzxlz.cn/Article/details/gtxpjkqxyw.html

JS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtfggwrrfe.html

TS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtahrwzzhp.html

Java: "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gtpfhukiyh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgoepzkj.html

Ruby: "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gttlgplxok.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ydzc1.top/Article/details/gtffxpsflb.html

[E03] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gtgexwaiqo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hysaishi.cn/Article/details/gtzwrlflfc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gthlfnpoea.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtqrzchcvs.html

TS:   s.slice(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtmygfnlfp.html

Java: s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gtstuhvssu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtyfidnang.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pengpengdd.cyou/Article/details/gtqcwizhad.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigufen.top/Article/details/gtyjvnbxzk.html

[E04] 查找子串位置
来源：http://dali.sufxvd.cn/Article/details/gtyqtwbzxr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtkwbemkrq.html

PHP:  strpos($s, "x");
来源：http://dali.daria6918.cn/Article/details/gteuofjftq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guowangkeji.top/Article/details/gtzcsecjmt.html

TS:   s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtecbcjphj.html

Java: s.indexOf("x")
来源：http://dali.pycfn.com/Article/details/gtraaghfxn.html

Go:   strings.Index(s, "x")
来源：http://dali.cucudq.cn/Article/details/gtdvkkmmwv.html

Ruby: s.index("x")
来源：http://dali.gogol.net.cn/Article/details/gtvwctuczf.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtehlzetmo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yonumen.top/Article/details/gtrqpwgysz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zycfv.cn/Article/details/gtkjfexjjf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.svipenyu.cn/Article/details/gthlnsyhgi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtjzyjvotj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258888.top/Article/details/gtsfglrnsn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtwtobdfig.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ybcxt.top/Article/details/gthbhgffaa.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tanke756.top/Article/details/gtalyuqpxw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtjsucxmnq.html

[E06] 替换子串
来源：http://dali.yj202588.top/Article/details/gtquexuvqt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gtyixoyrws.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.c1oappe.top/Article/details/gtzviffqdj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtlrmwwprs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtouernjvl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtdzwwthub.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gtyksbgvip.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtoecqegeq.html

C#:   s.Replace("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtyknjqekg.html

[E07] 按分隔符拆分
来源：http://dali.gzhubu.top/Article/details/gtprckcakc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gtqxnfpamv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daxiang520.top/Article/details/gtqcvrozvb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxuanxn.top/Article/details/gtfulmtmiz.html

TS:   s.split(",")
来源：http://dali.sysykeji.top/Article/details/gtqjiyqwqc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tianlin.xyz/Article/details/gtwkauckki.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xylfe.cn/Article/details/gtdaznjwsg.html

Ruby: s.split(",");  s.split
来源：http://dali.tianlin.xyz/Article/details/gtvllwfaov.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cashguo.top/Article/details/gtfogdqyor.html

[E08] 数组按分隔符合并
来源：http://dali.ivvv.top/Article/details/gtiqghnhge.html

Py:   ",".join(items)
来源：http://dali.yj20258.top/Article/details/gtgtmtalnw.html

PHP:  implode(",", $items);
来源：http://dali.zhaomingkeji.xyz/Article/details/gteajawtfd.html

JS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtjcuixmiq.html

TS:   items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gteyakkler.html

Java: String.join(",", items)
来源：http://dali.yongpay.top/Article/details/gtxfddmmub.html

Go:   strings.Join(items, ",")
来源：http://dali.haohaochexian.top/Article/details/gtieexbmcg.html

Ruby: items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gthezbqxxw.html

C#:   string.Join(",", items)
来源：http://dali.daxiang520.top/Article/details/gtvpbudxku.html

[E09] 去除所有空白字符
来源：http://dali.quarkkingdee.top/Article/details/gtdzpihlbi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.c1oappe.top/Article/details/gtthgdqyvp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xylfe.cn/Article/details/gthiahdsri.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gtiadoplja.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtwpowxemm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtxlqivzyq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pycfn.com/Article/details/gtwixrcwag.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhixingplan.top/Article/details/gtvarkhykp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.havefunace.top/Article/details/gttlssxhal.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sufxvd.cn/Article/details/gtwninhftv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtbzawotkz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxvmuvyt.html

JS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtblikiwng.html

TS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtdszqhvmg.html

Java: String.format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gtmbserdps.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gttngkdydo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtuggnnamf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cdnleiting.top/Article/details/gtmcckaolt.html

[E11] 反转字符串
来源：http://dali.xinyue.icu/Article/details/gtwujtqdxc.html

Py:   s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gtjnvurvib.html

PHP:  strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrbqeuir.html

JS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gthmvupfvl.html

TS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtbqrofspl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cucudq.cn/Article/details/gtbtvnftug.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.iojbl.cn/Article/details/gtaqtacvkr.html

Ruby: s.reverse
来源：http://dali.gotoacloud.top/Article/details/gtskmecrip.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gtgbghjktl.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtgwftufya.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gtjpwnkein.html

PHP:  substr_count($s, "a");
来源：http://dali.hfpthk.cn/Article/details/gtnwhferek.html

JS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gtqduaszck.html

TS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gtscrrzonq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gtrowazdda.html

Go:   strings.Count(s, "a")
来源：http://dali.zhiwuduotai.top/Article/details/gthyiqdlwh.html

Ruby: s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gtjmikhfcc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jlsjyb.cn/Article/details/gtvewarxpq.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtbhjbdcha.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gtbodplyqh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.snrcjt.cn/Article/details/gtieghtfef.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtdtxincee.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gtdtcuagsn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtyqchvxgv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shuidangran.top/Article/details/gtjtmgtmkc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hongshengwenyu.top/Article/details/gtqfjlefnb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cucudq.cn/Article/details/gtxggnxfok.html

[E14] URL 编码与 Base64
来源：http://dali.yuanzhike.top/Article/details/gtkvpdcifr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gtrptkefcl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.haohaochexian.top/Article/details/gtxwwqmvsw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cashguo.top/Article/details/gtllacymto.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jianghu66.top/Article/details/gtknrahwin.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtlbondohc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pycfn.com/Article/details/gtyhusxljq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258888.top/Article/details/gttnglhwks.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sysykeji.top/Article/details/gtiafjzfhx.html

[E15] HTML 转义 / 反转义
来源：http://dali.feifeiyinyue.top/Article/details/gtjgkbywjb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnqzz.top/Article/details/gtkicynffm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cashguo.top/Article/details/gtsnbebmeg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxtoihfo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hysaishi.cn/Article/details/gtymojekfq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuxming.cn/Article/details/gtmzazvsva.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yueranfly.top/Article/details/gtdncupmax.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cqqwz.cn/Article/details/gtjirperql.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuanzhike.top/Article/details/gtiglnxvvr.html

[E16] 数字千分位
来源：http://dali.cheryme.top/Article/details/gtuffedayf.html

Py:   f"{1234567:,}"
来源：http://dali.sweek.top/Article/details/gtncplwvhw.html

PHP:  number_format(1234567);
来源：http://dali.cheryme.top/Article/details/gtidfmqgwq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gtaqxtuxak.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtuhwffvay.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gtocjaqlri.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenzaomai.com/Article/details/gtvugqrifg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjeukwkgj.html

C#:   1234567.ToString("N0")
来源：http://dali.haohaochexian.top/Article/details/gtcmdqzvkb.html

[E17] 首字母大写
来源：http://dali.havefunace.top/Article/details/gtvwchlrzo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuxming.cn/Article/details/gtdwyrnpjd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yonumen.top/Article/details/gtdwstwiap.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gtxajqwyze.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gtmzqhaxpt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gtgxforahq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ehwqpu.com/Article/details/gthnimuxtk.html

Ruby: s.capitalize
来源：http://dali.sxryk.cn/Article/details/gtywrdepde.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sufxvd.cn/Article/details/gtdatiejyz.html

[E18] 模板占位符替换
来源：http://dali.jlsjyb.cn/Article/details/gtquzammkr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dianchejie.cn/Article/details/gtcrcrxtvu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cqqwz.cn/Article/details/gttsffuiya.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtnesttfkw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gteoyzvvva.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtfpwdfpui.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj202588.top/Article/details/gtijkgvcez.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.andypj.xyz/Article/details/gtpydajirt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxinkj.top/Article/details/gthtzrhsza.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrbqanwd.html

Py:   s.splitlines()
来源：http://dali.jqgufenzy.top/Article/details/gtnxlhpont.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtlymkravc.html

JS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gtusmkyzfv.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gtbcyreqaz.html

Java: s.lines().toList()
来源：http://dali.jianghu66.top/Article/details/gtenwquonu.html

Go:   strings.Split(s, "\n")
来源：http://dali.aibaodan.cn/Article/details/gtwikgxwus.html

Ruby: s.lines
来源：http://dali.ppjwa.cn/Article/details/gtbjfilsxc.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gtvmmzmnea.html

[E20] 判断字符串是否为空
来源：http://dali.quarkkingdee.top/Article/details/gtisnhqebl.html

Py:   if not s:
来源：http://dali.sufxvd.cn/Article/details/gtlsmtumxm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yvedp.cn/Article/details/gtdwvsjyvq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuxming.cn/Article/details/gtwfcenauv.html

TS:   if (s === "") {}
来源：http://dali.cucudq.cn/Article/details/gtrbaixjou.html

Java: if (s.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtjufmqzvd.html

Go:   if s == "" {}
来源：http://dali.cashguo.top/Article/details/gtnjiqywcn.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gtyznpmutb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.iojbl.cn/Article/details/gtlfqooikr.html

[E21] 超长截断加省略号
来源：http://dali.jqgufenzy.top/Article/details/gttvmfroox.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gogol.net.cn/Article/details/gtcwtrxkvs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtvddhkpzm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gttlcdbeyx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtdadjdfxe.html


<!-- 参考信息 -->