代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.birdmap.top/Article/details/gt2idesemia.html

[D20] 统计每个元素出现次数
来源：http://dali.andypj.xyz/Article/details/gt2jkumlaeo.html

Py:   Counter(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2mudorxwn.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gt2ubrlixbc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gt2ywiuwkge.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gt2ibqxlpbe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangdashe.top/Article/details/gt2ewyvbvag.html

Go:   // 手写 map[T]int
来源：http://dali.wangdashe.top/Article/details/gt2nfhxlwrj.html

Ruby: arr.tally
来源：http://dali.ybcxt.top/Article/details/gt2hktrylmu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shangyingyoupin.top/Article/details/gt2kivyoyeu.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258888.top/Article/details/gt2thfjvksa.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gt2gefegejm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guannengcc.top/Article/details/gt2wsmqonkm.html

JS:   arr.includes(x)
来源：http://dali.cqqwz.cn/Article/details/gt2rfgzyceg.html

TS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2cpnlvbiy.html

Java: list.contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pnanyhuf.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2jogmkobb.html

Ruby: arr.include?(x)
来源：http://dali.xziqi.cn/Article/details/gt2rjcnafqq.html

C#:   list.Contains(x)
来源：http://dali.0kj1m.cn/Article/details/gt2nfbbmtkl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2keabnbeo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2erletces.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zdqjudy.top/Article/details/gt2wbdnajtz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2idltezjw.html

TS:   [...arr];
来源：http://dali.yuxming.cn/Article/details/gt2tbsvglwo.html

Java: new ArrayList<>(list);
来源：http://dali.cqqwz.cn/Article/details/gt2fozcmirn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gt2rjwqycgf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhongyouzk.top/Article/details/gt2purvtymr.html

C#:   new List<int>(list);
来源：http://dali.jinqigfzy.top/Article/details/gt2pitupyjv.html

[D23] reduce 累积计算
来源：http://dali.fengsongda.top/Article/details/gt2muoiqbqf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hammf.cn/Article/details/gt2xbnkihis.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2kcvsrlsn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gt2kqurhnpe.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gt2pjlhagyf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hammf.cn/Article/details/gt2gwdmlwtq.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gt2zwbigouf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.birdmap.top/Article/details/gt2hjngwpog.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yueranfly.top/Article/details/gt2lkbbtbbe.html

[D24] 字典 / Map 基本操作
来源：http://dali.jiagoushi.top/Article/details/gt2nsihsbtf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhengqikj.top/Article/details/gt2fehampge.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.quarkkingdee.top/Article/details/gt2ajwwavnb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.mhx1999.top/Article/details/gt2fyatgecd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nwbrower.top/Article/details/gt2xxwrubwj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dianchejie.cn/Article/details/gt2yijcwkyb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gt2hizfixeb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenzaomai.com/Article/details/gt2awxekagu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shuidangran.top/Article/details/gt2qpxmtsdh.html

[D25] Set 集合去重与交并差
来源：http://dali.9152youxi.cn/Article/details/gt2bhwlmkyu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yonumen.top/Article/details/gt2ypizvhjo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aizwys.cn/Article/details/gt2oljhhqoc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqqpnkp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.andypj.xyz/Article/details/gt2wxsbrwgf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jyoumei.cn/Article/details/gt2lelhzsas.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgfzy.top/Article/details/gt2uzognrpj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2kqlscbyn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ppjwa.cn/Article/details/gt2mwwmceqi.html

[D26] 数组转字符串
来源：http://dali.tanke756.top/Article/details/gt2dzlqqctj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.andypj.xyz/Article/details/gt2yrdmjavd.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wezbxtxs.html

JS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gt2jsuddcnw.html

TS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gt2rcvexouw.html

Java: String.join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gt2cgcppvco.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hywenlv.cn/Article/details/gt2btogezim.html

Ruby: arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gt2vbtuvidw.html

C#:   string.Join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gt2lhjxlppz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2xdckzrpm.html

E. 字符串处理
来源：http://dali.jlsjyb.cn/Article/details/gt2jpbsnxad.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2dwpkggmg.html

[E01] 拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gt2xrljzbbs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.bjfxy.top/Article/details/gt2qvmqrsfz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ydzc1.top/Article/details/gt2njpxjqzk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gt2jafuxlxr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gt2qfnvnsak.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sweek.top/Article/details/gt2klmpjrza.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jiagoushi.top/Article/details/gt2lruyissw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.316326.xyz/Article/details/gt2pmeieqbi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2xnwvxbst.html

[E02] 重复字符串
来源：http://dali.0kj1m.cn/Article/details/gt2clhhxrky.html

Py:   "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gt2tctsfixq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.9152youxi.cn/Article/details/gt2drvgmmvy.html

JS:   "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gt2xkmmvjyk.html

TS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gt2rgaeqdgr.html

Java: "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gt2pfmfqexy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2aeyamlhi.html

Ruby: "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gt2ydezxpga.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.redwolf501.top/Article/details/gt2dzcpiuhc.html

[E03] 截取子串
来源：http://dali.yj202588.top/Article/details/gt2vhkzrfar.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxahznsn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2wecukrhy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gt2efsdpbzp.html

TS:   s.slice(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gt2ohpeqnlk.html

Java: s.substring(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gt2gbmmixpj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gt2mjsdgxix.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pengpengdd.cyou/Article/details/gt2jivulult.html

C#:   s.Substring(1, 3)
来源：http://dali.guowangkeji.top/Article/details/gt2wfrefolk.html

[E04] 查找子串位置
来源：http://dali.tian-w.cn/Article/details/gt2dsqijrtt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gt2juzdieij.html

PHP:  strpos($s, "x");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mfyfmpii.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dduemqvw.html

TS:   s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gt2viuzkcrm.html

Java: s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gt2wpcwswvl.html

Go:   strings.Index(s, "x")
来源：http://dali.yvedp.cn/Article/details/gt2axsiidyr.html

Ruby: s.index("x")
来源：http://dali.ivvv.top/Article/details/gt2lopgfnvw.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gt2kecmywzu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xylfe.cn/Article/details/gt2zhgltnaz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jiagoushi.top/Article/details/gt2obwjkkly.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xylfe.cn/Article/details/gt2zbikhzsu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gt2pealnpsz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2peqhgkpw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gt2mqhzwmtm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigfzy.top/Article/details/gt2ydnxfxso.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jlsjyb.cn/Article/details/gt2vmhkqsyw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gt2dcyjeraq.html

[E06] 替换子串
来源：http://dali.aibaodan.cn/Article/details/gt2xbkwmfly.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mabydofn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jiagoushi.top/Article/details/gt2hpgfoqge.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2plpddzgi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2yghbtpnx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2nzkuwrte.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gt2lbpiblqd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2oesznyjx.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2agyrsbpr.html

[E07] 按分隔符拆分
来源：http://dali.birdmap.top/Article/details/gt2hqiicxuw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.snrcjt.cn/Article/details/gt2uvumdzvl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2picvepnd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.birdmap.top/Article/details/gt2sjynqmuj.html

TS:   s.split(",")
来源：http://dali.9152youxi.cn/Article/details/gt2kgxmichm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mgagsmrc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jyoumei.cn/Article/details/gt2osfzzmut.html

Ruby: s.split(",");  s.split
来源：http://dali.iojbl.cn/Article/details/gt2bfzeizmd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.birdmap.top/Article/details/gt2nkdgjngq.html

[E08] 数组按分隔符合并
来源：http://dali.ehwqpu.com/Article/details/gt2ffjkogdm.html

Py:   ",".join(items)
来源：http://dali.yongpay.top/Article/details/gt2exjsjxdw.html

PHP:  implode(",", $items);
来源：http://dali.jqgufenzy.top/Article/details/gt2fqambgiz.html

JS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gjcoaksu.html

TS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2squktsaz.html

Java: String.join(",", items)
来源：http://dali.tanke756.top/Article/details/gt2suxezmte.html

Go:   strings.Join(items, ",")
来源：http://dali.chenlongwang.top/Article/details/gt2akqsouex.html

Ruby: items.join(",")
来源：http://dali.meibo888.top/Article/details/gt2iwwimyeh.html

C#:   string.Join(",", items)
来源：http://dali.xinyue.icu/Article/details/gt2qxwoegnf.html

[E09] 去除所有空白字符
来源：http://dali.daxiang520.top/Article/details/gt2rcgfkxfu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2foksdmjd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangdashe.top/Article/details/gt2rzuxebov.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gt2mebyeexc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gt2xleroyzs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rpmygswq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ppjwa.cn/Article/details/gt2sozvytcd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aibaodan.cn/Article/details/gt2nhmmplbr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gt2qxrvrnce.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yongpay.top/Article/details/gt2ryvbicly.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tian-w.cn/Article/details/gt2foiqosvt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yanxiufei.cn/Article/details/gt2rhawihfd.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfywkcf.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gt2shoumwtt.html

Java: String.format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gt2zcopgsfa.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gt2hyxogovn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gt2zqvdbldw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigfzy.top/Article/details/gt2hjbktscc.html

[E11] 反转字符串
来源：http://dali.zhixingplan.top/Article/details/gt2teisjjnh.html

Py:   s[::-1]
来源：http://dali.meibo888.top/Article/details/gt2rdqzkbwj.html

PHP:  strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gt2ertsmsni.html

JS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gt2podnsems.html

TS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gt2fyefppkw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2krfbrirv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fengsongda.top/Article/details/gt2wqgxqilp.html

Ruby: s.reverse
来源：http://dali.yj20258888.top/Article/details/gt2afzmvxfo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gt2yervzdno.html

[E12] 统计某字符出现次数
来源：http://dali.quarkkingdee.top/Article/details/gt2awyhybmd.html

Py:   s.count("a")
来源：http://dali.xylfe.cn/Article/details/gt2rkswjbto.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oikavmnf.html

JS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gt2dzafoghv.html

TS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gt2ldajrtfs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.feifeiyinyue.top/Article/details/gt2yqbguxzt.html

Go:   strings.Count(s, "a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kzvxvxvi.html

Ruby: s.count("a")
来源：http://dali.nwbrower.top/Article/details/gt2iezhjtri.html

C#:   s.Count(c => c == 'a')
来源：http://dali.feifeiyinyue.top/Article/details/gt2nvoagsry.html

[E13] 逐字符遍历
来源：http://dali.guowangkeji.top/Article/details/gt2abveydqs.html

Py:   for ch in s: print(ch)
来源：http://dali.sweek.top/Article/details/gt2iqrkzpri.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sxryk.cn/Article/details/gt2mhzqhkxq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gt2tkuzzggo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrqjpkni.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2komyrknx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guannengcc.top/Article/details/gt2zwmvfmyx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenzaomai.com/Article/details/gt2mqulmeju.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vujoeggc.html

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fsphxtmy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2obojuisy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gt2wuaatvmr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.redwolf501.top/Article/details/gt2gibiiqij.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.c1oappe.top/Article/details/gt2xutefjek.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.mhx1999.top/Article/details/gt2bdzgftjg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gotoacloud.top/Article/details/gt2qvzqtwhl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2sbabozbi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ehwqpu.com/Article/details/gt2oulaubxn.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gt2jjlyvvea.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgfzy.top/Article/details/gt2xjfibftk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xinyue.icu/Article/details/gt2ahghtinb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guannengcc.top/Article/details/gt2fnorvhxx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.9152youxi.cn/Article/details/gt2nbmuajgq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenjidiqi.icu/Article/details/gt2xshtnzlj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nbypsuvo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgfzy.top/Article/details/gt2jhyzbfhl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgfzy.top/Article/details/gt2ecohxrbr.html

[E16] 数字千分位
来源：http://dali.guowangkeji.top/Article/details/gt2ljrtkhpx.html

Py:   f"{1234567:,}"
来源：http://dali.meibo888.top/Article/details/gt2cgrkbmgv.html

PHP:  number_format(1234567);
来源：http://dali.hammf.cn/Article/details/gt2mcpyhqdi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gt2quauglra.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gt2tuiamwva.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jyoumei.cn/Article/details/gt2cuxvvdva.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gt2kilpuovv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2urpylfoo.html

C#:   1234567.ToString("N0")
来源：http://dali.iojbl.cn/Article/details/gt2rvntospp.html

[E17] 首字母大写
来源：http://dali.snrcjt.cn/Article/details/gt2rbbmazzp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gt2jtfvqkfd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daria6918.cn/Article/details/gt2jnfobeij.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gt2tshwuhfh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gt2yzefjhst.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.smart0.xyz/Article/details/gt2jkmquyvm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gt2gfuepdxq.html

Ruby: s.capitalize
来源：http://dali.meibo888.top/Article/details/gt2tgplooth.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daria6918.cn/Article/details/gt2ehkyepvh.html

[E18] 模板占位符替换
来源：http://dali.yonumen.top/Article/details/gt2qihgzuwk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eywejtnq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gt2bqzccwoz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gt2pfrqleli.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2mksofwcx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gt2kxsrlneq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258.top/Article/details/gt2penwoeat.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daria6918.cn/Article/details/gt2mmysgovn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.snrcjt.cn/Article/details/gt2dgbvcyuv.html

[E19] 多行文本按行拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzpmjxnm.html

Py:   s.splitlines()
来源：http://dali.havefunace.top/Article/details/gt2chpkqfkz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qcxcaacy.html

JS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gt2hdzbpnci.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nktphzce.html

Java: s.lines().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2tajsojhu.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gt2uzrlzngs.html

Ruby: s.lines
来源：http://dali.hysaishi.cn/Article/details/gt2eihxgncy.html

C#:   s.Split('\n')
来源：http://dali.zycfv.cn/Article/details/gt2mzkjlzpg.html

[E20] 判断字符串是否为空
来源：http://dali.xylfe.cn/Article/details/gt2qiijhluh.html

Py:   if not s:
来源：http://dali.andypj.xyz/Article/details/gt2forcnizw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hongshengwenyu.top/Article/details/gt2guwafqmn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangdashe.top/Article/details/gt2ybruswfm.html

TS:   if (s === "") {}
来源：http://dali.cheryme.top/Article/details/gt2afoeyhdd.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aywzfdra.html

Go:   if s == "" {}
来源：http://dali.cqqwz.cn/Article/details/gt2zinzzomq.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gt2asnlpycn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guannengcc.top/Article/details/gt2cdfzapkk.html

[E21] 超长截断加省略号
来源：http://dali.aibaodan.cn/Article/details/gt2yhpwgdns.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gkdpibtx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2qnvrtomd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2mgmkqway.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2rzctobwx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2enpsfaon.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangshuangyany.cn/Article/details/gt2ozlcxfhp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2xwanaynh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2gcctqquz.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gt2qghbyhzk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxinkj.top/Article/details/gt2kkhbbuyw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gt2stzqjsgb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gt2lcvaxfof.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gt2uvqbutmy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenzaomai.com/Article/details/gt2lzyobumz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.andypj.xyz/Article/details/gt2dxnvsbiq.html

Ruby: s.bytesize;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2ngapwjsu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gt2lgctzupx.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ibnylkrw.html

F. 文件与目录
来源：http://dali.ehwqpu.com/Article/details/gt2kwastbvo.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2uwvsyfms.html

[F01] 读取整个文件
来源：http://dali.yj20258888.top/Article/details/gt2njdjmeyo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hysaishi.cn/Article/details/gt2gbcuuhhc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2ekostetw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sxryk.cn/Article/details/gt2qspbsong.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gt2louwfduv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gt2xomvqike.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gt2ivfeainl.html

Ruby: File.read("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2dsopjywe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2orpvotku.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qmdwlopn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tanke756.top/Article/details/gt2xksndfpu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jiydblrg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gt2mzkiapvo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gt2yflaxijs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gt2uwkunnpt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gt2tygxsbdj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenlongwang.top/Article/details/gt2bagzopyd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.c1oappe.top/Article/details/gt2mgmukqph.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gt2yatsgtwl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odkrapnd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gt2mxvmgrfb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gt2hkgadchf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2laldertg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gt2tmcrzytn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jlquuyvp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yonumen.top/Article/details/gt2dcpsvzji.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gt2upcdfigg.html

[F04] 追加写入文件
来源：http://dali.jiagoushi.top/Article/details/gt2qvzmhgec.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2mmdqtyne.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzimzmix.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gt2kkafinyb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gt2zlhuavrk.html


<!-- 参考信息 -->