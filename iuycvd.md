代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxinkj.top/Article/details/gt2vkfpdgst.html

[D20] 统计每个元素出现次数
来源：http://dali.dianchejie.cn/Article/details/gt2qtptgsax.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2sroycqhw.html

PHP:  array_count_values($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2qjvdgynf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gt2ewritibc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gt2rtfdxuoa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sweek.top/Article/details/gt2cxpewbcd.html

Go:   // 手写 map[T]int
来源：http://dali.shangyingyoupin.top/Article/details/gt2zehjsxki.html

Ruby: arr.tally
来源：http://dali.cqqwz.cn/Article/details/gt2hvlqiaqi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ehwqpu.com/Article/details/gt2jkoqiesa.html

[D21] 判断是否包含某元素
来源：http://dali.jianghu66.top/Article/details/gt2favleolo.html

Py:   x in arr
来源：http://dali.smart0.xyz/Article/details/gt2hluzthhr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ydzc1.top/Article/details/gt2uiyklqws.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gt2rjkptjix.html

TS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gt2pnlshsdx.html

Java: list.contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vqppsnxb.html

Go:   slices.Contains(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2kntciqso.html

Ruby: arr.include?(x)
来源：http://dali.dianchejie.cn/Article/details/gt2ykzaffxa.html

C#:   list.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gt2mxbyutqr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yangfankeji.com/Article/details/gt2uyisnlbg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sysykeji.top/Article/details/gt2ttywzetd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hysaishi.cn/Article/details/gt2bleybzcn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2yiyckwtx.html

TS:   [...arr];
来源：http://dali.ybcxt.top/Article/details/gt2cvbiadii.html

Java: new ArrayList<>(list);
来源：http://dali.jyoumei.cn/Article/details/gt2nmydjthw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnqzz.top/Article/details/gt2dhqiavaz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2xyugzaqn.html

C#:   new List<int>(list);
来源：http://dali.chenlongwang.top/Article/details/gt2pquhpqao.html

[D23] reduce 累积计算
来源：http://dali.guannengcc.top/Article/details/gt2ziyhsevl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2mtetrpno.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dtxudnul.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gt2vidowywo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gt2cobinxms.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.vqdsnc.cn/Article/details/gt2tflmexrf.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gt2jxvrjrem.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shangyingyoupin.top/Article/details/gt2brzdxsmi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.birdmap.top/Article/details/gt2eydorejl.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2ecqnihom.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhiwuduotai.top/Article/details/gt2aknoyxxf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hywenlv.cn/Article/details/gt2lsoilico.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuanzhike.top/Article/details/gt2tgkarsmi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2gbnfhpee.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.andypj.xyz/Article/details/gt2zqpapows.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxuanxn.top/Article/details/gt2hmrnakbo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkikosrp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.kuanghao11.cn/Article/details/gt2bmikbmtw.html

[D25] Set 集合去重与交并差
来源：http://dali.sweek.top/Article/details/gt2alykhgpi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.quarkkingdee.top/Article/details/gt2sgaduzrs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ybcxt.top/Article/details/gt2mvdwypom.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.9152youxi.cn/Article/details/gt2kkafslah.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tian-w.cn/Article/details/gt2lbkrhmsa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2tskdvuoa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gt2vtsesagh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzlseejm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gt2skllnoym.html

[D26] 数组转字符串
来源：http://dali.chenlongwang.top/Article/details/gt2nawtafhn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2yodicqfa.html

PHP:  implode(", ", $arr);
来源：http://dali.daria6918.cn/Article/details/gt2odvxnodc.html

JS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gt2onzflicz.html

TS:   arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gt2urlwmhrb.html

Java: String.join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gt2evclyzhp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258888.top/Article/details/gt2ckydkroc.html

Ruby: arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gt2qaivzeuf.html

C#:   string.Join(", ", list)
来源：http://dali.cashguo.top/Article/details/gt2lsahnmbf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2xzxtydgi.html

E. 字符串处理
来源：http://dali.gogol.net.cn/Article/details/gt2lirfjfzp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2buquukag.html

[E01] 拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gt2azkzspit.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhiwuduotai.top/Article/details/gt2ajvxcimy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tianlin.xyz/Article/details/gt2naowdlmz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gt2vpgwjzuh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gt2zfetmoyo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fengsongda.top/Article/details/gt2iirghmdm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.haohaochexian.top/Article/details/gt2wlxirzeh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daria6918.cn/Article/details/gt2iudqkapk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2astjmoxq.html

[E02] 重复字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2opgphivi.html

Py:   "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gt2nkydzlcg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xylfe.cn/Article/details/gt2zsqwuvrc.html

JS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gt2cbwvomlv.html

TS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2btxjctho.html

Java: "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gt2hdaqvvhd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yongpay.top/Article/details/gt2rexgrpmq.html

Ruby: "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gt2ixcplysv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cucudq.cn/Article/details/gt2lfuqxqcp.html

[E03] 截取子串
来源：http://dali.yuxming.cn/Article/details/gt2acmkprbt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgfzy.top/Article/details/gt2anliggsw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2cenrywcm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.smart0.xyz/Article/details/gt2exsutvra.html

TS:   s.slice(1, 4)
来源：http://dali.havefunace.top/Article/details/gt2nxzorzen.html

Java: s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gt2ogpuirdx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daria6918.cn/Article/details/gt2kqhyjhrl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.c1oappe.top/Article/details/gt2vfbqvkqi.html

C#:   s.Substring(1, 3)
来源：http://dali.yuanzhike.top/Article/details/gt2rddbpbtq.html

[E04] 查找子串位置
来源：http://dali.hnxiangtu.top/Article/details/gt2itkckoxw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fzhhl.top/Article/details/gt2nyprgjlk.html

PHP:  strpos($s, "x");
来源：http://dali.cashguo.top/Article/details/gt2vkbkotlb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hywenlv.cn/Article/details/gt2lovgltzw.html

TS:   s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gt2ltldnwmj.html

Java: s.indexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gt2vwqsidrd.html

Go:   strings.Index(s, "x")
来源：http://dali.gogol.net.cn/Article/details/gt2swusepna.html

Ruby: s.index("x")
来源：http://dali.havefunace.top/Article/details/gt2ipajykhi.html

C#:   s.IndexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gt2ufndyxey.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llucgent.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnqzz.top/Article/details/gt2yxdripnp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hfpthk.cn/Article/details/gt2jmmxwmht.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gt2jmdkvypb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.mhx1999.top/Article/details/gt2cuoevmgt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gt2euluvwcn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fengsongda.top/Article/details/gt2fsjurllv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.snrcjt.cn/Article/details/gt2ehkamhqu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gt2rthvqcqk.html

[E06] 替换子串
来源：http://dali.zhongyouzk.top/Article/details/gt2xxeidsqs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2wgwhwqek.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2slkaiqqd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2qmummdst.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzgqunov.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zrewxrnz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jhzopnre.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2gnivskex.html

C#:   s.Replace("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2wnisignv.html

[E07] 按分隔符拆分
来源：http://dali.ehwqpu.com/Article/details/gt2zcmbkiyn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zfzfyrxg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258.top/Article/details/gt2laarqdgj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daria6918.cn/Article/details/gt2tlmjvfnd.html

TS:   s.split(",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2eqkgedqs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xinyue.icu/Article/details/gt2yymvtktd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2ujohggdy.html

Ruby: s.split(",");  s.split
来源：http://dali.gotoacloud.top/Article/details/gt2ivaeugai.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ivvv.top/Article/details/gt2sjqiryou.html

[E08] 数组按分隔符合并
来源：http://dali.aizwys.cn/Article/details/gt2wvotfrcy.html

Py:   ",".join(items)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cwnwuhqa.html

PHP:  implode(",", $items);
来源：http://dali.jinqigufen.top/Article/details/gt2rfccdkxj.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxymwsu.html

TS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gt2tmamwjgu.html

Java: String.join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gt2cygvsiyr.html

Go:   strings.Join(items, ",")
来源：http://dali.cucudq.cn/Article/details/gt2kmxxpiaw.html

Ruby: items.join(",")
来源：http://dali.yuxming.cn/Article/details/gt2uunxqcqp.html

C#:   string.Join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gt2bccjuwak.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gt2lxerkcbq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jyoumei.cn/Article/details/gt2joaaerfy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj202588.top/Article/details/gt2eixhpjip.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gt2hzvmjzol.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gt2bctgqxwr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xziqi.cn/Article/details/gt2zneuapjf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhixingplan.top/Article/details/gt2wgmgrxne.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yvedp.cn/Article/details/gt2yrrjdowy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gt2ooymchqf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sxryk.cn/Article/details/gt2zzplweeg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangdashe.top/Article/details/gt2ugalknhh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ooiqslwo.html

JS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gt2turhdxwd.html

TS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gt2rdopwzjw.html

Java: String.format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gt2rlxgkiyg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gt2oxcvuxor.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gt2kudkcxyc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jianghu66.top/Article/details/gt2uohvodor.html

[E11] 反转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xifbqigl.html

Py:   s[::-1]
来源：http://dali.redwolf501.top/Article/details/gt2qxusibmo.html

PHP:  strrev($s);
来源：http://dali.ybcxt.top/Article/details/gt2zckbjyhb.html

JS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2etebsmov.html

TS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2ycnhzjae.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxinkj.top/Article/details/gt2rmcacsbx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xylfe.cn/Article/details/gt2rbpaiygv.html

Ruby: s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2rafmhbgr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gt2jaqcxrsx.html

[E12] 统计某字符出现次数
来源：http://dali.zycfv.cn/Article/details/gt2bwowptzw.html

Py:   s.count("a")
来源：http://dali.mhx1999.top/Article/details/gt2bavjeaqq.html

PHP:  substr_count($s, "a");
来源：http://dali.wangdashe.top/Article/details/gt2wdwmhuss.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gt2kjfxiqhg.html

TS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gt2cbnsfxbm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aizwys.cn/Article/details/gt2bzppzzrj.html

Go:   strings.Count(s, "a")
来源：http://dali.guowangkeji.top/Article/details/gt2qggzyvhg.html

Ruby: s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2vbzteahs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gt2xwjycchc.html

[E13] 逐字符遍历
来源：http://dali.wangdashe.top/Article/details/gt2fbtnlhkr.html

Py:   for ch in s: print(ch)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2igytause.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tswdzgvf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gt2cbehdgnb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2zbuhvmwo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2czngriej.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2gnucptdk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gt2ealkyqjk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ppjwa.cn/Article/details/gt2kzfwowdj.html

[E14] URL 编码与 Base64
来源：http://dali.andypj.xyz/Article/details/gt2grscqwet.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gt2hsdeslkl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yongpay.top/Article/details/gt2fpdmqolz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.mhx1999.top/Article/details/gt2pndbumcl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jiagoushi.top/Article/details/gt2svvjtika.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tanke756.top/Article/details/gt2hnbpdlgp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnqzz.top/Article/details/gt2dufqnich.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dianchejie.cn/Article/details/gt2aaafwagx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sweek.top/Article/details/gt2mnaaclmv.html

[E15] HTML 转义 / 反转义
来源：http://dali.tanke756.top/Article/details/gt2zibigohm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hywenlv.cn/Article/details/gt2lgorowcv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj202588.top/Article/details/gt2npcryfyl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tanke756.top/Article/details/gt2wszqrlkq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ubbkbivx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.andypj.xyz/Article/details/gt2kmkdpsfv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cdnleiting.top/Article/details/gt2wglhsjzb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenlongwang.top/Article/details/gt2lveefsek.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gotoacloud.top/Article/details/gt2ggdbtsgk.html

[E16] 数字千分位
来源：http://dali.xuanzx.com/Article/details/gt2mxsqoust.html

Py:   f"{1234567:,}"
来源：http://dali.birdmap.top/Article/details/gt2sucgkgok.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gt2reagyito.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wmfmdcve.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gt2iaykwoqj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nwbrower.top/Article/details/gt2elltqcjc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yvedp.cn/Article/details/gt2vezjsttn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gt2wrmlfoat.html

C#:   1234567.ToString("N0")
来源：http://dali.snrcjt.cn/Article/details/gt2bohsmaew.html

[E17] 首字母大写
来源：http://dali.316326.xyz/Article/details/gt2euxaucqg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aizwys.cn/Article/details/gt2phwdqtso.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2cufsyuwe.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2qthyntdb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gt2lgefyxoe.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhixingplan.top/Article/details/gt2lchdcook.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2lqmkggpg.html

Ruby: s.capitalize
来源：http://dali.aibaodan.cn/Article/details/gt2nutsdgxm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnqzz.top/Article/details/gt2mrdfbtml.html

[E18] 模板占位符替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2hvlgovxb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gt2snajwrfv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gt2xbvhsgol.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gt2gxnqcnpl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2cltbtjfk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2belwmkdr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gt2dzcskyaf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aizwys.cn/Article/details/gt2twqnmuvr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ybcxt.top/Article/details/gt2yswxqqpr.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gt2ntgfshux.html

Py:   s.splitlines()
来源：http://dali.cqqwz.cn/Article/details/gt2fmjmtkuu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fengsongda.top/Article/details/gt2favenibb.html

JS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gt2wzhicnxu.html

TS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ykqlvefe.html

Java: s.lines().toList()
来源：http://dali.mhx1999.top/Article/details/gt2yvpqcozd.html

Go:   strings.Split(s, "\n")
来源：http://dali.birdmap.top/Article/details/gt2rmxbmxsx.html

Ruby: s.lines
来源：http://dali.hfpthk.cn/Article/details/gt2owhphnvj.html

C#:   s.Split('\n')
来源：http://dali.cqqwz.cn/Article/details/gt2kepxkzjv.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gt2nxzhckqt.html

Py:   if not s:
来源：http://dali.guowangkeji.top/Article/details/gt2adkwcxsl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jtiltlwv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnqzz.top/Article/details/gt2cqekrskg.html

TS:   if (s === "") {}
来源：http://dali.vqdsnc.cn/Article/details/gt2xgpwghjh.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2bymtxavd.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tbcnlgad.html

Ruby: if s.empty?
来源：http://dali.sweek.top/Article/details/gt2vwzibvul.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2rrqgabzn.html

[E21] 超长截断加省略号
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvfirwoa.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuanzx.com/Article/details/gt2jtzgmhot.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2ayxscduz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2saudnqqz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gt2crawxjlx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2korwhkno.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.9152youxi.cn/Article/details/gt2hdaxruit.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2cfjuhuxn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2isnbahar.html

[E22] 字节长度与字符长度
来源：http://dali.havefunace.top/Article/details/gt2ecspfzhy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eyibyjua.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgavweig.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2ejuzexab.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2txyecixx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenzaomai.com/Article/details/gt2yrjqcapg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.vqdsnc.cn/Article/details/gt2cgddunhe.html

Ruby: s.bytesize;  s.length
来源：http://dali.shzxlz.cn/Article/details/gt2jctwpiqq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fengsongda.top/Article/details/gt2hayzjzwe.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2cmiwjtpd.html

F. 文件与目录
来源：http://dali.jinqigfzy.top/Article/details/gt2jnegquyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvsodcp.html

[F01] 读取整个文件
来源：http://dali.316326.xyz/Article/details/gt2wsygtgda.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gogol.net.cn/Article/details/gt2umoqbytc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2dxyoynjb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jyoumei.cn/Article/details/gt2seuxogcl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ybcxt.top/Article/details/gt2qghxfomx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2eyiyysak.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aizwys.cn/Article/details/gt2nqrbzzpr.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2aexqtiyw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2lqszgyor.html

[F02] 逐行读取文件
来源：http://dali.birdmap.top/Article/details/gt2viobudyp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.andypj.xyz/Article/details/gt2whrntxja.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daria6918.cn/Article/details/gt2fozqzaux.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ghwabivl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gt2rdhsdxeh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gt2yxqanrqm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shzxlz.cn/Article/details/gt2pputtnaw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkrlqxds.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cashguo.top/Article/details/gt2ostnsmwh.html

[F03] 写入文件（覆盖）
来源：http://dali.0kj1m.cn/Article/details/gt2hrppixrm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gt2kfvohhyh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dasxuhhd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gt2vrdwgwht.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gt2aquuyhhg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tian-w.cn/Article/details/gt2vzedpfew.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hfpthk.cn/Article/details/gt2nnrnkdyk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxinkj.top/Article/details/gt2npqcldmv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gt2gwzwsqji.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gt2iszddoru.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2adsofmay.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ydzc1.top/Article/details/gt2xzgrywrb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gt2hhwkzjlw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2ftcrumna.html


<!-- 参考信息 -->