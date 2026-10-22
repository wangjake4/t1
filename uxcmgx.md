代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gt2mdengldn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxinkj.top/Article/details/gt2ttxoqxvd.html

Java: // 无解构
来源：http://dali.zycfv.cn/Article/details/gt2tpkvhjib.html

Go:   // 无解构
来源：http://dali.jianghu66.top/Article/details/gt2ptqxudjy.html

Ruby: a, b = pair
来源：http://dali.tianlin.xyz/Article/details/gt2ymuulobk.html

C#:   var (a, b) = pair;
来源：http://dali.cucudq.cn/Article/details/gt2jgpsslso.html

[C16] 函数 / 方法重载
来源：http://dali.hywenlv.cn/Article/details/gt2qsndnhwn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hammf.cn/Article/details/gt2zvoqiwus.html

PHP:  // 无重载
来源：http://dali.ydzc1.top/Article/details/gt2kkgbfkhu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yangfankeji.com/Article/details/gt2yhyvyxlu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jlsjyb.cn/Article/details/gt2dnfjpgik.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnqzz.top/Article/details/gt2ayqhxxpz.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ntjzikzq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxuanxn.top/Article/details/gt2luseogod.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.9152youxi.cn/Article/details/gt2hicbpmto.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2crzkkjbx.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gt2wggmeflc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2yyldgjyw.html

[D01] 创建数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gt2valyvwjm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2tubjmbmt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gt2ndnzycug.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ivvv.top/Article/details/gt2dqfdhgei.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuanzhike.top/Article/details/gt2wtajgrdd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.vqdsnc.cn/Article/details/gt2rjmwjfvc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.iojbl.cn/Article/details/gt2lscewiyg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.havefunace.top/Article/details/gt2ditfhkyp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hongshengwenyu.top/Article/details/gt2jakfztue.html

[D02] 追加元素到末尾
来源：http://dali.fzhhl.top/Article/details/gt2hdcgjxix.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dianchejie.cn/Article/details/gt2renmccvy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dashuyun.cn/Article/details/gt2vefwyvdb.html

JS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2mbhqomsu.html

TS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gt2szqwnhfz.html

Java: list.add(4);
来源：http://dali.cqqwz.cn/Article/details/gt2uvvedtyj.html

Go:   arr = append(arr, 4)
来源：http://dali.mhx1999.top/Article/details/gt2neexgivy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vojdaybs.html

C#:   list.Add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2neknpsgm.html

[D03] 在指定位置插入元素
来源：http://dali.jqgfzy.top/Article/details/gt2cnanhafl.html

Py:   arr.insert(0, 0)
来源：http://dali.pycfn.com/Article/details/gt2abeuzahr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ivvv.top/Article/details/gt2sdbzlbfg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cheryme.top/Article/details/gt2mjntdmhk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.meibo888.top/Article/details/gt2mcvyficc.html

Java: list.add(0, 0);
来源：http://dali.yj20258888.top/Article/details/gt2jciiibmk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ivvv.top/Article/details/gt2bnkaneib.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shzxlz.cn/Article/details/gt2awusepuk.html

C#:   list.Insert(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2uqwigjqr.html

[D04] 删除元素
来源：http://dali.0kj1m.cn/Article/details/gt2dhmxdfte.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cqqwz.cn/Article/details/gt2vobfprkz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tian-w.cn/Article/details/gt2rdwmrdhh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hammf.cn/Article/details/gt2gzsokhcx.html

TS:   arr.splice(0, 1);
来源：http://dali.meibo888.top/Article/details/gt2wtgiceaq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tianlin.xyz/Article/details/gt2thgyfbme.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dashuyun.cn/Article/details/gt2injzzxcb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yongpay.top/Article/details/gt2jaxjjity.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258.top/Article/details/gt2knyryzef.html

[D05] 访问与修改元素
来源：http://dali.xylfe.cn/Article/details/gt2doxifskx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gt2gjfbemcz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gt2lbmkadom.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eamojrvf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxuanxn.top/Article/details/gt2swucmzjn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pycfn.com/Article/details/gt2ftfwfceu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gt2uxshhtne.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gt2mqriormw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.316326.xyz/Article/details/gt2ivxdiicn.html

[D06] 数组长度
来源：http://dali.pycfn.com/Article/details/gt2mmufsfcy.html

Py:   len(arr)
来源：http://dali.316326.xyz/Article/details/gt2javlgdsq.html

PHP:  count($arr);
来源：http://dali.fzhhl.top/Article/details/gt2crrvinfp.html

JS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gt2zayawhdd.html

TS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gt2nuuzlihi.html

Java: list.size();
来源：http://dali.yvedp.cn/Article/details/gt2rxgwffea.html

Go:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2xupkenec.html

Ruby: arr.length; arr.size
来源：http://dali.quarkkingdee.top/Article/details/gt2fjbxvymb.html

C#:   list.Count;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lkgdldig.html

[D07] 切片 / 取子数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vzkbsvsa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shzxlz.cn/Article/details/gt2phipqwyp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hfpthk.cn/Article/details/gt2bitzltct.html

JS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gt2bppsrfqm.html

TS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gt2zpepodlw.html

Java: list.subList(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gt2juroyoiu.html

Go:   arr[1:4]
来源：http://dali.aizwys.cn/Article/details/gt2wcnxypaw.html

Ruby: arr[1, 3]
来源：http://dali.0kj1m.cn/Article/details/gt2mflfbvwk.html

C#:   list.GetRange(1, 3);
来源：http://dali.tanke756.top/Article/details/gt2rhzbuxaj.html

[D08] 合并两个数组
来源：http://dali.ybcxt.top/Article/details/gt2dqkddooy.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuanzhike.top/Article/details/gt2sjitmkbk.html

PHP:  array_merge($a, $b);
来源：http://dali.iojbl.cn/Article/details/gt2msxgtnjl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.mhx1999.top/Article/details/gt2humwjhjx.html

TS:   [...a, ...b];
来源：http://dali.guowangkeji.top/Article/details/gt2utllcman.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zycfv.cn/Article/details/gt2kyblksoz.html

Go:   append(a, b...)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vgejxnnh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuanzx.com/Article/details/gt2wqsyqdei.html

C#:   a.Concat(b).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2ovolxgnt.html

[D09] 排序（升序）
来源：http://dali.jqgfzy.top/Article/details/gt2ighsngrt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gt2zszyjfrl.html

PHP:  sort($arr);
来源：http://dali.316326.xyz/Article/details/gt2zrqampww.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cashguo.top/Article/details/gt2vdvcnvas.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigufen.top/Article/details/gt2iroyzeeu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sweek.top/Article/details/gt2jiccdmuj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2lhnvcyvg.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gt2ppwfazom.html

C#:   list.Sort();
来源：http://dali.gogol.net.cn/Article/details/gt2ztpkfjdo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ppjwa.cn/Article/details/gt2ujksyirw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sufxvd.cn/Article/details/gt2fpdqkqjc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gt2kjaublji.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gt2eajxnivu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gt2owraszvw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aibaodan.cn/Article/details/gt2epumnfva.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sysykeji.top/Article/details/gt2iftvkatq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxuanxn.top/Article/details/gt2yrhhdprc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sufxvd.cn/Article/details/gt2tmfejtlg.html

[D11] 反转数组
来源：http://dali.jinqigufen.top/Article/details/gt2bigzeljo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gt2cbwthced.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2bbnqgild.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.mhx1999.top/Article/details/gt2kzbzqehz.html

TS:   [...arr].reverse();
来源：http://dali.ydzc1.top/Article/details/gt2ijnztgrz.html

Java: Collections.reverse(list);
来源：http://dali.yanxiufei.cn/Article/details/gt2wyogejyg.html

Go:   slices.Reverse(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2zmimxpii.html

Ruby: arr.reverse
来源：http://dali.meibo888.top/Article/details/gt2sguzfjsd.html

C#:   list.Reverse();
来源：http://dali.havefunace.top/Article/details/gt2xmyetuza.html

[D12] 查找元素下标
来源：http://dali.cucudq.cn/Article/details/gt2zlpdawwk.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuxming.cn/Article/details/gt2fwkryiyx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yongpay.top/Article/details/gt2lvqgjsxx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gt2vidfiqgp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gt2rnggtjmf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hongshengwenyu.top/Article/details/gt2bfikojlb.html

Go:   slices.Index(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2wfhhjycc.html

Ruby: arr.index(x)
来源：http://dali.xylfe.cn/Article/details/gt2yrzdpmso.html

C#:   list.IndexOf(x);
来源：http://dali.nanxuanxn.top/Article/details/gt2naljqutm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpbczrln.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gt2gcyfwtrw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.meibo888.top/Article/details/gt2gbopjegk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gt2ruupnvdp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2seehfotu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2nsgljtin.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ppjwa.cn/Article/details/gt2dpeqerbs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tianlin.xyz/Article/details/gt2koazocgc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.birdmap.top/Article/details/gt2vhlvhzuo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guannengcc.top/Article/details/gt2sdsnymbk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258888.top/Article/details/gt2xnvezbjf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2xszrhvyd.html

JS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gt2sxrqhrha.html

TS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gt2zhcvuxou.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mfmazpjf.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gt2hqfnxyir.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jianghu66.top/Article/details/gt2zfklxhvq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hammf.cn/Article/details/gt2gdsgfbuv.html

[D15] 去重
来源：http://dali.aibaodan.cn/Article/details/gt2lmqjgqch.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gt2oftjmdgh.html

PHP:  array_unique($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2ncmuhlvn.html

JS:   [...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gt2imfjcowd.html

TS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gt2yiykdqrb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnxiangtu.top/Article/details/gt2qhhrjurh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sxryk.cn/Article/details/gt2glezduxi.html

Ruby: arr.uniq
来源：http://dali.yonumen.top/Article/details/gt2kzzwfljp.html

C#:   list.Distinct().ToList()
来源：http://dali.gzhubu.top/Article/details/gt2bpsjrvcm.html

[D16] 求和与平均值
来源：http://dali.andypj.xyz/Article/details/gt2uvprckvu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2rzscvdqv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xylfe.cn/Article/details/gt2zkvoepea.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gt2pneplcfv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2pzrosgee.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gt2phrfnvzj.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qckmzved.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmbuhtsr.html

C#:   list.Sum();  list.Average()
来源：http://dali.yanxiufei.cn/Article/details/gt2dotcejov.html

[D17] 最大值与最小值
来源：http://dali.dianchejie.cn/Article/details/gt2zbcxryaj.html

Py:   max(arr);  min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2wazwfjcw.html

PHP:  max($arr);  min($arr);
来源：http://dali.xylfe.cn/Article/details/gt2wkgwbytd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenzaomai.com/Article/details/gt2quibscep.html

TS:   Math.max(...arr);
来源：http://dali.redwolf501.top/Article/details/gt2huzkthjr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuanzhike.top/Article/details/gt2kqyszgnr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cashguo.top/Article/details/gt2amfmrxwg.html

Ruby: arr.max;  arr.min
来源：http://dali.zdqjudy.top/Article/details/gt2dbdwxfeg.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdrqdpl.html

[D18] 扁平化嵌套数组
来源：http://dali.sweek.top/Article/details/gt2gmuyvyzs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yanxiufei.cn/Article/details/gt2bgflwlnd.html

PHP:  array_merge(...$nested);
来源：http://dali.mhx1999.top/Article/details/gt2knrepcrh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.0kj1m.cn/Article/details/gt2alulboeg.html

TS:   nested.flat();
来源：http://dali.jyoumei.cn/Article/details/gt2twozdhoh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2pkjettqj.html

Go:   // 手写双层循环
来源：http://dali.jiagoushi.top/Article/details/gt2oiwvfbtd.html

Ruby: nested.flatten
来源：http://dali.redwolf501.top/Article/details/gt2qirbdoka.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2gdxvfgtq.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gt2nxhnvadp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.haohaochexian.top/Article/details/gt2ozsakimh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.c1oappe.top/Article/details/gt2xrpbayfa.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258.top/Article/details/gt2pzjezxxm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gt2edwyvjei.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gt2bnesqsxg.html

Go:   // 手写 map[string][]T
来源：http://dali.yuxming.cn/Article/details/gt2zfqfbrge.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ydzc1.top/Article/details/gt2nfeaegtd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenjidiqi.icu/Article/details/gt2fknpvnfb.html

[D20] 统计每个元素出现次数
来源：http://dali.yueranfly.top/Article/details/gt2rktjejor.html

Py:   Counter(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2azplavau.html

PHP:  array_count_values($arr);
来源：http://dali.daria6918.cn/Article/details/gt2uilpgyxg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gt2mkuhoanq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gt2xsuifpzb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgufenzy.top/Article/details/gt2zyweudin.html

Go:   // 手写 map[T]int
来源：http://dali.birdmap.top/Article/details/gt2flegdiew.html

Ruby: arr.tally
来源：http://dali.bjfxy.top/Article/details/gt2obwcclzx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuanzx.com/Article/details/gt2nuqjzoks.html

[D21] 判断是否包含某元素
来源：http://dali.ydzc1.top/Article/details/gt2cmuaelss.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2apnhbkhy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gt2gjbltupe.html

JS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2zgjhkrbl.html

TS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gt2ufvmcpuc.html

Java: list.contains(x)
来源：http://dali.dianchejie.cn/Article/details/gt2milrxwxg.html

Go:   slices.Contains(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2peevtdwb.html

Ruby: arr.include?(x)
来源：http://dali.guannengcc.top/Article/details/gt2rdjjgzqo.html

C#:   list.Contains(x)
来源：http://dali.meibo888.top/Article/details/gt2swovenrd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.quarkkingdee.top/Article/details/gt2ekcsnpnf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jcqxcfaa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.mhx1999.top/Article/details/gt2mbwxvutd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2scqkrpmr.html

TS:   [...arr];
来源：http://dali.shangyingyoupin.top/Article/details/gt2juxbscaj.html

Java: new ArrayList<>(list);
来源：http://dali.cdnleiting.top/Article/details/gt2azbtixjq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dashuyun.cn/Article/details/gt2kuhxnwrt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.9152youxi.cn/Article/details/gt2nudayuya.html

C#:   new List<int>(list);
来源：http://dali.hnqzz.top/Article/details/gt2spckotyb.html

[D23] reduce 累积计算
来源：http://dali.haohaochexian.top/Article/details/gt2otdhlzaq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2hooomohz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ydzc1.top/Article/details/gt2bnufcbcd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2gvxypgsp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gt2vetcxmjw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuetiantiany.cn/Article/details/gt2urynvtww.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gt2svvrnzcj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuetiantiany.cn/Article/details/gt2tmzueikc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuanzhike.top/Article/details/gt2ynaokyyp.html

[D24] 字典 / Map 基本操作
来源：http://dali.cqqwz.cn/Article/details/gt2cnnjsxoi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ivvv.top/Article/details/gt2jytywihl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ybcxt.top/Article/details/gt2nmmvzzdy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fzhhl.top/Article/details/gt2xxhodnjw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2fslfoemh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenzaomai.com/Article/details/gt2xhmillrl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sufxvd.cn/Article/details/gt2gvkbauvd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxuanxn.top/Article/details/gt2wrpytagu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sysykeji.top/Article/details/gt2haitymph.html

[D25] Set 集合去重与交并差
来源：http://dali.bjfxy.top/Article/details/gt2oiyfzmhu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guowangkeji.top/Article/details/gt2lmaizsrm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxvajnkc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhengqikj.top/Article/details/gt2kclwdmrl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cqqwz.cn/Article/details/gt2luggsqut.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2psxldhtk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yangfankeji.com/Article/details/gt2giaeizku.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cheryme.top/Article/details/gt2xpyrcwlq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.c1oappe.top/Article/details/gt2xinmitsw.html

[D26] 数组转字符串
来源：http://dali.gzhubu.top/Article/details/gt2caeuerzv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gt2zimvwpln.html

PHP:  implode(", ", $arr);
来源：http://dali.haohaochexian.top/Article/details/gt2zetlnamd.html

JS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gt2hpvvxwgm.html

TS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2orxwcnvz.html

Java: String.join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gt2khdjknkb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gt2tsmmhanm.html

Ruby: arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gt2fmkaagjv.html

C#:   string.Join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gt2qrncqmqi.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2xpnmhejp.html

E. 字符串处理
来源：http://dali.shuidangran.top/Article/details/gt2kmilxomu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2rlnvmdyz.html

[E01] 拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gt2fjpldyzp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yongpay.top/Article/details/gt2qquuvhpw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2kyqzstkx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gt2vaqkjtfw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gt2yshzmyag.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.svipenyu.cn/Article/details/gt2xwntlzot.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.meibo888.top/Article/details/gt2rvtgkjhp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gaohongyu789.top/Article/details/gt2eavsrkrm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tmmtmvat.html

[E02] 重复字符串
来源：http://dali.zhixingplan.top/Article/details/gt2lhwhmuqh.html

Py:   "ab" * 3
来源：http://dali.xinyue.icu/Article/details/gt2nodwhxgy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2tylaiznh.html

JS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gt2zmcitfev.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gt2iixqvtdp.html

Java: "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dtoavagj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.daxiang520.top/Article/details/gt2ukhzjkph.html

Ruby: "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gt2khfhgvph.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258888.top/Article/details/gt2dlrhzzeo.html

[E03] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhzaxplb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tanke756.top/Article/details/gt2nzlyefyp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gt2akatlusz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gt2yqefhrjt.html

TS:   s.slice(1, 4)
来源：http://dali.yvedp.cn/Article/details/gt2xvphzwjv.html

Java: s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gt2zpqovaxz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gt2qfelenus.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.meibo888.top/Article/details/gt2ayjgxemv.html

C#:   s.Substring(1, 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbpylpgb.html

[E04] 查找子串位置
来源：http://dali.hnqzz.top/Article/details/gt2wcnjerdw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2njwxnuud.html

PHP:  strpos($s, "x");
来源：http://dali.guannengcc.top/Article/details/gt2mpqecrwa.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yongpay.top/Article/details/gt2yhnyfivu.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gt2kypmhbks.html

Java: s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gt2zponewjv.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258888.top/Article/details/gt2vtepuzll.html

Ruby: s.index("x")
来源：http://dali.yj20258.top/Article/details/gt2erlsgdix.html

C#:   s.IndexOf("x")
来源：http://dali.c1oappe.top/Article/details/gt2ciulfbzt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cqqwz.cn/Article/details/gt2oukjsbbq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fzhhl.top/Article/details/gt2xbfwuynw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hysaishi.cn/Article/details/gt2ztebxzlr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2dcblggos.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sysykeji.top/Article/details/gt2odpjksqy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gt2lifhvxrg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hysaishi.cn/Article/details/gt2mxcseelt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yongpay.top/Article/details/gt2kqhdjbwd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gt2qaszlqqv.html


<!-- 参考信息 -->