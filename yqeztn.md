代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ydzc1.top/Article/details/gt2xgaggeuz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2pzoiqmsz.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gt2dlefqyek.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.c1oappe.top/Article/details/gt2tpobkrpi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gt2vndfbaud.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gt2wzlrmbgm.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gt2ydkurjds.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cdnleiting.top/Article/details/gt2nrcizahq.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gt2fbmebmyl.html

JS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vvocjppz.html

TS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2iyhjywug.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gt2coyyojdm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oplfadzl.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gt2hcuftnyv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gt2punmiyzg.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2orjxcnsq.html

H. 异常与错误处理
来源：http://dali.ydzc1.top/Article/details/gt2bpbwisnr.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2ontfnsna.html

[H01] try / catch 基础
来源：http://dali.0kj1m.cn/Article/details/gt2socqusea.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.andypj.xyz/Article/details/gt2ffyxexzf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2nrbswlib.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gt2rqlaxtlr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gt2rrgdytec.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gt2mgaachzr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gt2pyzmbrri.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.redwolf501.top/Article/details/gt2naupsgkx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qdgyljea.html

[H02] finally / ensure 收尾
来源：http://dali.jqgfzy.top/Article/details/gt2tkvanjol.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cdnleiting.top/Article/details/gt2jjfluojg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2cexfxwik.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2qylvgjfi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2lycnvhww.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2nlzhotwq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gt2mjypacjc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifoyezrx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yudpmjrk.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dyjiwpcs.html

Py:   raise ValueError("错误信息")
来源：http://dali.yueranfly.top/Article/details/gt2omguwspf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2fppkfnxu.html

JS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2nvwhxpeh.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2stjuszvh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2pdzujpzv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gt2iccfzmhh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xziqi.cn/Article/details/gt2irjrjrui.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hcfcehwa.html

[H04] 自定义异常类型
来源：http://dali.tanke756.top/Article/details/gt2dlwhmbuc.html

Py:   class MyError(Exception): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qvokbkkw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gt2bkuzvihy.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gt2lzmddizx.html

TS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gt2migbbejf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gt2ztmiyiik.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pftyjspf.html

Ruby: class MyError < StandardError; end
来源：http://dali.aibaodan.cn/Article/details/gt2jivujsdw.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gt2xowaipnw.html

[H05] 捕获特定类型
来源：http://dali.yuanzhike.top/Article/details/gt2hfxeltku.html

Py:   except ValueError as e:
来源：http://dali.shuidangran.top/Article/details/gt2ajzvfecm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangdashe.top/Article/details/gt2osudrbti.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gt2kpbiujqs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctbropyc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.svipenyu.cn/Article/details/gt2igwedeqk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jiagoushi.top/Article/details/gt2djnpsfpg.html

Ruby: rescue ArgumentError => e
来源：http://dali.aizwys.cn/Article/details/gt2engsqtxb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2vpnuxrpg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwevofgt.html

Py:   value = d.get("k") or default
来源：http://dali.yuxming.cn/Article/details/gt2ymhdmkfe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gt2efcdrxin.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gt2szuspimi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cpelqkds.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigufen.top/Article/details/gt2xovxgbyy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gt2pxlfpqij.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenlongwang.top/Article/details/gt2ayuvzzle.html

C#:   obj?.A?.B ?? default
来源：http://dali.yvedp.cn/Article/details/gt2xccgxgfs.html

[H07] 断言
来源：http://dali.svipenyu.cn/Article/details/gt2jtkrdumo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gt2rzziutym.html

PHP:  assert($x > 0);
来源：http://dali.hammf.cn/Article/details/gt2hkhqmoui.html

JS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2zybrgljp.html

TS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqslikcm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gt2eqaippau.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gt2umhutjdn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gotoacloud.top/Article/details/gt2xagxzgmz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tilweufz.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gt2wkcnibtf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iykcsrmt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnqzz.top/Article/details/gt2gbifvxxk.html

JS:   e.message;  e.stack
来源：http://dali.sxryk.cn/Article/details/gt2vurxflbg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gt2fridmaom.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhoulong.xyz/Article/details/gt2npmsqarr.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gt2uvafajvx.html

Ruby: e.message;  e.backtrace
来源：http://dali.xziqi.cn/Article/details/gt2imvhkppi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ehwqpu.com/Article/details/gt2ugoyeaps.html

[H09] 带错误码的异常
来源：http://dali.redwolf501.top/Article/details/gt2krqamykf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258.top/Article/details/gt2seuaylsw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zycfv.cn/Article/details/gt2jzmwmqqb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnqzz.top/Article/details/gt2jxzayvho.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sysykeji.top/Article/details/gt2gwlywwha.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shzxlz.cn/Article/details/gt2jelqgudv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sxryk.cn/Article/details/gt2qanpynxc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hammf.cn/Article/details/gt2ccditnoj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daria6918.cn/Article/details/gt2fgajmkha.html

[H10] 资源自动释放
来源：http://dali.cdnleiting.top/Article/details/gt2ljpyecxi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shzxlz.cn/Article/details/gt2cvjfhjsf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jianghu66.top/Article/details/gt2ixtvuarb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gt2xydlaisk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gt2fzbxlxie.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shzxlz.cn/Article/details/gt2odfmskvd.html

Go:   defer f.Close()
来源：http://dali.c1oappe.top/Article/details/gt2jykfacac.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gt2kbmgqqtx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2nmlvgola.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2likegfyc.html

I. 正则表达式
来源：http://dali.9152youxi.cn/Article/details/gt2emmbvkzr.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2hhqsopuq.html

[I01] 判断是否匹配
来源：http://dali.zhengqikj.top/Article/details/gt2ffolwixr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2evbiviyb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jianghu66.top/Article/details/gt2zdawtpbk.html

JS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gt2eywvypwn.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gt2kjjnspeg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cashguo.top/Article/details/gt2mbkyfhyy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.316326.xyz/Article/details/gt2mipdoyuu.html

Ruby: s.match?(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gt2hgkovcbm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxgqbhzo.html

[I02] 提取所有匹配
来源：http://dali.ehwqpu.com/Article/details/gt2frdywcnp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gt2uonekbyg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmyehieb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gt2yynhkflq.html

TS:   s.match(/\d+/g)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hpqociwc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gt2jvowtggf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangdashe.top/Article/details/gt2zwodqfza.html

Ruby: s.scan(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gt2pabaotqm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xyfimmmj.html

[I03] 提取捕获分组
来源：http://dali.snrcjt.cn/Article/details/gt2nyjbdlud.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdeocfgx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.redwolf501.top/Article/details/gt2eqwamsdl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.smart0.xyz/Article/details/gt2cuomlegj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guannengcc.top/Article/details/gt2aktqiucg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pycfn.com/Article/details/gt2ipxkduyv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hywenlv.cn/Article/details/gt2dviittxa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258.top/Article/details/gt2zoyjknco.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yonumen.top/Article/details/gt2rrtraqcq.html

[I04] 正则替换
来源：http://dali.birdmap.top/Article/details/gt2btogqprz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2lkyjvwru.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gt2efyyuwea.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gt2tjyzmkym.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gt2opukyjve.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gt2ubyhiwtl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwxwzia.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2qhvdpcmu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.316326.xyz/Article/details/gt2hufcrwja.html

[I05] 按正则拆分
来源：http://dali.yuanzhike.top/Article/details/gt2crezffpd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fengsongda.top/Article/details/gt2vhklkmvy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2nsurkxtf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vfpzazcn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gt2pjxzqhpe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gt2nhvumyhh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2vbmlaace.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gt2dgqmadqq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tianlin.xyz/Article/details/gt2rmuthgtf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gt2wdzuufhr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gt2rfnbvigo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daxiang520.top/Article/details/gt2kfwaikes.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gt2eleesutz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gt2jvajrhpv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2dgfnemhd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.vqdsnc.cn/Article/details/gt2dwhxmuap.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ydzc1.top/Article/details/gt2ivngcguh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2clrcpshr.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gt2cfuzgwqj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigufen.top/Article/details/gt2mlsgqjvn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hammf.cn/Article/details/gt2chrxroft.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yvedp.cn/Article/details/gt2mhgvgzvk.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gt2axynyljg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nfnsvkdd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhixingplan.top/Article/details/gt2pgmraqwl.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gt2vdohkllt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2whsohqau.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2emgwmqfz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jianghu66.top/Article/details/gt2tqujapmi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gt2axlpaonh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hueftzap.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gt2vepgibmv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gt2vmszquye.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.c1oappe.top/Article/details/gt2jtdpocxh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mrudopua.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gt2xruujvul.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2zfbbhrqq.html

J. 日期与时间
来源：http://dali.zdqjudy.top/Article/details/gt2ieypsvmz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2sxunlrad.html

[J01] 获取当前时间
来源：http://dali.cheryme.top/Article/details/gt2ksotcoiv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shzxlz.cn/Article/details/gt2nkltfhca.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gt2rwmrxnht.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gt2gvnaakmn.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gt2mpluuykk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2gqpampwi.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gt2owddwhpq.html

Ruby: Time.now
来源：http://dali.tanke756.top/Article/details/gt2xwgdsnyo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zycfv.cn/Article/details/gt2puevyojt.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gt2fzmutnzb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gt2ariwwsbp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gt2rxrjtxiy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jlsjyb.cn/Article/details/gt2mfxwukmk.html

TS:   d.toISOString()
来源：http://dali.yvedp.cn/Article/details/gt2ghvksupf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.9152youxi.cn/Article/details/gt2aiqmhmup.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxuanxn.top/Article/details/gt2btpeilov.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gt2jgksiate.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yongpay.top/Article/details/gt2qzozrqan.html

[J03] 字符串解析为日期
来源：http://dali.zycfv.cn/Article/details/gt2nzeyoaly.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cvlbmdbj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.bjfxy.top/Article/details/gt2xplskhbm.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2vutbdnsg.html

TS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2oktialdd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2rvdhgduu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gt2zkmzblhx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vqgltxtg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.meibo888.top/Article/details/gt2jduqupds.html

[J04] 时间戳与日期互转
来源：http://dali.haohaochexian.top/Article/details/gt2ytxmjsos.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2nenxfpht.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gt2sprizwrc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guannengcc.top/Article/details/gt2zhdwmthn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yongpay.top/Article/details/gt2baneuqgi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwsjyegp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2aoawinbp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2grwxjbyo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gt2rtcyhtkb.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gt2lsfjiamg.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gt2stoxoevx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.9152youxi.cn/Article/details/gt2nifaadgo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gt2pwkrkmjx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvgakwjv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258888.top/Article/details/gt2wkunezhf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daria6918.cn/Article/details/gt2svspwomb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aizwys.cn/Article/details/gt2qwwkuzqq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gt2ikihfgqz.html

[J06] 计算两时间之差
来源：http://dali.gogol.net.cn/Article/details/gt2mrrdskgq.html

Py:   (end - start).total_seconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zhxqooay.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pcdvmhmm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hywenlv.cn/Article/details/gt2khjrkynv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dashuyun.cn/Article/details/gt2bqykvrhu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yueranfly.top/Article/details/gt2dlhsffyn.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gt2uiiliold.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gt2bqddhqhk.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gt2gxsmrhoh.html

[J07] 比较两个日期
来源：http://dali.gaohongyu789.top/Article/details/gt2exkzyrmw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gt2dtrcaplo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sysykeji.top/Article/details/gt2tgelaxqx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gt2jbbrdqhs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gt2ejdojlad.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuxming.cn/Article/details/gt2tdrivfcq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yhqcbcib.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2iuofsjjw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2zopuswep.html

[J08] 提取年月日与星期
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sklgmveo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zycfv.cn/Article/details/gt2lsfigtfx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gt2jdboiyjf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangdashe.top/Article/details/gt2roiqxrim.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.quarkkingdee.top/Article/details/gt2otescgqq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gt2lijkuxlt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gt2ckglmrgx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangshuangyany.cn/Article/details/gt2ftxnceyr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pjvqjjhz.html

[J09] 时区处理
来源：http://dali.daria6918.cn/Article/details/gt2hfaangwl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2howlixel.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2noxesrdi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gt2tojuibqn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gt2utwavpxk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ehwqpu.com/Article/details/gt2hznbkcny.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gt2putlrmjl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guowangkeji.top/Article/details/gt2eziahiio.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xylfe.cn/Article/details/gt2szochjpu.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gt2dymoflzv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yanxiufei.cn/Article/details/gt2bgemkjfw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xylfe.cn/Article/details/gt2ouhujoyd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj202588.top/Article/details/gt2zfithupx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.redwolf501.top/Article/details/gt2jelnaziw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2hjqkbpto.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tian-w.cn/Article/details/gt2kupyzjlh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daxiang520.top/Article/details/gt2rottnxux.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fzhhl.top/Article/details/gt2tmefyuom.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2bjoyybau.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gt2jrouixma.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2pdsivyhr.html

[K01] 对象转 JSON 字符串
来源：http://dali.svipenyu.cn/Article/details/gt2bjmhehsd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gt2wiottqep.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gt2masdobli.html

JS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gt2fldwxduq.html

TS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dcjmkqsj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuanzx.com/Article/details/gt2cmpchuou.html

Go:   json.Marshal(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2txbosnsb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fzhhl.top/Article/details/gt2vvbuftsa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2okschvyx.html

[K02] JSON 字符串转对象
来源：http://dali.jqgufenzy.top/Article/details/gt2zmjnletq.html

Py:   json.loads(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqhryxxz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kitpbynt.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pabkswuq.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gt2epqnpfbv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2reuqfbqz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gt2gjryfvlp.html

Ruby: JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gt2afhswoyt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigufen.top/Article/details/gt2pmpgjsfl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djhsunbe.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gt2njbdlwap.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gt2qwrqrglv.html


<!-- 参考信息 -->