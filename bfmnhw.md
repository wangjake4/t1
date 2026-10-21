代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.yueranfly.top/Article/details/gtgnprgsdv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.birdmap.top/Article/details/gtjlgtafon.html

TS:   Math.max(...arr);
来源：http://dali.chenlongwang.top/Article/details/gtsvixhtdv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tianlin.xyz/Article/details/gtreofwdms.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtvzyqlmox.html

Ruby: arr.max;  arr.min
来源：http://dali.daria6918.cn/Article/details/gtqgxriept.html

C#:   list.Max();  list.Min()
来源：http://dali.yongpay.top/Article/details/gtefvckska.html

[D18] 扁平化嵌套数组
来源：http://dali.aizwys.cn/Article/details/gtfmzphryx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cheryme.top/Article/details/gtfuhiepyg.html

PHP:  array_merge(...$nested);
来源：http://dali.yongpay.top/Article/details/gtkxhtgbhy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.birdmap.top/Article/details/gtifxxeugm.html

TS:   nested.flat();
来源：http://dali.quarkkingdee.top/Article/details/gtuqqeipev.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.svipenyu.cn/Article/details/gtdbhtneds.html

Go:   // 手写双层循环
来源：http://dali.andypj.xyz/Article/details/gtvqtesknv.html

Ruby: nested.flatten
来源：http://dali.svipenyu.cn/Article/details/gtrrpdbxmf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.redwolf501.top/Article/details/gtgtqaqwif.html

[D19] 按字段分组
来源：http://dali.daria6918.cn/Article/details/gtpxddnkok.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuxming.cn/Article/details/gtcnresjei.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.haohaochexian.top/Article/details/gtiqiijier.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zycfv.cn/Article/details/gtshmknocu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gtvlivifbi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzhqjegy.html

Go:   // 手写 map[string][]T
来源：http://dali.yangfankeji.com/Article/details/gtfggnasry.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ppjwa.cn/Article/details/gttgiulrmv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhongyouzk.top/Article/details/gtrtldnnoz.html

[D20] 统计每个元素出现次数
来源：http://dali.yonumen.top/Article/details/gtvclxxfba.html

Py:   Counter(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtfvsojofp.html

PHP:  array_count_values($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtmmbtegvi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtbpljujzb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gtajbfnudq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.redwolf501.top/Article/details/gtzlfyedyi.html

Go:   // 手写 map[T]int
来源：http://dali.fzhhl.top/Article/details/gtvynyzmiv.html

Ruby: arr.tally
来源：http://dali.aibaodan.cn/Article/details/gtynhxqwup.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xziqi.cn/Article/details/gtvjvpljkk.html

[D21] 判断是否包含某元素
来源：http://dali.zdqjudy.top/Article/details/gtloqiimtk.html

Py:   x in arr
来源：http://dali.svipenyu.cn/Article/details/gtmffeqfnt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tanke756.top/Article/details/gtvevrdzdg.html

JS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gtsnhnvdww.html

TS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtfuowixwa.html

Java: list.contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtpxyskuvk.html

Go:   slices.Contains(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtdrrsvyhi.html

Ruby: arr.include?(x)
来源：http://dali.daxiang520.top/Article/details/gthihgszjx.html

C#:   list.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gtjlakihbn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuxming.cn/Article/details/gtxwmmfbtl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cucudq.cn/Article/details/gthhxtdfib.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hfpthk.cn/Article/details/gtqvwhvyuz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtfrdkmqkp.html

TS:   [...arr];
来源：http://dali.ppjwa.cn/Article/details/gtednktlyw.html

Java: new ArrayList<>(list);
来源：http://dali.meibo888.top/Article/details/gtjngdhpzw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbexfepk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojmzncon.html

C#:   new List<int>(list);
来源：http://dali.xinyue.icu/Article/details/gtllfxoazx.html

[D23] reduce 累积计算
来源：http://dali.ydzc1.top/Article/details/gtmwruviwp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yongpay.top/Article/details/gtkkvxennw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shuidangran.top/Article/details/gtwdsuilcg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gtoikrekdm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gthcnyvelg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tian-w.cn/Article/details/gtgjwywkrb.html

Go:   // 手写循环
来源：http://dali.snrcjt.cn/Article/details/gticrbccmr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgfzy.top/Article/details/gtbbtbuidz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gtirdwulua.html

[D24] 字典 / Map 基本操作
来源：http://dali.hfpthk.cn/Article/details/gtddcqclqe.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgrdaerj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tianlin.xyz/Article/details/gtdpgjrdth.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtusqaqdky.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtndwwwcqg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gtohvtxtww.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.smart0.xyz/Article/details/gtintazujp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xinyue.icu/Article/details/gtjthqjlei.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.smart0.xyz/Article/details/gtxosjleff.html

[D25] Set 集合去重与交并差
来源：http://dali.ydzc1.top/Article/details/gtqlohsrgu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sxryk.cn/Article/details/gtsfbbywib.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.0kj1m.cn/Article/details/gtvciitwnp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqnbgsij.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jlsjyb.cn/Article/details/gttdjsxibf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj202588.top/Article/details/gtitzqivrp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.svipenyu.cn/Article/details/gtkciwmutz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shzxlz.cn/Article/details/gtpivgbnta.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.fzhhl.top/Article/details/gtqqtlkuic.html

[D26] 数组转字符串
来源：http://dali.chenzaomai.com/Article/details/gtlvhmrhql.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gotoacloud.top/Article/details/gtkwkasotv.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gttzwjrjrv.html

JS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtovxphppz.html

TS:   arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gtrlaywxmr.html

Java: String.join(", ", list)
来源：http://dali.birdmap.top/Article/details/gtczyzljvf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xylfe.cn/Article/details/gtpglfmyea.html

Ruby: arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gtfjrjocvw.html

C#:   string.Join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gtvwrsnqvt.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtifmeeeca.html

E. 字符串处理
来源：http://dali.cheryme.top/Article/details/gtvgexdnak.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtxgriusfq.html

[E01] 拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtlittxtgv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xinyue.icu/Article/details/gtyaqmisxu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigufen.top/Article/details/gtscfwnixb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtzxdixmxx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gtljetbnav.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ppjwa.cn/Article/details/gtvnwfzdgo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aizwys.cn/Article/details/gtttzkvdwt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gtrbdopqum.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtmyvuavym.html

[E02] 重复字符串
来源：http://dali.ivvv.top/Article/details/gtwigewane.html

Py:   "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gtfqglqitl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhixingplan.top/Article/details/gtovvbnmnk.html

JS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtgobeycwp.html

TS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtbdlbjgqg.html

Java: "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gtqcrtaaph.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guowangkeji.top/Article/details/gtielngtas.html

Ruby: "ab" * 3
来源：http://dali.yueranfly.top/Article/details/gthxkafihr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.iojbl.cn/Article/details/gtnsmmgcgx.html

[E03] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gtcpcecmyi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dashuyun.cn/Article/details/gtsyzlzzjz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtvjehdgoo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtcuzkfzhz.html

TS:   s.slice(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtzgismwac.html

Java: s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtcxbeniwn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tian-w.cn/Article/details/gtuyjwtdet.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhengqikj.top/Article/details/gtolgcnufe.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigfzy.top/Article/details/gtpdtlxawh.html

[E04] 查找子串位置
来源：http://dali.zdqjudy.top/Article/details/gtoufvghdh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangdashe.top/Article/details/gtiauiztdc.html

PHP:  strpos($s, "x");
来源：http://dali.hammf.cn/Article/details/gtwcphoajk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258888.top/Article/details/gteulzbnmf.html

TS:   s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtezqgocrp.html

Java: s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtjprdaxby.html

Go:   strings.Index(s, "x")
来源：http://dali.gogol.net.cn/Article/details/gtnpegsgdr.html

Ruby: s.index("x")
来源：http://dali.jinqigufen.top/Article/details/gtwovuccbh.html

C#:   s.IndexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gtdrkluhvi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jlsjyb.cn/Article/details/gtpnchxbqf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.redwolf501.top/Article/details/gtheultmui.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shzxlz.cn/Article/details/gtrefqeajp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtvnxbzmwp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenlongwang.top/Article/details/gtriouzffe.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtsvrcfihf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pengpengdd.cyou/Article/details/gtymfznzzt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuanzhike.top/Article/details/gtfflxhifb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtuwxynvag.html

[E06] 替换子串
来源：http://dali.zhoulong.xyz/Article/details/gtnpbhrryr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtemkncqhq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gogol.net.cn/Article/details/gtnngimfzu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfyrjiri.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtcnoljusl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtlvfwvbmo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gtoyxdrqky.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtzltrnxzu.html

C#:   s.Replace("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtfjqwipxf.html

[E07] 按分隔符拆分
来源：http://dali.aizwys.cn/Article/details/gtrfakldaf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daria6918.cn/Article/details/gtctvpdylr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogfallfv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiowwgspj.html

TS:   s.split(",")
来源：http://dali.zycfv.cn/Article/details/gtpsgfzzol.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guannengcc.top/Article/details/gtjmtfatte.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hfpthk.cn/Article/details/gtaaphwven.html

Ruby: s.split(",");  s.split
来源：http://dali.zdqjudy.top/Article/details/gthuxgyciv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnxiangtu.top/Article/details/gtgbtdqzpp.html

[E08] 数组按分隔符合并
来源：http://dali.haohaochexian.top/Article/details/gtuwlfobpa.html

Py:   ",".join(items)
来源：http://dali.yangfankeji.com/Article/details/gtdjzbhcga.html

PHP:  implode(",", $items);
来源：http://dali.yj20258.top/Article/details/gtxqczfvfk.html

JS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtyiixdwyc.html

TS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtceknyzli.html

Java: String.join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtjvyveyvo.html

Go:   strings.Join(items, ",")
来源：http://dali.guowangkeji.top/Article/details/gttzeybbgm.html

Ruby: items.join(",")
来源：http://dali.tian-w.cn/Article/details/gtiqpnbjhi.html

C#:   string.Join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gtshjjhiba.html

[E09] 去除所有空白字符
来源：http://dali.chenzaomai.com/Article/details/gtkwoxqytq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtczujrcij.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aibaodan.cn/Article/details/gtalhydvwk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gthqqlqhxr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gtkcfdqdgj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aizwys.cn/Article/details/gtqblokxcf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shangyingyoupin.top/Article/details/gtojqkpwts.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daxiang520.top/Article/details/gtjrzqjarh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexxqokgn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hongshengwenyu.top/Article/details/gthxgysvti.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaanogbjv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shzxlz.cn/Article/details/gtwkwjznin.html

JS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtwmhopzga.html

TS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtvzojvhjz.html

Java: String.format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtcvejuads.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtoaemfubx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtqqmcurgb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zycfv.cn/Article/details/gtzuihypnt.html

[E11] 反转字符串
来源：http://dali.ehwqpu.com/Article/details/gthxciuthm.html

Py:   s[::-1]
来源：http://dali.sweek.top/Article/details/gtgmonqfjw.html

PHP:  strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtxgtsyung.html

JS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtjgsvnjwp.html

TS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtocsbofqg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sxryk.cn/Article/details/gtomvukwlw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jianghu66.top/Article/details/gtdtpguiuc.html

Ruby: s.reverse
来源：http://dali.tanke756.top/Article/details/gtxoilwiuk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gtpetwqhep.html

[E12] 统计某字符出现次数
来源：http://dali.nanxinkj.top/Article/details/gtglscdxgu.html

Py:   s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpbzztrf.html

PHP:  substr_count($s, "a");
来源：http://dali.meibo888.top/Article/details/gtosphsesx.html

JS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gtbmfkjqzy.html

TS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtmfciioln.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cashguo.top/Article/details/gthsmaztkd.html

Go:   strings.Count(s, "a")
来源：http://dali.zhixingplan.top/Article/details/gtvrldchqv.html

Ruby: s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtcaorkuxe.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hongshengwenyu.top/Article/details/gtaisetzob.html

[E13] 逐字符遍历
来源：http://dali.wangdashe.top/Article/details/gtaepsiske.html

Py:   for ch in s: print(ch)
来源：http://dali.ehwqpu.com/Article/details/gtlldthxjn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ehwqpu.com/Article/details/gtjgvmsdlj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gtihepjanx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtjucsndgb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gttlohjdcd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzayvdxz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gthewrlzgn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtpfpzpobe.html

[E14] URL 编码与 Base64
来源：http://dali.chenlongwang.top/Article/details/gtjclgvznk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gtttdazbrl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtesasocko.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sweek.top/Article/details/gtqjaoijuv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.smart0.xyz/Article/details/gtatmtcxhs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkamojeeb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guannengcc.top/Article/details/gthfrpounq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cashguo.top/Article/details/gtrpzmnoeu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtdqjnsidz.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangtech.top/Article/details/gtyohrodio.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.redwolf501.top/Article/details/gtvsrvaukt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ppjwa.cn/Article/details/gtpnnkhvxj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zdqjudy.top/Article/details/gtexufveug.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xinyue.icu/Article/details/gtdoffgpcc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guannengcc.top/Article/details/gtkfzrvkrq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daxiang520.top/Article/details/gtysanvfml.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtyqjysvyl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.birdmap.top/Article/details/gtrgqxnzll.html

[E16] 数字千分位
来源：http://dali.aizwys.cn/Article/details/gtcvbbyikf.html

Py:   f"{1234567:,}"
来源：http://dali.zhongyouzk.top/Article/details/gtnktshijg.html

PHP:  number_format(1234567);
来源：http://dali.tanke756.top/Article/details/gthkaatqtt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gtveqvnuei.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuygzskyq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gtwitxmfaz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yanxiufei.cn/Article/details/gtceewoiqi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.snrcjt.cn/Article/details/gtgqrooxcz.html

C#:   1234567.ToString("N0")
来源：http://dali.kuanghao11.cn/Article/details/gtrcwslfab.html

[E17] 首字母大写
来源：http://dali.tianlin.xyz/Article/details/gtsritiqoi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.svipenyu.cn/Article/details/gttulhsukw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gtffgqopst.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gtglrxdjnc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtpvriizur.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtakpfnvma.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.0kj1m.cn/Article/details/gtrstaaurs.html

Ruby: s.capitalize
来源：http://dali.vqdsnc.cn/Article/details/gtopvygpgh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangtech.top/Article/details/gtkaayldvx.html

[E18] 模板占位符替换
来源：http://dali.chenzaomai.com/Article/details/gtjakrkjrr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ehwqpu.com/Article/details/gtiwsvogfh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ehwqpu.com/Article/details/gtvgeemdia.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtdcbftxqy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtzncehnjh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtrkbhzpcu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtysjyxfjw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gtdcwirkdp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cdnleiting.top/Article/details/gtodqsfmcg.html

[E19] 多行文本按行拆分
来源：http://dali.hammf.cn/Article/details/gtuhbbqzvq.html

Py:   s.splitlines()
来源：http://dali.shangyingyoupin.top/Article/details/gtvyyrvcoz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtkphmqftm.html

JS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gtyamclqwj.html

TS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gtvksxokwo.html

Java: s.lines().toList()
来源：http://dali.pycfn.com/Article/details/gtpozyfmal.html

Go:   strings.Split(s, "\n")
来源：http://dali.zycfv.cn/Article/details/gtakaglpra.html

Ruby: s.lines
来源：http://dali.gogol.net.cn/Article/details/gtyfaimcaq.html

C#:   s.Split('\n')
来源：http://dali.nwbrower.top/Article/details/gtwjsttnko.html

[E20] 判断字符串是否为空
来源：http://dali.haohaochexian.top/Article/details/gtohexxnao.html

Py:   if not s:
来源：http://dali.ybcxt.top/Article/details/gttcqxvwse.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgfzy.top/Article/details/gtnxhkmeht.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsozhpel.html

TS:   if (s === "") {}
来源：http://dali.jianghu66.top/Article/details/gtbtuwxmlo.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gtxqquzoog.html

Go:   if s == "" {}
来源：http://dali.fengsongda.top/Article/details/gtssfcdptw.html

Ruby: if s.empty?
来源：http://dali.guowangkeji.top/Article/details/gtcbebykjv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xinyue.icu/Article/details/gtoodqbatt.html

[E21] 超长截断加省略号
来源：http://dali.ybcxt.top/Article/details/gtjsblxjpb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnxiangtu.top/Article/details/gtzowcjewp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrabdflv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtxjnjjllg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtmmeaacto.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtfoggecnk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gtwfssksry.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gttpjeipwy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gttrtfqwvo.html

[E22] 字节长度与字符长度
来源：http://dali.jqgfzy.top/Article/details/gtqysmjrxq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yvedp.cn/Article/details/gthadxjfst.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtxicfhomg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtttumjhaj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtufrnvpdm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.9152youxi.cn/Article/details/gtdododqek.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.redwolf501.top/Article/details/gttoutoysw.html

Ruby: s.bytesize;  s.length
来源：http://dali.yonumen.top/Article/details/gtgqahwetx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ivvv.top/Article/details/gtsabgofan.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtdszwmwib.html

F. 文件与目录
来源：http://dali.redwolf501.top/Article/details/gtgtbidbla.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtlwfhfuvu.html

[F01] 读取整个文件
来源：http://dali.meibo888.top/Article/details/gtfjsjcfmg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tanke756.top/Article/details/gtvmwpkejz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtcfemjkjl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gtnqirlaxk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtgwumcqkb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtmkepnuxx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nwbrower.top/Article/details/gtxsgrapdb.html

Ruby: File.read("a.txt")
来源：http://dali.hammf.cn/Article/details/gtyedltnxj.html


<!-- 参考信息 -->