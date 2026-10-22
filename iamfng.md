代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.havefunace.top/Article/details/gt2mdnrdxvq.html

Go:   // 手写双层循环
来源：http://dali.xuanzx.com/Article/details/gt2euqfzikt.html

Ruby: nested.flatten
来源：http://dali.vqdsnc.cn/Article/details/gt2otpmoqwd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2xfuncvjy.html

[D19] 按字段分组
来源：http://dali.snrcjt.cn/Article/details/gt2sduuqanq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2fgxigkpy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tian-w.cn/Article/details/gt2awykmnha.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuetiantiany.cn/Article/details/gt2piyqmkhx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gt2sxmkylfm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhengqikj.top/Article/details/gt2humlgcmy.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcvngdj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.c1oappe.top/Article/details/gt2gqturjyy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sysykeji.top/Article/details/gt2ydzknhap.html

[D20] 统计每个元素出现次数
来源：http://dali.snrcjt.cn/Article/details/gt2eqepvnjw.html

Py:   Counter(arr)
来源：http://dali.nwbrower.top/Article/details/gt2yskwltvd.html

PHP:  array_count_values($arr);
来源：http://dali.havefunace.top/Article/details/gt2mohiutgx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gt2wpoxxiez.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gt2leaquihi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuanzx.com/Article/details/gt2vylcdwpi.html

Go:   // 手写 map[T]int
来源：http://dali.jiagoushi.top/Article/details/gt2avlbkqbp.html

Ruby: arr.tally
来源：http://dali.meibo888.top/Article/details/gt2afauvpkq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nwbrower.top/Article/details/gt2vjzqsobu.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gt2dycrcpkf.html

Py:   x in arr
来源：http://dali.shzxlz.cn/Article/details/gt2pninwyaw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxuanxn.top/Article/details/gt2joboeuxf.html

JS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gt2lgqilnik.html

TS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gt2jfcsvxko.html

Java: list.contains(x)
来源：http://dali.yj20258888.top/Article/details/gt2ibgvbvyz.html

Go:   slices.Contains(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2etppelyw.html

Ruby: arr.include?(x)
来源：http://dali.jinqigufen.top/Article/details/gt2ghqekejl.html

C#:   list.Contains(x)
来源：http://dali.0kj1m.cn/Article/details/gt2sstwhvgv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhongyouzk.top/Article/details/gt2kfhmawae.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.havefunace.top/Article/details/gt2ouihsisx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guannengcc.top/Article/details/gt2jppdojsm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2fwupoidv.html

TS:   [...arr];
来源：http://dali.jqgufenzy.top/Article/details/gt2fwzuunxi.html

Java: new ArrayList<>(list);
来源：http://dali.gaohongyu789.top/Article/details/gt2nmisulvy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yueranfly.top/Article/details/gt2dpimladw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.birdmap.top/Article/details/gt2kxlfdpig.html

C#:   new List<int>(list);
来源：http://dali.tanke756.top/Article/details/gt2aqkoyudi.html

[D23] reduce 累积计算
来源：http://dali.yvedp.cn/Article/details/gt2wgrginsj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2cocmqygg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ppjwa.cn/Article/details/gt2woxgqgbs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gt2goeihynl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2lhnbqozp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fengsongda.top/Article/details/gt2iskobazb.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gt2ioeblcoh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhiwuduotai.top/Article/details/gt2ebjnzxzx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gt2bnpkuocw.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258888.top/Article/details/gt2rqdtpesx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vdqzmdaw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.snrcjt.cn/Article/details/gt2vauktrvm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dashuyun.cn/Article/details/gt2gvbvuxtv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.birdmap.top/Article/details/gt2pbjbumjx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuanzhike.top/Article/details/gt2cekdemob.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jiagoushi.top/Article/details/gt2khtkrhki.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.316326.xyz/Article/details/gt2sdxvzybu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.bjfxy.top/Article/details/gt2csspaarf.html

[D25] Set 集合去重与交并差
来源：http://dali.jlsjyb.cn/Article/details/gt2skfqjpbi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ehwqpu.com/Article/details/gt2vpxpkfza.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.0kj1m.cn/Article/details/gt2bzurwkgp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenzaomai.com/Article/details/gt2ocypesgc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gt2ejihwevu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.wangdashe.top/Article/details/gt2wnttykeh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zdqjudy.top/Article/details/gt2mpheaxkh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hfpthk.cn/Article/details/gt2nvoeumjy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2goxuyjov.html

[D26] 数组转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2qahvdaes.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yonumen.top/Article/details/gt2owfusdps.html

PHP:  implode(", ", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2hwuvvwfa.html

JS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gt2xfdwbvar.html

TS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcoghjvb.html

Java: String.join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wjvoqjpc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nwbrower.top/Article/details/gt2mcztmzee.html

Ruby: arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gt2gxgqxhok.html

C#:   string.Join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gt2dpodhvhe.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2lvhthqny.html

E. 字符串处理
来源：http://dali.ybcxt.top/Article/details/gt2mnpmlfuw.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2btzaqdvv.html

[E01] 拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2hgtrrlrm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.meibo888.top/Article/details/gt2mgfaulyc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2uhseefir.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gt2mjsqarmw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gt2aougmtda.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yongpay.top/Article/details/gt2uaqlmqtu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2tvifplma.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xirsmmww.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgwcbghf.html

[E02] 重复字符串
来源：http://dali.dashuyun.cn/Article/details/gt2aenlzjme.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gt2udhmtzzz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xfbegazi.html

JS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gt2knvfzqdv.html

TS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gt2xkfkxybm.html

Java: "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gt2wdrkwmdh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2tbzrvvwj.html

Ruby: "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ahzklrbh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hongshengwenyu.top/Article/details/gt2gojkxvbn.html

[E03] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gt2addlrhfa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cucudq.cn/Article/details/gt2qgvkcato.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2ntzbpeec.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gt2gdgitfxy.html

TS:   s.slice(1, 4)
来源：http://dali.cucudq.cn/Article/details/gt2rsrenypo.html

Java: s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gt2rktvfkoe.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yonumen.top/Article/details/gt2ftmwbdpj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangdashe.top/Article/details/gt2oajnphzo.html

C#:   s.Substring(1, 3)
来源：http://dali.cucudq.cn/Article/details/gt2ypazumdg.html

[E04] 查找子串位置
来源：http://dali.fzhhl.top/Article/details/gt2leruwyum.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gt2kityqsdp.html

PHP:  strpos($s, "x");
来源：http://dali.0kj1m.cn/Article/details/gt2xdqcicny.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xcbaegmh.html

TS:   s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gt2khtwmiju.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2esmhdxbr.html

Go:   strings.Index(s, "x")
来源：http://dali.wangdashe.top/Article/details/gt2rrmpcdlp.html

Ruby: s.index("x")
来源：http://dali.yueranfly.top/Article/details/gt2gazjhkwi.html

C#:   s.IndexOf("x")
来源：http://dali.yonumen.top/Article/details/gt2rjkrtxoz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tianlin.xyz/Article/details/gt2bessecps.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tianlin.xyz/Article/details/gt2xinpglgx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gaohongyu789.top/Article/details/gt2bebsqtdr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gt2htvwkrlb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2omrqezbv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gt2qizxgekh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.haohaochexian.top/Article/details/gt2txyfijfd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jlsjyb.cn/Article/details/gt2iaadcdnf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gt2ynrdhrdc.html

[E06] 替换子串
来源：http://dali.guowangkeji.top/Article/details/gt2ozbtkmpl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gt2mvsbgeky.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sysykeji.top/Article/details/gt2ayhkvqxk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ucewjvsu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2nsyrrvef.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2jhrflcsh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gt2aaofdqxr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2inigoiuw.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oyctqyeo.html

[E07] 按分隔符拆分
来源：http://dali.daxiang520.top/Article/details/gt2euidktol.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2whwouyjv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2vuzzwklp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.snrcjt.cn/Article/details/gt2agofmjyd.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gt2pgzsdtop.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dianchejie.cn/Article/details/gt2glmwsscg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gogol.net.cn/Article/details/gt2fkyxqpww.html

Ruby: s.split(",");  s.split
来源：http://dali.meibo888.top/Article/details/gt2decaasny.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sxryk.cn/Article/details/gt2ehmaruiu.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gt2fhllzjli.html

Py:   ",".join(items)
来源：http://dali.zhixingplan.top/Article/details/gt2tvnwaxqk.html

PHP:  implode(",", $items);
来源：http://dali.jinqigufen.top/Article/details/gt2degeyaqb.html

JS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gt2ofpddjeu.html

TS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gt2arprmnjs.html

Java: String.join(",", items)
来源：http://dali.hammf.cn/Article/details/gt2nzvipsxh.html

Go:   strings.Join(items, ",")
来源：http://dali.fengsongda.top/Article/details/gt2qoyldqls.html

Ruby: items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rhmrmuve.html

C#:   string.Join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gt2tbnrkjff.html

[E09] 去除所有空白字符
来源：http://dali.zdqjudy.top/Article/details/gt2qpdjoscb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2vlgcycnx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cashguo.top/Article/details/gt2orzrieeq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kryhnmnc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gt2jebfqwjc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tian-w.cn/Article/details/gt2vvkkcsaz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.redwolf501.top/Article/details/gt2czujznxe.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cqqwz.cn/Article/details/gt2vxfmhwxq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gt2xkyggnds.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gt2nuchlfcm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gt2ekfcwxyz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.meibo888.top/Article/details/gt2tfuatimp.html

JS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gt2hajknfpv.html

TS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gt2ercoffwm.html

Java: String.format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gt2agzjlqhc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gt2hpjvuphy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gt2ozatlfmi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gt2hvwgdato.html

[E11] 反转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbvsefcy.html

Py:   s[::-1]
来源：http://dali.yongpay.top/Article/details/gt2rkrhwzre.html

PHP:  strrev($s);
来源：http://dali.c1oappe.top/Article/details/gt2ffdgvdau.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2ugdrzgps.html

TS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2jvemzaag.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dashuyun.cn/Article/details/gt2moftqrlh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2klpyumdg.html

Ruby: s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2otbyxqgn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gt2tgymjxbg.html

[E12] 统计某字符出现次数
来源：http://dali.chenlongwang.top/Article/details/gt2duijccie.html

Py:   s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2blzujqas.html

PHP:  substr_count($s, "a");
来源：http://dali.zdqjudy.top/Article/details/gt2oxdjaybz.html

JS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gt2vbijxdjg.html

TS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gt2yokhcriy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cucudq.cn/Article/details/gt2woltqdqi.html

Go:   strings.Count(s, "a")
来源：http://dali.fzhhl.top/Article/details/gt2jzzfzgjt.html

Ruby: s.count("a")
来源：http://dali.zycfv.cn/Article/details/gt2ptakyzlx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yanxiufei.cn/Article/details/gt2edcnwtpz.html

[E13] 逐字符遍历
来源：http://dali.daria6918.cn/Article/details/gt2oudugbcy.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ernswzxg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gezqlnmv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gt2gefuzkaw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gt2lfquwfxf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2haxhtwsf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zycfv.cn/Article/details/gt2yucukxcc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gt2etioycey.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2bmdodjza.html

[E14] URL 编码与 Base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2szewpfdz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigufen.top/Article/details/gt2wbwhtmoi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.haohaochexian.top/Article/details/gt2gbjggfih.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mmkclmvi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sysykeji.top/Article/details/gt2mgeqtgbl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gt2zpjjoyzd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aizwys.cn/Article/details/gt2lsmweqfo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cdnleiting.top/Article/details/gt2qkmnysig.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cqqwz.cn/Article/details/gt2gqtaalxq.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gt2znsjvyfu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cucudq.cn/Article/details/gt2ulrtfmab.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dianchejie.cn/Article/details/gt2eztdkbcy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.0kj1m.cn/Article/details/gt2jleuegan.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gt2hlboegae.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ivvv.top/Article/details/gt2biwghaiw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.haohaochexian.top/Article/details/gt2qsmfawip.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2qwbayngo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yvedp.cn/Article/details/gt2ztmvfvwv.html

[E16] 数字千分位
来源：http://dali.daxiang520.top/Article/details/gt2rfvzzrbj.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dfqgytoq.html

PHP:  number_format(1234567);
来源：http://dali.sufxvd.cn/Article/details/gt2jvaitoto.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gt2kjqhtjeb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gt2upmljfxo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gt2xkeqaoba.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hammf.cn/Article/details/gt2wmpqzhth.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hfpthk.cn/Article/details/gt2aemamkxl.html

C#:   1234567.ToString("N0")
来源：http://dali.redwolf501.top/Article/details/gt2vmdcvaye.html

[E17] 首字母大写
来源：http://dali.sxryk.cn/Article/details/gt2qbyqnqyb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gt2bncjkqds.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.0kj1m.cn/Article/details/gt2opgjnjzx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gt2jwvioyxl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gt2jqotnivj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jianghu66.top/Article/details/gt2ijbyxdgr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yvedp.cn/Article/details/gt2vwbqcoak.html

Ruby: s.capitalize
来源：http://dali.yongpay.top/Article/details/gt2olbknymm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cheryme.top/Article/details/gt2atnqgckp.html

[E18] 模板占位符替换
来源：http://dali.yanxiufei.cn/Article/details/gt2nxauanej.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yongpay.top/Article/details/gt2xjwcwbsa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cqqwz.cn/Article/details/gt2rjumcjwc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gt2iwkkogyl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gt2ljkfcaqj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2bhbermmy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2vlpwemla.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yonumen.top/Article/details/gt2yqtnenrq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2mihvvwkd.html

[E19] 多行文本按行拆分
来源：http://dali.ydzc1.top/Article/details/gt2qceywdaf.html

Py:   s.splitlines()
来源：http://dali.haohaochexian.top/Article/details/gt2jkvapbuz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2zambrzhb.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gt2rpsqktim.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xareivne.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gt2uppricwc.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2dfhehpbi.html

Ruby: s.lines
来源：http://dali.aibaodan.cn/Article/details/gt2islonhoh.html

C#:   s.Split('\n')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qayraseg.html

[E20] 判断字符串是否为空
来源：http://dali.jlsjyb.cn/Article/details/gt2zsbichmf.html

Py:   if not s:
来源：http://dali.jinqigufen.top/Article/details/gt2truwvblj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ivvv.top/Article/details/gt2vrbsvssx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gt2smsyrant.html

TS:   if (s === "") {}
来源：http://dali.zhengqikj.top/Article/details/gt2xqzhcnqf.html

Java: if (s.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gt2ykrxreqs.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ytcxesap.html

Ruby: if s.empty?
来源：http://dali.cucudq.cn/Article/details/gt2aautqwsc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2qgqyggsy.html

[E21] 超长截断加省略号
来源：http://dali.quarkkingdee.top/Article/details/gt2srgfsdai.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.9152youxi.cn/Article/details/gt2mpzbfbru.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gt2xnhufehu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2osajmsjx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2iacqvjcu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2rporudem.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yongpay.top/Article/details/gt2qrwezqvu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2gpbrsuuw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2lteqoavc.html

[E22] 字节长度与字符长度
来源：http://dali.nwbrower.top/Article/details/gt2inbiioom.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.redwolf501.top/Article/details/gt2czgahstj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gt2vypafjag.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gt2hbxpqawr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gt2eqtyxahd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxodrcy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gt2piwahusr.html

Ruby: s.bytesize;  s.length
来源：http://dali.0kj1m.cn/Article/details/gt2rhnkrgtp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gt2etcmrjec.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2cmzcdcja.html

F. 文件与目录
来源：http://dali.cucudq.cn/Article/details/gt2iltvatxx.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsswhjlt.html

[F01] 读取整个文件
来源：http://dali.ehwqpu.com/Article/details/gt2yehgrozj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dashuyun.cn/Article/details/gt2fjhptuxd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2slqtutnx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jiagoushi.top/Article/details/gt2gwxpphrr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.iojbl.cn/Article/details/gt2bxupdicg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2iytemygz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gt2gxvaueqm.html

Ruby: File.read("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2mjmpvlxn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2nvoobegb.html

[F02] 逐行读取文件
来源：http://dali.xuanzx.com/Article/details/gt2uxblbdup.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yvedp.cn/Article/details/gt2tscxkjov.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qdtmwyhx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gt2elyanpse.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gt2jivjuipf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gt2igkbvxmi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gt2bcdbnuqw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ehwqpu.com/Article/details/gt2zltyrvlr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ivvv.top/Article/details/gt2hyzskros.html

[F03] 写入文件（覆盖）
来源：http://dali.c1oappe.top/Article/details/gt2elagltta.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tianlin.xyz/Article/details/gt2qvxhdppr.html


<!-- 参考信息 -->