代发 wailian999

Ruby: a, b = pair
来源：http://dali.0kj1m.cn/Article/details/gtftxllkoy.html

C#:   var (a, b) = pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtkpvzub.html

[C16] 函数 / 方法重载
来源：http://dali.ydzc1.top/Article/details/gtnnwdqusn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgufenzy.top/Article/details/gtmpgodevj.html

PHP:  // 无重载
来源：http://dali.meibo888.top/Article/details/gtypgsilfi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.guowangkeji.top/Article/details/gthzsmvumc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zdqjudy.top/Article/details/gtfjzupbnk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zdqjudy.top/Article/details/gtotciyosq.html

Go:   // 无重载：用不同函数名
来源：http://dali.gotoacloud.top/Article/details/gtnpkjmyuj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.c1oappe.top/Article/details/gtgsvgbemv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtsypfahyw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtsixbkzex.html

D. 数组 / 列表 / 集合
来源：http://dali.hywenlv.cn/Article/details/gtvthtmtcx.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtpfygavhz.html

[D01] 创建数组 / 列表
来源：http://dali.yj202588.top/Article/details/gthmllhxnc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.iojbl.cn/Article/details/gtuyuhnpqc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gtnnzfjmle.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ybcxt.top/Article/details/gtzcyhhsak.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ydzc1.top/Article/details/gtydishzmn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dianchejie.cn/Article/details/gtpmqalyvb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxyujyts.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daria6918.cn/Article/details/gtchxditto.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fzhhl.top/Article/details/gthpdqcajv.html

[D02] 追加元素到末尾
来源：http://dali.ybcxt.top/Article/details/gtxzpctqdp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gogol.net.cn/Article/details/gtqrlyucfk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yongpay.top/Article/details/gtzqlfgnno.html

JS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gtmjgfuckn.html

TS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gtzhznsgup.html

Java: list.add(4);
来源：http://dali.yvedp.cn/Article/details/gtgncecpsz.html

Go:   arr = append(arr, 4)
来源：http://dali.hnqzz.top/Article/details/gttwtpevmy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xziqi.cn/Article/details/gtpwgpspdb.html

C#:   list.Add(4);
来源：http://dali.haohaochexian.top/Article/details/gtyvfhzdyv.html

[D03] 在指定位置插入元素
来源：http://dali.aizwys.cn/Article/details/gtpmhgqmfx.html

Py:   arr.insert(0, 0)
来源：http://dali.snrcjt.cn/Article/details/gtzytkqxly.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfqtdjbb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yueranfly.top/Article/details/gtkyohdjla.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xylfe.cn/Article/details/gtmzxgkdlg.html

Java: list.add(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnilgbca.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cqqwz.cn/Article/details/gtahrywyji.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shzxlz.cn/Article/details/gtvwgcbwjb.html

C#:   list.Insert(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gthonfkxgt.html

[D04] 删除元素
来源：http://dali.redwolf501.top/Article/details/gtfqeflbds.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangdashe.top/Article/details/gtbedsdjhd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yongpay.top/Article/details/gtworkbrqp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gtbkdwhpnx.html

TS:   arr.splice(0, 1);
来源：http://dali.yuanzhike.top/Article/details/gtgwyiliam.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.mhx1999.top/Article/details/gtwefburwq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cheryme.top/Article/details/gtvxqccqdc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shzxlz.cn/Article/details/gtgsimcctg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenzaomai.com/Article/details/gtkgyliudh.html

[D05] 访问与修改元素
来源：http://dali.guannengcc.top/Article/details/gtzomkucca.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtydxumnvl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtabnvvlmc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxqipbgu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hysaishi.cn/Article/details/gtfpqbvlzp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yvedp.cn/Article/details/gtjswckygp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gtspbtvmtd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtsueubqtp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtbgufyqug.html

[D06] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtgbmedxxp.html

Py:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gtjvumvwko.html

PHP:  count($arr);
来源：http://dali.gzhubu.top/Article/details/gtaonrdexp.html

JS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtakmvaczv.html

TS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtyraltmdc.html

Java: list.size();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsbkpmxa.html

Go:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gtimwxucrw.html

Ruby: arr.length; arr.size
来源：http://dali.gaohongyu789.top/Article/details/gtcmadzihs.html

C#:   list.Count;
来源：http://dali.xuanzx.com/Article/details/gtpbggqdmd.html

[D07] 切片 / 取子数组
来源：http://dali.andypj.xyz/Article/details/gtkaeatkva.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnxiangtu.top/Article/details/gtbrmqzyab.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.birdmap.top/Article/details/gtejhsivgf.html

JS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gtwqlxwdab.html

TS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtybtfbvhn.html

Java: list.subList(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtgodufvqq.html

Go:   arr[1:4]
来源：http://dali.ppjwa.cn/Article/details/gttzdyzxcd.html

Ruby: arr[1, 3]
来源：http://dali.hfpthk.cn/Article/details/gtftgrovgw.html

C#:   list.GetRange(1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtxacrasxh.html

[D08] 合并两个数组
来源：http://dali.sufxvd.cn/Article/details/gtaspublug.html

Py:   a + b;  a.extend(b)
来源：http://dali.pycfn.com/Article/details/gtrssgthsv.html

PHP:  array_merge($a, $b);
来源：http://dali.bjfxy.top/Article/details/gttbhqhnpx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gaohongyu789.top/Article/details/gteqxwvjpy.html

TS:   [...a, ...b];
来源：http://dali.shzxlz.cn/Article/details/gtpyprcbgf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jianghu66.top/Article/details/gtamjkmvwg.html

Go:   append(a, b...)
来源：http://dali.pycfn.com/Article/details/gtpuzfqvpt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ivvv.top/Article/details/gthvjiokfm.html

C#:   a.Concat(b).ToList()
来源：http://dali.sxryk.cn/Article/details/gtjwlmbruk.html

[D09] 排序（升序）
来源：http://dali.bjfxy.top/Article/details/gthiilvnmh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gtliklxdsp.html

PHP:  sort($arr);
来源：http://dali.jianghu66.top/Article/details/gthsoahgox.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.haohaochexian.top/Article/details/gtvysygxpa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fzhhl.top/Article/details/gtpjnqjxen.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nwbrower.top/Article/details/gtuvojxnbd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gtyvfxvxwe.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gttwclruzt.html

C#:   list.Sort();
来源：http://dali.yj202588.top/Article/details/gtxtoivtmy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jianghu66.top/Article/details/gtploiefug.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xinyue.icu/Article/details/gtkfbkrrbv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhongyouzk.top/Article/details/gtowxnwhyr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gtnpmpsrwh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gtbizmxvew.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258.top/Article/details/gtnemngdja.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tian-w.cn/Article/details/gtwbiyisca.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shangyingyoupin.top/Article/details/gtoisecdgu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenlongwang.top/Article/details/gthqwjubqn.html

[D11] 反转数组
来源：http://dali.vqdsnc.cn/Article/details/gtevlbdxjo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cashguo.top/Article/details/gtqfxpccyo.html

PHP:  array_reverse($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtevviudpm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sxryk.cn/Article/details/gtidiloeqf.html

TS:   [...arr].reverse();
来源：http://dali.nwbrower.top/Article/details/gtdfwoetct.html

Java: Collections.reverse(list);
来源：http://dali.yj20258.top/Article/details/gtyuovtbju.html

Go:   slices.Reverse(arr)
来源：http://dali.guowangkeji.top/Article/details/gtfbtwuyfa.html

Ruby: arr.reverse
来源：http://dali.nanxinkj.top/Article/details/gtdhudoyec.html

C#:   list.Reverse();
来源：http://dali.ivvv.top/Article/details/gtfdzfembe.html

[D12] 查找元素下标
来源：http://dali.gaohongyu789.top/Article/details/gtnovwayyy.html

Py:   arr.index(x);  x in arr
来源：http://dali.jianghu66.top/Article/details/gtsjxajsor.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gzhubu.top/Article/details/gtmheceefl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gtpkrfjvhf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gttbjwrizz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangshuangyany.cn/Article/details/gtzirhlouk.html

Go:   slices.Index(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxsvmtst.html

Ruby: arr.index(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtalhtejqp.html

C#:   list.IndexOf(x);
来源：http://dali.mhx1999.top/Article/details/gtdvgmnree.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gaohongyu789.top/Article/details/gtpzhxvglg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ehwqpu.com/Article/details/gtttzvsyzt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fzhhl.top/Article/details/gtxvxvrtbz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtgkbiqbip.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenzaomai.com/Article/details/gtnnemdxtr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xziqi.cn/Article/details/gtjvckaplt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangshuangyany.cn/Article/details/gtfvlrgkar.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cdnleiting.top/Article/details/gtoovbtyiw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.meibo888.top/Article/details/gtvwlkabho.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jlsjyb.cn/Article/details/gtzydioawj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ybcxt.top/Article/details/gtifuhmjhj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gtcylbukxq.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtorsrdgby.html

TS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtovltfphw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fzhhl.top/Article/details/gtnlbokhaf.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gtxubufewi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangdashe.top/Article/details/gtdnoggttx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sysykeji.top/Article/details/gtdmgyphzm.html

[D15] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtenfjtsul.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hammf.cn/Article/details/gtileisjrt.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpdjlpaj.html

JS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtyaauhqlz.html

TS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtiyautzzg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigfzy.top/Article/details/gtmilxxjby.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.svipenyu.cn/Article/details/gtngdascjz.html

Ruby: arr.uniq
来源：http://dali.guannengcc.top/Article/details/gtxelwrgsz.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258.top/Article/details/gtdzpzerrt.html

[D16] 求和与平均值
来源：http://dali.pycfn.com/Article/details/gtommnzowp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtoxcwclgg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenlongwang.top/Article/details/gtgnmuykqv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gtannqjbwj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gtkdwmsruq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gtckjxyfna.html

Go:   // 手写循环累加
来源：http://dali.ydzc1.top/Article/details/gtnpsvzmyu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jlsjyb.cn/Article/details/gtgzwsddcd.html

C#:   list.Sum();  list.Average()
来源：http://dali.gotoacloud.top/Article/details/gthiwqmyek.html

[D17] 最大值与最小值
来源：http://dali.snrcjt.cn/Article/details/gtgsfxanbx.html

Py:   max(arr);  min(arr)
来源：http://dali.tanke756.top/Article/details/gtzlfyydxs.html

PHP:  max($arr);  min($arr);
来源：http://dali.meibo888.top/Article/details/gtksmzpmgf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yueranfly.top/Article/details/gtbbdkqyro.html

TS:   Math.max(...arr);
来源：http://dali.jqgfzy.top/Article/details/gtmfwupaer.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tian-w.cn/Article/details/gtrdldiitv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtyyoxrcpd.html

Ruby: arr.max;  arr.min
来源：http://dali.dianchejie.cn/Article/details/gtcwwppgis.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgfzy.top/Article/details/gtcmqeswlm.html

[D18] 扁平化嵌套数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumpknomo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gaohongyu789.top/Article/details/gtzgaupvpr.html

PHP:  array_merge(...$nested);
来源：http://dali.sufxvd.cn/Article/details/gtrcwrvhkc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhiwuduotai.top/Article/details/gtrpdseyff.html

TS:   nested.flat();
来源：http://dali.pengpengdd.cyou/Article/details/gtbhiwrovu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtwlhzttsi.html

Go:   // 手写双层循环
来源：http://dali.0kj1m.cn/Article/details/gtigzqciqh.html

Ruby: nested.flatten
来源：http://dali.shangyingyoupin.top/Article/details/gthrwzofyi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtltgtnfle.html

[D19] 按字段分组
来源：http://dali.hnxiangtu.top/Article/details/gtfiafplkf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258888.top/Article/details/gtbehebqep.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guowangkeji.top/Article/details/gtvpantbzd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhixingplan.top/Article/details/gtbxsxdxko.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gtasamnyzg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aizwys.cn/Article/details/gtlwkcjrxd.html

Go:   // 手写 map[string][]T
来源：http://dali.zdqjudy.top/Article/details/gtnnatsglf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtodtzxzoo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sysykeji.top/Article/details/gttcwhzaii.html

[D20] 统计每个元素出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtravoeftr.html

Py:   Counter(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtlextdqnn.html

PHP:  array_count_values($arr);
来源：http://dali.fengsongda.top/Article/details/gtjjpnfwqm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gtzqawzpex.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gtcmxrlzug.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigufen.top/Article/details/gtgfowqaxh.html

Go:   // 手写 map[T]int
来源：http://dali.havefunace.top/Article/details/gtodqtjcwd.html

Ruby: arr.tally
来源：http://dali.andypj.xyz/Article/details/gtlkwpxcsr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gtflgvukef.html

[D21] 判断是否包含某元素
来源：http://dali.jqgufenzy.top/Article/details/gtitpecwzn.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gtwyywypdj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtraymwdqh.html

JS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtwwunjfhb.html

TS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtbznznnfg.html

Java: list.contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtxnrkggee.html

Go:   slices.Contains(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtzaeqapjj.html

Ruby: arr.include?(x)
来源：http://dali.xinyue.icu/Article/details/gtzhrkodph.html

C#:   list.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gtmbsogghu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.haohaochexian.top/Article/details/gtbpoyoana.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtvjbsbtls.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guowangkeji.top/Article/details/gtwrraaods.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenlongwang.top/Article/details/gtynezzdew.html

TS:   [...arr];
来源：http://dali.svipenyu.cn/Article/details/gtlttybqrz.html

Java: new ArrayList<>(list);
来源：http://dali.gaohongyu789.top/Article/details/gtmysstvuw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhixingplan.top/Article/details/gtcrqtwitj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.9152youxi.cn/Article/details/gtaspqhgtv.html

C#:   new List<int>(list);
来源：http://dali.svipenyu.cn/Article/details/gtrvcppzyq.html

[D23] reduce 累积计算
来源：http://dali.quarkkingdee.top/Article/details/gtfzolvfea.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj202588.top/Article/details/gtploijltv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tian-w.cn/Article/details/gtfdpjawcq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gtobeglljd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkiofascs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.bjfxy.top/Article/details/gtvcclyydd.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcmzrlha.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.kuanghao11.cn/Article/details/gtaoylezun.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jianghu66.top/Article/details/gtjizbpfxj.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigfzy.top/Article/details/gtolxmkxjo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.quarkkingdee.top/Article/details/gtyxhyiabu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jyoumei.cn/Article/details/gtfbnqrgik.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.redwolf501.top/Article/details/gtpflpgjsm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yongpay.top/Article/details/gtchhuojyp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ppjwa.cn/Article/details/gtpfekaefs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ivvv.top/Article/details/gteoqvndce.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuanzx.com/Article/details/gtjkhqhiwb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenjidiqi.icu/Article/details/gtnvxidgwu.html

[D25] Set 集合去重与交并差
来源：http://dali.fengsongda.top/Article/details/gtsylaehoz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yanxiufei.cn/Article/details/gtwxusijaz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuanzx.com/Article/details/gtrnaxffkp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangdashe.top/Article/details/gtliiqoooa.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gtoesddenr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlbztqsy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jlsjyb.cn/Article/details/gtbmeshjtk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yanxiufei.cn/Article/details/gtbjxcilhn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gtopjukivu.html

[D26] 数组转字符串
来源：http://dali.hywenlv.cn/Article/details/gtpsyrsafx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jyoumei.cn/Article/details/gttwdrdxea.html

PHP:  implode(", ", $arr);
来源：http://dali.jyoumei.cn/Article/details/gtsznamdxi.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtmzljlozr.html

TS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtvpefrbuv.html

Java: String.join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtncxephlm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gtechnwbxe.html

Ruby: arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gthjbfqrjo.html

C#:   string.Join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gtfdrmqokj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtonxdgxka.html

E. 字符串处理
来源：http://dali.mhx1999.top/Article/details/gtsrydhwjw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtfipztuxx.html

[E01] 拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtvaimisfy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.mhx1999.top/Article/details/gtvgnucwir.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqinmmcs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtbqhzvlaw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtureqklnt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnqzz.top/Article/details/gtjlwwbrap.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ybcxt.top/Article/details/gtvikiirna.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aibaodan.cn/Article/details/gtillkpinb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtwowncjzr.html

[E02] 重复字符串
来源：http://dali.mhx1999.top/Article/details/gtzcddicua.html

Py:   "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluwssdii.html

PHP:  str_repeat("ab", 3);
来源：http://dali.quarkkingdee.top/Article/details/gtjlyemfzw.html

JS:   "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtshrtgltg.html

TS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtcpteyhft.html

Java: "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gtrcgvxcst.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuanzx.com/Article/details/gtpeignbxa.html

Ruby: "ab" * 3
来源：http://dali.316326.xyz/Article/details/gtodvvnwad.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gaohongyu789.top/Article/details/gtxyhlquff.html

[E03] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gtxwzetrsq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yueranfly.top/Article/details/gtiqswtpan.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtryteqfrg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtywhknnoi.html

TS:   s.slice(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gtrocyxofc.html

Java: s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtznvggnzo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigufen.top/Article/details/gtlcxdngcx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tanke756.top/Article/details/gtllqvijxn.html

C#:   s.Substring(1, 3)
来源：http://dali.yuxming.cn/Article/details/gtqduyqgxr.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbhzhmtw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gtovrdiyql.html

PHP:  strpos($s, "x");
来源：http://dali.zhiwuduotai.top/Article/details/gtsaycdtgm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cdnleiting.top/Article/details/gtczyovkdg.html

TS:   s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtvbcaudsu.html

Java: s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtiktfotbx.html

Go:   strings.Index(s, "x")
来源：http://dali.chenjidiqi.icu/Article/details/gtmrgmjdbe.html

Ruby: s.index("x")
来源：http://dali.cashguo.top/Article/details/gtfzbqjyuh.html

C#:   s.IndexOf("x")
来源：http://dali.andypj.xyz/Article/details/gttyyatkyo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpopmxne.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cucudq.cn/Article/details/gtdupcalux.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.birdmap.top/Article/details/gtgenslmlb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtjbafddrg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hfpthk.cn/Article/details/gtuignivks.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtlgkupbai.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.aizwys.cn/Article/details/gtqrtutred.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxxbdwch.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtlegqzxmb.html

[E06] 替换子串
来源：http://dali.zhixingplan.top/Article/details/gtepdzhaje.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangdashe.top/Article/details/gtmpkooyav.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.mhx1999.top/Article/details/gtzkmzezlz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtfdfugdlp.html


<!-- 参考信息 -->