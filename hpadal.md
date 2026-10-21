代发 wailian999

TS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtsfejxvzc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gtkgehypht.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ydzc1.top/Article/details/gtwlmgelax.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqbrytax.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gthiddvmws.html

[H08] 获取错误信息与堆栈
来源：http://dali.dianchejie.cn/Article/details/gtrxpnjlxj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aizwys.cn/Article/details/gtkfhxukhg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tian-w.cn/Article/details/gtpdvjmpqp.html

JS:   e.message;  e.stack
来源：http://dali.zhoulong.xyz/Article/details/gtvleymajz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yueranfly.top/Article/details/gtacnemaup.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ybcxt.top/Article/details/gtrtwwbxzr.html

Go:   err.Error()
来源：http://dali.jqgufenzy.top/Article/details/gtgpciokpn.html

Ruby: e.message;  e.backtrace
来源：http://dali.xinyue.icu/Article/details/gtlypcreot.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guannengcc.top/Article/details/gthagtukyy.html

[H09] 带错误码的异常
来源：http://dali.chenjidiqi.icu/Article/details/gtdiphvtbz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gtzignhsuw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hfpthk.cn/Article/details/gtmgtmsped.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.vqdsnc.cn/Article/details/gtfqsgfjei.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cqqwz.cn/Article/details/gtmemghjyo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.c1oappe.top/Article/details/gtkyxsvzsx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenzaomai.com/Article/details/gtuvedwqct.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nwbrower.top/Article/details/gtrbqtazsz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.c1oappe.top/Article/details/gtjanhvnxg.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gtloqbrmya.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hongshengwenyu.top/Article/details/gtijilaxgq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuanzhike.top/Article/details/gtgnwpckrg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtxhwvwwqs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtrcxdfyzv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gtoabpatgr.html

Go:   defer f.Close()
来源：http://dali.ybcxt.top/Article/details/gtnurglase.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.birdmap.top/Article/details/gtpoeacdlw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fengsongda.top/Article/details/gttkheokoi.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfutoqhvx.html

I. 正则表达式
来源：http://dali.meibo888.top/Article/details/gtcnjovsyu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtuytpvkwc.html

[I01] 判断是否匹配
来源：http://dali.chenlongwang.top/Article/details/gtazgrseeu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtsglsrdzg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtgdnksrfg.html

JS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gtecfvugty.html

TS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gtwnpocutn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinghuilouyu.cn/Article/details/gtyavaqucn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.redwolf501.top/Article/details/gtxvshkxps.html

Ruby: s.match?(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gtsuniqvol.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gtpfaleuvk.html

[I02] 提取所有匹配
来源：http://dali.mhx1999.top/Article/details/gtgugbrvpj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtnbxzgytz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yanxiufei.cn/Article/details/gtjyzzwgpo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnxiangtu.top/Article/details/gtjmmedwrs.html

TS:   s.match(/\d+/g)
来源：http://dali.gogol.net.cn/Article/details/gtlzzakmdi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangdashe.top/Article/details/gtzxpdlojs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gtmqwhxfmz.html

Ruby: s.scan(/\d+/)
来源：http://dali.havefunace.top/Article/details/gtjdsbolxb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtwwqjsdme.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gtrryezzoc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gtvzvwpcvg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yanxiufei.cn/Article/details/gtojqtsqyi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigufen.top/Article/details/gtzissanks.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.quarkkingdee.top/Article/details/gteqrxlkwi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hywenlv.cn/Article/details/gtnfeleyfp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gtudsxilvv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gogol.net.cn/Article/details/gtqkbgucae.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gtaklultyh.html

[I04] 正则替换
来源：http://dali.yueranfly.top/Article/details/gtomlgwoia.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zdqjudy.top/Article/details/gtnnlseloe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gtretxuzgi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsiolguab.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gtrejisqae.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtzffqdrqa.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ybcxt.top/Article/details/gtyaespbvr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnqzz.top/Article/details/gtvdxgruqg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.havefunace.top/Article/details/gtesydaeov.html

[I05] 按正则拆分
来源：http://dali.zhiwuduotai.top/Article/details/gthgabhrtf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gotoacloud.top/Article/details/gtnawiqdfk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtkkzrjrhq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gticawvuee.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtfidioojq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtlqojdslc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.havefunace.top/Article/details/gtbjrylkzy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtnipdsvjg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ppjwa.cn/Article/details/gtdvvzqyhq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xziqi.cn/Article/details/gtwiywqyce.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtecforyzg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinghuilouyu.cn/Article/details/gtggzswqyf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gtdpsrurew.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gttqsrnsmy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtyblppjjk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tianlin.xyz/Article/details/gtwfseptuq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.andypj.xyz/Article/details/gtxdmnrmwe.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtusogxggj.html

[I07] 忽略大小写与多行模式
来源：http://dali.bjfxy.top/Article/details/gtdfetwugd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gtwpyiqgdq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtqbfqrrcn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ivvv.top/Article/details/gtismzoesb.html

TS:   /error/gim
来源：http://dali.daria6918.cn/Article/details/gtsjtoldrk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gtrsbmzepa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.iojbl.cn/Article/details/gtbsqfappj.html

Ruby: s.scan(/error/i)
来源：http://dali.yonumen.top/Article/details/gtwkqqaqea.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gttoqufksi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkaytjtvj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuanzx.com/Article/details/gtgzojtrek.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gtssdgqgwr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtqzgkhejw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gtbllgnbfq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gtvgbffwyl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gtitkkhgcz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenlongwang.top/Article/details/gtexnzotkz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtdcrhzpuo.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtqzeedyns.html

J. 日期与时间
来源：http://dali.yuxming.cn/Article/details/gtttbgmnof.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtshxhtwep.html

[J01] 获取当前时间
来源：http://dali.yj20258888.top/Article/details/gtnggeitpd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnqzz.top/Article/details/gtjbphgqdf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gtpeyfvbmb.html

JS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gtueenirja.html

TS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gtlymgnobr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.haohaochexian.top/Article/details/gthhcctyyj.html

Go:   time.Now()
来源：http://dali.nanxuanxn.top/Article/details/gtcppkucmv.html

Ruby: Time.now
来源：http://dali.andypj.xyz/Article/details/gtlntbyqsu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigufen.top/Article/details/gtsglzirkp.html

[J02] 格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gtywssenqw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gtkidioqua.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gtbfuudtwv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gzhubu.top/Article/details/gtrnolezxs.html

TS:   d.toISOString()
来源：http://dali.fengsongda.top/Article/details/gtngseysbg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuanzhike.top/Article/details/gtfshezjfa.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuxming.cn/Article/details/gttinbfgxe.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gthezzgtsz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aizwys.cn/Article/details/gtaiucpoqu.html

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gtdqconezi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.mhx1999.top/Article/details/gtzcflllmg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shuidangran.top/Article/details/gtechkvrca.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrbdatxh.html

TS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtjwqagive.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtwedqxlsl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtthhbjggu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtdcnjdtrm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangdashe.top/Article/details/gtzjfqeevz.html

[J04] 时间戳与日期互转
来源：http://dali.jlsjyb.cn/Article/details/gtlmdvyomc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnqzz.top/Article/details/gtffpgyqtq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gtcuijjtmp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guowangkeji.top/Article/details/gtlckaaxuq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtjgbrfkfd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.birdmap.top/Article/details/gtikczjaab.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.svipenyu.cn/Article/details/gtghijzgux.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gtayhiiatm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cucudq.cn/Article/details/gtbgopuyez.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gtmfdbtsaq.html

Py:   now + timedelta(days=7)
来源：http://dali.hywenlv.cn/Article/details/gtpwgqibvz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cqqwz.cn/Article/details/gtlrpjnfgt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gtgauzwvud.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gtsqczsauw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.bjfxy.top/Article/details/gtefdlwosb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.mhx1999.top/Article/details/gthimdvtfg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjabsvhn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhengqikj.top/Article/details/gtktamsqak.html

[J06] 计算两时间之差
来源：http://dali.sxryk.cn/Article/details/gtkaocvkxy.html

Py:   (end - start).total_seconds()
来源：http://dali.dashuyun.cn/Article/details/gtvxwilhsj.html

PHP:  $end->diff($start)->days;
来源：http://dali.meibo888.top/Article/details/gtqkijvfqi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gotoacloud.top/Article/details/gtvhiozbfr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yongpay.top/Article/details/gtlsmnybjo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shangyingyoupin.top/Article/details/gtthvfxezc.html

Go:   end.Sub(start).Hours()
来源：http://dali.ehwqpu.com/Article/details/gtgwhcetrw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sweek.top/Article/details/gtihvocyee.html

C#:   (end - start).TotalSeconds
来源：http://dali.dashuyun.cn/Article/details/gtwbqeiffy.html

[J07] 比较两个日期
来源：http://dali.yangfankeji.com/Article/details/gtbzhcnxsn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtgahnyqyo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gtddqhljno.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtzjmwttdo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gtxjidbtxe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkrhjcvz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xziqi.cn/Article/details/gtvbobsdzo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtqgrectmp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtjzsizyjt.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gtqriqtddl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yongpay.top/Article/details/gtpaqwruab.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.redwolf501.top/Article/details/gtbmvmrdxn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gtmiqvslma.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.bjfxy.top/Article/details/gtfnylcrvg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gotoacloud.top/Article/details/gtmvblgutu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258888.top/Article/details/gttjtjahak.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigufen.top/Article/details/gtoajyotvs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gtarvvjgjv.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gtmrsczagn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ydzc1.top/Article/details/gtyshobsfn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sysykeji.top/Article/details/gtslbvvnnr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtslwdowkp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtywrixsac.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj202588.top/Article/details/gtqlhycigo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.vqdsnc.cn/Article/details/gtbbjwvnxq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgfzy.top/Article/details/gtzbisktle.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tianlin.xyz/Article/details/gtgdcmamrn.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gtuspavkad.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhongyouzk.top/Article/details/gtzopyjhzy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cashguo.top/Article/details/gtzljuvihm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtvbwyaypr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yongpay.top/Article/details/gtzrcxcjxu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gtgiwqklig.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zdqjudy.top/Article/details/gtecrzipml.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gtzyvzryal.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cqqwz.cn/Article/details/gtcoidngsp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtnkyczwlh.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gtptqfzoys.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtpqujhrfr.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gtcrlraynn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gtliavsblj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtrnxpswlm.html

JS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gthiotvxtv.html

TS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtjluxxjop.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dianchejie.cn/Article/details/gtualemurl.html

Go:   json.Marshal(obj)
来源：http://dali.iojbl.cn/Article/details/gtpaaeotuw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yvedp.cn/Article/details/gtpladrfbn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtvervwbeg.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gtqkwzqezv.html

Py:   json.loads(s)
来源：http://dali.yangfankeji.com/Article/details/gtshidjloj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hammf.cn/Article/details/gtrdrxhqry.html

JS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gttwvbiatt.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtgguqtokw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtghuidnne.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gttwysmiji.html

Ruby: JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtwwbcayyk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cheryme.top/Article/details/gtytjowlsc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hfpthk.cn/Article/details/gtoiwcloqy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gtrtzzzuqz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gtplhggjcp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gtfobspmof.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtfkcopdee.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cucudq.cn/Article/details/gtjzbeipyc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hfpthk.cn/Article/details/gtosqtuqtn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daria6918.cn/Article/details/gthivyvvpy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cashguo.top/Article/details/gthikrtqsx.html

[K04] 读取 JSON 文件
来源：http://dali.andypj.xyz/Article/details/gtrgzjtsgc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.0kj1m.cn/Article/details/gtdzkgdvoc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.haohaochexian.top/Article/details/gtzlepdvsw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtydgbhwpo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtlclxbyzx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gtakarvjvm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtrykadvyb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtsoatlbnn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.birdmap.top/Article/details/gtudzpdhwk.html

[K05] 深拷贝对象
来源：http://dali.tianlin.xyz/Article/details/gtdllgmybd.html

Py:   copy.deepcopy(obj)
来源：http://dali.pycfn.com/Article/details/gtkknswcdw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xinyue.icu/Article/details/gtsnlhmpop.html

JS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gtlpaezyfj.html

TS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtxigtsfgy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gtupydaisk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfieywvgw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqyymrlqj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbluevkay.html

[K06] 解析 URL 查询串
来源：http://dali.wangdashe.top/Article/details/gtvnrbujsr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtggkcpjog.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhengqikj.top/Article/details/gthxxivgwo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtmajsmqsy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gtzmhkozlu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gtctmlvzkp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtzucwbuup.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtalarzvrh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtvrbqajxt.html

[K07] 进制转换
来源：http://dali.cheryme.top/Article/details/gtjqtansln.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gthwgfprfk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cqqwz.cn/Article/details/gtczozlixk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtzfsmsccg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtfpaudzfk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtaemyubog.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sxryk.cn/Article/details/gtgsxaccsj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ydzc1.top/Article/details/gthdjuipwa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtzxazmqdy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.havefunace.top/Article/details/gtdhksizmr.html

Py:   pickle.dumps(obj)
来源：http://dali.guannengcc.top/Article/details/gthpqlzprz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gotoacloud.top/Article/details/gtlozilflf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gtxzfpspya.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtiajwaaau.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dianchejie.cn/Article/details/gtzpuwpyxw.html

Go:   encoding/gob
来源：http://dali.ivvv.top/Article/details/gtfsmomkji.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhengqikj.top/Article/details/gtabrfrhts.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtraklwtbt.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtjyngpkai.html

L. 网络请求
来源：http://dali.shangyingyoupin.top/Article/details/gtsgwklelv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtakhkhzwa.html

[L01] 发送 GET 请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsuxfdfxo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.bjfxy.top/Article/details/gtoblbagxm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tanke756.top/Article/details/gtsbymnrjm.html

JS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtghgiuatk.html

TS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gtatxvmgfl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvkbzcpc.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gtkpsfaeen.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tanke756.top/Article/details/gtmxabyrec.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ybcxt.top/Article/details/gtbfwuytmk.html

[L02] 发送 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gtkjylxsic.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gtjdopuhjl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sweek.top/Article/details/gtkgkepndo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gthxvypeii.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtamlkwqhg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxuanxn.top/Article/details/gtayqevlcz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daxiang520.top/Article/details/gtdiqrkspr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yonumen.top/Article/details/gtaqgljots.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.316326.xyz/Article/details/gtwonxujro.html

[L03] 设置自定义请求头
来源：http://dali.jqgfzy.top/Article/details/gtaljqgchy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.quarkkingdee.top/Article/details/gtrercrgvm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tianlin.xyz/Article/details/gtyschjokw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtknfkbplg.html


<!-- 参考信息 -->