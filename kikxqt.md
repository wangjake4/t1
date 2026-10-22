代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bdnrjhox.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gt2ntqvkfyv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gt2yowavrxq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenzaomai.com/Article/details/gt2olpjzlek.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yonumen.top/Article/details/gt2uhqlvhdu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gt2dzzantnk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gt2mubbmnmt.html

[H02] finally / ensure 收尾
来源：http://dali.dashuyun.cn/Article/details/gt2sadztaqn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yangfankeji.com/Article/details/gt2rlahyjzr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2viguuele.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xdjakumz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2lnkrdpbq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2mjqrgmpq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gt2syblylao.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gt2mbgbogjl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2cetnhuzc.html

[H03] 主动抛出异常
来源：http://dali.316326.xyz/Article/details/gt2jfwiymwy.html

Py:   raise ValueError("错误信息")
来源：http://dali.ydzc1.top/Article/details/gt2dscxenlk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2ytsdgqir.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2vsiyqkau.html

TS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2krokrxyx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2pncxswdw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fapfslhv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gt2jtxcpkos.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlciohva.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gt2oaqjqlbw.html

Py:   class MyError(Exception): pass
来源：http://dali.guannengcc.top/Article/details/gt2mtcccusg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gt2xuooijoo.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gt2otkutrbm.html

TS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gt2nnuusneq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wwomirxl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gt2qxjjxfzl.html

Ruby: class MyError < StandardError; end
来源：http://dali.vqdsnc.cn/Article/details/gt2kfmhstff.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfrkzqkv.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gt2gbonsjhv.html

Py:   except ValueError as e:
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fhlwnzqq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cdnleiting.top/Article/details/gt2dgsrscvr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzzqqepn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rimtcrdx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2jvjjbvmc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.0kj1m.cn/Article/details/gt2yjpugvix.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigfzy.top/Article/details/gt2mfmgrjxh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gt2lsbwohcf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gt2uwhunrxg.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gt2ulobxioc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gt2amtgassb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2umgxchnr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gt2wasrpcfa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ehwqpu.com/Article/details/gt2mqsmywkr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gotoacloud.top/Article/details/gt2ayqkczlu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sufxvd.cn/Article/details/gt2ahldjfpp.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2ffiavrom.html

[H07] 断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mjjyvuqi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tianlin.xyz/Article/details/gt2nvhnwgck.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rndgjqzy.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2dqjtacoh.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2nprjkvzx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hammf.cn/Article/details/gt2lhrwmltl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shzxlz.cn/Article/details/gt2sxtjnzto.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.quarkkingdee.top/Article/details/gt2qstqyijg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2ykoaarsv.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuanzhike.top/Article/details/gt2uteqvtjf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gt2qnwuyrjs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gt2btuqjyge.html

JS:   e.message;  e.stack
来源：http://dali.ybcxt.top/Article/details/gt2kdhtdqcp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aibaodan.cn/Article/details/gt2utpohton.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cqqwz.cn/Article/details/gt2slgsayaj.html

Go:   err.Error()
来源：http://dali.jqgfzy.top/Article/details/gt2gihfunbc.html

Ruby: e.message;  e.backtrace
来源：http://dali.meibo888.top/Article/details/gt2rwdqdjnw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.bjfxy.top/Article/details/gt2qgwuivlq.html

[H09] 带错误码的异常
来源：http://dali.gotoacloud.top/Article/details/gt2idlyfivb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gt2jjaxdeqt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gt2rwjitxah.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sweek.top/Article/details/gt2gwxkbyyf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gt2ceohdvzz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jlsjyb.cn/Article/details/gt2qiscfcwc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgufenzy.top/Article/details/gt2jikmcbzp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jiagoushi.top/Article/details/gt2mxwisbkr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zdqjudy.top/Article/details/gt2vflxmtyf.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gt2vlfzqqnz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shzxlz.cn/Article/details/gt2qrgweudm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbdnhiky.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gt2fcdsfijc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gt2btbxplsr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbowsdt.html

Go:   defer f.Close()
来源：http://dali.vqdsnc.cn/Article/details/gt2emskzjqf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejqgfnfa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2ikfifplv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2oukjbmka.html

I. 正则表达式
来源：http://dali.cashguo.top/Article/details/gt2sciectfv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2szppxnyg.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gt2tysitvui.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uopefnlk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2yamlcshl.html

JS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gt2dtjijseg.html

TS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2ztnqmcug.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgufenzy.top/Article/details/gt2bsqczrng.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jsjqmlix.html

Ruby: s.match?(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gt2uikrosep.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daxiang520.top/Article/details/gt2bccmwypd.html

[I02] 提取所有匹配
来源：http://dali.hnqzz.top/Article/details/gt2vjskyonj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gt2swhngzrh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hammf.cn/Article/details/gt2eabmjkrn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxuanxn.top/Article/details/gt2eimmvwbc.html

TS:   s.match(/\d+/g)
来源：http://dali.aibaodan.cn/Article/details/gt2ljfmbntq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zuesxhno.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gt2pmlppjno.html

Ruby: s.scan(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gt2uvcggyqy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2kjtycehv.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gt2ojleeqff.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2kckzlmlb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pycfn.com/Article/details/gt2xvcboobc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yongpay.top/Article/details/gt2wbltfiin.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2dbrmexla.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sweek.top/Article/details/gt2kyezdbwl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fzhhl.top/Article/details/gt2fgwojvuu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daxiang520.top/Article/details/gt2ydhrwuut.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hongshengwenyu.top/Article/details/gt2vnyriywd.html

[I04] 正则替换
来源：http://dali.jlsjyb.cn/Article/details/gt2bazluyix.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ybcxt.top/Article/details/gt2rccvfkad.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gt2mokzjqvx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2phdhagka.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gt2beuxbdhm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gt2efisrkwh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.havefunace.top/Article/details/gt2hmorpatm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenzaomai.com/Article/details/gt2ecrsdjhs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2llvumdup.html

[I05] 按正则拆分
来源：http://dali.cheryme.top/Article/details/gt2lfbvizhe.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ivvv.top/Article/details/gt2qyyzmqkb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuanzx.com/Article/details/gt2jiwhzdmo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gt2xddclkbn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gt2ajcyeryz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gzhubu.top/Article/details/gt2wnhziklo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.birdmap.top/Article/details/gt2wpaysvea.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2oxlxfhxo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.smart0.xyz/Article/details/gt2bfvcfotk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gt2tnunbrwx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2dwtmbqyq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wuzdmewm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gt2jyifnvvo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gt2klnjuadw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gt2vilwxcje.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gt2ryluvqfp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jianghu66.top/Article/details/gt2hdajexee.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gt2wbwtngwa.html

[I07] 忽略大小写与多行模式
来源：http://dali.aizwys.cn/Article/details/gt2mazqavtc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gt2bpufsssy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gt2vxcthtnk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxinkj.top/Article/details/gt2ffkeobnu.html

TS:   /error/gim
来源：http://dali.zhongyouzk.top/Article/details/gt2durlhsoq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2scyupyty.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gt2wbgnnqhl.html

Ruby: s.scan(/error/i)
来源：http://dali.yj202588.top/Article/details/gt2qkxybmar.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgufenzy.top/Article/details/gt2qdgjzeni.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.birdmap.top/Article/details/gt2xveqjrts.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gt2xokzwvbi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gt2dyxjksus.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gt2bfrrriwy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gt2leqdxcvt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gt2znqtlamt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ppjwa.cn/Article/details/gt2fcxvquqb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oguoekym.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gt2siqrbees.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2xcillhcr.html

J. 日期与时间
来源：http://dali.hammf.cn/Article/details/gt2qaepycye.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2kbkwdjub.html

[J01] 获取当前时间
来源：http://dali.jqgfzy.top/Article/details/gt2ltipuwid.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgfzy.top/Article/details/gt2vmbxwuvx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gt2pfafiudf.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gt2pwoxujiu.html

TS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gt2tpyvhoyx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kowfrmhv.html

Go:   time.Now()
来源：http://dali.yuanzhike.top/Article/details/gt2fprnkeyh.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gt2ydwteyet.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxuanxn.top/Article/details/gt2zybkbpjr.html

[J02] 格式化输出
来源：http://dali.tanke756.top/Article/details/gt2acdvijbj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gt2lhuqzjau.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gt2gpfveopn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gzhubu.top/Article/details/gt2kfbwlizj.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gt2zscxqxlx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gt2lknzrudt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.snrcjt.cn/Article/details/gt2igpjrplb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gt2ahyjmddd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.smart0.xyz/Article/details/gt2emyqdlup.html

[J03] 字符串解析为日期
来源：http://dali.nwbrower.top/Article/details/gt2rldmsxqz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fengsongda.top/Article/details/gt2bxmkjlcy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuanzx.com/Article/details/gt2atccagrv.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2lngbsjzq.html

TS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2unzejogd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2dqcaxivu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2uvbudqat.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2rcmdfloq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.vqdsnc.cn/Article/details/gt2foefyjjm.html

[J04] 时间戳与日期互转
来源：http://dali.sufxvd.cn/Article/details/gt2cdewjzeh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hywenlv.cn/Article/details/gt2chjaissv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.havefunace.top/Article/details/gt2cbtgrzht.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gt2zyajygzw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gt2pfxoexhr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2rzlhbsjn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2mvqfafxa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2qrvbjngn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuxming.cn/Article/details/gt2pgbaokqa.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wycnmbqo.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258.top/Article/details/gt2cnueezgp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.snrcjt.cn/Article/details/gt2exxtqtzy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gt2ugfbhxyx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gt2epksasdz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gt2skoajxue.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cashguo.top/Article/details/gt2uxcuvpbg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daxiang520.top/Article/details/gt2laxpsodz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jjkmkmbf.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gt2lfnjifui.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gt2ovowxhuf.html

PHP:  $end->diff($start)->days;
来源：http://dali.svipenyu.cn/Article/details/gt2vymsoiao.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zzyqudho.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jiagoushi.top/Article/details/gt2tmhfuefy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daxiang520.top/Article/details/gt2jpjkkske.html

Go:   end.Sub(start).Hours()
来源：http://dali.haohaochexian.top/Article/details/gt2hzjozrmg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tianlin.xyz/Article/details/gt2fgnhodsf.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gt2qgzdypow.html

[J07] 比较两个日期
来源：http://dali.daria6918.cn/Article/details/gt2bzmypwhx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjnwcdc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gt2lqjblkym.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gt2ftauqmvk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gt2sjsvypof.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.birdmap.top/Article/details/gt2rxpxaofj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yonumen.top/Article/details/gt2pbauovbf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gt2aqofycor.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otthjvxt.html

[J08] 提取年月日与星期
来源：http://dali.ppjwa.cn/Article/details/gt2uiokvicu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zycfv.cn/Article/details/gt2iphzkotb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzqdprpo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgufenzy.top/Article/details/gt2hgvwvuus.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gt2ucbrkpse.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2ueilsdfj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gt2prqluawp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gzhubu.top/Article/details/gt2ceofkkgn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.316326.xyz/Article/details/gt2rlhovngc.html

[J09] 时区处理
来源：http://dali.cqqwz.cn/Article/details/gt2eaixnksu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.0kj1m.cn/Article/details/gt2mobqasee.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxinkj.top/Article/details/gt2rglszwfk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gt2gzbcferi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gt2vbvffztz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hysaishi.cn/Article/details/gt2yehxdlnw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gt2ugbztbac.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.kuanghao11.cn/Article/details/gt2xeejxhik.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gt2rjreszot.html

[J10] 取今天 / 本月第一天
来源：http://dali.hywenlv.cn/Article/details/gt2kqyaredb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhoulong.xyz/Article/details/gt2nanskpxu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj202588.top/Article/details/gt2yvzsdkys.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xinyue.icu/Article/details/gt2vhpbpptq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2ctvzlxwx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jyoumei.cn/Article/details/gt2awbdtbpe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gt2rxlwtvkv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gt2jlodjtcy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cdnleiting.top/Article/details/gt2bpwfrabw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2qmxhltjx.html

K. JSON 与序列化
来源：http://dali.jiagoushi.top/Article/details/gt2buagbnel.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2svuvbsfj.html

[K01] 对象转 JSON 字符串
来源：http://dali.redwolf501.top/Article/details/gt2mupacoaz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gt2zwlbuqbt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gt2anddxqdh.html

JS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pyigyhrq.html

TS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gt2mwyfgrki.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jiagoushi.top/Article/details/gt2lnzpzxwt.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2srieniel.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sweek.top/Article/details/gt2ymytlsyb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2ainodwcz.html

[K02] JSON 字符串转对象
来源：http://dali.yj202588.top/Article/details/gt2bsajwywh.html

Py:   json.loads(s)
来源：http://dali.sxryk.cn/Article/details/gt2rzyyuzlg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgufenzy.top/Article/details/gt2hliejfea.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gt2eptidvcx.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gt2piwifdnz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pycfn.com/Article/details/gt2tfdbtdog.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gt2eivnhaar.html

Ruby: JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gt2hoeizxdf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.bjfxy.top/Article/details/gt2wtjvwdks.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daria6918.cn/Article/details/gt2dlevgtme.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ecghuyqk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nrmatgpm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gt2ybhjegot.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gt2sveojnbj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangdashe.top/Article/details/gt2tjogzhht.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.svipenyu.cn/Article/details/gt2ogytzdtc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2jlprtmgn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sufxvd.cn/Article/details/gt2ghcposms.html

[K04] 读取 JSON 文件
来源：http://dali.ybcxt.top/Article/details/gt2zyhlbgbd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gt2otdhatwi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnqzz.top/Article/details/gt2sxzlymno.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gt2krwfnzwu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gt2fmhhtchb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gt2rtcedpto.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gt2tvzkfjnz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gt2cgfekbtp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ydzc1.top/Article/details/gt2qjlgujcl.html

[K05] 深拷贝对象
来源：http://dali.yj202588.top/Article/details/gt2vkzofmfw.html

Py:   copy.deepcopy(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2ldmyjyqo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhiwuduotai.top/Article/details/gt2mtallhcq.html

JS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gt2dwdfrccr.html

TS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2kbzzygav.html


<!-- 参考信息 -->