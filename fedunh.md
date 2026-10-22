代发 wailian999

Go:   slices.Contains(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2dorhczlh.html

Ruby: arr.include?(x)
来源：http://dali.gogol.net.cn/Article/details/gt2dsfqbzav.html

C#:   list.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gt2upravtul.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgfzy.top/Article/details/gt2qfvdfyxm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2iqmvruos.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dianchejie.cn/Article/details/gt2zogknhtw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fzhhl.top/Article/details/gt2ibjlvqpb.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gt2jwtknpkx.html

Java: new ArrayList<>(list);
来源：http://dali.yongpay.top/Article/details/gt2dqgpixzv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daria6918.cn/Article/details/gt2xnawtonn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yonumen.top/Article/details/gt2jlotjgzp.html

C#:   new List<int>(list);
来源：http://dali.cdnleiting.top/Article/details/gt2iznzvyoc.html

[D23] reduce 累积计算
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ezhzjqga.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2oheliyqw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hywenlv.cn/Article/details/gt2jsbxumdx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2ewmlkgpi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2agxpdqnc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yanxiufei.cn/Article/details/gt2vhunsxbi.html

Go:   // 手写循环
来源：http://dali.yj202588.top/Article/details/gt2fgronxth.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenlongwang.top/Article/details/gt2nsiuqift.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hysaishi.cn/Article/details/gt2omxhzuks.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pniewzpg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ydzc1.top/Article/details/gt2ojwltirr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xinyue.icu/Article/details/gt2daogndxl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yvedp.cn/Article/details/gt2ehulsnsq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2ijujwpud.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.havefunace.top/Article/details/gt2fuotsfrt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gogol.net.cn/Article/details/gt2glwouucw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2aplwfvct.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenzaomai.com/Article/details/gt2wbauxmqy.html

[D25] Set 集合去重与交并差
来源：http://dali.jlsjyb.cn/Article/details/gt2fywoodxz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guannengcc.top/Article/details/gt2fedbhivv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.birdmap.top/Article/details/gt2izqqulzy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhixingplan.top/Article/details/gt2siwurewk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jlsjyb.cn/Article/details/gt2frenxuyf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cashguo.top/Article/details/gt2dmpfhbyu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gt2qmnnmrts.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yonumen.top/Article/details/gt2zgbkobei.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tanke756.top/Article/details/gt2tqfhfzfj.html

[D26] 数组转字符串
来源：http://dali.andypj.xyz/Article/details/gt2cjrshbxr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.snrcjt.cn/Article/details/gt2rszhpcrp.html

PHP:  implode(", ", $arr);
来源：http://dali.dashuyun.cn/Article/details/gt2lthkqfpv.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wcjmrjua.html

TS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gt2eiwmuywz.html

Java: String.join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gt2rzzyimsn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hysaishi.cn/Article/details/gt2lywariat.html

Ruby: arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gt2sqzcefzf.html

C#:   string.Join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gt2ecqkctmj.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2dyqdioxm.html

E. 字符串处理
来源：http://dali.wangdashe.top/Article/details/gt2umtkcahi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ojquhasf.html

[E01] 拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2rdcvhaqi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guowangkeji.top/Article/details/gt2zbxzjuxz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gotoacloud.top/Article/details/gt2kpgverca.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gt2yxqiakhu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2wxbnaoak.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xinyue.icu/Article/details/gt2ddooscxg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rrlqchlh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangdashe.top/Article/details/gt2nhgqryix.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kciamtru.html

[E02] 重复字符串
来源：http://dali.pycfn.com/Article/details/gt2hgrcqjix.html

Py:   "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gt2qqrqosvn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.havefunace.top/Article/details/gt2mqotsnqd.html

JS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gt2doerjpaa.html

TS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gt2tbjkivup.html

Java: "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zgpfrlqn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hywenlv.cn/Article/details/gt2igofakkn.html

Ruby: "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gt2rrtjynqj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hywenlv.cn/Article/details/gt2hfprhyha.html

[E03] 截取子串
来源：http://dali.guannengcc.top/Article/details/gt2hnyblqqs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.redwolf501.top/Article/details/gt2wbxpwjwi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ckjggrby.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gt2dlvjkffk.html

TS:   s.slice(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gt2slhxzcmt.html

Java: s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gt2bwxqftke.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.haohaochexian.top/Article/details/gt2kzdmjokd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yvedp.cn/Article/details/gt2hcahjkfu.html

C#:   s.Substring(1, 3)
来源：http://dali.cdnleiting.top/Article/details/gt2xpukiwdh.html

[E04] 查找子串位置
来源：http://dali.gzhubu.top/Article/details/gt2xoxvrnls.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fengsongda.top/Article/details/gt2menetmms.html

PHP:  strpos($s, "x");
来源：http://dali.yvedp.cn/Article/details/gt2lhtjjxww.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idgpfwqt.html

TS:   s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2qktqnsfk.html

Java: s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gt2ihzrowzy.html

Go:   strings.Index(s, "x")
来源：http://dali.iojbl.cn/Article/details/gt2ujvbwwrs.html

Ruby: s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rjoarvwh.html

C#:   s.IndexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gt2vcjfkthk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hammf.cn/Article/details/gt2brxjufof.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxinkj.top/Article/details/gt2jzoxqrug.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuxming.cn/Article/details/gt2rkfdhylt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gt2tpcqhzib.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2dcfwoslo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gt2eseueiiw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cashguo.top/Article/details/gt2toudlowv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daria6918.cn/Article/details/gt2uugujmpy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ckgwmmxt.html

[E06] 替换子串
来源：http://dali.gotoacloud.top/Article/details/gt2qyrguqjc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gt2qlquukoq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guannengcc.top/Article/details/gt2wlzdtxqw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2jzzxksmr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2xpahaxao.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2holgkcza.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gt2ojoyuppp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2nvjvhlcc.html

C#:   s.Replace("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2vcipuauk.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gt2zkmniyzm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhoulong.xyz/Article/details/gt2bhkvhgbt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2tjmhdjsk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cdnleiting.top/Article/details/gt2eqiqsqbh.html

TS:   s.split(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2vhgjfqdt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.svipenyu.cn/Article/details/gt2zqlnfcoh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dashuyun.cn/Article/details/gt2bvhbonvc.html

Ruby: s.split(",");  s.split
来源：http://dali.ppjwa.cn/Article/details/gt2wwzgnwdb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2heljekdc.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gt2pmamzinm.html

Py:   ",".join(items)
来源：http://dali.jyoumei.cn/Article/details/gt2rtypyazd.html

PHP:  implode(",", $items);
来源：http://dali.snrcjt.cn/Article/details/gt2ufvthzds.html

JS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gt2qajailms.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gt2xkevdvav.html

Java: String.join(",", items)
来源：http://dali.ivvv.top/Article/details/gt2yzaylwcq.html

Go:   strings.Join(items, ",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2enrvjrtf.html

Ruby: items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2bqrxfpkv.html

C#:   string.Join(",", items)
来源：http://dali.nwbrower.top/Article/details/gt2ljkahudn.html

[E09] 去除所有空白字符
来源：http://dali.yuanzhike.top/Article/details/gt2vswcnyrd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.svipenyu.cn/Article/details/gt2hoyxxlis.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hammf.cn/Article/details/gt2yjmbvxca.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gt2mjyquray.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gt2buqgbtnt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aizwys.cn/Article/details/gt2zxxmdrnu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gt2ctxpvrkz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2teujgrba.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.meibo888.top/Article/details/gt2plnnxupm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sweek.top/Article/details/gt2tbzhaxhe.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tian-w.cn/Article/details/gt2pgenktsj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhongyouzk.top/Article/details/gt2wuhgafxn.html

JS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gt2psjvgnzb.html

TS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gt2xgxvtauv.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gt2hsvcgirx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbucbawk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jzswinwg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.iojbl.cn/Article/details/gt2mcqzdqej.html

[E11] 反转字符串
来源：http://dali.fengsongda.top/Article/details/gt2mxdmykej.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gt2jhsdafwc.html

PHP:  strrev($s);
来源：http://dali.smart0.xyz/Article/details/gt2kwiofekq.html

JS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gt2khsihuzg.html

TS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2obukjbtc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yvedp.cn/Article/details/gt2lzjwalmp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kibcweot.html

Ruby: s.reverse
来源：http://dali.jyoumei.cn/Article/details/gt2swrlwqrn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gt2dykjvdgq.html

[E12] 统计某字符出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dfmibzne.html

Py:   s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gt2hvyhecpg.html

PHP:  substr_count($s, "a");
来源：http://dali.wangshuangyany.cn/Article/details/gt2qmeabeip.html

JS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gt2bhxuhoua.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gt2kkawhvkf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aryffcei.html

Go:   strings.Count(s, "a")
来源：http://dali.dashuyun.cn/Article/details/gt2kztdkokj.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gt2vfcnunmd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shzxlz.cn/Article/details/gt2ijgxlkvv.html

[E13] 逐字符遍历
来源：http://dali.jinqigufen.top/Article/details/gt2etabrigp.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxuanxn.top/Article/details/gt2hrkhjnoa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jianghu66.top/Article/details/gt2horxyews.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gt2jswwdppj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2exyvcrlj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bgfulpks.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gt2butnswdy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2evnlalyd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yueranfly.top/Article/details/gt2fbiktawz.html

[E14] URL 编码与 Base64
来源：http://dali.jyoumei.cn/Article/details/gt2rzoyqbmb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.bjfxy.top/Article/details/gt2bkucbtph.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yongpay.top/Article/details/gt2bgssxylf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hysaishi.cn/Article/details/gt2nazhllsv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.smart0.xyz/Article/details/gt2ukipigys.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qheqeasp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.svipenyu.cn/Article/details/gt2itegnhhx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpesbita.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhengqikj.top/Article/details/gt2fldzdwle.html

[E15] HTML 转义 / 反转义
来源：http://dali.guowangkeji.top/Article/details/gt2pgouxora.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj202588.top/Article/details/gt2jrqwaqax.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cqqwz.cn/Article/details/gt2paxpgugc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2ycwfqixu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigfzy.top/Article/details/gt2morzudxu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yanxiufei.cn/Article/details/gt2ljyzfeor.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hrufrjsr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ydzc1.top/Article/details/gt2ueileqbu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuanzx.com/Article/details/gt2azlcvuux.html

[E16] 数字千分位
来源：http://dali.dianchejie.cn/Article/details/gt2pwkfurtq.html

Py:   f"{1234567:,}"
来源：http://dali.smart0.xyz/Article/details/gt2ajlbxlqi.html

PHP:  number_format(1234567);
来源：http://dali.chenzaomai.com/Article/details/gt2hifxslvk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gt2yzcpicna.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gt2wbojtmpn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhengqikj.top/Article/details/gt2pcbbwyut.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.andypj.xyz/Article/details/gt2eadtpbjo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hysaishi.cn/Article/details/gt2dxauthmd.html

C#:   1234567.ToString("N0")
来源：http://dali.xziqi.cn/Article/details/gt2txsyjieh.html

[E17] 首字母大写
来源：http://dali.xziqi.cn/Article/details/gt2vyaflvqw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258.top/Article/details/gt2pxmcnogs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnqzz.top/Article/details/gt2xhjvrsiv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jiagoushi.top/Article/details/gt2jatfdlcd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gt2lgkpgtcs.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcagtbxt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gt2arfbcvji.html

Ruby: s.capitalize
来源：http://dali.iojbl.cn/Article/details/gt2owhcombs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cheryme.top/Article/details/gt2nmssnjww.html

[E18] 模板占位符替换
来源：http://dali.yuanzhike.top/Article/details/gt2dhshblng.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gt2llgayskc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xziqi.cn/Article/details/gt2gdmtsiuh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2xzdiqkri.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gt2zutecjaf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2qisfkocj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2ttphqaab.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cdnleiting.top/Article/details/gt2atbjodyh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aizwys.cn/Article/details/gt2qlvjgxtw.html

[E19] 多行文本按行拆分
来源：http://dali.redwolf501.top/Article/details/gt2vxqgyupv.html

Py:   s.splitlines()
来源：http://dali.sysykeji.top/Article/details/gt2ophmhxxr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2pngpgfsu.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gt2rdedappg.html

TS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gt2lxgqqzrv.html

Java: s.lines().toList()
来源：http://dali.gzhubu.top/Article/details/gt2rkjuvgea.html

Go:   strings.Split(s, "\n")
来源：http://dali.sufxvd.cn/Article/details/gt2ifjhbhtk.html

Ruby: s.lines
来源：http://dali.zhoulong.xyz/Article/details/gt2vwhucotg.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2azrthdtx.html

[E20] 判断字符串是否为空
来源：http://dali.dianchejie.cn/Article/details/gt2tdqeymbf.html

Py:   if not s:
来源：http://dali.jqgfzy.top/Article/details/gt2wkrgehnl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenlongwang.top/Article/details/gt2fbqtosuc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2afviwdmi.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivvpfmms.html

Java: if (s.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gt2pxvqvwkq.html

Go:   if s == "" {}
来源：http://dali.yueranfly.top/Article/details/gt2pwrgweeh.html

Ruby: if s.empty?
来源：http://dali.yvedp.cn/Article/details/gt2sexcjrcf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.svipenyu.cn/Article/details/gt2yxpdnhhy.html

[E21] 超长截断加省略号
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qlzsvqno.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gt2gqurfqyb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2pkaamlhd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2cfpijrtm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2niyczswd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2ybukqlpw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dashuyun.cn/Article/details/gt2lkqfkqsy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2meqmpxrj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2dmbgoocg.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigufen.top/Article/details/gt2mhjywdvc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2kouiynjb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2aabhkdio.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gt2wminonbe.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gt2wgowtncd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gt2tnktaxld.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ircvbqus.html

Ruby: s.bytesize;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2kmnejszl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yueranfly.top/Article/details/gt2iodbabge.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dszbpcvb.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gt2ymshzrar.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2dznxqgag.html

[F01] 读取整个文件
来源：http://dali.yvedp.cn/Article/details/gt2bxyptjvd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gaohongyu789.top/Article/details/gt2nrxsgkxn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2patnnxrc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gt2pgedmezz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2znsbgxov.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2xhiikabg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yanxiufei.cn/Article/details/gt2dyeaypds.html

Ruby: File.read("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2hdgcxrtu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2bwpagdbo.html

[F02] 逐行读取文件
来源：http://dali.jinqigufen.top/Article/details/gt2afhroxht.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ytrrsqoq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.iojbl.cn/Article/details/gt2fqzfzamz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gt2bhsvfngv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gt2aimzpdjv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gt2rvggowqk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cxyxgjlt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xziqi.cn/Article/details/gt2ujutplwq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tianlin.xyz/Article/details/gt2nybkmzvt.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gt2gsmhjyma.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cqqwz.cn/Article/details/gt2keqlycsu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gt2ditqtsks.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gt2zkqraxms.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gt2mredlfcz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.haohaochexian.top/Article/details/gt2zffffgyl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wuouqipr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqkpjjbj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gt2wfxmbhqn.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2roeilpmj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.havefunace.top/Article/details/gt2lycaxkvj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gt2jhzxlnfl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gt2qchqsynn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zknrtlrz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gt2wpgjzshr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gogol.net.cn/Article/details/gt2cyenrsaq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gt2tdbmravs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ehwqpu.com/Article/details/gt2puqcvxrk.html

[F05] 判断文件或目录是否存在
来源：http://dali.tian-w.cn/Article/details/gt2xvophnpa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dianchejie.cn/Article/details/gt2hphkwgau.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2cgjxbyex.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2ejtfutgy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2kgrfgjkm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2twhlkwar.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.9152youxi.cn/Article/details/gt2pibopovy.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2godscccu.html

C#:   File.Exists("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2ymimjbqt.html

[F06] 删除文件
来源：http://dali.hysaishi.cn/Article/details/gt2hytbxzbr.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djkbyqdk.html

PHP:  unlink("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2mgmwavpd.html


<!-- 参考信息 -->