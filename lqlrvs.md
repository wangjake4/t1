代发 wailian999

TS:   public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtvnpstdvi.html

Java: public / protected / private / 默认包级
来源：http://dali.gotoacloud.top/Article/details/gtplolbzoh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xziqi.cn/Article/details/gtuydhbtxi.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gtblfdwern.html

C#:   public / protected / private / internal
来源：http://dali.hongshengwenyu.top/Article/details/gtdkhxeswv.html

[G11] getter / setter
来源：http://dali.pycfn.com/Article/details/gtbhdpvjzw.html

Py:   @property 与 @x.setter
来源：http://dali.316326.xyz/Article/details/gtyctvcogl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtraheuhqt.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtcsqtdjgf.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvipsrnoy.html

Java: public String getName() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtgdcyxnsu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtfjjlejtq.html

Ruby: attr_accessor :name
来源：http://dali.shangyingyoupin.top/Article/details/gtnefcsich.html

C#:   public string Name { get; set; }
来源：http://dali.haohaochexian.top/Article/details/gtegscclgh.html

[G12] 对象转字符串
来源：http://dali.tian-w.cn/Article/details/gtsuatdjiw.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtzuqmncuw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtvslnrbqp.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtwkcenuuw.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtmozpcxum.html

Java: @Override public String toString() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtzteqpvkk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gthcmbfsep.html

Ruby: def to_s; @name; end
来源：http://dali.sysykeji.top/Article/details/gtvyuvssfz.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gtpsoskdih.html

[G13] 判断对象类型
来源：http://dali.xinyue.icu/Article/details/gthkkjgrlp.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gtwvdkhafi.html

PHP:  $u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtewobrpml.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtijwkaajq.html

TS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtgumnwjup.html

Java: u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtbqkqkejt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtdopmxucs.html

Ruby: u.is_a?(User)
来源：http://dali.nanxinkj.top/Article/details/gthftvjqou.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gtaoggkrxe.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gtcksacrkg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.mhx1999.top/Article/details/gtrownzeau.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gtprpkjyek.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tianlin.xyz/Article/details/gtowjgtgzi.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcoeoayx.html

Java: record User(String name, int age) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtttcaizou.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gtucirozhd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangshuangyany.cn/Article/details/gttbqfxkvp.html

C#:   record User(string Name, int Age);
来源：http://dali.zhoulong.xyz/Article/details/gtcnvjdixk.html

[G15] 枚举
来源：http://dali.gzhubu.top/Article/details/gtgovqydpe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hammf.cn/Article/details/gtrbeumiot.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmzlqacgk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.havefunace.top/Article/details/gtcglgswix.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gttpziynfi.html

Java: enum Color { RED, GREEN }
来源：http://dali.gzhubu.top/Article/details/gtlcacfolw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigfzy.top/Article/details/gtlqicqguk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yueranfly.top/Article/details/gtnfexhjke.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gtjjruigmt.html

[G16] 对象转数组 / 字典
来源：http://dali.jianghu66.top/Article/details/gtlezgsrvt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.vqdsnc.cn/Article/details/gtnzkracnx.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigufen.top/Article/details/gtrvvdqknt.html

JS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gtlrrnjuqd.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtwtbfymad.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.9152youxi.cn/Article/details/gtkzhhkepb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gtdzfeskya.html

Ruby: obj.instance_variables
来源：http://dali.yuxming.cn/Article/details/gtplzylrhi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuqhxwsg.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxwtzxzss.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gtmdkxpryy.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtjtqqmzho.html

[H01] try / catch 基础
来源：http://dali.yj202588.top/Article/details/gtfswsoswg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gtbnodivxu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ehwqpu.com/Article/details/gtghioldwa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtcsrfyafi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwoknjppq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtomycgizx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hammf.cn/Article/details/gtivbophpm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxinkj.top/Article/details/gtwnnjyyqx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fzhhl.top/Article/details/gtxuxyqatu.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gtekglglgo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gtjfiunzac.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtqwecvoee.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtkheeglle.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtfexqdmhz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtqcfcyodt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gtlmhpikcm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.0kj1m.cn/Article/details/gtxzybfcag.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtfciuhxnx.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gtdshvjugs.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhaomingkeji.xyz/Article/details/gteewypiit.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtyphntxsz.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtkzkmgdzt.html

TS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtiqgrieqt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtfsfkqssd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sweek.top/Article/details/gtlzqkvcfo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gtfvaiuzzn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtfwfrpijt.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gtaoxlknyx.html

Py:   class MyError(Exception): pass
来源：http://dali.yuanzhike.top/Article/details/gtdbpopxww.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtwivunqks.html

JS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtxafiyags.html

TS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gtttwatwos.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtzsrrgzru.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258888.top/Article/details/gtfvvfczag.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhiwuduotai.top/Article/details/gtoolcvxpj.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gtfvromxxr.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gtxnztekmg.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gttwgadqxm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gtoyucgzkh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtlkwsrxpf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtkamgveph.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuanzx.com/Article/details/gtdeiaerdt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xziqi.cn/Article/details/gtmthitpzs.html

Ruby: rescue ArgumentError => e
来源：http://dali.316326.xyz/Article/details/gtnmigmvxs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxinkj.top/Article/details/gtxxkbprxd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenzaomai.com/Article/details/gtdteqlbip.html

Py:   value = d.get("k") or default
来源：http://dali.jinyuanbaomall.cn/Article/details/gteiafaapj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gtjpwkubtn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gtwgszoppt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtqetafczs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yanxiufei.cn/Article/details/gtwgqkquqi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdshhsptm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenlongwang.top/Article/details/gtiqyooycu.html

C#:   obj?.A?.B ?? default
来源：http://dali.fzhhl.top/Article/details/gtrxdhyoju.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gtbcvmatwj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sweek.top/Article/details/gtabgcqkpu.html

PHP:  assert($x > 0);
来源：http://dali.yongpay.top/Article/details/gttleatjfy.html

JS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjonsycc.html

TS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtaeintfhj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fzhhl.top/Article/details/gtjnbtnnst.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sxryk.cn/Article/details/gtuaodgtgg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zdqjudy.top/Article/details/gtwixuflii.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtopwjxsac.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuxming.cn/Article/details/gtifhbhsxg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhoulong.xyz/Article/details/gtahaujhqn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangshuangyany.cn/Article/details/gtymblbyli.html

JS:   e.message;  e.stack
来源：http://dali.yj20258888.top/Article/details/gtrmqstyun.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.haohaochexian.top/Article/details/gtnprlvfek.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jiagoushi.top/Article/details/gtvnlkbuay.html

Go:   err.Error()
来源：http://dali.hnqzz.top/Article/details/gtlafvhpai.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkkvzgms.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tanke756.top/Article/details/gtazdubgzp.html

[H09] 带错误码的异常
来源：http://dali.svipenyu.cn/Article/details/gtvedbttbx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gtlvlgkupg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gtqtgismhz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gtabqutjqb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guowangkeji.top/Article/details/gtfraswant.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxinkj.top/Article/details/gtkgmdduly.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.andypj.xyz/Article/details/gtjllxswzb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhoulong.xyz/Article/details/gtrtbdgbze.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenjidiqi.icu/Article/details/gtasdxndbg.html

[H10] 资源自动释放
来源：http://dali.fengsongda.top/Article/details/gthttzsmbu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchtqginh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pengpengdd.cyou/Article/details/gtpnmgzeit.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gtuojktssz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtkpwgkysc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gtbrzyyxol.html

Go:   defer f.Close()
来源：http://dali.hnqzz.top/Article/details/gtwtzqjezl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cashguo.top/Article/details/gtqjrsyswu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtuoiaklzt.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtupxircor.html

I. 正则表达式
来源：http://dali.jinqigfzy.top/Article/details/gtwmkvzyiv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtaogqcqfe.html

[I01] 判断是否匹配
来源：http://dali.zhengqikj.top/Article/details/gtxhjwrnmo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gtuwobqzay.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtcittuzyb.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gttmvxnfhf.html

TS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gtxenpaift.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nwbrower.top/Article/details/gtbtunkctf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hysaishi.cn/Article/details/gtoanmvuck.html

Ruby: s.match?(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtkxthkgrl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sxryk.cn/Article/details/gthujngpez.html

[I02] 提取所有匹配
来源：http://dali.jqgfzy.top/Article/details/gtzsyurfba.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gtgslnpcuh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.bjfxy.top/Article/details/gtpboirdwr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuanzx.com/Article/details/gtrghyymdw.html

TS:   s.match(/\d+/g)
来源：http://dali.redwolf501.top/Article/details/gtwkwdtyla.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhoulong.xyz/Article/details/gthdfkesci.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtrjideesa.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtzathqfnh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ydzc1.top/Article/details/gtrtiiaoui.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gtzuentqxz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jlsjyb.cn/Article/details/gtgegvjwmy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.birdmap.top/Article/details/gtebjkanjc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gtlckopvxr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gtaxjdzhmf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgufenzy.top/Article/details/gtrrctcvio.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxhscqrf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gtsdyjsgwo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258888.top/Article/details/gtntoxpskf.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gtsxydseqg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigfzy.top/Article/details/gtnfjfsesv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gtizxtbvjf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gturrtwwtc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtmsfxzqjs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gtbtweisqw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.0kj1m.cn/Article/details/gtvpxjdgnl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cheryme.top/Article/details/gtrafnhcfs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gtrmlxwasb.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gtgwfxocxt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yueranfly.top/Article/details/gtkthfwzux.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtpbcuogby.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtvfmrlsrs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtrkiplkqv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gtvkgnumua.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtnhdieavi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtqvvaygym.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtccnjfwvb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gtawlqvdkj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtfwwynjwo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gtqfmhtqox.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtvadsdnzg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gtcavbhkge.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtzddyrgqx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekyeapmi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cheryme.top/Article/details/gtvurjehpb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtrgdgqapd.html

[I07] 忽略大小写与多行模式
来源：http://dali.shangyingyoupin.top/Article/details/gtrqofivut.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.kuanghao11.cn/Article/details/gtwuxbvtyi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.birdmap.top/Article/details/gtkaxyotzi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gtlglsgfsp.html

TS:   /error/gim
来源：http://dali.fzhhl.top/Article/details/gtoxindhuz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gtvwuldkmk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gtpreqabkf.html

Ruby: s.scan(/error/i)
来源：http://dali.wangshuangyany.cn/Article/details/gtqvclands.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywmeihdw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sxryk.cn/Article/details/gtpqxvhced.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgufenzy.top/Article/details/gtgucqjsys.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gtovnfrbod.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtmnfsmcll.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gtcnutwlar.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gtyzaegyck.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hammf.cn/Article/details/gtrtzsegit.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daria6918.cn/Article/details/gtrecddbpe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtzfiabbmc.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtehaooqum.html

J. 日期与时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtouqcagjx.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtburljpgv.html

[J01] 获取当前时间
来源：http://dali.c1oappe.top/Article/details/gtwxwtyidn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yanxiufei.cn/Article/details/gttzensjfo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gtxpzscumi.html

JS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gtjryadnwf.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gtyljzuycx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guowangkeji.top/Article/details/gtgbyalvgi.html

Go:   time.Now()
来源：http://dali.havefunace.top/Article/details/gtrvxyexfy.html

Ruby: Time.now
来源：http://dali.chenlongwang.top/Article/details/gtfghjwdyb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258.top/Article/details/gtilhdibnp.html

[J02] 格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtzofruvtx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gtdfmohrpc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gtgkncljqs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nwbrower.top/Article/details/gtpqtvlmyo.html

TS:   d.toISOString()
来源：http://dali.nanxinkj.top/Article/details/gtubrozciv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cheryme.top/Article/details/gtnmhoaatb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gttjcnhlos.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gtytmjfksx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shuidangran.top/Article/details/gtwpwprqem.html

[J03] 字符串解析为日期
来源：http://dali.xylfe.cn/Article/details/gtnefqreqq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.quarkkingdee.top/Article/details/gtdvageigw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cashguo.top/Article/details/gtgfqwzuqb.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtqzhibowq.html

TS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtckwztszg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtvzhwgtcp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gttgqomabz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtnsqhrzvh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gtvemuwcpt.html

[J04] 时间戳与日期互转
来源：http://dali.yuanzhike.top/Article/details/gtilkoyere.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gtsmrnudxd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cheryme.top/Article/details/gtnfgjaeel.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gotoacloud.top/Article/details/gtxozmyxdo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tianlin.xyz/Article/details/gtmnjoogfp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gtugdrtsgn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtybshalkw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gogol.net.cn/Article/details/gtnlyeprhs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hysaishi.cn/Article/details/gtjxdbhdun.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangshuangyany.cn/Article/details/gtnyjfnbbu.html

Py:   now + timedelta(days=7)
来源：http://dali.ydzc1.top/Article/details/gtzwiqydls.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gtbotulxvx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtpkibhpdb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gtfydoxlsn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ppjwa.cn/Article/details/gtkbtcppel.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zycfv.cn/Article/details/gtqenqhxbt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.snrcjt.cn/Article/details/gtfcnuizjb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jianghu66.top/Article/details/gtorzfnwkq.html

[J06] 计算两时间之差
来源：http://dali.yuanzhike.top/Article/details/gtebzomhzg.html

Py:   (end - start).total_seconds()
来源：http://dali.daria6918.cn/Article/details/gtdjberhti.html

PHP:  $end->diff($start)->days;
来源：http://dali.xziqi.cn/Article/details/gtaqpqxrpn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gtxagaiybw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.quarkkingdee.top/Article/details/gtpaalmwxj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daxiang520.top/Article/details/gtxjnootxc.html

Go:   end.Sub(start).Hours()
来源：http://dali.cdnleiting.top/Article/details/gtouejzwoe.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangshuangyany.cn/Article/details/gtgtarimkm.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gtslazzfmf.html

[J07] 比较两个日期
来源：http://dali.9152youxi.cn/Article/details/gtrlvelrwz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtmmpxfswd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daria6918.cn/Article/details/gtldvfcmmx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtgjuywnkf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gtdodejryu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cashguo.top/Article/details/gtipfxtiik.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gtuwtwuwcn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtoietkdot.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtgokkzyex.html

[J08] 提取年月日与星期
来源：http://dali.vqdsnc.cn/Article/details/gtfoaictis.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hywenlv.cn/Article/details/gtkcudvegr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258888.top/Article/details/gtlutridkz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewrkhbaq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ivvv.top/Article/details/gtoglmezcx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.9152youxi.cn/Article/details/gtzzcrsvvl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gtmafbzqmx.html


<!-- 参考信息 -->