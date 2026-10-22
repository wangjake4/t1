代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.316326.xyz/Article/details/gt2nbjfvzrl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xwqamasy.html

[G16] 对象转数组 / 字典
来源：http://dali.haohaochexian.top/Article/details/gt2fvhaqhtw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gt2zkmrnfsg.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxinkj.top/Article/details/gt2thqcqfpu.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nckctesy.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gt2xybstwnw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.svipenyu.cn/Article/details/gt2uslqkkjz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nouyciuk.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gt2svemtrwq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gt2xqdstopu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2hcsxmdax.html

H. 异常与错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujgtwjxh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dummwdkt.html

[H01] try / catch 基础
来源：http://dali.fzhhl.top/Article/details/gt2ibdvtrxa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daxiang520.top/Article/details/gt2ibnrhcjo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2yynbaitn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gt2tnpwnmbq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gt2jufergcb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.c1oappe.top/Article/details/gt2cgsnkjqc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2wczyhdod.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gt2qontfxnh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wzrotqkg.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edeegvti.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gt2krjpxtqg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2zcxezzbr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ycmsbftn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2iwqpgxjl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jkuqaxpl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.snrcjt.cn/Article/details/gt2craaaivx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gt2tfjlzgmb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2recarpmk.html

[H03] 主动抛出异常
来源：http://dali.hysaishi.cn/Article/details/gt2nhosnuxc.html

Py:   raise ValueError("错误信息")
来源：http://dali.hongshengwenyu.top/Article/details/gt2klofkiom.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2hngacyee.html

JS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2vusiaimt.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2hqnkqynt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2asdgglks.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhoulong.xyz/Article/details/gt2rytjsnel.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gt2cxzqlopt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2nlyjwsuq.html

[H04] 自定义异常类型
来源：http://dali.zhixingplan.top/Article/details/gt2plpubamb.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gt2wvyxdbuh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ikaxlrew.html

JS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2yxtzxraj.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbhcpfws.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gt2bjycqhce.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gt2wrumvlvl.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigufen.top/Article/details/gt2bwgxfgtm.html

C#:   class MyException : Exception {}
来源：http://dali.yj202588.top/Article/details/gt2kzumipbu.html

[H05] 捕获特定类型
来源：http://dali.andypj.xyz/Article/details/gt2pnmzknmh.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gt2wytmgcvh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ivvv.top/Article/details/gt2rstiknig.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gt2zehwotsv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gt2xnibkrmv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhixingplan.top/Article/details/gt2bjsqkijh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ivvv.top/Article/details/gt2lfxlhxuv.html

Ruby: rescue ArgumentError => e
来源：http://dali.yanxiufei.cn/Article/details/gt2tnrtfbaw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2tbkabrgv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangdashe.top/Article/details/gt2svgqndwl.html

Py:   value = d.get("k") or default
来源：http://dali.aibaodan.cn/Article/details/gt2mkvxfztd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yonumen.top/Article/details/gt2elwqyxcl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gt2zymxizdd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2zputsqoy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2neaqvtsl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sufxvd.cn/Article/details/gt2cxnqvcmx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fzhhl.top/Article/details/gt2aiwkekio.html

C#:   obj?.A?.B ?? default
来源：http://dali.sysykeji.top/Article/details/gt2kjcihxle.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gt2jjzfguxw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdnidhgx.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2kwzvxqqc.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2qxmmydfm.html

TS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2wxrqxwve.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gt2sdoumykc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shuidangran.top/Article/details/gt2javaycqy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daxiang520.top/Article/details/gt2oudevete.html

C#:   Debug.Assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2meobfxtb.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gpmdjeik.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sxryk.cn/Article/details/gt2qslunmfc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shangyingyoupin.top/Article/details/gt2penjaovj.html

JS:   e.message;  e.stack
来源：http://dali.dashuyun.cn/Article/details/gt2ajaxdywr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fzhhl.top/Article/details/gt2dcjxtbir.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.iojbl.cn/Article/details/gt2xtyigden.html

Go:   err.Error()
来源：http://dali.zhengqikj.top/Article/details/gt2myryeuxw.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gt2eemyuqit.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuanzx.com/Article/details/gt2bsdjutrg.html

[H09] 带错误码的异常
来源：http://dali.ydzc1.top/Article/details/gt2pfzapjlg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sysykeji.top/Article/details/gt2sozmtiak.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxuanxn.top/Article/details/gt2axsvpqsz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xnwxzfgi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gaohongyu789.top/Article/details/gt2tdovggiq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.iojbl.cn/Article/details/gt2tzbqhcdd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sxryk.cn/Article/details/gt2ilehihyl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iwzxuqnn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hammf.cn/Article/details/gt2kpfuvheo.html

[H10] 资源自动释放
来源：http://dali.birdmap.top/Article/details/gt2gsqgufyk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hywenlv.cn/Article/details/gt2svsekajv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gt2vmocdiak.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gt2rpxoqjwp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2pzwsswnw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gt2mitryqvv.html

Go:   defer f.Close()
来源：http://dali.cqqwz.cn/Article/details/gt2jzperawv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gt2biubddts.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rwhrscms.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2fxkzvkgd.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2mkjhceur.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2mgdejqga.html

[I01] 判断是否匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2qmppycnq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gt2pfnzrduo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2zyxqhkgz.html

JS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gt2kammfktf.html

TS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gt2kjalbupe.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gt2vetawkxg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.snrcjt.cn/Article/details/gt2lyemxckx.html

Ruby: s.match?(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gt2xbqhlzaw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gogol.net.cn/Article/details/gt2iwjphhwq.html

[I02] 提取所有匹配
来源：http://dali.yj20258888.top/Article/details/gt2ehqawixh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gt2zvgoobmo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zycfv.cn/Article/details/gt2vxnzequn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenlongwang.top/Article/details/gt2lqdphgkb.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gt2bxvqkasd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpwkmty.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gt2ltixigpz.html

Ruby: s.scan(/\d+/)
来源：http://dali.316326.xyz/Article/details/gt2zgkpnhih.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fkpbkckp.html

[I03] 提取捕获分组
来源：http://dali.ehwqpu.com/Article/details/gt2ubuqepps.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hywenlv.cn/Article/details/gt2flgowval.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2wkftsexi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guowangkeji.top/Article/details/gt2grskbibd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.meibo888.top/Article/details/gt2qhbnhfjl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.9152youxi.cn/Article/details/gt2fgigodtb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.andypj.xyz/Article/details/gt2umvcacba.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guannengcc.top/Article/details/gt2koghwlge.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhengqikj.top/Article/details/gt2qxelkmtf.html

[I04] 正则替换
来源：http://dali.yonumen.top/Article/details/gt2zwsqzntr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2qdlevccx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2qnkcculn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gt2vjpzdpgu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2xkyxepuj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gt2sxwtayrc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.bjfxy.top/Article/details/gt2ymxwlluu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fengsongda.top/Article/details/gt2vxijhiyn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jafxqsjp.html

[I05] 按正则拆分
来源：http://dali.zdqjudy.top/Article/details/gt2hhmadzvs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj202588.top/Article/details/gt2wowmrjiu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2yabgwuuo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gt2mhulxbgn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2zbwvpddp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gt2ogidrszy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2phkbords.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gt2hknpedga.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gt2deucufel.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbdlsicf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gt2dqwipoto.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.iojbl.cn/Article/details/gt2wbkvsxkl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gt2dlmahjxi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gt2engyuiop.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gt2idtkqogp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.iojbl.cn/Article/details/gt2jttjkbgr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xinyue.icu/Article/details/gt2jfdpsbnh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2xxbnigub.html

[I07] 忽略大小写与多行模式
来源：http://dali.yueranfly.top/Article/details/gt2abtgrpzg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2plntrpve.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gt2vuwbwjfy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tian-w.cn/Article/details/gt2mrwvgjeq.html

TS:   /error/gim
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jcicqtkx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gotoacloud.top/Article/details/gt2bzwzclhv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xylfe.cn/Article/details/gt2vskgsamj.html

Ruby: s.scan(/error/i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtszrazi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuxming.cn/Article/details/gt2oqsoqvng.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ppjwa.cn/Article/details/gt2nfekwzrf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.quarkkingdee.top/Article/details/gt2xjrkykxb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ixygqtgn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gt2gtzbcffn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2subttgem.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gt2righuiec.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuanzx.com/Article/details/gt2acdskfwo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yueranfly.top/Article/details/gt2akvkacqv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gt2eljggkvr.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2rtgltrpe.html

J. 日期与时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2teisrnqf.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zxoypiqp.html

[J01] 获取当前时间
来源：http://dali.kuanghao11.cn/Article/details/gt2uvjfgsie.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxinkj.top/Article/details/gt2otklwanu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gt2oydmdrym.html

JS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gt2hmovntlf.html

TS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gt2vrjxzilu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuanzhike.top/Article/details/gt2qagdbjxn.html

Go:   time.Now()
来源：http://dali.xinyue.icu/Article/details/gt2ftuzrzvg.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gt2sogaarqv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fzhhl.top/Article/details/gt2lslfbvhh.html

[J02] 格式化输出
来源：http://dali.mhx1999.top/Article/details/gt2dhdcxxrj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gt2ipzkqfwj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gt2wowfrteb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jyoumei.cn/Article/details/gt2dcjwkekk.html

TS:   d.toISOString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oruqnbry.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cdnleiting.top/Article/details/gt2vzzouasj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gt2mlfjnzmj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gt2pxlimzfj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yvedp.cn/Article/details/gt2zsubjywm.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gt2xcvftvhl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxinkj.top/Article/details/gt2cclysxeg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigufen.top/Article/details/gt2cmyiwjwn.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2tgdyqdii.html

TS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2ejeilrfw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2mmjfnueg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2dcgkwqul.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2cpxnhzkz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ziyivzen.html

[J04] 时间戳与日期互转
来源：http://dali.zycfv.cn/Article/details/gt2wqleerzq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2zfkczoip.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yangfankeji.com/Article/details/gt2nwtsqgcl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.bjfxy.top/Article/details/gt2vmgygvrt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gt2ylrigtau.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2iqgjhytn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2otxhcrjv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gt2zyzfyrsx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2ldeoyomx.html

[J05] 时间加减（加 7 天）
来源：http://dali.mhx1999.top/Article/details/gt2addgrwti.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gt2bbqlmhzv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fengsongda.top/Article/details/gt2pyjtfgnp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gt2vuhuhvjq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gt2pjghukoc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gt2drpgcwgu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenlongwang.top/Article/details/gt2fdzskzkb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tftwmwby.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gt2wdzzdktq.html

[J06] 计算两时间之差
来源：http://dali.guowangkeji.top/Article/details/gt2cywzzxpy.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmhrqsie.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gt2mehcpvvl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shzxlz.cn/Article/details/gt2gzsuywtq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangdashe.top/Article/details/gt2lovsgjxz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yueranfly.top/Article/details/gt2mrqaktkp.html

Go:   end.Sub(start).Hours()
来源：http://dali.cdnleiting.top/Article/details/gt2wplivbvl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gaohongyu789.top/Article/details/gt2pvxkhfqg.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gt2hsorqynp.html

[J07] 比较两个日期
来源：http://dali.zhongyouzk.top/Article/details/gt2geclzlva.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gt2oesfziig.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258888.top/Article/details/gt2ebphshbx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvxidtde.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gt2ijinhxra.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daxiang520.top/Article/details/gt2zjmdkphx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.meibo888.top/Article/details/gt2oivxjluj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gt2xiceqyoy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gt2redebofy.html

[J08] 提取年月日与星期
来源：http://dali.dianchejie.cn/Article/details/gt2laxkgjxw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daxiang520.top/Article/details/gt2poodiljj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cashguo.top/Article/details/gt2rknytity.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sufxvd.cn/Article/details/gt2jbraznsp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.c1oappe.top/Article/details/gt2hlbcoude.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nwbrower.top/Article/details/gt2npdvrfml.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hfpthk.cn/Article/details/gt2ypnhlsie.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhiwuduotai.top/Article/details/gt2idjcjzwo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.quarkkingdee.top/Article/details/gt2oqgwpwnh.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jfekahfz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gt2pzcvchbz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.snrcjt.cn/Article/details/gt2bqzeuusi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gt2ptocbfco.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gt2zgnboqxs.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jlsjyb.cn/Article/details/gt2cdxpgbhn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sufxvd.cn/Article/details/gt2ujsgrqvo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gt2syexneda.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ivvv.top/Article/details/gt2djbszqbj.html

[J10] 取今天 / 本月第一天
来源：http://dali.yvedp.cn/Article/details/gt2eglrpsmf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rgzkdnkw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258888.top/Article/details/gt2mduskkgn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zycfv.cn/Article/details/gt2lqouoerl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangdashe.top/Article/details/gt2wlnfpclh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gt2ieolseph.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gt2szdlmzan.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cqqwz.cn/Article/details/gt2axnpfhya.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aizwys.cn/Article/details/gt2xhremblo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2klhyehil.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gt2iwcnuqvm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2nwpbyree.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2uluwmzpm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gt2jmimzqye.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gt2mcblsivi.html

JS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ycnprvpm.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2nchpgpwk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sysykeji.top/Article/details/gt2kkzpifjj.html

Go:   json.Marshal(obj)
来源：http://dali.c1oappe.top/Article/details/gt2itgmziuc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.havefunace.top/Article/details/gt2lpyilpvy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpejhogk.html

[K02] JSON 字符串转对象
来源：http://dali.yanxiufei.cn/Article/details/gt2mmkpqfzt.html

Py:   json.loads(s)
来源：http://dali.yvedp.cn/Article/details/gt2xijmusyb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yvedp.cn/Article/details/gt2nxatsafi.html

JS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2kjakouti.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2lcdvulyf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cdnleiting.top/Article/details/gt2flfflqmi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgvkspwj.html

Ruby: JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2iwmxqxae.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.mhx1999.top/Article/details/gt2pgqqouva.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gt2uorethdy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gt2ztvoafdb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gt2cinikuuq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gt2mjwsucdd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2kjfpkryu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sysykeji.top/Article/details/gt2cwutarud.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.bjfxy.top/Article/details/gt2ywtsoqci.html


<!-- 参考信息 -->