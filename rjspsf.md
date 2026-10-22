代发 wailian999

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258.top/Article/details/gt2azqtdzky.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwuwgnci.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuanzx.com/Article/details/gt2ukaajrjr.html

TS:   [...arr];
来源：http://dali.gogol.net.cn/Article/details/gt2rkbovqef.html

Java: new ArrayList<>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mtqinjii.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bifppngm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gaohongyu789.top/Article/details/gt2tcduient.html

C#:   new List<int>(list);
来源：http://dali.nanxinkj.top/Article/details/gt2pqvrccuj.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gt2prcslcdg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2jmcloyrc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258.top/Article/details/gt2ixfimylk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gt2uhxzgges.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gt2rbgubcnn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daria6918.cn/Article/details/gt2wltprfij.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gt2wpuigfph.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gaohongyu789.top/Article/details/gt2xartuevd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yvedp.cn/Article/details/gt2balyeqtb.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2epekaxal.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.haohaochexian.top/Article/details/gt2oflgvyes.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tianlin.xyz/Article/details/gt2fxxupwuk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.meibo888.top/Article/details/gt2ocotocsb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2nduexkgb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cucudq.cn/Article/details/gt2ypjkekgr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pycfn.com/Article/details/gt2llyrzaoj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xziqi.cn/Article/details/gt2cwknlbaz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zycfv.cn/Article/details/gt2tdmnrxts.html

[D25] Set 集合去重与交并差
来源：http://dali.mhx1999.top/Article/details/gt2dvsuhfoj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gotoacloud.top/Article/details/gt2iqlriwig.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cqqwz.cn/Article/details/gt2luoxfmkq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shuidangran.top/Article/details/gt2cqjpwrmq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xziqi.cn/Article/details/gt2bzmbgyfa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ivvv.top/Article/details/gt2jilvjhjt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sweek.top/Article/details/gt2tgwmmfvb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fengsongda.top/Article/details/gt2gnvmtreh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.redwolf501.top/Article/details/gt2yslhblcc.html

[D26] 数组转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmxdylgd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.birdmap.top/Article/details/gt2fowkgxoh.html

PHP:  implode(", ", $arr);
来源：http://dali.sweek.top/Article/details/gt2bdzdzymo.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gt2nceskqso.html

TS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gt2kuwnfmkk.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2invnttnt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gt2gsezbnok.html

Ruby: arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gt2bvwqtpnf.html

C#:   string.Join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gt2xepnsodf.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2hqhqcyho.html

E. 字符串处理
来源：http://dali.hysaishi.cn/Article/details/gt2utwyyzxw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2gcusblyx.html

[E01] 拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2uomwxzsv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuetiantiany.cn/Article/details/gt2zgkhrljl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgfzy.top/Article/details/gt2mbsqybpz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gt2goiiircu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gt2czvhbfmp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgufenzy.top/Article/details/gt2srcnkvmy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dianchejie.cn/Article/details/gt2wnzhutxh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ivvv.top/Article/details/gt2odxnichl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2mueipmgv.html

[E02] 重复字符串
来源：http://dali.haohaochexian.top/Article/details/gt2ctjwkpvn.html

Py:   "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gt2wobzpago.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ybcxt.top/Article/details/gt2ovziagvs.html

JS:   "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqaximrr.html

TS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2oyerblzx.html

Java: "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gt2fhtidrll.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cqqwz.cn/Article/details/gt2ltteuvqk.html

Ruby: "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gt2zawppdau.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jlsjyb.cn/Article/details/gt2ovxjyugq.html

[E03] 截取子串
来源：http://dali.316326.xyz/Article/details/gt2hoqbqakr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2iiikihws.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2cerldrea.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gt2eetxguvk.html

TS:   s.slice(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2ibyewcfe.html

Java: s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gt2vevjybme.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jiagoushi.top/Article/details/gt2djlgzvhp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gt2uuoydezr.html

C#:   s.Substring(1, 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2lhdatspk.html

[E04] 查找子串位置
来源：http://dali.jqgufenzy.top/Article/details/gt2fjwhiuyh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvolnwvc.html

PHP:  strpos($s, "x");
来源：http://dali.havefunace.top/Article/details/gt2uqtlerwm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shuidangran.top/Article/details/gt2wycptpaj.html

TS:   s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gt2obphwvke.html

Java: s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gt2baofhuxd.html

Go:   strings.Index(s, "x")
来源：http://dali.yanxiufei.cn/Article/details/gt2fqzxjyau.html

Ruby: s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gt2nmryncsq.html

C#:   s.IndexOf("x")
来源：http://dali.yongpay.top/Article/details/gt2qjztwlit.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hysaishi.cn/Article/details/gt2nravdaim.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daxiang520.top/Article/details/gt2vbgarykc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hfpthk.cn/Article/details/gt2riwqvdaj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gt2flhqsbwu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ivvv.top/Article/details/gt2wunmlpvc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2nggzwucu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cdnleiting.top/Article/details/gt2muwxoefr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hysaishi.cn/Article/details/gt2cznidkuw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnqzz.top/Article/details/gt2dfsnqeru.html

[E06] 替换子串
来源：http://dali.yj20258888.top/Article/details/gt2skrtpsru.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gt2cdecmemc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ppjwa.cn/Article/details/gt2passsnxf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gt2zxngsoqu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2qpmpxycn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2foxurvod.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzinnxai.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gt2pbonjsxy.html

C#:   s.Replace("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjotjykh.html

[E07] 按分隔符拆分
来源：http://dali.fengsongda.top/Article/details/gt2uofpdxxj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigfzy.top/Article/details/gt2najyngko.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2xkbtquwa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lvnfvoyt.html

TS:   s.split(",")
来源：http://dali.hysaishi.cn/Article/details/gt2vdjivrwh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwkhimny.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2durruloq.html

Ruby: s.split(",");  s.split
来源：http://dali.chenzaomai.com/Article/details/gt2eksqelwk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.birdmap.top/Article/details/gt2mxcinwsp.html

[E08] 数组按分隔符合并
来源：http://dali.nwbrower.top/Article/details/gt2pmbigsho.html

Py:   ",".join(items)
来源：http://dali.havefunace.top/Article/details/gt2qnanceup.html

PHP:  implode(",", $items);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhjpreyd.html

JS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gt2jfcwejqr.html

TS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gt2jqsevaog.html

Java: String.join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gt2bshntmgo.html

Go:   strings.Join(items, ",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lwqywcrv.html

Ruby: items.join(",")
来源：http://dali.birdmap.top/Article/details/gt2guilhctw.html

C#:   string.Join(",", items)
来源：http://dali.xylfe.cn/Article/details/gt2uimiskbt.html

[E09] 去除所有空白字符
来源：http://dali.jiagoushi.top/Article/details/gt2rhzwdhsj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxinkj.top/Article/details/gt2wwedcrvr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hcivmjbr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uguvmuqg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gt2jixghilu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gt2mrbrarql.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yongpay.top/Article/details/gt2kuynztjw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gt2zxvxpmvn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daria6918.cn/Article/details/gt2dvwrcivo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pycfn.com/Article/details/gt2yjhkqpkl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2vwxxwysb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yonumen.top/Article/details/gt2mjjronpm.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kqgszrap.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gt2qzpuperu.html

Java: String.format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gt2senlemnk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gt2pmrfcjdr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gt2gurdpzmz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenlongwang.top/Article/details/gt2aatfnuon.html

[E11] 反转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvhydoph.html

Py:   s[::-1]
来源：http://dali.bjfxy.top/Article/details/gt2iobosmay.html

PHP:  strrev($s);
来源：http://dali.iojbl.cn/Article/details/gt2ioudakdd.html

JS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2neokciog.html

TS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2tnqmgccr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tanke756.top/Article/details/gt2vdqfxhnx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zycfv.cn/Article/details/gt2lqkrcgde.html

Ruby: s.reverse
来源：http://dali.shzxlz.cn/Article/details/gt2gjovcmld.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gt2aockpfan.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gt2nbnwsyhj.html

Py:   s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gt2uuyspkds.html

PHP:  substr_count($s, "a");
来源：http://dali.hnxiangtu.top/Article/details/gt2enwouayj.html

JS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aykdbxvb.html

TS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gt2azokjzsp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.svipenyu.cn/Article/details/gt2kczhrvzn.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxinkj.top/Article/details/gt2sxbtiqfy.html

Ruby: s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gt2sapzievn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.birdmap.top/Article/details/gt2nzrdpkee.html

[E13] 逐字符遍历
来源：http://dali.hysaishi.cn/Article/details/gt2citppsal.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gt2lskxakip.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.9152youxi.cn/Article/details/gt2fovexhee.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gt2rbcncqjl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmpwqhxc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vnfxdips.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.iojbl.cn/Article/details/gt2cyrzjhrd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gt2lnftdgli.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2vroihviu.html

[E14] URL 编码与 Base64
来源：http://dali.zhixingplan.top/Article/details/gt2qzdiajuz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gt2nhfgzdff.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gt2pjhfznit.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wcvqcbmp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xinyue.icu/Article/details/gt2balgbivv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxinkj.top/Article/details/gt2xurhyywe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj202588.top/Article/details/gt2tfhqzgmp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2wneeevfk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cheryme.top/Article/details/gt2vrhohajf.html

[E15] HTML 转义 / 反转义
来源：http://dali.wangdashe.top/Article/details/gt2mlidottd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxinkj.top/Article/details/gt2arvessdd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cdnleiting.top/Article/details/gt2yskddmqa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxkugtsn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gt2seefeeex.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnqzz.top/Article/details/gt2icczvzip.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xylfe.cn/Article/details/gt2txwgyoqh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yonumen.top/Article/details/gt2dfagbpgq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sweek.top/Article/details/gt2wlbnucaz.html

[E16] 数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gt2eythdmrx.html

Py:   f"{1234567:,}"
来源：http://dali.meibo888.top/Article/details/gt2ejxidxcm.html

PHP:  number_format(1234567);
来源：http://dali.zhixingplan.top/Article/details/gt2kffvpaut.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xpqdwupg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gt2fcmkzlkk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.meibo888.top/Article/details/gt2qvkgcrhc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuxming.cn/Article/details/gt2gaftydqt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guowangkeji.top/Article/details/gt2asuaewpt.html

C#:   1234567.ToString("N0")
来源：http://dali.ydzc1.top/Article/details/gt2mrogqnum.html

[E17] 首字母大写
来源：http://dali.jyoumei.cn/Article/details/gt2ltvhaesp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gogol.net.cn/Article/details/gt2aoozkfkf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gt2dqupvtgs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gt2mxjtftmt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gt2wwxatxaj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ivvv.top/Article/details/gt2ofhohqlx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nwbrower.top/Article/details/gt2onvljxbs.html

Ruby: s.capitalize
来源：http://dali.aibaodan.cn/Article/details/gt2vkroegrq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yueranfly.top/Article/details/gt2oaxprsia.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gt2dkijeusg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnxiangtu.top/Article/details/gt2sldfxhrn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gt2pkdnwbpv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2hphumwxz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2bprvxeeo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kxqbgymq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gt2ymjdslga.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cashguo.top/Article/details/gt2pzftlvik.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.meibo888.top/Article/details/gt2spdfywhc.html

[E19] 多行文本按行拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nqeepsuy.html

Py:   s.splitlines()
来源：http://dali.zycfv.cn/Article/details/gt2lyaqiamz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kylivjng.html

JS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gt2wneejvnb.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gt2bfmryawb.html

Java: s.lines().toList()
来源：http://dali.yvedp.cn/Article/details/gt2ojtvfvhh.html

Go:   strings.Split(s, "\n")
来源：http://dali.svipenyu.cn/Article/details/gt2fwetwnja.html

Ruby: s.lines
来源：http://dali.hnxiangtu.top/Article/details/gt2sydmovfi.html

C#:   s.Split('\n')
来源：http://dali.cdnleiting.top/Article/details/gt2lguynavf.html

[E20] 判断字符串是否为空
来源：http://dali.birdmap.top/Article/details/gt2ocmtecvp.html

Py:   if not s:
来源：http://dali.quarkkingdee.top/Article/details/gt2mgxgqqzb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xylfe.cn/Article/details/gt2ttxtnyiv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gt2srxmupyu.html

TS:   if (s === "") {}
来源：http://dali.hnxiangtu.top/Article/details/gt2apsxpppg.html

Java: if (s.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2sotxkysl.html

Go:   if s == "" {}
来源：http://dali.aibaodan.cn/Article/details/gt2hqtdowry.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gt2daaqkxji.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2nseosuka.html

[E21] 超长截断加省略号
来源：http://dali.daxiang520.top/Article/details/gt2opnptisp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gogol.net.cn/Article/details/gt2tgphihpt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gt2mydkamcc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qjvhwqvl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gt2eejcizzs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2lwrzrdml.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gt2ldzvjzbq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2pdhjluvt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2ufzhmtaj.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tzbzkyqb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tian-w.cn/Article/details/gt2hosozgtc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2qzkaezdl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gt2sbvsnowj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmgljwtx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gotoacloud.top/Article/details/gt2qmqbvqpy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigufen.top/Article/details/gt2ckszvsrz.html

Ruby: s.bytesize;  s.length
来源：http://dali.tanke756.top/Article/details/gt2jbhynohe.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ydzc1.top/Article/details/gt2quiavfrv.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2abafslxw.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2apigpawt.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2tuecfyxv.html

[F01] 读取整个文件
来源：http://dali.smart0.xyz/Article/details/gt2qtqvyxum.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfrdqkz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2estprtfx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fengsongda.top/Article/details/gt2tabbqlou.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gt2ujpvetey.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2tgznxarm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yonumen.top/Article/details/gt2bpshhoco.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2dbbbbrzd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2dgdmembg.html

[F02] 逐行读取文件
来源：http://dali.jiagoushi.top/Article/details/gt2evafiern.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgufenzy.top/Article/details/gt2dddkpsbp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gt2uehyukmy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gt2etisoyri.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gt2wmlxpboe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gt2dfbxoida.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xylfe.cn/Article/details/gt2fahxkcaa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daxiang520.top/Article/details/gt2zrtiaokj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cwnmtemy.html

[F03] 写入文件（覆盖）
来源：http://dali.xuanzx.com/Article/details/gt2cfawwiwx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gt2hvygoabs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gt2bnkjahca.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gt2vxuaaxgc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gt2ylydsjqs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2tzsqqnru.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hywenlv.cn/Article/details/gt2hopqseno.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ybcxt.top/Article/details/gt2tvvdwolg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gt2lmmlwifs.html

[F04] 追加写入文件
来源：http://dali.zycfv.cn/Article/details/gt2nmstghrd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cucudq.cn/Article/details/gt2oxmcjqld.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yvkqzkya.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gt2vlnrbtca.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2brtkcsnk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fzhhl.top/Article/details/gt2bbafqygo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ugvofphx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sufxvd.cn/Article/details/gt2ahyzlybh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jiagoushi.top/Article/details/gt2xzblefkw.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangdashe.top/Article/details/gt2cckaatuo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dianchejie.cn/Article/details/gt2ozsisbxg.html

PHP:  file_exists("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2mmbvtkrf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2jthosfwx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ksmwoagk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gt2uhlpdjwt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangdashe.top/Article/details/gt2waxcnuol.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2cvsrlcfl.html

C#:   File.Exists("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2nrxlvprh.html

[F06] 删除文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2hfxzvnut.html

Py:   os.remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2botnpqiw.html

PHP:  unlink("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2dhyxehpm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2oyomsjyj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dlszynrj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2cumaywuw.html

Go:   os.Remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gyqawpdk.html


<!-- 参考信息 -->