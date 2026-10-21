代发 wailian999

[Q65] 回滚事务
来源：http://dali.wangdashe.top/Article/details/gtapedhxed.html

ROLLBACK;
来源：http://dali.redwolf501.top/Article/details/gtleqhhdvo.html

[Q66] 行锁查询
来源：http://dali.svipenyu.cn/Article/details/gtzovlqass.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hfpthk.cn/Article/details/gthhtseqtb.html

[Q67] 设置隔离级别
来源：http://dali.chenlongwang.top/Article/details/gttlhjhozp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258.top/Article/details/gtzdijebvs.html

[Q68] 保存点
来源：http://dali.gaohongyu789.top/Article/details/gtlzshqlrj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gtiviqunyg.html

ROLLBACK TO sp1;
来源：http://dali.sysykeji.top/Article/details/gtpgkqcuhh.html

[Q69] 查看执行计划
来源：http://dali.nwbrower.top/Article/details/gtrghgxjnc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sysykeji.top/Article/details/gtxlxlchey.html

[Q70] 更新统计信息
来源：http://dali.yanxiufei.cn/Article/details/gttopedaly.html

ANALYZE TABLE users;
来源：http://dali.sysykeji.top/Article/details/gthuvxjvbj.html

[Q71] 查看建表语句
来源：http://dali.chenzaomai.com/Article/details/gtqdpghvsp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ydzc1.top/Article/details/gtliriejbx.html

[Q72] 查看索引
来源：http://dali.shuidangran.top/Article/details/gtdhfwxouj.html

SHOW INDEX FROM users;
来源：http://dali.sweek.top/Article/details/gttmfacstw.html

[Q73] 查看表状态
来源：http://dali.aibaodan.cn/Article/details/gtflngwqzu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aibaodan.cn/Article/details/gtqnotxoki.html

[Q74] 强制使用索引
来源：http://dali.jianghu66.top/Article/details/gtsoysgefb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.havefunace.top/Article/details/gtxtjzzlpc.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtwqdfnljf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtvjlpseod.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.svipenyu.cn/Article/details/gtynkirlgv.html

[Q76] 按天统计
来源：http://dali.sufxvd.cn/Article/details/gtxwtzaqsa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dianchejie.cn/Article/details/gtkumdtuwj.html

[Q77] 时间加减
来源：http://dali.nanxinkj.top/Article/details/gtyszyiqyx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cqqwz.cn/Article/details/gtpovccgpe.html

[Q78] 当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtvacmcveg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhhrfdtt.html

[Q79] 字符串拼接
来源：http://dali.zycfv.cn/Article/details/gttcxusldt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gogol.net.cn/Article/details/gtbxinrptk.html

[Q80] 字符串截取
来源：http://dali.birdmap.top/Article/details/gtxfqicagb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj202588.top/Article/details/gtzxtndjhn.html

[Q81] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gtaqojpwqu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zycfv.cn/Article/details/gtmssydbyi.html

[Q82] 字符长度与字节长度
来源：http://dali.zhiwuduotai.top/Article/details/gtaeejizls.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtvzzthgvy.html

[Q83] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gtkmmcbjip.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtrgxuoqyg.html

[Q84] 去除首尾空格
来源：http://dali.daria6918.cn/Article/details/gtncvgsjbm.html

SELECT TRIM(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtiuxxaddu.html

[Q85] 数值取整
来源：http://dali.hnxiangtu.top/Article/details/gtgntuysah.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.pengpengdd.cyou/Article/details/gtnrilyzui.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258.top/Article/details/gtzeqaijlb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gtauauwecz.html

[Q87] JSON 字段做条件
来源：http://dali.hnqzz.top/Article/details/gtzjmonvvd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shuidangran.top/Article/details/gtklyjhimd.html

[Q88] 行转列（条件聚合）
来源：http://dali.0kj1m.cn/Article/details/gtzsibabkz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.kuanghao11.cn/Article/details/gtntibijld.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cucudq.cn/Article/details/gtutqfjvzy.html

[Q89] 判断表是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtyzuqjzeu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gtvwbrfxtf.html

[Q90] 生成序号列
来源：http://dali.zhongyouzk.top/Article/details/gtuuefcibb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cashguo.top/Article/details/gtjxhbzdez.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtieijhgmt.html

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gtnnzvwkrs.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtqncscgyd.html

[R01] shebang 与严格模式
来源：http://dali.yuxming.cn/Article/details/gtjkvluxgz.html

#!/usr/bin/env bash
来源：http://dali.haohaochexian.top/Article/details/gtdodlrsip.html

set -euo pipefail
来源：http://dali.cashguo.top/Article/details/gtyndnnhdg.html

[R02] 变量赋值与使用
来源：http://dali.havefunace.top/Article/details/gtazmlgiah.html

name="Tom"; echo "$name"
来源：http://dali.cqqwz.cn/Article/details/gttuxmfzfu.html

[R03] 只读变量
来源：http://dali.sweek.top/Article/details/gtiacvhcju.html

readonly PI=3.14
来源：http://dali.jinyuanbaomall.cn/Article/details/gtatprfetf.html

[R04] 位置参数
来源：http://dali.chenjidiqi.icu/Article/details/gtiubulicp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ppjwa.cn/Article/details/gtolvighpq.html

[R05] 参数默认值
来源：http://dali.cdnleiting.top/Article/details/gtdrwhznpn.html

name="${1:-default}"
来源：http://dali.pycfn.com/Article/details/gtqwocbsvm.html

[R06] 判断命令是否存在
来源：http://dali.chenzaomai.com/Article/details/gtiaiwycyj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtkelnkpmp.html

[R07] if 判断文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfggsuic.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hysaishi.cn/Article/details/gtxrzlcgjp.html

[R08] 数值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtnwswskai.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gtokarxcjt.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gtgwsfwhzt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtzgnrmupz.html

[R10] 正则匹配
来源：http://dali.ybcxt.top/Article/details/gtipmrfzqj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tianlin.xyz/Article/details/gtrilemgvw.html

[R11] case 多分支
来源：http://dali.xinyue.icu/Article/details/gtvwrudozp.html

case "$1" in
来源：http://dali.9152youxi.cn/Article/details/gttaouvidl.html

start) echo "启动" ;;
来源：http://dali.andypj.xyz/Article/details/gtkbdxrldo.html

stop)  echo "停止" ;;
来源：http://dali.zhixingplan.top/Article/details/gtmnrwxtkc.html

*)     echo "未知命令" ;;
来源：http://dali.daxiang520.top/Article/details/gtocdqaffh.html

esac
来源：http://dali.birdmap.top/Article/details/gtjornegvg.html

[R12] for 遍历文件
来源：http://dali.cashguo.top/Article/details/gtcxvntqub.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dianchejie.cn/Article/details/gthfmdnrni.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gtwvjdlgno.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtykohmefx.html

[R14] C 风格 for
来源：http://dali.yj20258.top/Article/details/gtqzqowmbc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gtpfvvzyup.html

[R15] while 逐行读文件
来源：http://dali.jianghu66.top/Article/details/gthegnemwk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fengsongda.top/Article/details/gtntzbetbs.html

[R16] until 等待条件
来源：http://dali.yueranfly.top/Article/details/gtpictirtl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gtarmtbann.html

[R17] 数组定义与取值
来源：http://dali.jlsjyb.cn/Article/details/gtnbvmavzr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jyoumei.cn/Article/details/gtykaqiuyg.html

[R18] 遍历数组
来源：http://dali.yj20258.top/Article/details/gthyfklerh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtvgustyso.html

[R19] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtbjdxfqjt.html

echo "${#arr[@]}"
来源：http://dali.jyoumei.cn/Article/details/gthmbuktjo.html

[R20] 关联数组（字典）
来源：http://dali.wangshuangyany.cn/Article/details/gtwuxedlcs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.aibaodan.cn/Article/details/gtjluqwbih.html

[R21] 字符串长度
来源：http://dali.yuxming.cn/Article/details/gteacgtmdh.html

echo "${#s}"
来源：http://dali.cashguo.top/Article/details/gthwgydisx.html

[R22] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gtejwupmme.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gtjcdaiuup.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtpgrjhdqc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gogol.net.cn/Article/details/gtisyeryzr.html

[R24] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gtdpeudnoz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenzaomai.com/Article/details/gtijdpnnrn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhongyouzk.top/Article/details/gtutrjbbeh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.havefunace.top/Article/details/gtrlzeecrl.html

[R26] 命令替换
来源：http://dali.ehwqpu.com/Article/details/gtvanytjtq.html

now=$(date +%F); echo "$now"
来源：http://dali.wangshuangyany.cn/Article/details/gtpfpaqzhj.html

[R27] 算术展开
来源：http://dali.kuanghao11.cn/Article/details/gtcwxfzrye.html

echo $((1 + 2 * 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkraxuve.html

[R28] 浮点运算
来源：http://dali.yj20258888.top/Article/details/gtabxgkngg.html

echo "scale=2; 10/3" | bc
来源：http://dali.daria6918.cn/Article/details/gtvanobazh.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gtvwxzegmp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sweek.top/Article/details/gtvgjfmwuf.html

[R30] 函数返回状态码
来源：http://dali.yongpay.top/Article/details/gtcdyiqlwm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gtbttmaxhf.html

[R31] 局部变量
来源：http://dali.jqgfzy.top/Article/details/gtmuvhbtcz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhoulong.xyz/Article/details/gtyrnmqvfg.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gtqgavnijp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gtlctcwedx.html

[R33] 捕获错误并提示行号
来源：http://dali.havefunace.top/Article/details/gtonsttanu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jlsjyb.cn/Article/details/gtbvlncawk.html

[R34] 退出时清理
来源：http://dali.ydzc1.top/Article/details/gtgeqljces.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtgxiykbgw.html

[R35] 后台执行并等待
来源：http://dali.vqdsnc.cn/Article/details/gtffgavxcr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cheryme.top/Article/details/gtefsexojn.html

[R36] 并发执行多个任务
来源：http://dali.yvedp.cn/Article/details/gtizirqccs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guowangkeji.top/Article/details/gtqrnancyp.html

[R37] 把输出赋给变量
来源：http://dali.chenzaomai.com/Article/details/gtzwpdelmm.html

files=$(ls -1)
来源：http://dali.sxryk.cn/Article/details/gtzbujiaqb.html

[R38] 管道串联
来源：http://dali.ehwqpu.com/Article/details/gtvjvvputa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guannengcc.top/Article/details/gtvvripaxc.html

[R39] 重定向标准输出与错误
来源：http://dali.zhixingplan.top/Article/details/gtckkejzcp.html

cmd > out.log 2>&1
来源：http://dali.nwbrower.top/Article/details/gtlsajklfg.html

[R40] 追加写日志
来源：http://dali.andypj.xyz/Article/details/gtlqfrnpbz.html

echo "log" >> out.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlngqygia.html

[R41] 丢弃输出
来源：http://dali.zhixingplan.top/Article/details/gtwnyyfkju.html

cmd >/dev/null 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtzamefddg.html

[R42] 输入重定向
来源：http://dali.yanxiufei.cn/Article/details/gtltbxoela.html

wc -l < a.txt
来源：http://dali.ivvv.top/Article/details/gtcdpaxetq.html

[R43] 按名字查找文件
来源：http://dali.iojbl.cn/Article/details/gtomxskyrm.html

find . -name "*.log" -type f
来源：http://dali.yongpay.top/Article/details/gtlljcnoai.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gtnrofbvry.html

find . -mtime -7 -type f
来源：http://dali.snrcjt.cn/Article/details/gtmiqabpvk.html

[R45] 批量删除
来源：http://dali.yuxming.cn/Article/details/gtkwujcgtl.html

find . -name "*.tmp" -delete
来源：http://dali.snrcjt.cn/Article/details/gtpqiotnow.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gtixkcnruu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnizjify.html

[R47] sed 单行替换
来源：http://dali.hnxiangtu.top/Article/details/gtwjwejdow.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258888.top/Article/details/gttswqxsbj.html

[R48] awk 取指定列
来源：http://dali.havefunace.top/Article/details/gtozdcqmlf.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtrukvtieu.html

[R49] awk 带条件
来源：http://dali.quarkkingdee.top/Article/details/gtresdknaz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ybcxt.top/Article/details/gtzdbckhxp.html

[R50] awk 求和
来源：http://dali.nwbrower.top/Article/details/gtsrbitdyq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fengsongda.top/Article/details/gtppvmczqm.html

[R51] 排序去重取前几
来源：http://dali.nwbrower.top/Article/details/gtgmrxoxsf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tian-w.cn/Article/details/gtllynqzxv.html

[R52] 统计行数
来源：http://dali.ybcxt.top/Article/details/gtwvmprpfu.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtymmtiazr.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gtcucsvokn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gtdumdsxdd.html

[R54] 比较两个文件
来源：http://dali.iojbl.cn/Article/details/gtoswfyvns.html

diff a.txt b.txt
来源：http://dali.jinqigfzy.top/Article/details/gtctppqkvl.html

[R55] 压缩与解压
来源：http://dali.sysykeji.top/Article/details/gtvievopuf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnxiangtu.top/Article/details/gtptiqzspf.html

[R56] 远程拷贝
来源：http://dali.daxiang520.top/Article/details/gthdhirrpi.html

scp file user@host:/path/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiatqbllf.html

[R57] 远程执行命令
来源：http://dali.xuetiantiany.cn/Article/details/gtyvbhwzvl.html

ssh user@host 'uptime'
来源：http://dali.fengsongda.top/Article/details/gthkcedpcl.html

[R58] 下载文件
来源：http://dali.gotoacloud.top/Article/details/gtcaobmckk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuxming.cn/Article/details/gtqgrdfxfi.html

[R59] 发 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtojjbvidx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zycfv.cn/Article/details/gtqnclrqyn.html

[R60] 只看 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtwdqcfjpe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sufxvd.cn/Article/details/gtuyjtgojs.html

[R61] 磁盘占用
来源：http://dali.meibo888.top/Article/details/gtosrgfzxu.html

df -h;  du -sh *
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywdnevbv.html

[R62] 找最占空间的文件
来源：http://dali.xziqi.cn/Article/details/gtpqvjaszo.html

du -ah . | sort -rh | head -10
来源：http://dali.chenlongwang.top/Article/details/gtjotwhfsu.html

[R63] 内存与进程
来源：http://dali.jianghu66.top/Article/details/gtieanxpgw.html

free -h;  ps aux | grep nginx
来源：http://dali.shzxlz.cn/Article/details/gtjbnwkqxy.html

[R64] 结束进程
来源：http://dali.nwbrower.top/Article/details/gtkspjpoow.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuanzhike.top/Article/details/gtowqarnmk.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gthzfyynxt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigufen.top/Article/details/gtoiiqhsji.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gtocdojxdk.html

crontab -e;  crontab -l
来源：http://dali.jyoumei.cn/Article/details/gtwtaurbaf.html

[R67] 生成随机十六进制串
来源：http://dali.cqqwz.cn/Article/details/gtmugbyrpu.html

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gtjjwyxhls.html

[R68] 计算文件校验值
来源：http://dali.shzxlz.cn/Article/details/gtfpbhaujz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gtoulgnphj.html

[R69] 生成随机密码
来源：http://dali.9152youxi.cn/Article/details/gtupoqittm.html

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gteetkhafv.html

[R70] 时间戳与互转
来源：http://dali.jyoumei.cn/Article/details/gtwzwcdqdw.html

date +%s;  date -d @1700000000
来源：http://dali.birdmap.top/Article/details/gturwsuilr.html

[R71] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gtxxzxjzbd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.haohaochexian.top/Article/details/gtifvvpbjs.html

[R72] 等待端口就绪
来源：http://dali.mhx1999.top/Article/details/gtwcqrxgss.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtoyrxqhul.html

[R73] 分割大日志
来源：http://dali.svipenyu.cn/Article/details/gtdzhksdtp.html

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gtowgyhnht.html

[R74] 批量重命名
来源：http://dali.yj20258888.top/Article/details/gtohkpsjma.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenlongwang.top/Article/details/gtygdbsicv.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gtudgjjfqr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigfzy.top/Article/details/gtraqndtkt.html

[R76] 使用临时文件
来源：http://dali.nanxinkj.top/Article/details/gtgvrfcrjm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gtnjdfgzhy.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gtpgqufbjk.html

read -rp "请输入: " ans
来源：http://dali.sysykeji.top/Article/details/gtuguogxxp.html

[R78] 交互式菜单
来源：http://dali.gaohongyu789.top/Article/details/gtqtwujxrc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.feifeiyinyue.top/Article/details/gtyqegzczl.html

[R79] 解析命令行选项
来源：http://dali.0kj1m.cn/Article/details/gtwixvtiys.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daxiang520.top/Article/details/gtehhyugws.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gthmdsexzs.html

time ./run.sh
来源：http://dali.yangfankeji.com/Article/details/gtgtvthgjc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtyhjyachm.html

S. C / C++ 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvomqzec.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtzzkprhgf.html

[S01] C：Hello World
来源：http://dali.sysykeji.top/Article/details/gtxnkqabeu.html

#include <stdio.h>
来源：http://dali.jyoumei.cn/Article/details/gtotgwxxaf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sweek.top/Article/details/gtxiobvbzt.html

[S02] C：变量与格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtxtpqwuhn.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuetiantiany.cn/Article/details/gtxyeghtgl.html

[S03] C：读入整数
来源：http://dali.yueranfly.top/Article/details/gtlnzrnakt.html

int x; scanf("%d", &x);
来源：http://dali.sxryk.cn/Article/details/gtqjllccxo.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gtusblfzvm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zdqjudy.top/Article/details/gtvenrfrel.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtembtpjhl.html

strlen(s)
来源：http://dali.hnqzz.top/Article/details/gtaevrguef.html

[S06] C：字符串比较
来源：http://dali.xylfe.cn/Article/details/gtaohxrjmv.html

strcmp(a, b) == 0
来源：http://dali.yj20258.top/Article/details/gtdweuzuzn.html

[S07] C：数组遍历求和
来源：http://dali.andypj.xyz/Article/details/gtjrjulszo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gttngnnnmw.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigufen.top/Article/details/gtqteqshvj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.bjfxy.top/Article/details/gtltxchixq.html

[S09] C：结构体定义与初始化
来源：http://dali.yongpay.top/Article/details/gtllsuzpdw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhiwuduotai.top/Article/details/gtueblsorz.html

[S10] C：指针与解引用
来源：http://dali.hysaishi.cn/Article/details/gtuyugimti.html

int *p = &a;  *p = 5;
来源：http://dali.c1oappe.top/Article/details/gtjqaxmych.html

[S11] C：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtikxdahhv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yangfankeji.com/Article/details/gtapwloijq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnxiangtu.top/Article/details/gtnwukyccs.html

fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtzdmkpris.html

[S12] C：写文件
来源：http://dali.wangdashe.top/Article/details/gtjcdzagds.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gtagpbsqpv.html

[S13] C：宏定义
来源：http://dali.nwbrower.top/Article/details/gtvwokcvan.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yonumen.top/Article/details/gtdaszcksb.html

[S14] C：枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtamyllpsa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gtsgfgiyki.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gtyxrgrvaj.html

(double) a / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthicqfvas.html

[S16] C：位操作置位
来源：http://dali.9152youxi.cn/Article/details/gtcdhbhvbm.html

x |= (1 << 3);
来源：http://dali.gotoacloud.top/Article/details/gtrbvylftt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtnowjuucs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.snrcjt.cn/Article/details/gtbdawmhtl.html

[S18] C：命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqbeoucj.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gteidookki.html

[S19] C：快速排序
来源：http://dali.cheryme.top/Article/details/gtdhvamgbb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gtdmvzncmc.html

[S20] C：二分查找
来源：http://dali.xinyue.icu/Article/details/gtvzxfcuvm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtvdbrkryp.html

[S21] C：字符类别判断
来源：http://dali.ppjwa.cn/Article/details/gtyovksprk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhengqikj.top/Article/details/gtuysisvzq.html

[S22] C：字符串转数字
来源：http://dali.9152youxi.cn/Article/details/gtyghyzmwm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sweek.top/Article/details/gtzqfofldi.html

[S23] C：随机数
来源：http://dali.iojbl.cn/Article/details/gtswvhrdmm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigfzy.top/Article/details/gtedqfqhtm.html

[S24] C：获取本地时间
来源：http://dali.shzxlz.cn/Article/details/gtmqzwaqxr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fengsongda.top/Article/details/gtwwhbtlql.html

[S25] C：内存拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtyixxseng.html

memcpy(dst, src, n);
来源：http://dali.yonumen.top/Article/details/gthitxjunm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gtpodmbwpu.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrnhxgxk.html

[S27] C：定义常量
来源：http://dali.ybcxt.top/Article/details/gtktzwbwcl.html

const double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtshgpcrcu.html

[S28] C：静态变量
来源：http://dali.yvedp.cn/Article/details/gtrorbtlnr.html

static int counter = 0;
来源：http://dali.hywenlv.cn/Article/details/gtexxqsbkl.html

[S29] C：变参函数
来源：http://dali.redwolf501.top/Article/details/gtdwuzpcxd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgcgwrwi.html

[S30] C：头文件保护
来源：http://dali.316326.xyz/Article/details/gtulljvzov.html

#ifndef X_H
来源：http://dali.cqqwz.cn/Article/details/gtlvfivzwy.html

#define X_H
来源：http://dali.ybcxt.top/Article/details/gtaovskmja.html

#endif
来源：http://dali.xuanzx.com/Article/details/gtfqfecysf.html

[S31] C++：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtohtovbfn.html

#include <iostream>
来源：http://dali.zdqjudy.top/Article/details/gtlehfpeom.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnqzz.top/Article/details/gtqemltlvx.html

[S32] C++：字符串
来源：http://dali.chenzaomai.com/Article/details/gtrsgnxawo.html

std::string s = "hi";  s += "!";
来源：http://dali.pycfn.com/Article/details/gtvpiittca.html

[S33] C++：vector 增删
来源：http://dali.pengpengdd.cyou/Article/details/gtdiztbdhx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ivvv.top/Article/details/gtvofudhly.html

[S34] C++：遍历 vector
来源：http://dali.hywenlv.cn/Article/details/gtzkodzmrb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gtgyrkorbd.html


<!-- 参考信息 -->