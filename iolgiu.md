代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2fvxjzpsz.html

Go:   // 手写双层循环
来源：http://dali.ehwqpu.com/Article/details/gt2hpidwilo.html

Ruby: nested.flatten
来源：http://dali.nanxinkj.top/Article/details/gt2sfibshkd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2vrhpqqlf.html

[D19] 按字段分组
来源：http://dali.haohaochexian.top/Article/details/gt2rhkmvsxk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.haohaochexian.top/Article/details/gt2shbtyswz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daria6918.cn/Article/details/gt2tkxcnetg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sysykeji.top/Article/details/gt2yaqnbdgb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dtlzdbhm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.316326.xyz/Article/details/gt2hpubrait.html

Go:   // 手写 map[string][]T
来源：http://dali.bjfxy.top/Article/details/gt2eerzvsqu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangdashe.top/Article/details/gt2dbatokvo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.redwolf501.top/Article/details/gt2rdificwa.html

[D20] 统计每个元素出现次数
来源：http://dali.dashuyun.cn/Article/details/gt2bjqvldvy.html

Py:   Counter(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2yygpxmjg.html

PHP:  array_count_values($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2stcbrnzc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gt2mzucgaku.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gt2befvclqd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj202588.top/Article/details/gt2slmnkica.html

Go:   // 手写 map[T]int
来源：http://dali.bjfxy.top/Article/details/gt2cofyaoad.html

Ruby: arr.tally
来源：http://dali.ppjwa.cn/Article/details/gt2eakqgqfo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shuidangran.top/Article/details/gt2inbrkfdp.html

[D21] 判断是否包含某元素
来源：http://dali.zhoulong.xyz/Article/details/gt2pvacqoyw.html

Py:   x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gt2rfvhifcv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ihvcbkte.html

JS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gt2ifzjbxih.html

TS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2dncnwivv.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2njanlvld.html

Go:   slices.Contains(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2dujxkylu.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bccdbeek.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gt2gvatcaxt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gt2mkyckqxv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guannengcc.top/Article/details/gt2qskmnmqe.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yongpay.top/Article/details/gt2ctoagyth.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.316326.xyz/Article/details/gt2lrcbetxs.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gt2tnedlfmh.html

Java: new ArrayList<>(list);
来源：http://dali.dashuyun.cn/Article/details/gt2ttcpxhqx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qkekozrj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxinkj.top/Article/details/gt2trypxxff.html

C#:   new List<int>(list);
来源：http://dali.sysykeji.top/Article/details/gt2nvmcocws.html

[D23] reduce 累积计算
来源：http://dali.andypj.xyz/Article/details/gt2dktcovgh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2gskkdbiv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yonumen.top/Article/details/gt2jhfljptf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iwkxgilj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2texlljuc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fzhhl.top/Article/details/gt2qfjnsvdh.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gt2ceyhvljk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jyoumei.cn/Article/details/gt2ieofwtuo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jianghu66.top/Article/details/gt2sdmffulk.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2tthkttda.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xinyue.icu/Article/details/gt2tgwwlffy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gogol.net.cn/Article/details/gt2wohshdcl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.smart0.xyz/Article/details/gt2nblshkhh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2ovbjmivm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ppjwa.cn/Article/details/gt2onrciipx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yyazwndy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dashuyun.cn/Article/details/gt2omrcaqog.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.9152youxi.cn/Article/details/gt2xrymylve.html

[D25] Set 集合去重与交并差
来源：http://dali.zycfv.cn/Article/details/gt2rroeftlm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sufxvd.cn/Article/details/gt2nnzefyds.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnxiangtu.top/Article/details/gt2xtxohbox.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cqqwz.cn/Article/details/gt2qepbsepf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zycfv.cn/Article/details/gt2tzaeuegl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sxryk.cn/Article/details/gt2qlrsllru.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuxming.cn/Article/details/gt2gnpenbcx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aizwys.cn/Article/details/gt2iamdmrdm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gt2hqsttgvb.html

[D26] 数组转字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2miokeaux.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxubgyaz.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2zdfiyzih.html

JS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gt2norkcyjg.html

TS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gt2gpgqxcvm.html

Java: String.join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gt2hvvcvalm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.redwolf501.top/Article/details/gt2jpuytxur.html

Ruby: arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gt2aokrvjib.html

C#:   string.Join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gt2phehrkoj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2talhrjud.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gt2agokvsrd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2qgncrfzr.html

[E01] 拼接字符串
来源：http://dali.iojbl.cn/Article/details/gt2aqktnwxg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shuidangran.top/Article/details/gt2fevezhyi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2wxabfapk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gt2xgtbnhfc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2ameccqvi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.redwolf501.top/Article/details/gt2qqyiokwt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.bjfxy.top/Article/details/gt2hyfjwbia.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nwbrower.top/Article/details/gt2echvexgx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vpomfcsb.html

[E02] 重复字符串
来源：http://dali.zycfv.cn/Article/details/gt2iesodnsi.html

Py:   "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gt2qtvzhnor.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ybcxt.top/Article/details/gt2dghlxcex.html

JS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xlfcldtl.html

TS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2gfinmxfu.html

Java: "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gt2mobinfla.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.316326.xyz/Article/details/gt2onzkcgns.html

Ruby: "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gt2zwcuemff.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yanxiufei.cn/Article/details/gt2etzqsbzi.html

[E03] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gt2vadpdbyk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhengqikj.top/Article/details/gt2yjlgjrih.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzbxivek.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymeoyguk.html

TS:   s.slice(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2brynbads.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdaozgr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.redwolf501.top/Article/details/gt2ahwqhkgw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuanzhike.top/Article/details/gt2hzodlpbi.html

C#:   s.Substring(1, 3)
来源：http://dali.yongpay.top/Article/details/gt2miepypxd.html

[E04] 查找子串位置
来源：http://dali.ppjwa.cn/Article/details/gt2upipjuei.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2sfztxgsk.html

PHP:  strpos($s, "x");
来源：http://dali.sxryk.cn/Article/details/gt2dlywvugk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjmiignh.html

TS:   s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gt2nsbmvnlx.html

Java: s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fuchkbug.html

Go:   strings.Index(s, "x")
来源：http://dali.cashguo.top/Article/details/gt2zcesizal.html

Ruby: s.index("x")
来源：http://dali.havefunace.top/Article/details/gt2uxmedsub.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxmwdgcq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hammf.cn/Article/details/gt2auxaxeii.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.kuanghao11.cn/Article/details/gt2yrqbpmmk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aizwys.cn/Article/details/gt2ahlmcwcw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.havefunace.top/Article/details/gt2mxidtiyu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shzxlz.cn/Article/details/gt2otmhgdjm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hvqsiplo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jyoumei.cn/Article/details/gt2frotewvd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ehwqpu.com/Article/details/gt2vfcmejdi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2cufgmplq.html

[E06] 替换子串
来源：http://dali.9152youxi.cn/Article/details/gt2llwytsju.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqfcdkps.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.haohaochexian.top/Article/details/gt2ezspfjpe.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2zrcuntee.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2qztwzjhi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2uiuyanzu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gt2mzxmzajx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfgklvgx.html

C#:   s.Replace("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2uwwaqxmm.html

[E07] 按分隔符拆分
来源：http://dali.ivvv.top/Article/details/gt2ycrysbtx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.mhx1999.top/Article/details/gt2upqogknx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2unuwyein.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.andypj.xyz/Article/details/gt2oiwhgmec.html

TS:   s.split(",")
来源：http://dali.ydzc1.top/Article/details/gt2giyghqkr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dashuyun.cn/Article/details/gt2vwawgtdy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2tmxuulap.html

Ruby: s.split(",");  s.split
来源：http://dali.yj20258888.top/Article/details/gt2jlgeslic.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tianlin.xyz/Article/details/gt2zcnririw.html

[E08] 数组按分隔符合并
来源：http://dali.jiagoushi.top/Article/details/gt2przgwzfk.html

Py:   ",".join(items)
来源：http://dali.zycfv.cn/Article/details/gt2iskmxhmb.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qihbbdfk.html

JS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gt2ahhqzikl.html

TS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2nffwmtpv.html

Java: String.join(",", items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qzjvjpac.html

Go:   strings.Join(items, ",")
来源：http://dali.shuidangran.top/Article/details/gt2wrmjsdfz.html

Ruby: items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gt2cwrvbhah.html

C#:   string.Join(",", items)
来源：http://dali.xuanzx.com/Article/details/gt2xdbyqppu.html

[E09] 去除所有空白字符
来源：http://dali.pengpengdd.cyou/Article/details/gt2ztchvnfx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daxiang520.top/Article/details/gt2obealvtq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sweek.top/Article/details/gt2yhqsfrew.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gt2sapkelyo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gt2qlbvkrwu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gt2nyvhxdxs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenzaomai.com/Article/details/gt2axiepzpy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.c1oappe.top/Article/details/gt2rffyfase.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zhliamvc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hywenlv.cn/Article/details/gt2anfwakaj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yonumen.top/Article/details/gt2xucebbbd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daxiang520.top/Article/details/gt2qxcuhgyj.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gt2mfbpvcku.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnnnrqa.html

Java: String.format("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gt2wklnshid.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gt2tpcfqyta.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gt2rnhhthwf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yonumen.top/Article/details/gt2gpxzackz.html

[E11] 反转字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2mtisella.html

Py:   s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gt2mzumlfwv.html

PHP:  strrev($s);
来源：http://dali.xinyue.icu/Article/details/gt2dvbnlqri.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gt2qcqupcgr.html

TS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2ojkhhpqn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.quarkkingdee.top/Article/details/gt2yrkfqqfd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgxmtzup.html

Ruby: s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wsmbrmfn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gt2hyqhelgf.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gt2hqelggfv.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gt2uyfcpwva.html

PHP:  substr_count($s, "a");
来源：http://dali.cqqwz.cn/Article/details/gt2wcsjsrel.html

JS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gt2nmgizmry.html

TS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gt2goqfwgqr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shangyingyoupin.top/Article/details/gt2esbqmwmp.html

Go:   strings.Count(s, "a")
来源：http://dali.hysaishi.cn/Article/details/gt2verwroht.html

Ruby: s.count("a")
来源：http://dali.cashguo.top/Article/details/gt2xgclvrzk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gt2qgqtaqgy.html

[E13] 逐字符遍历
来源：http://dali.yuxming.cn/Article/details/gt2outbwmku.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigufen.top/Article/details/gt2ukydxpyy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fengsongda.top/Article/details/gt2cufhhewl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gt2dzajdeeu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gt2vcpfckwq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258888.top/Article/details/gt2qpnwutfx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2qygbdjhe.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gt2hhmhgqkg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gt2eriraduo.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigufen.top/Article/details/gt2cvnkdjdt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shuidangran.top/Article/details/gt2zpcwdcwm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2aaivywik.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cashguo.top/Article/details/gt2nrimkvee.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ioecfsjj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gt2olxeojqm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sxryk.cn/Article/details/gt2lempymeu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dashuyun.cn/Article/details/gt2vyorioyj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.havefunace.top/Article/details/gt2ikmzzyki.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenlongwang.top/Article/details/gt2xzmalyle.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjtajcvd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fzhhl.top/Article/details/gt2srzprpwv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sysykeji.top/Article/details/gt2dfykgdpf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.0kj1m.cn/Article/details/gt2rbzdembw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gt2dxsshyaa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pycfn.com/Article/details/gt2hieirqji.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zksoxtjb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nwbrower.top/Article/details/gt2pcpaabej.html

[E16] 数字千分位
来源：http://dali.nanxinkj.top/Article/details/gt2yqdyoyki.html

Py:   f"{1234567:,}"
来源：http://dali.pycfn.com/Article/details/gt2vopwdhzt.html

PHP:  number_format(1234567);
来源：http://dali.gogol.net.cn/Article/details/gt2bznvlnwu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gt2ypkmroae.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gt2fepltsyd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gt2ktjhlewa.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gogol.net.cn/Article/details/gt2ipyhbbnw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258888.top/Article/details/gt2aecsaqzp.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gt2srdugbep.html

[E17] 首字母大写
来源：http://dali.c1oappe.top/Article/details/gt2crrzyjgx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gotoacloud.top/Article/details/gt2vztcddsq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ehwqpu.com/Article/details/gt2oswhyngi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gt2jnjmclcp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gt2eebfvzxo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guannengcc.top/Article/details/gt2amqpztdj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhongyouzk.top/Article/details/gt2xomagwid.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gt2flissehd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gzhubu.top/Article/details/gt2oxwucvgl.html

[E18] 模板占位符替换
来源：http://dali.zhongyouzk.top/Article/details/gt2uwwgnhhz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.0kj1m.cn/Article/details/gt2duzzftid.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guowangkeji.top/Article/details/gt2hkdzjbzk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2dncpxgqn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2mbrmsyek.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2wjhcbkbc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2tjfhvqkz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hywenlv.cn/Article/details/gt2bwwsybzm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.kuanghao11.cn/Article/details/gt2hmmwupyr.html

[E19] 多行文本按行拆分
来源：http://dali.wangdashe.top/Article/details/gt2tpoeepwx.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2okopzkbo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2cwdomwge.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gt2lspntgts.html

TS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gt2blaoldhu.html

Java: s.lines().toList()
来源：http://dali.ehwqpu.com/Article/details/gt2xncbomtf.html

Go:   strings.Split(s, "\n")
来源：http://dali.birdmap.top/Article/details/gt2bzarwiol.html

Ruby: s.lines
来源：http://dali.hnxiangtu.top/Article/details/gt2kswqlfak.html

C#:   s.Split('\n')
来源：http://dali.yj20258888.top/Article/details/gt2gidyaaic.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gt2iobevtkm.html

Py:   if not s:
来源：http://dali.cqqwz.cn/Article/details/gt2hjuuteez.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daxiang520.top/Article/details/gt2siwsyiai.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gt2dipvryee.html

TS:   if (s === "") {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpyovbjs.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bxuasghx.html

Go:   if s == "" {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2nngbnogr.html

Ruby: if s.empty?
来源：http://dali.mhx1999.top/Article/details/gt2lciqkzer.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xinyue.icu/Article/details/gt2vfyymhqm.html

[E21] 超长截断加省略号
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwxfstqw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhixingplan.top/Article/details/gt2heeldddn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2uwamfzjm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuiieyh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gt2plfriepv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2eokbprlc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fybvsgkx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2ieqtrcel.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2dqefijyi.html

[E22] 字节长度与字符长度
来源：http://dali.havefunace.top/Article/details/gt2uocevaom.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.smart0.xyz/Article/details/gt2rvxrixjd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gt2iagsxzvf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gt2uubavlox.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2qmwyflgt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nwbrower.top/Article/details/gt2jkvrzweg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gt2qmqgmlou.html

Ruby: s.bytesize;  s.length
来源：http://dali.cqqwz.cn/Article/details/gt2sejjsxql.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gt2omaotcym.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2tlbdrock.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gt2jhodoqyv.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2smfuirgk.html

[F01] 读取整个文件
来源：http://dali.haohaochexian.top/Article/details/gt2sngtxbir.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gotoacloud.top/Article/details/gt2paglwyqk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2rqjgvyik.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dianchejie.cn/Article/details/gt2zcbysppv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gt2jxkuycey.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gt2ipfiygyn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxinkj.top/Article/details/gt2tnfdlvsk.html

Ruby: File.read("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2gbvjoxyo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2zbnlayxn.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2mfpjiavv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guowangkeji.top/Article/details/gt2egmbemxt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cqqwz.cn/Article/details/gt2ofujusss.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gt2qlncmjrn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gt2fizeeoqj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gt2basvtcle.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.quarkkingdee.top/Article/details/gt2jievsuna.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gfejajxt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2labajolv.html

[F03] 写入文件（覆盖）
来源：http://dali.jlsjyb.cn/Article/details/gt2srmkcqcn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gzhubu.top/Article/details/gt2invccgtv.html


<!-- 参考信息 -->