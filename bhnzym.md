代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dashuyun.cn/Article/details/gttferpkji.html

Go:   // 手写双层循环
来源：http://dali.mhx1999.top/Article/details/gthamimrmf.html

Ruby: nested.flatten
来源：http://dali.ybcxt.top/Article/details/gtvnuiqjci.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtcocbdxgs.html

[D19] 按字段分组
来源：http://dali.chenlongwang.top/Article/details/gtndkzbpyo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gtbfdeukmy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sweek.top/Article/details/gtvfgyykia.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fzhhl.top/Article/details/gtkuswqppp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gtcldqakam.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zdqjudy.top/Article/details/gtluhnheak.html

Go:   // 手写 map[string][]T
来源：http://dali.ybcxt.top/Article/details/gtupctsoee.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.0kj1m.cn/Article/details/gtvadzbnqm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcxqzocf.html

[D20] 统计每个元素出现次数
来源：http://dali.iojbl.cn/Article/details/gtusmlizpo.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtonxlkbnw.html

PHP:  array_count_values($arr);
来源：http://dali.guannengcc.top/Article/details/gtgksxiyva.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgjjcxra.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtrvetafhx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuanzx.com/Article/details/gttzwojjee.html

Go:   // 手写 map[T]int
来源：http://dali.mhx1999.top/Article/details/gtmgzrxrdl.html

Ruby: arr.tally
来源：http://dali.xuanzx.com/Article/details/gtwekvlyii.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fzhhl.top/Article/details/gtfzssaarc.html

[D21] 判断是否包含某元素
来源：http://dali.vqdsnc.cn/Article/details/gtoarslpzk.html

Py:   x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakhghnqf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zycfv.cn/Article/details/gtgyebakzw.html

JS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gtvwsppgac.html

TS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gtleeksmsg.html

Java: list.contains(x)
来源：http://dali.mhx1999.top/Article/details/gtuqcodtge.html

Go:   slices.Contains(arr, x)
来源：http://dali.yongpay.top/Article/details/gtrywsodke.html

Ruby: arr.include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gtqmlwaegs.html

C#:   list.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gtfciolcxj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnxiangtu.top/Article/details/gtfreikcqj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gtkfixempa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.9152youxi.cn/Article/details/gtlvhpiryi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yonumen.top/Article/details/gtumynluuh.html

TS:   [...arr];
来源：http://dali.sysykeji.top/Article/details/gtrxrogqfm.html

Java: new ArrayList<>(list);
来源：http://dali.xylfe.cn/Article/details/gtktfalpix.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.havefunace.top/Article/details/gtbpvlfint.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhengqikj.top/Article/details/gtmhbnudig.html

C#:   new List<int>(list);
来源：http://dali.tianlin.xyz/Article/details/gtjhrzarau.html

[D23] reduce 累积计算
来源：http://dali.jqgfzy.top/Article/details/gtilfapvni.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hywenlv.cn/Article/details/gtvxgzrehv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cucudq.cn/Article/details/gtghfmxdub.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gtrscjyzme.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gthxutxuvg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.c1oappe.top/Article/details/gtknaaxlfd.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtjqayxjtk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.havefunace.top/Article/details/gtwglsbpzm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgufenzy.top/Article/details/gtsorrbmfb.html

[D24] 字典 / Map 基本操作
来源：http://dali.jlsjyb.cn/Article/details/gtmwmwsdoo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gtslerkfqs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jiagoushi.top/Article/details/gthfkcbfdl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtfvfuiskw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtycpndffc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhiwuduotai.top/Article/details/gtlebaaayz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ydzc1.top/Article/details/gtaonfcgtn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgufenzy.top/Article/details/gtdzplyfow.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.svipenyu.cn/Article/details/gtxxosnhxd.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gtxvjczcvy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmvblzcr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypmdjfoy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yvedp.cn/Article/details/gtstjlggfu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuetiantiany.cn/Article/details/gtobuoqbme.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtpmclumsz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guannengcc.top/Article/details/gtzvstivzt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daria6918.cn/Article/details/gtndwfgpny.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.redwolf501.top/Article/details/gtxcbppdab.html

[D26] 数组转字符串
来源：http://dali.shuidangran.top/Article/details/gtsyertshq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.iojbl.cn/Article/details/gtmuogmvxh.html

PHP:  implode(", ", $arr);
来源：http://dali.smart0.xyz/Article/details/gttwceipyr.html

JS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqphnkngw.html

TS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtuhozibrz.html

Java: String.join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gtxrawgqxn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dianchejie.cn/Article/details/gtdlzzhugv.html

Ruby: arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtpeovxfbw.html

C#:   string.Join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gtiusxbaaw.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiludqqly.html

E. 字符串处理
来源：http://dali.guowangkeji.top/Article/details/gthxrseidb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtigppqcqb.html

[E01] 拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtruvtfwzs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenjidiqi.icu/Article/details/gtrbvolstm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tianlin.xyz/Article/details/gtakjqzllm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtkfaorxrq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gtfrgzdpkg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigfzy.top/Article/details/gtymiwvqxe.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnxiangtu.top/Article/details/gtldshrssd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.birdmap.top/Article/details/gtceyymalr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtofbvtpon.html

[E02] 重复字符串
来源：http://dali.hammf.cn/Article/details/gtffsqfigj.html

Py:   "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gtczpaqwby.html

PHP:  str_repeat("ab", 3);
来源：http://dali.smart0.xyz/Article/details/gtgiylqcmr.html

JS:   "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gttzouqwqs.html

TS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtvhtazspg.html

Java: "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtmwwhqqvm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.mhx1999.top/Article/details/gtkjoagbbp.html

Ruby: "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gtxsjwhltl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sweek.top/Article/details/gtuahbzqvq.html

[E03] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gtesqmvksl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xylfe.cn/Article/details/gtddiremvb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtqbtdnzzk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrftlscgx.html

TS:   s.slice(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gtklegakaf.html

Java: s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtrgfpccky.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtvzfsneye.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aibaodan.cn/Article/details/gtkfpikrln.html

C#:   s.Substring(1, 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtautwrpaf.html

[E04] 查找子串位置
来源：http://dali.ydzc1.top/Article/details/gtzvglpxdt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fengsongda.top/Article/details/gtbhixjuia.html

PHP:  strpos($s, "x");
来源：http://dali.zhiwuduotai.top/Article/details/gtlzvfmmqi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvckjgki.html

TS:   s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gtcdnsklfm.html

Java: s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gtxcytvukv.html

Go:   strings.Index(s, "x")
来源：http://dali.jiagoushi.top/Article/details/gtbjmjstqo.html

Ruby: s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtdolcxpzm.html

C#:   s.IndexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gtjwlfdwvz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aizwys.cn/Article/details/gtqzkowobn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tianlin.xyz/Article/details/gtenzdvfpa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yvedp.cn/Article/details/gtluyuubee.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtcdpfyrru.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hysaishi.cn/Article/details/gtekfyxoif.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gteateflsk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenlongwang.top/Article/details/gtmfqjhhxx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gzhubu.top/Article/details/gtnssdjdfn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daxiang520.top/Article/details/gttkxxklke.html

[E06] 替换子串
来源：http://dali.c1oappe.top/Article/details/gtbblowseb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gtopdahzrr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxinkj.top/Article/details/gtxokinuzg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtcutwcilx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtmlyhawqu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtvoxyyjvg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gtxqtgaqrb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtblglmkju.html

C#:   s.Replace("a", "b")
来源：http://dali.yonumen.top/Article/details/gtvciqgajn.html

[E07] 按分隔符拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtnhdrrxho.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tian-w.cn/Article/details/gtzgvybhpg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtcqzszxgw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hysaishi.cn/Article/details/gtcepyrwjh.html

TS:   s.split(",")
来源：http://dali.zhixingplan.top/Article/details/gtpgdhormg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryfghxpy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cqqwz.cn/Article/details/gthiplzgdg.html

Ruby: s.split(",");  s.split
来源：http://dali.ppjwa.cn/Article/details/gtzoouhcjl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigufen.top/Article/details/gtgvqrasge.html

[E08] 数组按分隔符合并
来源：http://dali.quarkkingdee.top/Article/details/gtqyscuhdj.html

Py:   ",".join(items)
来源：http://dali.gogol.net.cn/Article/details/gtqbkwcqva.html

PHP:  implode(",", $items);
来源：http://dali.jinqigfzy.top/Article/details/gtusfmhwfi.html

JS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtmnzwkqxn.html

TS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtouvlaywc.html

Java: String.join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gthslcwxjq.html

Go:   strings.Join(items, ",")
来源：http://dali.sxryk.cn/Article/details/gtrhaamgia.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoltzumf.html

C#:   string.Join(",", items)
来源：http://dali.316326.xyz/Article/details/gtezdiplaa.html

[E09] 去除所有空白字符
来源：http://dali.tian-w.cn/Article/details/gtrmdbuxal.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtvlcrvcca.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.haohaochexian.top/Article/details/gtbsdndlcq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtfdfirfwe.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gtkycwikmt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxobhgxvs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gogol.net.cn/Article/details/gtvemxoaem.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtcqtwjymj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtemnxxqcf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gogol.net.cn/Article/details/gtwhymzhmo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.birdmap.top/Article/details/gtltpjqwnl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yvedp.cn/Article/details/gtdjgjzzrx.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gttgodatcw.html

TS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtojesljtq.html

Java: String.format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtkpvrzeoz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtzjjgzzio.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtadjjqeot.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zdqjudy.top/Article/details/gtxzitmnus.html

[E11] 反转字符串
来源：http://dali.hysaishi.cn/Article/details/gtfuiplvmu.html

Py:   s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtzvsexakc.html

PHP:  strrev($s);
来源：http://dali.316326.xyz/Article/details/gtjizviwpz.html

JS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtanqpjayf.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtbrlsrgvs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtthxgvetg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.andypj.xyz/Article/details/gtixqybkme.html

Ruby: s.reverse
来源：http://dali.yonumen.top/Article/details/gtonhrbpev.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gtazqcsrqt.html

[E12] 统计某字符出现次数
来源：http://dali.9152youxi.cn/Article/details/gtmefrgput.html

Py:   s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gthsddwkqm.html

PHP:  substr_count($s, "a");
来源：http://dali.yvedp.cn/Article/details/gtzlnnwayr.html

JS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtnabmzakm.html

TS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gtdzsrlvsn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gotoacloud.top/Article/details/gtpfpqzjgu.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258888.top/Article/details/gtpejtmuyq.html

Ruby: s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gttskfxjrd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhixingplan.top/Article/details/gtbsbfuhqg.html

[E13] 逐字符遍历
来源：http://dali.sweek.top/Article/details/gtcrstxqzb.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxuanxn.top/Article/details/gtfjjvblct.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gtwygkqucq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtvjbbbdcz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtqqatxhyf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtwmkuxjit.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zdqjudy.top/Article/details/gthcqxsgdg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenlongwang.top/Article/details/gtujbqgfzx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtodncieux.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gtqwxgumhn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.svipenyu.cn/Article/details/gtvgbvvemy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jiagoushi.top/Article/details/gtdadtrxld.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sweek.top/Article/details/gtefildori.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.redwolf501.top/Article/details/gtrvfmvyuo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtvcrbohhj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinghuilouyu.cn/Article/details/gtngwgrakq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhixingplan.top/Article/details/gtvhxkjxoj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbrmdyjv.html

[E15] HTML 转义 / 反转义
来源：http://dali.nwbrower.top/Article/details/gtgzayhlnk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtezyqeted.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdcbabie.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj202588.top/Article/details/gtjruozumn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenzaomai.com/Article/details/gtjwikqgoq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.kuanghao11.cn/Article/details/gtlmhiljkv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafwuszrk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenlongwang.top/Article/details/gtfswckuyt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yonumen.top/Article/details/gtgjykiuof.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjmzkyrf.html

Py:   f"{1234567:,}"
来源：http://dali.dashuyun.cn/Article/details/gtrnyurmjz.html

PHP:  number_format(1234567);
来源：http://dali.nwbrower.top/Article/details/gtylhizwux.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gtwtgtnlfz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwjtmdhh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtkvxnarox.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.iojbl.cn/Article/details/gtavpkelis.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gtwnoqgafb.html

C#:   1234567.ToString("N0")
来源：http://dali.cashguo.top/Article/details/gtobknlczv.html

[E17] 首字母大写
来源：http://dali.haohaochexian.top/Article/details/gtgtivyruu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gtjrnnncik.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zdqjudy.top/Article/details/gtkjiwfsfa.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtflxgvknt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskozullj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.316326.xyz/Article/details/gtgqxumgxp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuanzhike.top/Article/details/gthcsiepyo.html

Ruby: s.capitalize
来源：http://dali.gzhubu.top/Article/details/gtfsorpfxr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhoulong.xyz/Article/details/gtpflrshfj.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gtejfkgvcd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gtlsaqibao.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cheryme.top/Article/details/gtzfyuzupr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtpccrsvtp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtnskggwyy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtjearzxmb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tanke756.top/Article/details/gtsqjxgxyo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cheryme.top/Article/details/gtovggmbuf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhiwuduotai.top/Article/details/gtbdvieyoe.html

[E19] 多行文本按行拆分
来源：http://dali.yueranfly.top/Article/details/gtkdojqocs.html

Py:   s.splitlines()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizdolxhf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtbdkjkgei.html

JS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtzcalvtjd.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteuekfhgh.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtkwxrijhd.html

Go:   strings.Split(s, "\n")
来源：http://dali.yvedp.cn/Article/details/gtjhmbxlob.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzkshpvk.html

C#:   s.Split('\n')
来源：http://dali.hnqzz.top/Article/details/gteylifehq.html

[E20] 判断字符串是否为空
来源：http://dali.dashuyun.cn/Article/details/gteswybeve.html

Py:   if not s:
来源：http://dali.ehwqpu.com/Article/details/gtoycwqgcy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.quarkkingdee.top/Article/details/gtykovtvbf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigfzy.top/Article/details/gtjrbbdbka.html

TS:   if (s === "") {}
来源：http://dali.wangshuangyany.cn/Article/details/gtfxdadcba.html

Java: if (s.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gtqklesgrq.html

Go:   if s == "" {}
来源：http://dali.shangyingyoupin.top/Article/details/gtccbuajet.html

Ruby: if s.empty?
来源：http://dali.zycfv.cn/Article/details/gtzfzrjzrq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvzfikhez.html

[E21] 超长截断加省略号
来源：http://dali.gotoacloud.top/Article/details/gtzrgjqhxx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenlongwang.top/Article/details/gtbnkmzwpb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtvotmpbqa.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtoasyfmgo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtdngpupxd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtrcsekrww.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.andypj.xyz/Article/details/gtbejgsjej.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtjxeejkgp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtcsovgpko.html

[E22] 字节长度与字符长度
来源：http://dali.jiagoushi.top/Article/details/gtiopoeops.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jianghu66.top/Article/details/gtazmlewoh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtwuauylwr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gtkummojmf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxlxhgzx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yongpay.top/Article/details/gtanzcyhyj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tianlin.xyz/Article/details/gtcxlcmrku.html

Ruby: s.bytesize;  s.length
来源：http://dali.yueranfly.top/Article/details/gtikjwfeue.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtmpcwcrcb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtbpchqfom.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtbjxyop.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtvzlrksvh.html

[F01] 读取整个文件
来源：http://dali.tianlin.xyz/Article/details/gtfgumkevn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gtcafjippy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtlmnqqeub.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuanzhike.top/Article/details/gtusmrlmpk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtaegwhwwp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgerjeae.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shangyingyoupin.top/Article/details/gtgykqousp.html

Ruby: File.read("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtstdhwsif.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthyfnrvfp.html

[F02] 逐行读取文件
来源：http://dali.daria6918.cn/Article/details/gtbzzpsyjh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aizwys.cn/Article/details/gteermysqp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.iojbl.cn/Article/details/gtvyutvgsa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gtuhkkmzbe.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtkupkdchl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gtsglsvpdu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.andypj.xyz/Article/details/gthnfdbfvo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj202588.top/Article/details/gtqwsggtny.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yanxiufei.cn/Article/details/gtknwnpzto.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gtencpnoqi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftglagdi.html


<!-- 参考信息 -->