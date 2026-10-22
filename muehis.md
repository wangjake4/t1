代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.0kj1m.cn/Article/details/gtrsifoouu.html

Ruby: arr.max;  arr.min
来源：http://dali.tian-w.cn/Article/details/gtsiuigafy.html

C#:   list.Max();  list.Min()
来源：http://dali.hfpthk.cn/Article/details/gtzdeydpab.html

[D18] 扁平化嵌套数组
来源：http://dali.chenzaomai.com/Article/details/gtbdgxdtlt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhongyouzk.top/Article/details/gtngyjkwmx.html

PHP:  array_merge(...$nested);
来源：http://dali.quarkkingdee.top/Article/details/gtmbxwitms.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sweek.top/Article/details/gtkvcictwa.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gtsnnckdhl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.c1oappe.top/Article/details/gtizoosdro.html

Go:   // 手写双层循环
来源：http://dali.birdmap.top/Article/details/gtecgllrug.html

Ruby: nested.flatten
来源：http://dali.redwolf501.top/Article/details/gtxxjpgena.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gthetenmkv.html

[D19] 按字段分组
来源：http://dali.gaohongyu789.top/Article/details/gtshgnhjeu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yongpay.top/Article/details/gtkgydiaio.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gtdxtmgngc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.mhx1999.top/Article/details/gtajwqanfb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.meibo888.top/Article/details/gtinkcezzo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhiwuduotai.top/Article/details/gtsfocsxni.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnjnwtap.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xziqi.cn/Article/details/gtmowltqac.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.birdmap.top/Article/details/gtjeqrpbzo.html

[D20] 统计每个元素出现次数
来源：http://dali.zhengqikj.top/Article/details/gttncgfhfd.html

Py:   Counter(arr)
来源：http://dali.cqqwz.cn/Article/details/gtrlimejpa.html

PHP:  array_count_values($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtksjdupsp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtdzjkmwao.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gtreccwlos.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guannengcc.top/Article/details/gtugtptyoi.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gthsbhzpef.html

Ruby: arr.tally
来源：http://dali.redwolf501.top/Article/details/gtbhbolwuf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxinkj.top/Article/details/gtwfccxbus.html

[D21] 判断是否包含某元素
来源：http://dali.hfpthk.cn/Article/details/gteofyymeo.html

Py:   x in arr
来源：http://dali.iojbl.cn/Article/details/gtybssmskj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbyqgxwy.html

JS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gthdfcvlrs.html

TS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gtgiuonodq.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtrtikpjcm.html

Go:   slices.Contains(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtqowpsumz.html

Ruby: arr.include?(x)
来源：http://dali.hammf.cn/Article/details/gttrbreobe.html

C#:   list.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtitrepttv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gaohongyu789.top/Article/details/gtmuawwwrg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fengsongda.top/Article/details/gtrpudgukf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnqzz.top/Article/details/gtunnwhysc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gotoacloud.top/Article/details/gtsmdyzklu.html

TS:   [...arr];
来源：http://dali.hnqzz.top/Article/details/gtnaqwnpnc.html

Java: new ArrayList<>(list);
来源：http://dali.hywenlv.cn/Article/details/gtwuyxmnwv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zycfv.cn/Article/details/gtxfumoyql.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jyoumei.cn/Article/details/gtefwtkppj.html

C#:   new List<int>(list);
来源：http://dali.svipenyu.cn/Article/details/gtfofyhtgo.html

[D23] reduce 累积计算
来源：http://dali.yj20258.top/Article/details/gtsvkaocjb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tianlin.xyz/Article/details/gtrgwbgeqc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtzycjhihn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gtgzkdhvnp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxeotbtf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zdqjudy.top/Article/details/gtnethmeab.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gtlaqhpuhw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sweek.top/Article/details/gtryqsjxtm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.mhx1999.top/Article/details/gtatlazytb.html

[D24] 字典 / Map 基本操作
来源：http://dali.redwolf501.top/Article/details/gtmpjzezdw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cqqwz.cn/Article/details/gthqadqctw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.bjfxy.top/Article/details/gtxwjcazet.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jiagoushi.top/Article/details/gtbiadmmzc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtixaewoon.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.andypj.xyz/Article/details/gtgpunciiu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cheryme.top/Article/details/gtybbwrjgo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aizwys.cn/Article/details/gtnfepunbz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zdqjudy.top/Article/details/gtkzcmqxah.html

[D25] Set 集合去重与交并差
来源：http://dali.gogol.net.cn/Article/details/gtvyictusx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pengpengdd.cyou/Article/details/gtkxiedzsn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.andypj.xyz/Article/details/gtcmhjnrvf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ybcxt.top/Article/details/gtwcpqzleq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgfzy.top/Article/details/gtgzydpaja.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gthmzlipzh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xziqi.cn/Article/details/gtkbzxebaq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtbrgvwwrn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gtqslvvxos.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gtcejbfclf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuanzhike.top/Article/details/gtwphchnts.html

PHP:  implode(", ", $arr);
来源：http://dali.hfpthk.cn/Article/details/gtztjjymno.html

JS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtpabcwpxn.html

TS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtgburdhur.html

Java: String.join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gtyvviehqj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258888.top/Article/details/gtlmqtmprf.html

Ruby: arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gtxomvopmq.html

C#:   string.Join(", ", list)
来源：http://dali.yj202588.top/Article/details/gtgwqjuhht.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtzkwgythe.html

E. 字符串处理
来源：http://dali.aizwys.cn/Article/details/gtggydetkk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtuwcyarca.html

[E01] 拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtjepgspds.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.redwolf501.top/Article/details/gtxxpssabk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.c1oappe.top/Article/details/gtjktilwxh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gterumgbzm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsflgbkoa.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xylfe.cn/Article/details/gtjizfodph.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cheryme.top/Article/details/gtutlcwiby.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuanzhike.top/Article/details/gtgtnhmomc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtvwndmgqi.html

[E02] 重复字符串
来源：http://dali.jianghu66.top/Article/details/gtpuharoyq.html

Py:   "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gtxnrabizt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ppjwa.cn/Article/details/gttotdmjeh.html

JS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtxxiriffg.html

TS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtcpudlgqm.html

Java: "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmaivczr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.iojbl.cn/Article/details/gtoxlemhsg.html

Ruby: "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtvtuqygpn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhengqikj.top/Article/details/gtuirkqrsq.html

[E03] 截取子串
来源：http://dali.ybcxt.top/Article/details/gtwoqwnsjn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hysaishi.cn/Article/details/gtjmbjrvqv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtvfxhggvk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtpkxqflkt.html

TS:   s.slice(1, 4)
来源：http://dali.meibo888.top/Article/details/gtjchgwpva.html

Java: s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtwukolasw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gthaobnsna.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xuanzx.com/Article/details/gtpoltrsku.html

C#:   s.Substring(1, 3)
来源：http://dali.hnqzz.top/Article/details/gtzifbrktf.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gtrhfanltm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.havefunace.top/Article/details/gtaqvacujs.html

PHP:  strpos($s, "x");
来源：http://dali.shuidangran.top/Article/details/gtyzritiiw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhixingplan.top/Article/details/gtrcxrggab.html

TS:   s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gtzjfhgmzr.html

Java: s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtwtswncjm.html

Go:   strings.Index(s, "x")
来源：http://dali.tian-w.cn/Article/details/gtmdkqqsua.html

Ruby: s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gtonucuzlv.html

C#:   s.IndexOf("x")
来源：http://dali.redwolf501.top/Article/details/gtjhmqdxvu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhixingplan.top/Article/details/gtuoxdybqf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cdnleiting.top/Article/details/gtzvnunjsl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.snrcjt.cn/Article/details/gtizipmgsk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtcweqqpsk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daxiang520.top/Article/details/gtzcwimltg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gtfoslkcni.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xinyue.icu/Article/details/gttyzsragn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shuidangran.top/Article/details/gtppjfcpzp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sysykeji.top/Article/details/gtsrzvhghc.html

[E06] 替换子串
来源：http://dali.yuxming.cn/Article/details/gtkzxfmmhp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gtqntagfwz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gotoacloud.top/Article/details/gtulfdxmsc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtuzewpjcn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtchxcfcvq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gthohtoghh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gtteunozxd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtlswubnyv.html

C#:   s.Replace("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtgyqpipmv.html

[E07] 按分隔符拆分
来源：http://dali.ivvv.top/Article/details/gtderivxie.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gtndrlwmqi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.smart0.xyz/Article/details/gtaoblykbx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gtknvvhtnz.html

TS:   s.split(",")
来源：http://dali.aibaodan.cn/Article/details/gtiustjiel.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yonumen.top/Article/details/gtpwhedykd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtpeesxlwu.html

Ruby: s.split(",");  s.split
来源：http://dali.yuxming.cn/Article/details/gtxouuvgnr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuxming.cn/Article/details/gtwbkyzfns.html

[E08] 数组按分隔符合并
来源：http://dali.tianlin.xyz/Article/details/gtmpzicvls.html

Py:   ",".join(items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrwzyqnv.html

PHP:  implode(",", $items);
来源：http://dali.cheryme.top/Article/details/gtfgtcjijb.html

JS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gtwffpqwfj.html

TS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtqshuqdyu.html

Java: String.join(",", items)
来源：http://dali.hammf.cn/Article/details/gtidjpqhcg.html

Go:   strings.Join(items, ",")
来源：http://dali.ppjwa.cn/Article/details/gtbxfyuwyl.html

Ruby: items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtgzvyvioj.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtqqgjrzux.html

[E09] 去除所有空白字符
来源：http://dali.yonumen.top/Article/details/gtsqwxwlhi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jianghu66.top/Article/details/gtgjjsxyjb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sweek.top/Article/details/gtxmeoioyy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gtlsycjqfs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gtpdcqxrna.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtkoafivfi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnxiangtu.top/Article/details/gthtteodgd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jlsjyb.cn/Article/details/gtazstcvda.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gtqizmnybs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258888.top/Article/details/gtbjqxiimt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgtgqeai.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xinyue.icu/Article/details/gtbdbhrfyx.html

JS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtuwoseptf.html

TS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtixartkvj.html

Java: String.format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblaflwkb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtdqcgzkdm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtrmrpdfgp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yonumen.top/Article/details/gtodfjocje.html

[E11] 反转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtyrarqkua.html

Py:   s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gtwhfxttsb.html

PHP:  strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtdpgyxqyp.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtazlzhcgd.html

TS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtfgkrgesy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cashguo.top/Article/details/gtphayzglu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aizwys.cn/Article/details/gtptcqmqpr.html

Ruby: s.reverse
来源：http://dali.yvedp.cn/Article/details/gtackyaksi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gtbduiwmuu.html

[E12] 统计某字符出现次数
来源：http://dali.dashuyun.cn/Article/details/gtrhrcljxr.html

Py:   s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gtowbgeekb.html

PHP:  substr_count($s, "a");
来源：http://dali.zhixingplan.top/Article/details/gtdqhpawij.html

JS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gtzqceumkb.html

TS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gthjmdubdr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenjidiqi.icu/Article/details/gtrrunsbsd.html

Go:   strings.Count(s, "a")
来源：http://dali.hammf.cn/Article/details/gtlqdtyyxh.html

Ruby: s.count("a")
来源：http://dali.daria6918.cn/Article/details/gtalzwjkny.html

C#:   s.Count(c => c == 'a')
来源：http://dali.havefunace.top/Article/details/gtamlnisay.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gtyctwgxsz.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gtbcnxrnia.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.redwolf501.top/Article/details/gtaprkfkez.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtxegbgngn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gtonxgeemw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gtfzthwiwa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnqzz.top/Article/details/gtdasdkatl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yanxiufei.cn/Article/details/gtypsktzen.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtzxixuhrd.html

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvkulfgs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenlongwang.top/Article/details/gthkjkczle.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gogol.net.cn/Article/details/gtaffsgxtq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aizwys.cn/Article/details/gtfuohgyqd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgfzy.top/Article/details/gtusktyviz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jianghu66.top/Article/details/gttyijzttt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xinyue.icu/Article/details/gtnwrrbfrg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gtjuoonobr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtgkikioop.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhongyouzk.top/Article/details/gtrjbjgukc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtmtqvcmfo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenzaomai.com/Article/details/gtegeflnpg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gotoacloud.top/Article/details/gtsumlvois.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sufxvd.cn/Article/details/gtrvoofjso.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cqqwz.cn/Article/details/gtxqrsdemm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtlrhvtxpq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtdzzorigm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hfpthk.cn/Article/details/gtsstukpbd.html

[E16] 数字千分位
来源：http://dali.smart0.xyz/Article/details/gtyeffqnym.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gtbipdqkcw.html

PHP:  number_format(1234567);
来源：http://dali.pycfn.com/Article/details/gtwluoivrh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtpfsisgsn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gtxpacqucg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gtpplrkxgz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hammf.cn/Article/details/gtuslyjxro.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xinyue.icu/Article/details/gtehxynpaw.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gtmtjnwxfc.html

[E17] 首字母大写
来源：http://dali.ppjwa.cn/Article/details/gtcawgmdxb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hongshengwenyu.top/Article/details/gtwqllcmhd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yangfankeji.com/Article/details/gtxgcyquqh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gttrcrfaab.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gterbppnch.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ydzc1.top/Article/details/gtemgegiek.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.c1oappe.top/Article/details/gtccfxatbs.html

Ruby: s.capitalize
来源：http://dali.quarkkingdee.top/Article/details/gtlsbkplgl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ivvv.top/Article/details/gtfjmtngea.html

[E18] 模板占位符替换
来源：http://dali.jlsjyb.cn/Article/details/gtajmtixge.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cashguo.top/Article/details/gtsfkggbht.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxuanxn.top/Article/details/gtnytjhitu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtcgytpubi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtkfccmxbj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtahxlczzn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtxzsngzpe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cheryme.top/Article/details/gtqnquhfhn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gtkmlroehw.html

[E19] 多行文本按行拆分
来源：http://dali.zhixingplan.top/Article/details/gtbhqcpygp.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gttmrpwnbr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.havefunace.top/Article/details/gtnodufved.html

JS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtcummcxla.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtbjdrjnqd.html

Java: s.lines().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtxmsdigee.html

Go:   strings.Split(s, "\n")
来源：http://dali.dianchejie.cn/Article/details/gtntsemehd.html

Ruby: s.lines
来源：http://dali.gzhubu.top/Article/details/gtoyibytoj.html

C#:   s.Split('\n')
来源：http://dali.yangfankeji.com/Article/details/gtqczfkydf.html

[E20] 判断字符串是否为空
来源：http://dali.jyoumei.cn/Article/details/gtbrjawqsd.html

Py:   if not s:
来源：http://dali.zhiwuduotai.top/Article/details/gtxesffgei.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.birdmap.top/Article/details/gthzvsxtbp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yanxiufei.cn/Article/details/gtfyiktxuu.html

TS:   if (s === "") {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtufjtmnzu.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtzdzolzry.html

Go:   if s == "" {}
来源：http://dali.hfpthk.cn/Article/details/gtvicsssrb.html

Ruby: if s.empty?
来源：http://dali.yangfankeji.com/Article/details/gteccmsipy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hysaishi.cn/Article/details/gtuljcdoeh.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gtooagtspj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sysykeji.top/Article/details/gtgfmpkpgb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtdyfpbfoo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksdrosiw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtqhkoaola.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gttzrdheyx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgxitpoc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gtvwqbmzjf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtqfjfflbs.html

[E22] 字节长度与字符长度
来源：http://dali.chenzaomai.com/Article/details/gtwkgxtwcy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtpcxiaayt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtsumsfxto.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtvabwzquh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtvhtdnqte.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ppjwa.cn/Article/details/gtabsjsans.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.haohaochexian.top/Article/details/gtpijyzfom.html

Ruby: s.bytesize;  s.length
来源：http://dali.jianghu66.top/Article/details/gtshqeqwxr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtragwuhvq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtxnalvzws.html

F. 文件与目录
来源：http://dali.xylfe.cn/Article/details/gtntpxfljf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gttlivquxc.html

[F01] 读取整个文件
来源：http://dali.dashuyun.cn/Article/details/gtcqdvyjds.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhengqikj.top/Article/details/gtbjnvecxu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yonumen.top/Article/details/gtsouuttst.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhengqikj.top/Article/details/gtsvlsggnn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtxwmhmnau.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtnkjaagkl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yueranfly.top/Article/details/gtktzgtmhb.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtyfxpvryw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtloyucmui.html

[F02] 逐行读取文件
来源：http://dali.ydzc1.top/Article/details/gtpnehelym.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ybcxt.top/Article/details/gttfehqdod.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yonumen.top/Article/details/gtszjlrtfj.html


<!-- 参考信息 -->