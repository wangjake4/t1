代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sufxvd.cn/Article/details/gtvgxinduw.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtleckahzq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hammf.cn/Article/details/gtrdnoszzo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtifkshsqf.html

[D15] 去重
来源：http://dali.jlsjyb.cn/Article/details/gteddpyfst.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gtbtidepai.html

PHP:  array_unique($arr);
来源：http://dali.xinyue.icu/Article/details/gtsqhbyngq.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtnrwibxbj.html

TS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtrptrxjzg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.redwolf501.top/Article/details/gtqfwqyhcu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gogol.net.cn/Article/details/gtbzkxdeib.html

Ruby: arr.uniq
来源：http://dali.vqdsnc.cn/Article/details/gtdcomuvhp.html

C#:   list.Distinct().ToList()
来源：http://dali.aibaodan.cn/Article/details/gtudqtopne.html

[D16] 求和与平均值
来源：http://dali.yuanzhike.top/Article/details/gtyhihoupa.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtyoysscxg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtdwjkxovt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gtuwyasfbc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gttfegmalp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufhdmsfg.html

Go:   // 手写循环累加
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxufbaxzg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.smart0.xyz/Article/details/gthmsnekxq.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvmgakux.html

[D17] 最大值与最小值
来源：http://dali.hnqzz.top/Article/details/gtezugcxmu.html

Py:   max(arr);  min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtuaugsigc.html

PHP:  max($arr);  min($arr);
来源：http://dali.gotoacloud.top/Article/details/gtnogoszad.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtfcussunr.html

TS:   Math.max(...arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqyhspov.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gtzvvhkijj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gtrqatfxkc.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqbvfrpj.html

C#:   list.Max();  list.Min()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxgvknsj.html

[D18] 扁平化嵌套数组
来源：http://dali.mhx1999.top/Article/details/gttjxowhsl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhengqikj.top/Article/details/gttaiacixe.html

PHP:  array_merge(...$nested);
来源：http://dali.hfpthk.cn/Article/details/gtvgvzwlzb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.dianchejie.cn/Article/details/gtpqmanbzo.html

TS:   nested.flat();
来源：http://dali.daria6918.cn/Article/details/gtdldofthk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gtkersrxnb.html

Go:   // 手写双层循环
来源：http://dali.pycfn.com/Article/details/gtmjorahed.html

Ruby: nested.flatten
来源：http://dali.gotoacloud.top/Article/details/gttbvxdcth.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cheryme.top/Article/details/gtepkchoui.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gtbvokwbez.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenlongwang.top/Article/details/gtkqxkpxqz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fzhhl.top/Article/details/gtbisivats.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gtksowiqop.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuxofprd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gtzhmjfauf.html

Go:   // 手写 map[string][]T
来源：http://dali.gogol.net.cn/Article/details/gtcmllcqxr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sufxvd.cn/Article/details/gtvcenijwh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gotoacloud.top/Article/details/gthtrdcats.html

[D20] 统计每个元素出现次数
来源：http://dali.nwbrower.top/Article/details/gttrvcfhxm.html

Py:   Counter(arr)
来源：http://dali.daria6918.cn/Article/details/gtphuqmltc.html

PHP:  array_count_values($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfreujlsv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtxgbfvrdu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gtpcexytnm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.redwolf501.top/Article/details/gtfkvofibc.html

Go:   // 手写 map[T]int
来源：http://dali.xuetiantiany.cn/Article/details/gtuqmqwczx.html

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gtbazsqgvk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hnxiangtu.top/Article/details/gttgmmehdh.html

[D21] 判断是否包含某元素
来源：http://dali.jqgfzy.top/Article/details/gtoutomaqe.html

Py:   x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndymbjpn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zdqjudy.top/Article/details/gttsxpncvr.html

JS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhhobqbw.html

TS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gtoehuikip.html

Java: list.contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gttrhqckfa.html

Go:   slices.Contains(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtqkbxmelo.html

Ruby: arr.include?(x)
来源：http://dali.dashuyun.cn/Article/details/gttrvshbys.html

C#:   list.Contains(x)
来源：http://dali.hammf.cn/Article/details/gteqgwebyy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tianlin.xyz/Article/details/gtxfcvzwra.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guannengcc.top/Article/details/gtkvhxvmcm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hysaishi.cn/Article/details/gtkwemhjtd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nwbrower.top/Article/details/gtffxljxkh.html

TS:   [...arr];
来源：http://dali.cdnleiting.top/Article/details/gtkubotgvz.html

Java: new ArrayList<>(list);
来源：http://dali.jqgfzy.top/Article/details/gtqnhjoeaa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.316326.xyz/Article/details/gtuownhcjd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhongyouzk.top/Article/details/gtdlhrdpov.html

C#:   new List<int>(list);
来源：http://dali.sysykeji.top/Article/details/gtewcdresg.html

[D23] reduce 累积计算
来源：http://dali.jqgufenzy.top/Article/details/gtwozaeglx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenzaomai.com/Article/details/gtgeivzfxk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigufen.top/Article/details/gtzwqotrnm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gtufjzbtzi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gttkjwmcft.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.svipenyu.cn/Article/details/gtipanrviy.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gteqicwcpa.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.316326.xyz/Article/details/gtiawflnpj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.9152youxi.cn/Article/details/gtutvcqfmm.html

[D24] 字典 / Map 基本操作
来源：http://dali.ivvv.top/Article/details/gtfdqkqvjk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tianlin.xyz/Article/details/gtbmvgtixw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gogol.net.cn/Article/details/gtahfylswe.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.snrcjt.cn/Article/details/gtlgdguizc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtxitxblir.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fzhhl.top/Article/details/gttwhxekwn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgfzy.top/Article/details/gtlwmmrteq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvfjujbe.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jyoumei.cn/Article/details/gtvbgzyjfd.html

[D25] Set 集合去重与交并差
来源：http://dali.guowangkeji.top/Article/details/gtcyiqalju.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnqzz.top/Article/details/gtgsklvqnf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.andypj.xyz/Article/details/gtvbexvrqq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenlongwang.top/Article/details/gtlwoqwgvp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.vqdsnc.cn/Article/details/gtikolpyfb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ybcxt.top/Article/details/gtomkcumda.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhengqikj.top/Article/details/gtzyaahwxb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jlsjyb.cn/Article/details/gtvbjuhzpy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtmxdentia.html

[D26] 数组转字符串
来源：http://dali.yuanzhike.top/Article/details/gtcddkmzuh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shzxlz.cn/Article/details/gtqsqfwere.html

PHP:  implode(", ", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtmlxgvxly.html

JS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtgfiwiuub.html

TS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaycptxxa.html

Java: String.join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gthtaohnui.html

Go:   strings.Join(strs, ", ")
来源：http://dali.haohaochexian.top/Article/details/gtrpnright.html

Ruby: arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtixfaazzo.html

C#:   string.Join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gtftuxuxvq.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtajnvzxhz.html

E. 字符串处理
来源：http://dali.fengsongda.top/Article/details/gtboykyunr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtzpuwoqnr.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtsxpdntdi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hongshengwenyu.top/Article/details/gtncpbkztq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhengqikj.top/Article/details/gtponuecll.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtjdaihbir.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gtbkeyplhc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuetiantiany.cn/Article/details/gtvhdetiaa.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.bjfxy.top/Article/details/gtztetekgg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangshuangyany.cn/Article/details/gtzymvounf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtmzftqocd.html

[E02] 重复字符串
来源：http://dali.yj20258888.top/Article/details/gtxgldvvpw.html

Py:   "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtyhqrkfas.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnxiangtu.top/Article/details/gtktbdgogf.html

JS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtgyvdauzp.html

TS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtipxghtjy.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtjrwgmqvg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jiagoushi.top/Article/details/gthhjewsbm.html

Ruby: "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gtfmzxkfbi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenlongwang.top/Article/details/gtnjdgsxcr.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtkmsfwfdi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.0kj1m.cn/Article/details/gtqtjjeagb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtzueycajh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtkmpcogne.html

TS:   s.slice(1, 4)
来源：http://dali.havefunace.top/Article/details/gtibyhdhem.html

Java: s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtarcnfuhq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sysykeji.top/Article/details/gtelryoyze.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pengpengdd.cyou/Article/details/gtpweodixv.html

C#:   s.Substring(1, 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizbmxayz.html

[E04] 查找子串位置
来源：http://dali.meibo888.top/Article/details/gtrmbkfmad.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gtquumjhrc.html

PHP:  strpos($s, "x");
来源：http://dali.sweek.top/Article/details/gtnmnkhkjn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sweek.top/Article/details/gtttusmdtv.html

TS:   s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtlfwswtrt.html

Java: s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtqngvrqnm.html

Go:   strings.Index(s, "x")
来源：http://dali.yangfankeji.com/Article/details/gtojxgwfno.html

Ruby: s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlkyuiqx.html

C#:   s.IndexOf("x")
来源：http://dali.birdmap.top/Article/details/gtcbdsabbd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.9152youxi.cn/Article/details/gtibframhj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shzxlz.cn/Article/details/gtlvuoyezr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigufen.top/Article/details/gturzagjjb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtajndqupr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sysykeji.top/Article/details/gtwhblmblx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtovnurfrz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pycfn.com/Article/details/gtssusoxns.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhoulong.xyz/Article/details/gtstmnmjnu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtjahmvogk.html

[E06] 替换子串
来源：http://dali.hnxiangtu.top/Article/details/gtjvhqszja.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtquddqbfz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgfzy.top/Article/details/gtvscwxpwv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtyvgxqeyo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtkqrkwdct.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtdnevdmnl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gtqwqpsphe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtesxcybia.html

C#:   s.Replace("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtdbihqjsj.html

[E07] 按分隔符拆分
来源：http://dali.smart0.xyz/Article/details/gtltmffpxj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.bjfxy.top/Article/details/gtloeysavp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.bjfxy.top/Article/details/gtutxvpjzr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yangfankeji.com/Article/details/gtueyicyub.html

TS:   s.split(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqiomkhdx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.mhx1999.top/Article/details/gtffyuuoao.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yvedp.cn/Article/details/gtpjjdliox.html

Ruby: s.split(",");  s.split
来源：http://dali.cashguo.top/Article/details/gtlerolatw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gtmlyogynv.html

[E08] 数组按分隔符合并
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfydkjgqs.html

Py:   ",".join(items)
来源：http://dali.tian-w.cn/Article/details/gtszpjmqhq.html

PHP:  implode(",", $items);
来源：http://dali.zhixingplan.top/Article/details/gtrmmlzbsr.html

JS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtzlupnrzb.html

TS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gttgrqzxsr.html

Java: String.join(",", items)
来源：http://dali.zycfv.cn/Article/details/gtogdotdxb.html

Go:   strings.Join(items, ",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrojinwsm.html

Ruby: items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtkxnvmvmp.html

C#:   string.Join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gttxnwuzul.html

[E09] 去除所有空白字符
来源：http://dali.zhongyouzk.top/Article/details/gtjhqcccmn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yonumen.top/Article/details/gtyrueklvq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxizcsozv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtxmyowbkv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gtonlcmpfe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gttwdrypim.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aizwys.cn/Article/details/gtbkixznle.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.redwolf501.top/Article/details/gtfgxyxdae.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gtshsabkvi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jianghu66.top/Article/details/gtmgfnnskh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtnrxxqojb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cashguo.top/Article/details/gtrsldoyhv.html

JS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtwjqwynjn.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtbpadinvd.html

Java: String.format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtesfqlcut.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtunhbuqqk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtvlcyqybh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnxiangtu.top/Article/details/gtjtpzbfzk.html

[E11] 反转字符串
来源：http://dali.chenzaomai.com/Article/details/gtwhyndias.html

Py:   s[::-1]
来源：http://dali.xuanzx.com/Article/details/gtchxznzud.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtwfjhwiai.html

JS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtyjyeydli.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtuxtddfoy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigufen.top/Article/details/gtgcxjxxaq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.bjfxy.top/Article/details/gtidsmhgpj.html

Ruby: s.reverse
来源：http://dali.sysykeji.top/Article/details/gtlfmzbrss.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gtqxxgdaxr.html

[E12] 统计某字符出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtrfssoxgc.html

Py:   s.count("a")
来源：http://dali.fengsongda.top/Article/details/gtkvbyisdd.html

PHP:  substr_count($s, "a");
来源：http://dali.snrcjt.cn/Article/details/gtfddtnwpy.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtlsbmhrpk.html

TS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gtuhmqatjw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.meibo888.top/Article/details/gtcjhpngmg.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgufenzy.top/Article/details/gtsifdzeuh.html

Ruby: s.count("a")
来源：http://dali.xziqi.cn/Article/details/gtdfdsqnji.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sufxvd.cn/Article/details/gtwoqzmjix.html

[E13] 逐字符遍历
来源：http://dali.c1oappe.top/Article/details/gttoexevqg.html

Py:   for ch in s: print(ch)
来源：http://dali.kuanghao11.cn/Article/details/gthtkulrkc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtorjvgkbw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtfgqrarfs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtesccpqqa.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xylfe.cn/Article/details/gtvvazqhsz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sweek.top/Article/details/gttlxekedh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangshuangyany.cn/Article/details/gtjkvrdonx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtnpbaaxuv.html

[E14] URL 编码与 Base64
来源：http://dali.wangshuangyany.cn/Article/details/gtiligimad.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhengqikj.top/Article/details/gtoupimiyr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pycfn.com/Article/details/gtvoatehsu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangdashe.top/Article/details/gttliktdol.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuanzx.com/Article/details/gtpznxevuk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gzhubu.top/Article/details/gtnlmdyvnv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dashuyun.cn/Article/details/gtpirxtimm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aibaodan.cn/Article/details/gthitncmmc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gtgpgcgcks.html

[E15] HTML 转义 / 反转义
来源：http://dali.daxiang520.top/Article/details/gtusthjdtf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxinkj.top/Article/details/gtmofqzmyj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.meibo888.top/Article/details/gtynzurfpd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xinyue.icu/Article/details/gtczxerkzc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.havefunace.top/Article/details/gtzrjovtmk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sufxvd.cn/Article/details/gtluhahxpg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gtahbilnrn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yonumen.top/Article/details/gtuhmrbokj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dianchejie.cn/Article/details/gtuewzicnp.html

[E16] 数字千分位
来源：http://dali.daxiang520.top/Article/details/gthqwfulzo.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigfzy.top/Article/details/gtfddmvrky.html

PHP:  number_format(1234567);
来源：http://dali.chenlongwang.top/Article/details/gtquthkuca.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gtbjaebksh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gtpiunspgv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaufdwvtg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuanzx.com/Article/details/gtqnfiknzd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gtanyxvqyz.html

C#:   1234567.ToString("N0")
来源：http://dali.xylfe.cn/Article/details/gtqawimryu.html

[E17] 首字母大写
来源：http://dali.hfpthk.cn/Article/details/gtnbvpeqwe.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuanzx.com/Article/details/gtudbsonxp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sysykeji.top/Article/details/gtzceeezex.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtunjxtmiq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gtfnkflpne.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guannengcc.top/Article/details/gtffghbifb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guowangkeji.top/Article/details/gtclmijlsl.html

Ruby: s.capitalize
来源：http://dali.sysykeji.top/Article/details/gtmgodwxak.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhongyouzk.top/Article/details/gttyfkprog.html

[E18] 模板占位符替换
来源：http://dali.wangdashe.top/Article/details/gtyvzrmyls.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqggiaar.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangshuangyany.cn/Article/details/gttmilwaey.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtxdgrjkhr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtwmcredxa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtpskbwuym.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjzegfju.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ybcxt.top/Article/details/gtnmobjnku.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gttfvhmsdq.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gtfmugcubl.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gtchmfykwq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.bjfxy.top/Article/details/gtcqqsutnt.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gtjddrlbiq.html

TS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gttvmmdarb.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtogndnrhg.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgufenzy.top/Article/details/gtcuoovklh.html

Ruby: s.lines
来源：http://dali.kuanghao11.cn/Article/details/gtkwpturub.html

C#:   s.Split('\n')
来源：http://dali.daxiang520.top/Article/details/gtnuwrtjqs.html

[E20] 判断字符串是否为空
来源：http://dali.jqgufenzy.top/Article/details/gttgptefff.html

Py:   if not s:
来源：http://dali.aibaodan.cn/Article/details/gteznxccsb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tian-w.cn/Article/details/gtuxjruytl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gtuofryewi.html

TS:   if (s === "") {}
来源：http://dali.yj202588.top/Article/details/gtczoriaev.html

Java: if (s.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtlfmzawzv.html

Go:   if s == "" {}
来源：http://dali.aizwys.cn/Article/details/gtidzlytwx.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gtstgchdjt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hfpthk.cn/Article/details/gtjbpfdxve.html

[E21] 超长截断加省略号
来源：http://dali.cashguo.top/Article/details/gtzizehcki.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.meibo888.top/Article/details/gterbdgqcu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtktpchqsi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinoovnyj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtgwiygxmc.html


<!-- 参考信息 -->