代发 wailian999

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gt2zxcgrvje.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gt2vavlguhy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yanxiufei.cn/Article/details/gt2aiugeudf.html

Go:   // 手写 map[T]int
来源：http://dali.shuidangran.top/Article/details/gt2xsdawoqh.html

Ruby: arr.tally
来源：http://dali.guannengcc.top/Article/details/gt2jxulaulr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cqqwz.cn/Article/details/gt2ohaklrzw.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpytqlw.html

Py:   x in arr
来源：http://dali.shzxlz.cn/Article/details/gt2xodfynxb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hammf.cn/Article/details/gt2yymipium.html

JS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2slryokwi.html

TS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vomwkzeh.html

Java: list.contains(x)
来源：http://dali.zdqjudy.top/Article/details/gt2ixmkwtrg.html

Go:   slices.Contains(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2grhbtxst.html

Ruby: arr.include?(x)
来源：http://dali.mhx1999.top/Article/details/gt2fepcvumz.html

C#:   list.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2cnzbtnuu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuetiantiany.cn/Article/details/gt2xjsxznii.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sxryk.cn/Article/details/gt2qejblgzs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cucudq.cn/Article/details/gt2quoegzft.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2uvnesacc.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gt2gjmeoehe.html

Java: new ArrayList<>(list);
来源：http://dali.gotoacloud.top/Article/details/gt2cyjduzkw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuxming.cn/Article/details/gt2tszfbfzh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dashuyun.cn/Article/details/gt2nmgquyjg.html

C#:   new List<int>(list);
来源：http://dali.xziqi.cn/Article/details/gt2ykfjfzad.html

[D23] reduce 累积计算
来源：http://dali.yj20258888.top/Article/details/gt2zvxqdfrn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2fylefnvo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2rxtkekau.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2yctkkuwr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gt2ucyynonb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jyoumei.cn/Article/details/gt2myifzrzf.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2dpvycmms.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jyoumei.cn/Article/details/gt2zpuoqezo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.c1oappe.top/Article/details/gt2nanignmi.html

[D24] 字典 / Map 基本操作
来源：http://dali.fzhhl.top/Article/details/gt2wsiwcxme.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tanke756.top/Article/details/gt2pygivzbt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhengqikj.top/Article/details/gt2klovztzc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.meibo888.top/Article/details/gt2sgcnrvkd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2iwkhvltf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zycfv.cn/Article/details/gt2qnzwdmxd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gt2sgqsvird.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qykjkukg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pdtnrdte.html

[D25] Set 集合去重与交并差
来源：http://dali.mhx1999.top/Article/details/gt2ckiqscdg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jyoumei.cn/Article/details/gt2nxurzxst.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cucudq.cn/Article/details/gt2mymiguta.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnqzz.top/Article/details/gt2luviaido.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tianlin.xyz/Article/details/gt2qzyoerbp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sxryk.cn/Article/details/gt2rjforazn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.mhx1999.top/Article/details/gt2leyjpomk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2boddpaoj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2alzpgcjy.html

[D26] 数组转字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2ixyionlv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dashuyun.cn/Article/details/gt2pmvexcxi.html

PHP:  implode(", ", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wtdyvymv.html

JS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gt2tcrqhrzr.html

TS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gt2ctprjoch.html

Java: String.join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gt2vrcilbnj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258.top/Article/details/gt2eehmocfk.html

Ruby: arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kujtjenf.html

C#:   string.Join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gt2rrhxyhoo.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2gjdksjni.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxwuwza.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2edddzoxy.html

[E01] 拼接字符串
来源：http://dali.316326.xyz/Article/details/gt2llzpkvoi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ivvv.top/Article/details/gt2eeqbcdzb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2ekiskulh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gt2ujsdtkjc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gt2ngpjfyfv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yueranfly.top/Article/details/gt2juulpnft.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tanke756.top/Article/details/gt2erwjorms.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jlsjyb.cn/Article/details/gt2upajvfjh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2sonchvsh.html

[E02] 重复字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2nubbfmbj.html

Py:   "ab" * 3
来源：http://dali.meibo888.top/Article/details/gt2pqictnwq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tanke756.top/Article/details/gt2zcdnzbdc.html

JS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gt2jtgkahhn.html

TS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2vmoffmav.html

Java: "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gt2hrkytxco.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gotoacloud.top/Article/details/gt2xfkkzmtr.html

Ruby: "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gt2zktyqjke.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daxiang520.top/Article/details/gt2rmkjraib.html

[E03] 截取子串
来源：http://dali.xziqi.cn/Article/details/gt2ivcovslt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xylfe.cn/Article/details/gt2zqycafpr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gt2kgkryvjq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gt2cvljfssl.html

TS:   s.slice(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gt2zorsnnte.html

Java: s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gt2gbrvgkjf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ivvv.top/Article/details/gt2zilrdnpo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hnqzz.top/Article/details/gt2wzplhame.html

C#:   s.Substring(1, 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2fouuvugv.html

[E04] 查找子串位置
来源：http://dali.redwolf501.top/Article/details/gt2pmdcahat.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dprliwes.html

PHP:  strpos($s, "x");
来源：http://dali.hammf.cn/Article/details/gt2pzkcumze.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxinkj.top/Article/details/gt2aprrlyvd.html

TS:   s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gt2eqeurmlh.html

Java: s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gt2cjjcwqqi.html

Go:   strings.Index(s, "x")
来源：http://dali.yuxming.cn/Article/details/gt2giqxuvxc.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2swirilbj.html

C#:   s.IndexOf("x")
来源：http://dali.daxiang520.top/Article/details/gt2ekhjyekg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xziqi.cn/Article/details/gt2mjwrpzfm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.quarkkingdee.top/Article/details/gt2alyzmryh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhongyouzk.top/Article/details/gt2erskvsbn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2teuztfws.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hywenlv.cn/Article/details/gt2dznqkmib.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gt2wpwqhghz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nludthhi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gogol.net.cn/Article/details/gt2tlsneykb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ydzc1.top/Article/details/gt2mwthsply.html

[E06] 替换子串
来源：http://dali.kuanghao11.cn/Article/details/gt2cesmxlxc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gt2fciqwcih.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yonumen.top/Article/details/gt2nhqfwopy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2krxywtvj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2svocqcwz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2jwpwfntb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zycfv.cn/Article/details/gt2rgaivsok.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2dzhhjdtl.html

C#:   s.Replace("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2vjfcuwfg.html

[E07] 按分隔符拆分
来源：http://dali.jqgfzy.top/Article/details/gt2zvvmucnk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.andypj.xyz/Article/details/gt2nwosdocp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2ftsnuxfi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zdqjudy.top/Article/details/gt2sngriscg.html

TS:   s.split(",")
来源：http://dali.jyoumei.cn/Article/details/gt2lfzonnps.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258.top/Article/details/gt2pvqzhktk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xziqi.cn/Article/details/gt2cuefkmbw.html

Ruby: s.split(",");  s.split
来源：http://dali.fzhhl.top/Article/details/gt2tbmbsrlp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gzhubu.top/Article/details/gt2gqsaemqc.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbpxxsi.html

Py:   ",".join(items)
来源：http://dali.gaohongyu789.top/Article/details/gt2vvnqsxai.html

PHP:  implode(",", $items);
来源：http://dali.aibaodan.cn/Article/details/gt2xcokwnoi.html

JS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gt2zoguvwwx.html

TS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2bkynnqxa.html

Java: String.join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gt2ldptskdx.html

Go:   strings.Join(items, ",")
来源：http://dali.ydzc1.top/Article/details/gt2hhtsqcsf.html

Ruby: items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gt2ibvhmixp.html

C#:   string.Join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gt2yuenaqny.html

[E09] 去除所有空白字符
来源：http://dali.zhoulong.xyz/Article/details/gt2mzokxqsx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.316326.xyz/Article/details/gt2vcpgeuyo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tian-w.cn/Article/details/gt2rhqrlpzk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gt2unuoazdq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gt2aggaylwm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xinyue.icu/Article/details/gt2gvobhtmn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnxiangtu.top/Article/details/gt2ywevvzhl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gt2nocmbeuj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgnlrgfl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.redwolf501.top/Article/details/gt2nqhutnpc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gt2flcomooj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dashuyun.cn/Article/details/gt2kneyuggf.html

JS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2nrhxlcvx.html

TS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2mwyxetes.html

Java: String.format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gt2manynude.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gt2gsvulqcj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gt2wjvtcuim.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pengpengdd.cyou/Article/details/gt2jqlqkwba.html

[E11] 反转字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2jbdgfpqj.html

Py:   s[::-1]
来源：http://dali.yueranfly.top/Article/details/gt2rmzgvjkp.html

PHP:  strrev($s);
来源：http://dali.tanke756.top/Article/details/gt2opjxfqnp.html

JS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gt2iqkmfgym.html

TS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2mefnyjnq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2dxfiyorr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.mhx1999.top/Article/details/gt2mrullmnw.html

Ruby: s.reverse
来源：http://dali.haohaochexian.top/Article/details/gt2bunsxtut.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gt2dsknwiqq.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2talsbmdq.html

Py:   s.count("a")
来源：http://dali.daria6918.cn/Article/details/gt2ldsrtsqb.html

PHP:  substr_count($s, "a");
来源：http://dali.zhengqikj.top/Article/details/gt2vbgrbpiv.html

JS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gt2prfwfudy.html

TS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otsjrcuz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cdnleiting.top/Article/details/gt2adxoriox.html

Go:   strings.Count(s, "a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqnjaktj.html

Ruby: s.count("a")
来源：http://dali.wangdashe.top/Article/details/gt2hohihafu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jlsjyb.cn/Article/details/gt2jyaraeao.html

[E13] 逐字符遍历
来源：http://dali.cdnleiting.top/Article/details/gt2efugidvr.html

Py:   for ch in s: print(ch)
来源：http://dali.hywenlv.cn/Article/details/gt2nthbbdhk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zycfv.cn/Article/details/gt2gefggsud.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gt2lqomdhhp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gt2lwljhswd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuanzhike.top/Article/details/gt2ksmdwmmm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pycfn.com/Article/details/gt2xccotmeu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuanzx.com/Article/details/gt2aqdzfwbq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2aivtisfr.html

[E14] URL 编码与 Base64
来源：http://dali.iojbl.cn/Article/details/gt2ojnzluwg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuxming.cn/Article/details/gt2kkpxhljf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2qesficyb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnxiangtu.top/Article/details/gt2zrgnketg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.smart0.xyz/Article/details/gt2cebhhulj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.birdmap.top/Article/details/gt2nscolzhu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.birdmap.top/Article/details/gt2fvcummef.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnqzz.top/Article/details/gt2tuoyxitk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daria6918.cn/Article/details/gt2myfdvxqh.html

[E15] HTML 转义 / 反转义
来源：http://dali.gaohongyu789.top/Article/details/gt2qkewnxed.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxinkj.top/Article/details/gt2nhcklxud.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xinyue.icu/Article/details/gt2msttpbyn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gyyponbh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shuidangran.top/Article/details/gt2glxnopcc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cqqwz.cn/Article/details/gt2ulwuvzkb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2kifcltmv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ehwqpu.com/Article/details/gt2kjowxuep.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tianlin.xyz/Article/details/gt2xxbumoci.html

[E16] 数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gt2mpkqwnew.html

Py:   f"{1234567:,}"
来源：http://dali.tian-w.cn/Article/details/gt2fmijhezl.html

PHP:  number_format(1234567);
来源：http://dali.sxryk.cn/Article/details/gt2vkhmxibq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gt2shqfagoa.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gt2lxfkzcug.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.havefunace.top/Article/details/gt2hloxfcxt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenzaomai.com/Article/details/gt2feibxwff.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gt2ltzcykjd.html

C#:   1234567.ToString("N0")
来源：http://dali.sufxvd.cn/Article/details/gt2tadjoulg.html

[E17] 首字母大写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivofpohl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guannengcc.top/Article/details/gt2ktvxaqqt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2myrdvetx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gt2torvikmj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gt2fwwtrizq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ppjwa.cn/Article/details/gt2kmqtvjlr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gt2cciszqgc.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mfnyejeq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.smart0.xyz/Article/details/gt2graprobm.html

[E18] 模板占位符替换
来源：http://dali.aizwys.cn/Article/details/gt2sswfevgr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jiceebta.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gt2gzettylc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2knpcgkmv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2scfgatmb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2fofhwryi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2uyulgjni.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.snrcjt.cn/Article/details/gt2pnbgpixa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hammf.cn/Article/details/gt2afwsmpab.html

[E19] 多行文本按行拆分
来源：http://dali.yueranfly.top/Article/details/gt2gewzjaxa.html

Py:   s.splitlines()
来源：http://dali.jyoumei.cn/Article/details/gt2usltyohk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yonumen.top/Article/details/gt2rjaywcwn.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gt2mntderxr.html

TS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gt2eoshndkl.html

Java: s.lines().toList()
来源：http://dali.jiagoushi.top/Article/details/gt2mufciinb.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lorhgqpr.html

Ruby: s.lines
来源：http://dali.hfpthk.cn/Article/details/gt2pgejpnli.html

C#:   s.Split('\n')
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewskrgrn.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gt2fdqgfnjm.html

Py:   if not s:
来源：http://dali.sweek.top/Article/details/gt2jeqybbxc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tianlin.xyz/Article/details/gt2cvxtzcax.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nwbrower.top/Article/details/gt2omufoshs.html

TS:   if (s === "") {}
来源：http://dali.sysykeji.top/Article/details/gt2uvjubogg.html

Java: if (s.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gt2knrfhllh.html

Go:   if s == "" {}
来源：http://dali.redwolf501.top/Article/details/gt2mljceczd.html

Ruby: if s.empty?
来源：http://dali.gaohongyu789.top/Article/details/gt2fqmlumdr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gt2tftuklgh.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gt2awyqygip.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xziqi.cn/Article/details/gt2bsclgbqe.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2saknmecl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2qsjmspav.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2yvoygtvh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2ktuyohws.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dashuyun.cn/Article/details/gt2ilzmferv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2urwidwlj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2nwltlfbs.html

[E22] 字节长度与字符长度
来源：http://dali.ehwqpu.com/Article/details/gt2ggtpqwud.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sufxvd.cn/Article/details/gt2plimwxbi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2shndccco.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gt2iwpojlvr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gt2jxzuccyb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gt2sjafrcmx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj202588.top/Article/details/gt2augdzumc.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkcnnpjw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gt2hytbqsor.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2afwvrghj.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gt2cqvxfmpv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2eystjwzw.html

[F01] 读取整个文件
来源：http://dali.aizwys.cn/Article/details/gt2njbeifxt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258888.top/Article/details/gt2imeipyly.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2osdblwka.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gt2erxwxrxk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nwbrower.top/Article/details/gt2xttcgfiz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2ayspavtd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.9152youxi.cn/Article/details/gt2frlgveaj.html

Ruby: File.read("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2fasfbsza.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2hdhmpnkn.html

[F02] 逐行读取文件
来源：http://dali.yueranfly.top/Article/details/gt2lawalelo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shuidangran.top/Article/details/gt2bangxmuk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghfgproj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gt2fauhgqwv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gt2uffexzdy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gt2qpvbmrsm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxuanxn.top/Article/details/gt2lmdegmqo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxinkj.top/Article/details/gt2xuqzosnx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lpzshkcs.html

[F03] 写入文件（覆盖）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qizopong.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fengsongda.top/Article/details/gt2fzdrdusn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gt2likbtjqc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2dhsbmcxi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bmvmkfzj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.snrcjt.cn/Article/details/gt2unrzwemp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cqqwz.cn/Article/details/gt2rbachnpm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgufenzy.top/Article/details/gt2egjarygy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gt2gmxetrte.html

[F04] 追加写入文件
来源：http://dali.svipenyu.cn/Article/details/gt2ibgzhpwa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2adizgtdr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ppjwa.cn/Article/details/gt2zzvvymdn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gt2rdxlkeie.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2znzwxfpw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gt2qvmswmuu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pycfn.com/Article/details/gt2tmwbjssk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ehwqpu.com/Article/details/gt2vjtrrnec.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj202588.top/Article/details/gt2vhrhjjbi.html


<!-- 参考信息 -->