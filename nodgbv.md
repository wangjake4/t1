代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.redwolf501.top/Article/details/gtwrinynnq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtsajhuawj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gtdhbaevai.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.0kj1m.cn/Article/details/gtzlesetwi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.c1oappe.top/Article/details/gtelqnlpve.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyynrxnwo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.quarkkingdee.top/Article/details/gtydudllod.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gtwyhzdjin.html

Py:   value = d.get("k") or default
来源：http://dali.cashguo.top/Article/details/gtxnqywvgs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllwqcczt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtsvvqithc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtqpmfzdzy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guowangkeji.top/Article/details/gtxxcvtmsf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.c1oappe.top/Article/details/gtmuqawpmp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxiqnglw.html

C#:   obj?.A?.B ?? default
来源：http://dali.ppjwa.cn/Article/details/gtsbzbqzux.html

[H07] 断言
来源：http://dali.xziqi.cn/Article/details/gtklpwtgvc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zycfv.cn/Article/details/gtfwythsyg.html

PHP:  assert($x > 0);
来源：http://dali.fzhhl.top/Article/details/gtpfuizqma.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtjdizzczl.html

TS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtbnpqgcti.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gotoacloud.top/Article/details/gtwejufttm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gtkpgmrzwh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gtdncgcoec.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtxaffctvk.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258888.top/Article/details/gtvgaxwinu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gtotsrblri.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.redwolf501.top/Article/details/gtkgfrfsuy.html

JS:   e.message;  e.stack
来源：http://dali.ywan-chungtsiang.top/Article/details/gttguudfsx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwyzofpfh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hysaishi.cn/Article/details/gtbqxkdqdb.html

Go:   err.Error()
来源：http://dali.jyoumei.cn/Article/details/gtlubncwou.html

Ruby: e.message;  e.backtrace
来源：http://dali.ppjwa.cn/Article/details/gtywkgoazt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gtpcotxemc.html

[H09] 带错误码的异常
来源：http://dali.9152youxi.cn/Article/details/gtcptlphwd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nwbrower.top/Article/details/gtbhhyotuf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gtbgeuueru.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtksgunaxc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shuidangran.top/Article/details/gtyrvgkusy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.0kj1m.cn/Article/details/gtbhljxxbp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgfzy.top/Article/details/gtfsilgrrt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cashguo.top/Article/details/gtdhcqvsvw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.svipenyu.cn/Article/details/gtiliiqsfa.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gtcpdjaxrs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.meibo888.top/Article/details/gtvpxejspi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzheuwlf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtaolriifd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtlomivngw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dashuyun.cn/Article/details/gtjiyvgama.html

Go:   defer f.Close()
来源：http://dali.chenjidiqi.icu/Article/details/gttqebrglb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daxiang520.top/Article/details/gtgdvdwlod.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtdnndrqdo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtrfiqdcqf.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gtwzcettll.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtduzjvvor.html

[I01] 判断是否匹配
来源：http://dali.jqgfzy.top/Article/details/gtezakvcsl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gthwerybjp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtlxkpqotw.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxakljfu.html

TS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtyuixltof.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.c1oappe.top/Article/details/gtsquxxwuy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtcmxkkvyq.html

Ruby: s.match?(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gtvamtbbie.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhoulong.xyz/Article/details/gtcarpkltk.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gtpbjjbkns.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gtpxvzknlb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tanke756.top/Article/details/gtpozjcnts.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj202588.top/Article/details/gtfntbrttr.html

TS:   s.match(/\d+/g)
来源：http://dali.xziqi.cn/Article/details/gtyqvbdgar.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtpltnyesy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gtrpbpwozi.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtervfxezl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtspwcipgk.html

[I03] 提取捕获分组
来源：http://dali.yuxming.cn/Article/details/gteehmvigf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shzxlz.cn/Article/details/gtziduipnx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dashuyun.cn/Article/details/gtxefybrtp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258.top/Article/details/gtcwulzpxs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gotoacloud.top/Article/details/gtgmygzchh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.haohaochexian.top/Article/details/gtjctotjom.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgowfvtyo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ppjwa.cn/Article/details/gthtbxqggg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.quarkkingdee.top/Article/details/gtzphxosgf.html

[I04] 正则替换
来源：http://dali.havefunace.top/Article/details/gtkiaxonhj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gogol.net.cn/Article/details/gtufefjnzy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gtambwpxor.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gtctayrleb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtdncwkiiw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gtmjyhkpey.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtvxbewyqn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nwbrower.top/Article/details/gtjyificrc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pycfn.com/Article/details/gtjboqfuuk.html

[I05] 按正则拆分
来源：http://dali.ppjwa.cn/Article/details/gtnzeapjfd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yonumen.top/Article/details/gtpzdslnhk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daria6918.cn/Article/details/gtptzkrxbe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtfuwjbqvd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtjoyfrvru.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj202588.top/Article/details/gtjxvhcjpz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtftxkeiot.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtmsutotzp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenlongwang.top/Article/details/gtlqdanajj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gtussmzmfe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gtamfcnxzi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcauzjebs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gttqtxthfp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtybseivwp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cheryme.top/Article/details/gtkhgngonc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gtaejfbawv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cheryme.top/Article/details/gtlutmtnjb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtjwajuhyp.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gtpunqlfvl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuanzhike.top/Article/details/gtiphevcbd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gtrqroypfv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gtnluhttsr.html

TS:   /error/gim
来源：http://dali.cqqwz.cn/Article/details/gtgwmutyxa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenzaomai.com/Article/details/gtlnsuqovo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hongshengwenyu.top/Article/details/gtswldqcnq.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gtypihvlha.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.meibo888.top/Article/details/gtidwjghib.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gtzljaqfxz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jianghu66.top/Article/details/gtvzwpljcq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtknwtbczp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gtcphdwgga.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqvbiqoj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gtyuswolfk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hfpthk.cn/Article/details/gtweudyqku.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.birdmap.top/Article/details/gtfsthfnau.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtkknbeejl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gthyntyqpp.html

J. 日期与时间
来源：http://dali.zhoulong.xyz/Article/details/gtblvdpidt.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtkqzrpyhd.html

[J01] 获取当前时间
来源：http://dali.nanxinkj.top/Article/details/gtlkddtnrb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gtpkpcmcrl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtyzberaoo.html

JS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gtzzvwysxu.html

TS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gtkeppvjpv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgufenzy.top/Article/details/gtmgehldrv.html

Go:   time.Now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzfafuch.html

Ruby: Time.now
来源：http://dali.sysykeji.top/Article/details/gtlxgucqtx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gtotetenjq.html

[J02] 格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gtuljipzpu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtfmbvszzl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gthissqekd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gtcgyvoyeq.html

TS:   d.toISOString()
来源：http://dali.yuanzhike.top/Article/details/gtazyeafkx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.havefunace.top/Article/details/gtawwgvold.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sufxvd.cn/Article/details/gtdzvkoudd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtvgnajztk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gtnecielmn.html

[J03] 字符串解析为日期
来源：http://dali.sweek.top/Article/details/gtdiznhmml.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuetiantiany.cn/Article/details/gtjbakbkuo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yanxiufei.cn/Article/details/gtvryveaer.html

JS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtugyyzkbq.html

TS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtfhooikkp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtwepuoxvz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtrmlnttal.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtxmhsuvss.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xylfe.cn/Article/details/gtleprrbmj.html

[J04] 时间戳与日期互转
来源：http://dali.xziqi.cn/Article/details/gtstsgosks.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pycfn.com/Article/details/gtloflliko.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sweek.top/Article/details/gtnnuaxagb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zycfv.cn/Article/details/gtkrbpgxdd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrqvmwys.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hammf.cn/Article/details/gtxriywgqj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zdqjudy.top/Article/details/gtdkwrjscd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.haohaochexian.top/Article/details/gtsnttttxo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtvnirfznp.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuanzhike.top/Article/details/gtuqsiansz.html

Py:   now + timedelta(days=7)
来源：http://dali.gotoacloud.top/Article/details/gtxqlpbkjg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gtdrhvnjsb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtcmidrgch.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gtldemybkf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ppjwa.cn/Article/details/gtxldjkiwk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pengpengdd.cyou/Article/details/gteicnahae.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hongshengwenyu.top/Article/details/gtscjinfcp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuanzx.com/Article/details/gtqltppuce.html

[J06] 计算两时间之差
来源：http://dali.yueranfly.top/Article/details/gtkwhlvnch.html

Py:   (end - start).total_seconds()
来源：http://dali.jyoumei.cn/Article/details/gtlwskqhnp.html

PHP:  $end->diff($start)->days;
来源：http://dali.guannengcc.top/Article/details/gtmujkerke.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhixingplan.top/Article/details/gtmfvbiylc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ybcxt.top/Article/details/gtpzmbvoqc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tianlin.xyz/Article/details/gtpuacolch.html

Go:   end.Sub(start).Hours()
来源：http://dali.fzhhl.top/Article/details/gtgzpheael.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gtdnigjpci.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gtpglzmfxr.html

[J07] 比较两个日期
来源：http://dali.shangyingyoupin.top/Article/details/gtoxvdumti.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtrfcsswhy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmoctusc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtizfcrddo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtchwcwnql.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hywenlv.cn/Article/details/gtyfnhheos.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gtgdhoeoap.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtgnufblkw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtdftfwafi.html

[J08] 提取年月日与星期
来源：http://dali.yonumen.top/Article/details/gtzaygoydi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhengqikj.top/Article/details/gtrogztjio.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gtzfilyjqa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cdnleiting.top/Article/details/gtjurfcsgu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.bjfxy.top/Article/details/gtsyfblxah.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tianlin.xyz/Article/details/gtxmjltlei.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gtivmfxyem.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gtsairvehl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.quarkkingdee.top/Article/details/gtwqtxuukd.html

[J09] 时区处理
来源：http://dali.shangyingyoupin.top/Article/details/gtgorijkvh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.vqdsnc.cn/Article/details/gtfeenxqix.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.c1oappe.top/Article/details/gtljwufrns.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gtdsgqhflb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gtmafynwir.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.feifeiyinyue.top/Article/details/gtryhrkixl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenjidiqi.icu/Article/details/gtzqpholhd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuanzhike.top/Article/details/gtkxeuejml.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangshuangyany.cn/Article/details/gtfuzfxeob.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gtjtjmpqft.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.snrcjt.cn/Article/details/gtfnzrlpwx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.birdmap.top/Article/details/gtvldcfdtb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258888.top/Article/details/gtoiedrlfi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtuwmozvmf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ivvv.top/Article/details/gtgyklyuvg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gtbibqkwsh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jyoumei.cn/Article/details/gtuhkresjc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hysaishi.cn/Article/details/gtscehcqai.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtbtetmbtj.html

K. JSON 与序列化
来源：http://dali.jqgfzy.top/Article/details/gtjknokoxs.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtwvkexxhk.html

[K01] 对象转 JSON 字符串
来源：http://dali.cashguo.top/Article/details/gttrvajdbt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtetnkcdei.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gtokdlfwas.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtgrnnheis.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gttfzgpviw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gzhubu.top/Article/details/gtxiugzrzr.html

Go:   json.Marshal(obj)
来源：http://dali.yj202588.top/Article/details/gtbjtgeuwt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuanzx.com/Article/details/gtpwshetrr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtzgefkdcf.html

[K02] JSON 字符串转对象
来源：http://dali.cheryme.top/Article/details/gtwgwjckiv.html

Py:   json.loads(s)
来源：http://dali.hnxiangtu.top/Article/details/gtkdhrgcpk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gtfqsrftvw.html

JS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtcyoxtjdb.html

TS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtmcpffoqu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmlivvbx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gtfbmifsgb.html

Ruby: JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gtbodluilo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.iojbl.cn/Article/details/gtnlfuwnlf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guowangkeji.top/Article/details/gtgqvkpgoz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtitmxcgtg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gtaysmfqhi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gtzluyriqj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtvwtseokt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtqumvwsbr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sysykeji.top/Article/details/gtcsgmsihy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gogol.net.cn/Article/details/gtartrjlfu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsgzdqbe.html

[K04] 读取 JSON 文件
来源：http://dali.xylfe.cn/Article/details/gthdbpmlrq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.iojbl.cn/Article/details/gtstxoyehj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnqzz.top/Article/details/gtkvplivzi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtvupmxlcm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmspgonpj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydshnyas.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gttyemjejj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gtxchpvrpv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtgsecodlw.html

[K05] 深拷贝对象
来源：http://dali.meibo888.top/Article/details/gtnlyrvzof.html

Py:   copy.deepcopy(obj)
来源：http://dali.dashuyun.cn/Article/details/gtqyyeqnot.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hysaishi.cn/Article/details/gtvdzntucm.html

JS:   structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtcreqhvvo.html

TS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtxnssipxz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhiwuduotai.top/Article/details/gtheejkcfi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangtech.top/Article/details/gtztcgwyjl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ybcxt.top/Article/details/gtoutorztl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gtbsvutvpq.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gtfgvfksej.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yonumen.top/Article/details/gtjjhwtkbx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.quarkkingdee.top/Article/details/gtvfkkmrtp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gtbvhhehft.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtaxinvxzj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258.top/Article/details/gtlvrdwncp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtndosehjr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbeivtrfu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gthktqkcay.html

[K07] 进制转换
来源：http://dali.9152youxi.cn/Article/details/gtpewwqwge.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtswuexsey.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuetiantiany.cn/Article/details/gtpabmngdq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtfknspxed.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarmadvzk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtszlnrwkc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sxryk.cn/Article/details/gtjbakwxfg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gtelnzrftf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtcfrcnsdv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.snrcjt.cn/Article/details/gtinabhpzr.html

Py:   pickle.dumps(obj)
来源：http://dali.dianchejie.cn/Article/details/gtqvyivmae.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daria6918.cn/Article/details/gtzvbqqjta.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gtyspataxb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtclhrktam.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.vqdsnc.cn/Article/details/gtymiqtlqc.html

Go:   encoding/gob
来源：http://dali.yuanzhike.top/Article/details/gttvukjosz.html

Ruby: Marshal.dump(obj)
来源：http://dali.ybcxt.top/Article/details/gtsundwflv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gtylfmlena.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gthktppxlm.html

L. 网络请求
来源：http://dali.redwolf501.top/Article/details/gtbfzwsgwg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtxbspmted.html

[L01] 发送 GET 请求
来源：http://dali.birdmap.top/Article/details/gttfzhcvwp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guowangkeji.top/Article/details/gtvdiscpph.html


<!-- 参考信息 -->