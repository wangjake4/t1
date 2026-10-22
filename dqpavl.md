代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sufxvd.cn/Article/details/gt2sxnaafso.html

[D20] 统计每个元素出现次数
来源：http://dali.sweek.top/Article/details/gt2izldyqdy.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aoaxwgnh.html

PHP:  array_count_values($arr);
来源：http://dali.redwolf501.top/Article/details/gt2gmurlvhh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gt2plqtroaa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sweek.top/Article/details/gt2scuigycu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gt2upovipbg.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gt2khaxulzp.html

Ruby: arr.tally
来源：http://dali.jinqigufen.top/Article/details/gt2imgarion.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tianlin.xyz/Article/details/gt2sodwjlov.html

[D21] 判断是否包含某元素
来源：http://dali.hywenlv.cn/Article/details/gt2fshqdhww.html

Py:   x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgtmtmfg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yvedp.cn/Article/details/gt2dawfnbil.html

JS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2bcszmlfe.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imvtktfi.html

Java: list.contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ulysjjoe.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2ohomurvy.html

Ruby: arr.include?(x)
来源：http://dali.bjfxy.top/Article/details/gt2xemzzmxx.html

C#:   list.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xurntgqo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhixingplan.top/Article/details/gt2nousyslx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xylfe.cn/Article/details/gt2qasorxwy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dashuyun.cn/Article/details/gt2wnywfvrl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cashguo.top/Article/details/gt2rafnoies.html

TS:   [...arr];
来源：http://dali.meibo888.top/Article/details/gt2zcbcobtx.html

Java: new ArrayList<>(list);
来源：http://dali.havefunace.top/Article/details/gt2qdrqdqbh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qwraaiht.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sxryk.cn/Article/details/gt2nbnazuwt.html

C#:   new List<int>(list);
来源：http://dali.andypj.xyz/Article/details/gt2qvpplavh.html

[D23] reduce 累积计算
来源：http://dali.c1oappe.top/Article/details/gt2mxaxtdua.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2ejutugvy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gogol.net.cn/Article/details/gt2uzwhgkrq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gt2qnqmkyss.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gt2ycmhnnla.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sweek.top/Article/details/gt2ytojszcy.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gt2mpldquyc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuxming.cn/Article/details/gt2huqofkob.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daxiang520.top/Article/details/gt2hkomfiff.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnxiangtu.top/Article/details/gt2bhwbchcs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gt2ekzmljes.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shuidangran.top/Article/details/gt2oqlprbez.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aibaodan.cn/Article/details/gt2brgkwnen.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nwbrower.top/Article/details/gt2haqhcevq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cucudq.cn/Article/details/gt2ozbcepet.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgfzy.top/Article/details/gt2dveageyh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zdqjudy.top/Article/details/gt2zywtqjhz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xylfe.cn/Article/details/gt2akvdclvr.html

[D25] Set 集合去重与交并差
来源：http://dali.wangdashe.top/Article/details/gt2wirtnfov.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shzxlz.cn/Article/details/gt2sihajqyk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnqzz.top/Article/details/gt2gfcgnlzy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zdqjudy.top/Article/details/gt2lgtjovdj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwqljnn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2aktuigmk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuetiantiany.cn/Article/details/gt2nmxrmore.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hfpthk.cn/Article/details/gt2jwzoogvq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2cqqzbzlx.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tmhcjqdf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuxming.cn/Article/details/gt2secjxfgz.html

PHP:  implode(", ", $arr);
来源：http://dali.haohaochexian.top/Article/details/gt2mfuaymok.html

JS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gt2axwcxisd.html

TS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gt2atujnrti.html

Java: String.join(", ", list)
来源：http://dali.yj20258.top/Article/details/gt2nyylqznl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhixingplan.top/Article/details/gt2pppcgsqq.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2atqukcae.html

C#:   string.Join(", ", list)
来源：http://dali.pycfn.com/Article/details/gt2gcmiyyix.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2mjjahzfx.html

E. 字符串处理
来源：http://dali.cucudq.cn/Article/details/gt2schxrmru.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2xeruhlrz.html

[E01] 拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gt2thtiqmne.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuanzx.com/Article/details/gt2oohureos.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aizwys.cn/Article/details/gt2bwhntelo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gt2fqvtvffo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gt2olzqobia.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ivvv.top/Article/details/gt2wyqjwres.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigufen.top/Article/details/gt2oehsxujb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cucudq.cn/Article/details/gt2jikproez.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2gboliwxd.html

[E02] 重复字符串
来源：http://dali.hnqzz.top/Article/details/gt2ieijdmxh.html

Py:   "ab" * 3
来源：http://dali.yj20258.top/Article/details/gt2rxdnnhal.html

PHP:  str_repeat("ab", 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2nihravhb.html

JS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gt2jeimnwkx.html

TS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzltbnks.html

Java: "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gt2biiiqbtw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hywenlv.cn/Article/details/gt2rdeznben.html

Ruby: "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gt2kkpksqge.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenjidiqi.icu/Article/details/gt2fhkvlmpi.html

[E03] 截取子串
来源：http://dali.yvedp.cn/Article/details/gt2uklzjeto.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iuzvybdt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2xuhrbphl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2emoboyfe.html

TS:   s.slice(1, 4)
来源：http://dali.tian-w.cn/Article/details/gt2tatwvgol.html

Java: s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gt2vwkfnckq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hywenlv.cn/Article/details/gt2eogbpcya.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenzaomai.com/Article/details/gt2ppzlipbu.html

C#:   s.Substring(1, 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2iyytekte.html

[E04] 查找子串位置
来源：http://dali.tanke756.top/Article/details/gt2puvredgs.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnqzz.top/Article/details/gt2hryhfwak.html

PHP:  strpos($s, "x");
来源：http://dali.vqdsnc.cn/Article/details/gt2bdfvtmia.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gzhubu.top/Article/details/gt2jqylwmsb.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gt2ofehvgyv.html

Java: s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gt2crgxvkip.html

Go:   strings.Index(s, "x")
来源：http://dali.wangdashe.top/Article/details/gt2tiphdekk.html

Ruby: s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2kxuqurbb.html

C#:   s.IndexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2qaetuwzs.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aibaodan.cn/Article/details/gt2pzvsvcse.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2torohpiu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gaohongyu789.top/Article/details/gt2rdiyrsxw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2ocemglpy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xinyue.icu/Article/details/gt2fjyozkms.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gt2qiifoamv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gotoacloud.top/Article/details/gt2zkacdwmh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tianlin.xyz/Article/details/gt2bmwrylwr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zhxkhaia.html

[E06] 替换子串
来源：http://dali.fengsongda.top/Article/details/gt2zomomhme.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gt2ioaekelz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cdnleiting.top/Article/details/gt2dkqwnhze.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xkvqblom.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2mckbfmnp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2kjotnbaq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gt2pxfbctgb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jlqojjmt.html

C#:   s.Replace("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2kingbrcn.html

[E07] 按分隔符拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmyqtsye.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hammf.cn/Article/details/gt2tzbzojes.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2ywexbkyp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ivvv.top/Article/details/gt2hijendda.html

TS:   s.split(",")
来源：http://dali.dianchejie.cn/Article/details/gt2leblmwte.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yongpay.top/Article/details/gt2caslscul.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yvedp.cn/Article/details/gt2zwhllndp.html

Ruby: s.split(",");  s.split
来源：http://dali.havefunace.top/Article/details/gt2npsgdqgo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangshuangyany.cn/Article/details/gt2djedqbed.html

[E08] 数组按分隔符合并
来源：http://dali.yueranfly.top/Article/details/gt2diknztiw.html

Py:   ",".join(items)
来源：http://dali.cheryme.top/Article/details/gt2usxvqdij.html

PHP:  implode(",", $items);
来源：http://dali.yuanzhike.top/Article/details/gt2tmvkpatk.html

JS:   items.join(",")
来源：http://dali.pycfn.com/Article/details/gt2wvnrdjpe.html

TS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gt2lhvexiiv.html

Java: String.join(",", items)
来源：http://dali.sysykeji.top/Article/details/gt2hftuulfg.html

Go:   strings.Join(items, ",")
来源：http://dali.andypj.xyz/Article/details/gt2vmyceboz.html

Ruby: items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gt2zrnzpxbz.html

C#:   string.Join(",", items)
来源：http://dali.tanke756.top/Article/details/gt2mncejseg.html

[E09] 去除所有空白字符
来源：http://dali.jinqigfzy.top/Article/details/gt2qitvioqw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigufen.top/Article/details/gt2oznrckmn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2pnhmaudc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gt2sbssacrf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gt2hjwhgfuc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hecixusc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fdiofhbs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ozwlshbb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gt2rrfleddm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.andypj.xyz/Article/details/gt2uzrhgbic.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tanke756.top/Article/details/gt2jdeyrskd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.smart0.xyz/Article/details/gt2bqcqnlfx.html

JS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gt2owzosxkl.html

TS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gt2sklwppez.html

Java: String.format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gt2aocydknn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gt2xfxxogay.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gt2gxgguoml.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dianchejie.cn/Article/details/gt2lqlepndz.html

[E11] 反转字符串
来源：http://dali.andypj.xyz/Article/details/gt2lnkwzqxm.html

Py:   s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gt2moisimvx.html

PHP:  strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gt2kckupdet.html

JS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gt2jayujkna.html

TS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2apjciets.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.havefunace.top/Article/details/gt2souowzrp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gt2yfsmblcz.html

Ruby: s.reverse
来源：http://dali.aizwys.cn/Article/details/gt2hiutqexf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lackqzwt.html

[E12] 统计某字符出现次数
来源：http://dali.redwolf501.top/Article/details/gt2nhvwytvq.html

Py:   s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpfptqbk.html

PHP:  substr_count($s, "a");
来源：http://dali.ivvv.top/Article/details/gt2wwvtrtpo.html

JS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gt2fgncbncx.html

TS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfxspisx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hongshengwenyu.top/Article/details/gt2nytebnej.html

Go:   strings.Count(s, "a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jefkjili.html

Ruby: s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gt2filmpsmk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.feifeiyinyue.top/Article/details/gt2gtztmcix.html

[E13] 逐字符遍历
来源：http://dali.chenlongwang.top/Article/details/gt2vgsadafj.html

Py:   for ch in s: print(ch)
来源：http://dali.aizwys.cn/Article/details/gt2xdphzovc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ivvv.top/Article/details/gt2xrzcfgsp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2ecaxstpn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gt2mmhbrkbp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2jxsscxbn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vzoptbzg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpvsgbg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gt2wlwenfdt.html

[E14] URL 编码与 Base64
来源：http://dali.yuanzhike.top/Article/details/gt2iyvpuyac.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gt2nvpoykfe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tian-w.cn/Article/details/gt2sdaewpye.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shuidangran.top/Article/details/gt2kwxpkber.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gt2zmbrmjzc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tanke756.top/Article/details/gt2hltjnqzo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.haohaochexian.top/Article/details/gt2tdzxesat.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tian-w.cn/Article/details/gt2konsfcgy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.snrcjt.cn/Article/details/gt2cytxzarm.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigfzy.top/Article/details/gt2gjssnktg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gkqfyhov.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uanmbrvd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gt2tuayfuav.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxuanxn.top/Article/details/gt2bqgtspsv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.c1oappe.top/Article/details/gt2vgrnycgv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ydzc1.top/Article/details/gt2lgvochbp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cnjavdyf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gt2ofnrhkgc.html

[E16] 数字千分位
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fxnjhoog.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2byhhmhnq.html

PHP:  number_format(1234567);
来源：http://dali.dashuyun.cn/Article/details/gt2kzqotioz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gt2nodzagqs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gt2emwhehuf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gt2thgafgze.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhoulong.xyz/Article/details/gt2dtsljfos.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fzhhl.top/Article/details/gt2pmpdzfly.html

C#:   1234567.ToString("N0")
来源：http://dali.jlsjyb.cn/Article/details/gt2qcauobay.html

[E17] 首字母大写
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2drdbzffd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.birdmap.top/Article/details/gt2bdidrbea.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gt2ymyhdjri.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gt2bscscmks.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jzvstqjb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xziqi.cn/Article/details/gt2zchxgpbs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pycfn.com/Article/details/gt2xgcxmnpl.html

Ruby: s.capitalize
来源：http://dali.yonumen.top/Article/details/gt2qeqklndy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.iojbl.cn/Article/details/gt2dlecucwg.html

[E18] 模板占位符替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2shzrgivn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.daxiang520.top/Article/details/gt2vqzmwmuj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigfzy.top/Article/details/gt2bmpdsuzf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2rvwpxpzf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2hpbcuwzf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2oifsnspr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2ksjgbktm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jianghu66.top/Article/details/gt2meycejkk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.smart0.xyz/Article/details/gt2kmfonfjq.html

[E19] 多行文本按行拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jlfpvibb.html

Py:   s.splitlines()
来源：http://dali.sufxvd.cn/Article/details/gt2bjemmxjf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2ltzzjhjk.html

JS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gt2lnqvsxcs.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gt2kpazuxyz.html

Java: s.lines().toList()
来源：http://dali.zhengqikj.top/Article/details/gt2adpzegjp.html

Go:   strings.Split(s, "\n")
来源：http://dali.smart0.xyz/Article/details/gt2vcsanayr.html

Ruby: s.lines
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cjhrvwpt.html

C#:   s.Split('\n')
来源：http://dali.andypj.xyz/Article/details/gt2lymluzig.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258888.top/Article/details/gt2mzdcbawx.html

Py:   if not s:
来源：http://dali.gotoacloud.top/Article/details/gt2umcrqbjf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.iojbl.cn/Article/details/gt2ewjpvsse.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangdashe.top/Article/details/gt2wyiiuonq.html

TS:   if (s === "") {}
来源：http://dali.guannengcc.top/Article/details/gt2pfmiiqyb.html

Java: if (s.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gt2pfoblhto.html

Go:   if s == "" {}
来源：http://dali.yj202588.top/Article/details/gt2ahldicqd.html

Ruby: if s.empty?
来源：http://dali.yangfankeji.com/Article/details/gt2rbjmsuyw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jiagoushi.top/Article/details/gt2zyltwngq.html

[E21] 超长截断加省略号
来源：http://dali.cheryme.top/Article/details/gt2aybauyhn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rceniymg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2cjbjqmiy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gt2tkmljfei.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2qqfoenmj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2saxclgwy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.birdmap.top/Article/details/gt2nwtgixwv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2trzhfssb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gt2iqfwruqq.html

[E22] 字节长度与字符长度
来源：http://dali.yangfankeji.com/Article/details/gt2wisuksma.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ypknvbxu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gt2ptouyrmx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gt2xkrnvbta.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gt2rpexljcw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ydzc1.top/Article/details/gt2hgqxsskl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.andypj.xyz/Article/details/gt2esktgfvd.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2mnpfjfus.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cashguo.top/Article/details/gt2ftvmkjem.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2epppjoou.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gt2riootssn.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2rowtahgq.html

[F01] 读取整个文件
来源：http://dali.nanxinkj.top/Article/details/gt2nlbpzbhw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.kuanghao11.cn/Article/details/gt2jwdfkteq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2pbrkeidf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.iojbl.cn/Article/details/gt2wjwwjnxy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gt2qcaffjem.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2ntirkfhi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.9152youxi.cn/Article/details/gt2fyowdfqh.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2yjhcvfdh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2axaxmpgj.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gt2ymmjaftj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yanxiufei.cn/Article/details/gt2grjenuqg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gt2dainmegx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gt2zsjskglm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2crrtmxmr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjvoxjnr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ecnvnngh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj202588.top/Article/details/gt2jyanljia.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258.top/Article/details/gt2lnyjyrny.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bnwqvcgx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gt2erokxbnq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gt2zhnierwm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gt2seraihef.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gt2vjfsvesx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtasgee.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigufen.top/Article/details/gt2dcgbotdz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.haohaochexian.top/Article/details/gt2ydjsxsng.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gt2ahveauyq.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gt2djcvnilh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuanzx.com/Article/details/gt2lmhcnhiu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.kuanghao11.cn/Article/details/gt2bvzijlyc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gt2zgjsgihs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2yksmvkyk.html


<!-- 参考信息 -->