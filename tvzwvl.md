代发 wailian999

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxuanxn.top/Article/details/gt2oyboqwzs.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pttmjjhu.html

TS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gt2tcugcmol.html

Java: list.contains(x)
来源：http://dali.316326.xyz/Article/details/gt2bsgomlhd.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jlhnvsrb.html

Ruby: arr.include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2mejorsma.html

C#:   list.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjyczjei.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigufen.top/Article/details/gt2yhxaqnlh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2qzivnvyd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.c1oappe.top/Article/details/gt2qrbwbftp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jianghu66.top/Article/details/gt2vwtqgzfq.html

TS:   [...arr];
来源：http://dali.quarkkingdee.top/Article/details/gt2pcfoynip.html

Java: new ArrayList<>(list);
来源：http://dali.ivvv.top/Article/details/gt2gjkawirg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yongpay.top/Article/details/gt2rbdoqept.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuxming.cn/Article/details/gt2hzujudqy.html

C#:   new List<int>(list);
来源：http://dali.yanxiufei.cn/Article/details/gt2aqvorecy.html

[D23] reduce 累积计算
来源：http://dali.yuanzhike.top/Article/details/gt2uiiosqsm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.iojbl.cn/Article/details/gt2oyfzksts.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aizwys.cn/Article/details/gt2bridesww.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2bugndcjc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwbtxzxu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aibaodan.cn/Article/details/gt2zuxrrfzi.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bcwqvpim.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ivvv.top/Article/details/gt2ilbokbkq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cashguo.top/Article/details/gt2taqfqlgm.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigufen.top/Article/details/gt2xqwfbulx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yanxiufei.cn/Article/details/gt2nxzckxbo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2bdscdfrs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sweek.top/Article/details/gt2fustwapi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.316326.xyz/Article/details/gt2qoqhhneu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xylfe.cn/Article/details/gt2whwuvmum.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yangfankeji.com/Article/details/gt2caeefkbh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ppjwa.cn/Article/details/gt2xehfngqi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhixingplan.top/Article/details/gt2mbbmrhcb.html

[D25] Set 集合去重与交并差
来源：http://dali.fzhhl.top/Article/details/gt2xxautavn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cqqwz.cn/Article/details/gt2pusjxabm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.havefunace.top/Article/details/gt2pryymgzb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jianghu66.top/Article/details/gt2hloicapv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sufxvd.cn/Article/details/gt2xyawdyhz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ybcxt.top/Article/details/gt2toivbijl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hammf.cn/Article/details/gt2vzkfeifu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangdashe.top/Article/details/gt2kacloczo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yueranfly.top/Article/details/gt2kxgkgvrw.html

[D26] 数组转字符串
来源：http://dali.hammf.cn/Article/details/gt2ypkkcgcf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2iwrylmep.html

PHP:  implode(", ", $arr);
来源：http://dali.chenlongwang.top/Article/details/gt2nvmzqoqe.html

JS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gt2kczrdshe.html

TS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gt2xnvbzfsv.html

Java: String.join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gt2dzglltdb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gt2tpijmtjx.html

Ruby: arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gt2nfsaafcn.html

C#:   string.Join(", ", list)
来源：http://dali.havefunace.top/Article/details/gt2gaaucexd.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2jltbsufh.html

E. 字符串处理
来源：http://dali.ybcxt.top/Article/details/gt2dtsafnfv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2dxbbrtxe.html

[E01] 拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2bgfkiqaa.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gt2nstbfjfh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenlongwang.top/Article/details/gt2ufcxaoxv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2isykelpq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gt2msnygzfb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2zsndcjji.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gt2zbpijgts.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guannengcc.top/Article/details/gt2dhdddnzr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2hbqxvwtb.html

[E02] 重复字符串
来源：http://dali.hysaishi.cn/Article/details/gt2zgchtkzl.html

Py:   "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gt2kzdqoryn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yongpay.top/Article/details/gt2tdvmqosi.html

JS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxvvuirr.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gt2ousyjswb.html

Java: "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gt2ywlvittu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuxming.cn/Article/details/gt2bmdtxprr.html

Ruby: "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gt2pelyncka.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ehwqpu.com/Article/details/gt2cdlakpfm.html

[E03] 截取子串
来源：http://dali.cheryme.top/Article/details/gt2voaadshx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258888.top/Article/details/gt2yoskfbzh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gt2dzylleso.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gt2iugmjwns.html

TS:   s.slice(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2fxtpuhil.html

Java: s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gt2qpurcalu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigufen.top/Article/details/gt2xxrsevyo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ppjwa.cn/Article/details/gt2gljapkhi.html

C#:   s.Substring(1, 3)
来源：http://dali.yuxming.cn/Article/details/gt2tjhiqxme.html

[E04] 查找子串位置
来源：http://dali.chenlongwang.top/Article/details/gt2echgauvv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqcnfgnh.html

PHP:  strpos($s, "x");
来源：http://dali.kuanghao11.cn/Article/details/gt2dcewmjmi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qfmlvrhe.html

TS:   s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2lgxiaypk.html

Java: s.indexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gt2vcqlwkpo.html

Go:   strings.Index(s, "x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmuzsyjy.html

Ruby: s.index("x")
来源：http://dali.yongpay.top/Article/details/gt2vqbkaowj.html

C#:   s.IndexOf("x")
来源：http://dali.bjfxy.top/Article/details/gt2lxrfyrqa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aygbwkly.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cucudq.cn/Article/details/gt2vzwwoulv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yueranfly.top/Article/details/gt2wkwjeipv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gt2hobsapgx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gaohongyu789.top/Article/details/gt2cklbxcio.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gt2rqbrxvoi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.redwolf501.top/Article/details/gt2gcnkvlqz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qpatdmom.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xziqi.cn/Article/details/gt2hnyutzgp.html

[E06] 替换子串
来源：http://dali.guowangkeji.top/Article/details/gt2hfytcnym.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gt2pynzeotj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2lotzjste.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2qgxnjgkw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xdrcnhcg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkvgbudt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulvbfsyu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2qamybhqp.html

C#:   s.Replace("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2toyzfdfl.html

[E07] 按分隔符拆分
来源：http://dali.mhx1999.top/Article/details/gt2kxxkkiwp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.mhx1999.top/Article/details/gt2byzpgcdw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2ovykiull.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guowangkeji.top/Article/details/gt2muqztbua.html

TS:   s.split(",")
来源：http://dali.hfpthk.cn/Article/details/gt2sdftwxyy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fzhhl.top/Article/details/gt2ajiczoyz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sysykeji.top/Article/details/gt2jdijchzt.html

Ruby: s.split(",");  s.split
来源：http://dali.c1oappe.top/Article/details/gt2ztdeuapc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gt2byapkpaa.html

[E08] 数组按分隔符合并
来源：http://dali.zhongyouzk.top/Article/details/gt2tlhzwelf.html

Py:   ",".join(items)
来源：http://dali.hfpthk.cn/Article/details/gt2tfyvyqhn.html

PHP:  implode(",", $items);
来源：http://dali.jinqigfzy.top/Article/details/gt2hsgdqbne.html

JS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gt2xrdkameg.html

TS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gt2qzqndara.html

Java: String.join(",", items)
来源：http://dali.ydzc1.top/Article/details/gt2cjgdtjdq.html

Go:   strings.Join(items, ",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ycjpmlbz.html

Ruby: items.join(",")
来源：http://dali.meibo888.top/Article/details/gt2xdbhrunh.html

C#:   string.Join(",", items)
来源：http://dali.pycfn.com/Article/details/gt2nsboutzu.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gt2dvgceinz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ivvv.top/Article/details/gt2jdblopjz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cucudq.cn/Article/details/gt2ggqefrre.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gt2hdkuayij.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gt2gjbtpdmh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ivvv.top/Article/details/gt2uftgprrh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuanzx.com/Article/details/gt2vnjhinro.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hysaishi.cn/Article/details/gt2cxltjysk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258.top/Article/details/gt2zlweulfe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuanzhike.top/Article/details/gt2yvxeqtim.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2uyeamqqj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.svipenyu.cn/Article/details/gt2ogavbome.html

JS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gt2inikamql.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gt2ckyvsuco.html

Java: String.format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gt2trhesdox.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2oamzqict.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gt2lbltsphc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jiagoushi.top/Article/details/gt2krzdsvpz.html

[E11] 反转字符串
来源：http://dali.hysaishi.cn/Article/details/gt2wjgjtejr.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gt2gzvfbvys.html

PHP:  strrev($s);
来源：http://dali.ybcxt.top/Article/details/gt2tyrwrvwx.html

JS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2mxoxksrl.html

TS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gt2mmzhdqal.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhengqikj.top/Article/details/gt2uryfbjau.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zycfv.cn/Article/details/gt2verybspa.html

Ruby: s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lwbnxict.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gt2czqkvrpj.html

[E12] 统计某字符出现次数
来源：http://dali.sufxvd.cn/Article/details/gt2tclfowmz.html

Py:   s.count("a")
来源：http://dali.shuidangran.top/Article/details/gt2oitanuno.html

PHP:  substr_count($s, "a");
来源：http://dali.bjfxy.top/Article/details/gt2tnhuvnar.html

JS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmishuqv.html

TS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gt2hlnkrozz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daria6918.cn/Article/details/gt2ytbydmfe.html

Go:   strings.Count(s, "a")
来源：http://dali.sysykeji.top/Article/details/gt2ygvokudd.html

Ruby: s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zcmlxccf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.redwolf501.top/Article/details/gt2ekjogadp.html

[E13] 逐字符遍历
来源：http://dali.cashguo.top/Article/details/gt2fcmeanao.html

Py:   for ch in s: print(ch)
来源：http://dali.xuanzx.com/Article/details/gt2cambpcwv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.havefunace.top/Article/details/gt2uurkxyzx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gt2lozpdktx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gt2phaebdey.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gt2iuuejgpn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cdnleiting.top/Article/details/gt2jlovggrk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gt2kpyooawr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2lcjngcqt.html

[E14] URL 编码与 Base64
来源：http://dali.zhiwuduotai.top/Article/details/gt2gftporjj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gt2wcthvrdx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hfpthk.cn/Article/details/gt2upjagjtv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jlsjyb.cn/Article/details/gt2zxbmawnj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aizwys.cn/Article/details/gt2bqkzpzmu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gt2nqcothom.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gt2xkzbxuqs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zycfv.cn/Article/details/gt2hakkmecv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258888.top/Article/details/gt2gvfbdorw.html

[E15] HTML 转义 / 反转义
来源：http://dali.xziqi.cn/Article/details/gt2dxushhug.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.havefunace.top/Article/details/gt2ufifobhp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cucudq.cn/Article/details/gt2rtoljcqt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2nepnkjtt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgufenzy.top/Article/details/gt2igjlyjsc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangdashe.top/Article/details/gt2wocojvfb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xinyue.icu/Article/details/gt2kngmzach.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2fyhevndb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sysykeji.top/Article/details/gt2tmlysocw.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gt2igqivifu.html

Py:   f"{1234567:,}"
来源：http://dali.redwolf501.top/Article/details/gt2foqraamo.html

PHP:  number_format(1234567);
来源：http://dali.shangyingyoupin.top/Article/details/gt2lmffsabf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gt2duhueshh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gt2izfrmvzt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gt2drcnfqlo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gotoacloud.top/Article/details/gt2ejifglyt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dianchejie.cn/Article/details/gt2hmecjalv.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258888.top/Article/details/gt2epqtvvqk.html

[E17] 首字母大写
来源：http://dali.meibo888.top/Article/details/gt2yzjoxdtk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mrwpjslk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cdnleiting.top/Article/details/gt2wmjkubqk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gt2wrvffaez.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gt2ajwonnez.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tian-w.cn/Article/details/gt2ovrlzrxc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yueranfly.top/Article/details/gt2nqeemcpv.html

Ruby: s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gt2judcwzug.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sufxvd.cn/Article/details/gt2wqkwftgm.html

[E18] 模板占位符替换
来源：http://dali.havefunace.top/Article/details/gt2kuzudxzw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.haohaochexian.top/Article/details/gt2respsuqc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigfzy.top/Article/details/gt2pigfvija.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gt2byzdkhkb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tirmbuan.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2cbedbtkc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nwbrower.top/Article/details/gt2bshulela.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhongyouzk.top/Article/details/gt2jnrxcsby.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yvedp.cn/Article/details/gt2asxxovhv.html

[E19] 多行文本按行拆分
来源：http://dali.guowangkeji.top/Article/details/gt2qwegapam.html

Py:   s.splitlines()
来源：http://dali.jiagoushi.top/Article/details/gt2prafmlwp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2yirxabmx.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhvnpfme.html

TS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gt2atdfaebi.html

Java: s.lines().toList()
来源：http://dali.hfpthk.cn/Article/details/gt2eaeaenth.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenlongwang.top/Article/details/gt2chdabugs.html

Ruby: s.lines
来源：http://dali.316326.xyz/Article/details/gt2mthresjp.html

C#:   s.Split('\n')
来源：http://dali.guannengcc.top/Article/details/gt2jvbseqmn.html

[E20] 判断字符串是否为空
来源：http://dali.nwbrower.top/Article/details/gt2zaexceeg.html

Py:   if not s:
来源：http://dali.jiagoushi.top/Article/details/gt2lpdwelcs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuetiantiany.cn/Article/details/gt2vyojdqjl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gt2xyqvirrv.html

TS:   if (s === "") {}
来源：http://dali.hysaishi.cn/Article/details/gt2cpovhwpo.html

Java: if (s.isEmpty()) {}
来源：http://dali.c1oappe.top/Article/details/gt2dlpolcws.html

Go:   if s == "" {}
来源：http://dali.vqdsnc.cn/Article/details/gt2dlukteen.html

Ruby: if s.empty?
来源：http://dali.jyoumei.cn/Article/details/gt2lgvqbnig.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2movbwxou.html

[E21] 超长截断加省略号
来源：http://dali.bjfxy.top/Article/details/gt2jdyplknb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gt2ubbvtzvv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2ozcfnagn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2bepcrimz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gt2gzkblray.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gt2jswylyug.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gt2giwezrxl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2znprcyij.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2vzllfuyd.html

[E22] 字节长度与字符长度
来源：http://dali.snrcjt.cn/Article/details/gt2ulzzfiic.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.haohaochexian.top/Article/details/gt2wmsyiruh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2xamrgkmj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gt2ktgdwiee.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gt2hxzwexvd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gt2ptyfarft.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gotoacloud.top/Article/details/gt2adgdujos.html

Ruby: s.bytesize;  s.length
来源：http://dali.zycfv.cn/Article/details/gt2vgqsuojo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sufxvd.cn/Article/details/gt2peekweom.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2qejspqyf.html

F. 文件与目录
来源：http://dali.yanxiufei.cn/Article/details/gt2ahpzvqrd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2tugcfurz.html

[F01] 读取整个文件
来源：http://dali.yj20258.top/Article/details/gt2sweanghv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yonumen.top/Article/details/gt2aeymjiye.html

PHP:  file_get_contents("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2dqygwpzy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shzxlz.cn/Article/details/gt2necrmwbo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gt2ofkynqdu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2urekbybh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnqzz.top/Article/details/gt2igpowzag.html

Ruby: File.read("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2moerlvah.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2krsfbdjy.html

[F02] 逐行读取文件
来源：http://dali.andypj.xyz/Article/details/gt2fbobetjt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yongpay.top/Article/details/gt2qjaphlvk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgufenzy.top/Article/details/gt2cphhyofn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gt2vgmvycak.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2aqyhulql.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gt2bkupicqq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jiagoushi.top/Article/details/gt2amekloom.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vrnjqvdt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hammf.cn/Article/details/gt2gzvazqhi.html

[F03] 写入文件（覆盖）
来源：http://dali.shzxlz.cn/Article/details/gt2qzaqcafz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqjixkox.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gt2mudhvlvb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gt2fdmxrujw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gt2icnhezbk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dianchejie.cn/Article/details/gt2ueqbcuej.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cqqwz.cn/Article/details/gt2msfrtvuf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jianghu66.top/Article/details/gt2izmqihtv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gt2adthyxvt.html

[F04] 追加写入文件
来源：http://dali.sxryk.cn/Article/details/gt2izwnxnnl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dashuyun.cn/Article/details/gt2gnvmqlqn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gt2krmqtvhl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qtrbqpod.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gt2dnnjmifg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mbqnedip.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mbpafsdq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gzhubu.top/Article/details/gt2aylghpiw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnqzz.top/Article/details/gt2itskvhts.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qbojgxsz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cucudq.cn/Article/details/gt2xhqwipos.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2ozihjywl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ppxcanbs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjfbkhvt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2gpfigxsw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.quarkkingdee.top/Article/details/gt2ysmoqggh.html

Ruby: File.exist?("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2okixfxwc.html


<!-- 参考信息 -->