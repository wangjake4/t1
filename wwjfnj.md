代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.zhixingplan.top/Article/details/gt2vcoaixrd.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2crzhlafd.html

[D01] 创建数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gt2ecuyslqc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dianchejie.cn/Article/details/gt2ylzjgxbe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aibaodan.cn/Article/details/gt2hxkdtnrv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zycfv.cn/Article/details/gt2iownxdpf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.smart0.xyz/Article/details/gt2xbkkuhrg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhoulong.xyz/Article/details/gt2rrlmhwda.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daria6918.cn/Article/details/gt2sislihfh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenlongwang.top/Article/details/gt2crmjpzfy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hysaishi.cn/Article/details/gt2rdgkupyg.html

[D02] 追加元素到末尾
来源：http://dali.tian-w.cn/Article/details/gt2ejmfrjhv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hongshengwenyu.top/Article/details/gt2xaotyahj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzuwekwl.html

JS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gt2jtqajnhy.html

TS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gt2uwbkgvra.html

Java: list.add(4);
来源：http://dali.hywenlv.cn/Article/details/gt2yohsfhrd.html

Go:   arr = append(arr, 4)
来源：http://dali.gogol.net.cn/Article/details/gt2wcokvuuf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258.top/Article/details/gt2ffdqzcca.html

C#:   list.Add(4);
来源：http://dali.haohaochexian.top/Article/details/gt2ldiwrcvy.html

[D03] 在指定位置插入元素
来源：http://dali.smart0.xyz/Article/details/gt2ajbcfmjo.html

Py:   arr.insert(0, 0)
来源：http://dali.meibo888.top/Article/details/gt2wlzffnlt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fzhhl.top/Article/details/gt2tkqiyspq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jlsjyb.cn/Article/details/gt2jtfzdqrw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tianlin.xyz/Article/details/gt2qozohtqc.html

Java: list.add(0, 0);
来源：http://dali.gzhubu.top/Article/details/gt2jeoucaem.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sxryk.cn/Article/details/gt2coouvfgh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.havefunace.top/Article/details/gt2frmqhvsf.html

C#:   list.Insert(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gt2tguhuyli.html

[D04] 删除元素
来源：http://dali.yvedp.cn/Article/details/gt2nwqmvcyv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.havefunace.top/Article/details/gt2anpznpun.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xvcurjlp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shangyingyoupin.top/Article/details/gt2eleydkcw.html

TS:   arr.splice(0, 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oiitabed.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.c1oappe.top/Article/details/gt2jewoqusg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yangfankeji.com/Article/details/gt2yucwmnue.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqnxhkyr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258888.top/Article/details/gt2kasrhibl.html

[D05] 访问与修改元素
来源：http://dali.jiagoushi.top/Article/details/gt2mxhtssfy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gt2echqguvt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yyonkpma.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gt2oxhjlgef.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cashguo.top/Article/details/gt2edmexztf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mwnlshth.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gt2kwvetzkn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2pfdhbzuw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gt2cxtkjeby.html

[D06] 数组长度
来源：http://dali.yvedp.cn/Article/details/gt2xqucsiad.html

Py:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2yvoiikus.html

PHP:  count($arr);
来源：http://dali.shuidangran.top/Article/details/gt2mtikhtse.html

JS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lrdbkxfm.html

TS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2skwvffvs.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gt2ktwlsmau.html

Go:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2nzhrotil.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gt2tnvsffey.html

C#:   list.Count;
来源：http://dali.316326.xyz/Article/details/gt2lqqgrsel.html

[D07] 切片 / 取子数组
来源：http://dali.zdqjudy.top/Article/details/gt2pxseumxm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuanzx.com/Article/details/gt2psphigrc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuanzhike.top/Article/details/gt2ylalfmeq.html

JS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gt2mmrkbdzf.html

TS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gt2zlvzvxay.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gt2jalyrvfu.html

Go:   arr[1:4]
来源：http://dali.chenjidiqi.icu/Article/details/gt2zosgcqjl.html

Ruby: arr[1, 3]
来源：http://dali.zdqjudy.top/Article/details/gt2taezdlux.html

C#:   list.GetRange(1, 3);
来源：http://dali.gotoacloud.top/Article/details/gt2vlnksdbk.html

[D08] 合并两个数组
来源：http://dali.nwbrower.top/Article/details/gt2cncqgtri.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigfzy.top/Article/details/gt2wzutxjcb.html

PHP:  array_merge($a, $b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tseeztfn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxinkj.top/Article/details/gt2gmvnhuza.html

TS:   [...a, ...b];
来源：http://dali.jinqigufen.top/Article/details/gt2cmhqgclb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dianchejie.cn/Article/details/gt2lhriilfg.html

Go:   append(a, b...)
来源：http://dali.ybcxt.top/Article/details/gt2gquouczg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gt2iratlome.html

C#:   a.Concat(b).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2zimhxuyw.html

[D09] 排序（升序）
来源：http://dali.guannengcc.top/Article/details/gt2idmiaybm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gt2evxjveef.html

PHP:  sort($arr);
来源：http://dali.ydzc1.top/Article/details/gt2fdiwitue.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shzxlz.cn/Article/details/gt2dxdkwrlm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pycfn.com/Article/details/gt2hgfuccyb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sufxvd.cn/Article/details/gt2pxdopabg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pwemsqzd.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gt2aukxvvvq.html

C#:   list.Sort();
来源：http://dali.hfpthk.cn/Article/details/gt2lbxzlmuz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fzhhl.top/Article/details/gt2bdzqgwle.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yvedp.cn/Article/details/gt2tpedswtt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yangfankeji.com/Article/details/gt2tutyookn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gt2vmzseuff.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.9152youxi.cn/Article/details/gt2ixcaciau.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dianchejie.cn/Article/details/gt2vriltdmf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gaohongyu789.top/Article/details/gt2hiesgchm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jyoumei.cn/Article/details/gt2tavjtsgw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuanzhike.top/Article/details/gt2calxedcs.html

[D11] 反转数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kcmawdyp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dianchejie.cn/Article/details/gt2grynylcr.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tpazabnl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.kuanghao11.cn/Article/details/gt2ngvzhaur.html

TS:   [...arr].reverse();
来源：http://dali.cdnleiting.top/Article/details/gt2qjijltij.html

Java: Collections.reverse(list);
来源：http://dali.shzxlz.cn/Article/details/gt2shjjvxay.html

Go:   slices.Reverse(arr)
来源：http://dali.cashguo.top/Article/details/gt2qabmjogb.html

Ruby: arr.reverse
来源：http://dali.bjfxy.top/Article/details/gt2amdbnmra.html

C#:   list.Reverse();
来源：http://dali.nanxinkj.top/Article/details/gt2pkcwsbaf.html

[D12] 查找元素下标
来源：http://dali.smart0.xyz/Article/details/gt2ibuwunyx.html

Py:   arr.index(x);  x in arr
来源：http://dali.9152youxi.cn/Article/details/gt2jpoijkel.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2sekypfay.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ujgbasyf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gt2npjhbvmp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jyoumei.cn/Article/details/gt2svtalqyj.html

Go:   slices.Index(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2zrcrxpvk.html

Ruby: arr.index(x)
来源：http://dali.ehwqpu.com/Article/details/gt2yrhzstow.html

C#:   list.IndexOf(x);
来源：http://dali.hywenlv.cn/Article/details/gt2joefsmnl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cheryme.top/Article/details/gt2szmapsnw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqiewwmx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.birdmap.top/Article/details/gt2bokdrctb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gt2fumsypsr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jmevhyzb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuxming.cn/Article/details/gt2ehkwxnzb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxuanxn.top/Article/details/gt2llzvtkxr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvoaxxdf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jianghu66.top/Article/details/gt2fiahrror.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sufxvd.cn/Article/details/gt2auzbeicm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigufen.top/Article/details/gt2akgignif.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gt2rhsqyzpq.html

JS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gt2rhgiwjng.html

TS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kritacvx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guannengcc.top/Article/details/gt2ffweiiib.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2axrgrnvu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cashguo.top/Article/details/gt2sszxmlhs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2vjvyspzp.html

[D15] 去重
来源：http://dali.cqqwz.cn/Article/details/gt2ytekowdn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gt2ltlwysvo.html

PHP:  array_unique($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jttbzutv.html

JS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gt2owoofbnp.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2exvwsvjm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vnwvrzmp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guowangkeji.top/Article/details/gt2tikwxrwi.html

Ruby: arr.uniq
来源：http://dali.zhixingplan.top/Article/details/gt2hnskctmn.html

C#:   list.Distinct().ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2vyzqvegz.html

[D16] 求和与平均值
来源：http://dali.yueranfly.top/Article/details/gt2zdslpmsn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jhedqdlh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shuidangran.top/Article/details/gt2cesufzek.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2xjukdcof.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gt2yucskpxs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tanke756.top/Article/details/gt2mzhhpzav.html

Go:   // 手写循环累加
来源：http://dali.yueranfly.top/Article/details/gt2bfagivgk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.316326.xyz/Article/details/gt2jopxzpzj.html

C#:   list.Sum();  list.Average()
来源：http://dali.daria6918.cn/Article/details/gt2usxzuqnt.html

[D17] 最大值与最小值
来源：http://dali.snrcjt.cn/Article/details/gt2ojdkvxov.html

Py:   max(arr);  min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2dueyqomh.html

PHP:  max($arr);  min($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2wjasfiaj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.andypj.xyz/Article/details/gt2qkezdxba.html

TS:   Math.max(...arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ictsqvjp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yueranfly.top/Article/details/gt2gnqltozs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gzhubu.top/Article/details/gt2gzuqnrpw.html

Ruby: arr.max;  arr.min
来源：http://dali.ivvv.top/Article/details/gt2zojydher.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258.top/Article/details/gt2iphiltis.html

[D18] 扁平化嵌套数组
来源：http://dali.smart0.xyz/Article/details/gt2tioujblp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tianlin.xyz/Article/details/gt2ughrahsv.html

PHP:  array_merge(...$nested);
来源：http://dali.zhoulong.xyz/Article/details/gt2ieekyegu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yonumen.top/Article/details/gt2tcjodrdx.html

TS:   nested.flat();
来源：http://dali.hongshengwenyu.top/Article/details/gt2rydwrqtp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2lrhkldvo.html

Go:   // 手写双层循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2vaggkdoy.html

Ruby: nested.flatten
来源：http://dali.meibo888.top/Article/details/gt2zebhkekv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2oebhcxjs.html

[D19] 按字段分组
来源：http://dali.nanxuanxn.top/Article/details/gt2khjjhnuu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yvedp.cn/Article/details/gt2aigmwrvh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hysaishi.cn/Article/details/gt2aaiwroet.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jianghu66.top/Article/details/gt2yomvdzry.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gt2eerujmbc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gt2gnuvstja.html

Go:   // 手写 map[string][]T
来源：http://dali.zhixingplan.top/Article/details/gt2eaiqcvyi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ybcxt.top/Article/details/gt2dimklgml.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnxiangtu.top/Article/details/gt2lzomgyih.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigfzy.top/Article/details/gt2ipqclrva.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2bnjkpfcn.html

PHP:  array_count_values($arr);
来源：http://dali.guannengcc.top/Article/details/gt2kfsogzhr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gt2gkkgacsr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gt2qlazpsqa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjxjnjap.html

Go:   // 手写 map[T]int
来源：http://dali.chenlongwang.top/Article/details/gt2xscfosbx.html

Ruby: arr.tally
来源：http://dali.daxiang520.top/Article/details/gt2fsoazepo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sxryk.cn/Article/details/gt2ontbblhp.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fbbjqxag.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gt2xezlmyqz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnqzz.top/Article/details/gt2phefjoca.html

JS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pvmadxcb.html

TS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gt2srjtkiaa.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gt2rbqoauli.html

Go:   slices.Contains(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2vubszcvn.html

Ruby: arr.include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2forvtais.html

C#:   list.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nbdxnsvx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gt2ldadibew.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yongpay.top/Article/details/gt2bfwwlivh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aizwys.cn/Article/details/gt2zjmhynsl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2gcnttcsv.html

TS:   [...arr];
来源：http://dali.xuanzx.com/Article/details/gt2jvwozdii.html

Java: new ArrayList<>(list);
来源：http://dali.c1oappe.top/Article/details/gt2kjwmepzy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guowangkeji.top/Article/details/gt2nhuliwrd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhengqikj.top/Article/details/gt2jmxktnjl.html

C#:   new List<int>(list);
来源：http://dali.havefunace.top/Article/details/gt2bivenyyl.html

[D23] reduce 累积计算
来源：http://dali.hysaishi.cn/Article/details/gt2cmunydtt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daria6918.cn/Article/details/gt2dnbpqdlu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2mpbkapyn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qzucietw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zxmshird.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ehwqpu.com/Article/details/gt2lldivxvn.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gt2zukpcqbp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dashuyun.cn/Article/details/gt2jsoblcjq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.haohaochexian.top/Article/details/gt2akhnajgn.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenlongwang.top/Article/details/gt2zrgfqvlm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ehwqpu.com/Article/details/gt2chtuykqo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2srhlqtlm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hfpthk.cn/Article/details/gt2fcwzdwie.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2zajbppgf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hfpthk.cn/Article/details/gt2rbobjxqg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aibaodan.cn/Article/details/gt2olzlgdlr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yangfankeji.com/Article/details/gt2krbayaxi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gt2mbacqyvp.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxinkj.top/Article/details/gt2eaykssim.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhongyouzk.top/Article/details/gt2bunmgwkg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gzhubu.top/Article/details/gt2fcmarvrf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shzxlz.cn/Article/details/gt2efvouxnz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixxdrqbe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuanzhike.top/Article/details/gt2vkohgtjw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhengqikj.top/Article/details/gt2fsabtqxd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jianghu66.top/Article/details/gt2yuwlvskw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hysaishi.cn/Article/details/gt2xptsatma.html

[D26] 数组转字符串
来源：http://dali.dianchejie.cn/Article/details/gt2tqumehzx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ivvv.top/Article/details/gt2upohnczl.html

PHP:  implode(", ", $arr);
来源：http://dali.xziqi.cn/Article/details/gt2kvhnhefl.html

JS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gt2osqaeooo.html

TS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2jyqnzrae.html

Java: String.join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gt2vxdzccbm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daria6918.cn/Article/details/gt2ybjxjyph.html

Ruby: arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gt2bjslmvke.html

C#:   string.Join(", ", list)
来源：http://dali.fengsongda.top/Article/details/gt2ctjnzczw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2cyoccpvo.html

E. 字符串处理
来源：http://dali.ydzc1.top/Article/details/gt2gmpntvzc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2bivlsjja.html

[E01] 拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2khrktrhd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj202588.top/Article/details/gt2udgajanv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2phzynojx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gt2hleuvbez.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gt2auqucudv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dashuyun.cn/Article/details/gt2gwwkzzkj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yongpay.top/Article/details/gt2jqvqrdbb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dashuyun.cn/Article/details/gt2oqoxzmii.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2ttciqhut.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gt2xfkbghvq.html

Py:   "ab" * 3
来源：http://dali.yonumen.top/Article/details/gt2wirgcpbj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangdashe.top/Article/details/gt2qvuubcvv.html

JS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2iwmoinld.html

TS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gt2rkmirrqi.html

Java: "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbvqpicr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.c1oappe.top/Article/details/gt2zlueihho.html

Ruby: "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gt2khaunwze.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guannengcc.top/Article/details/gt2pmdooyiv.html

[E03] 截取子串
来源：http://dali.yvedp.cn/Article/details/gt2cujrvftf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gotoacloud.top/Article/details/gt2jmrjxchg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gt2svsrtffl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gt2bjtbedrn.html

TS:   s.slice(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gt2kbipqwqf.html

Java: s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wkbhsnyx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ppjwa.cn/Article/details/gt2xvffnxto.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymldxhiz.html

C#:   s.Substring(1, 3)
来源：http://dali.shuidangran.top/Article/details/gt2hygeajdz.html

[E04] 查找子串位置
来源：http://dali.svipenyu.cn/Article/details/gt2jglrliqi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.havefunace.top/Article/details/gt2cdkqygrn.html

PHP:  strpos($s, "x");
来源：http://dali.guowangkeji.top/Article/details/gt2lmlhpplh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2scwapwiq.html

TS:   s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gt2jbllcvkz.html

Java: s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gt2jmobtsfj.html

Go:   strings.Index(s, "x")
来源：http://dali.yvedp.cn/Article/details/gt2immtrxhp.html

Ruby: s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2oniqsqdw.html

C#:   s.IndexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxrjopkd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cdnleiting.top/Article/details/gt2ybsboznd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhixingplan.top/Article/details/gt2ssjfjcfh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sxryk.cn/Article/details/gt2goqaipzu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xjxunmgf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.c1oappe.top/Article/details/gt2nfxvrveh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gt2uwrypdom.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yonumen.top/Article/details/gt2lbhuvtfo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hfpthk.cn/Article/details/gt2gjwmhhgb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nwbrower.top/Article/details/gt2wjceznse.html

[E06] 替换子串
来源：http://dali.redwolf501.top/Article/details/gt2nqxjnegi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gt2awqdxkgg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aizwys.cn/Article/details/gt2iqrrsuea.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2bhbrxqwm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2ickufdhv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jjzrcpkb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gt2ajmaljjl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2iihzaoga.html

C#:   s.Replace("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2elusiekb.html

[E07] 按分隔符拆分
来源：http://dali.yonumen.top/Article/details/gt2nwgttyzq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnqzz.top/Article/details/gt2mrxmbvgx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2mellhhjy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.c1oappe.top/Article/details/gt2ohecevwj.html

TS:   s.split(",")
来源：http://dali.cashguo.top/Article/details/gt2lkyqxttr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cdcoxods.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nimtvloj.html


<!-- 参考信息 -->