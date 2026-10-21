代发 wailian999

[Q65] 回滚事务
来源：http://dali.hfpthk.cn/Article/details/gtenkbcgjy.html

ROLLBACK;
来源：http://dali.c1oappe.top/Article/details/gtmgfsitcf.html

[Q66] 行锁查询
来源：http://dali.sweek.top/Article/details/gtxixqlimm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.wangshuangyany.cn/Article/details/gtzsdythmr.html

[Q67] 设置隔离级别
来源：http://dali.fzhhl.top/Article/details/gtuhdjjhas.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.smart0.xyz/Article/details/gtptetvdqq.html

[Q68] 保存点
来源：http://dali.wangdashe.top/Article/details/gtsypbxqos.html

SAVEPOINT sp1;
来源：http://dali.fzhhl.top/Article/details/gtlevddmhx.html

ROLLBACK TO sp1;
来源：http://dali.haohaochexian.top/Article/details/gtphfcroov.html

[Q69] 查看执行计划
来源：http://dali.shangyingyoupin.top/Article/details/gtieaejaub.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.andypj.xyz/Article/details/gtuwqqgohl.html

[Q70] 更新统计信息
来源：http://dali.tanke756.top/Article/details/gtmmsvflrs.html

ANALYZE TABLE users;
来源：http://dali.ppjwa.cn/Article/details/gtpnpbyudn.html

[Q71] 查看建表语句
来源：http://dali.sufxvd.cn/Article/details/gtftfplaxy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yongpay.top/Article/details/gtoojvxlel.html

[Q72] 查看索引
来源：http://dali.jlsjyb.cn/Article/details/gtpzqubxst.html

SHOW INDEX FROM users;
来源：http://dali.smart0.xyz/Article/details/gtqpihgreq.html

[Q73] 查看表状态
来源：http://dali.zhongyouzk.top/Article/details/gtaarzczrb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258888.top/Article/details/gtnobrwsip.html

[Q74] 强制使用索引
来源：http://dali.zycfv.cn/Article/details/gtvxardoao.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.0kj1m.cn/Article/details/gtwyzjmbzs.html

[Q75] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gtdzuroccj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtzxzrfxqb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenjidiqi.icu/Article/details/gtwhhmbpui.html

[Q76] 按天统计
来源：http://dali.haohaochexian.top/Article/details/gtutjowmxp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sxryk.cn/Article/details/gtovasupkl.html

[Q77] 时间加减
来源：http://dali.9152youxi.cn/Article/details/gtdsvidowl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zycfv.cn/Article/details/gtykcnixmg.html

[Q78] 当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gtxuvswcup.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.316326.xyz/Article/details/gtnhdwpdqi.html

[Q79] 字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtguhrwkat.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gtxyqjorta.html

[Q80] 字符串截取
来源：http://dali.hnqzz.top/Article/details/gtyprznlfc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtaiwdqsev.html

[Q81] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gtxmgxavum.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtrgsyjnef.html

[Q82] 字符长度与字节长度
来源：http://dali.snrcjt.cn/Article/details/gttdvflhfx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtomthkzec.html

[Q83] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtdoxaaujx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtimxpygzt.html

[Q84] 去除首尾空格
来源：http://dali.tian-w.cn/Article/details/gtwsarhrgo.html

SELECT TRIM(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtwvipjawl.html

[Q85] 数值取整
来源：http://dali.feifeiyinyue.top/Article/details/gtkcdwoxoh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfhiqsoc.html

[Q86] 读取 JSON 字段
来源：http://dali.svipenyu.cn/Article/details/gtplssldwb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yangfankeji.com/Article/details/gtipzytgrl.html

[Q87] JSON 字段做条件
来源：http://dali.guannengcc.top/Article/details/gtakxmeleu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gtkixavlij.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuetiantiany.cn/Article/details/gtzapwczuu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gtaimnkhsa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.c1oappe.top/Article/details/gtrumdgzgs.html

[Q89] 判断表是否存在
来源：http://dali.zycfv.cn/Article/details/gtjazjjyks.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.mhx1999.top/Article/details/gtyncpyxxy.html

[Q90] 生成序号列
来源：http://dali.svipenyu.cn/Article/details/gtzbyaotnb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fengsongda.top/Article/details/gtncavszow.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtydtpjtwb.html

R. Bash 专题
来源：http://dali.shangyingyoupin.top/Article/details/gtnmkgmitf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtelaijcdb.html

[R01] shebang 与严格模式
来源：http://dali.zhoulong.xyz/Article/details/gtvdsrsfrw.html

#!/usr/bin/env bash
来源：http://dali.pycfn.com/Article/details/gtimulkpbc.html

set -euo pipefail
来源：http://dali.yongpay.top/Article/details/gtehrajibu.html

[R02] 变量赋值与使用
来源：http://dali.9152youxi.cn/Article/details/gtbzwoamrt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gthxttaqxj.html

[R03] 只读变量
来源：http://dali.vqdsnc.cn/Article/details/gthhzngwqo.html

readonly PI=3.14
来源：http://dali.fengsongda.top/Article/details/gtczkvvkrn.html

[R04] 位置参数
来源：http://dali.nanxinkj.top/Article/details/gtbwbdzhfi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigufen.top/Article/details/gtrtlfptlq.html

[R05] 参数默认值
来源：http://dali.yangfankeji.com/Article/details/gtbqzppybm.html

name="${1:-default}"
来源：http://dali.sxryk.cn/Article/details/gtjoswvsip.html

[R06] 判断命令是否存在
来源：http://dali.iojbl.cn/Article/details/gtlmnbzvbv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.snrcjt.cn/Article/details/gtiifdzdbm.html

[R07] if 判断文件
来源：http://dali.cashguo.top/Article/details/gtjktgtsis.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwoypndwe.html

[R08] 数值比较
来源：http://dali.xinyue.icu/Article/details/gtpwogflee.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ehwqpu.com/Article/details/gtuttwzzua.html

[R09] 字符串比较
来源：http://dali.yj20258888.top/Article/details/gtqglgptqy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuxming.cn/Article/details/gtqrzpmtbw.html

[R10] 正则匹配
来源：http://dali.jiagoushi.top/Article/details/gtddvszpgn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.iojbl.cn/Article/details/gtvmiqbyzq.html

[R11] case 多分支
来源：http://dali.shzxlz.cn/Article/details/gtdmeofxvg.html

case "$1" in
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtliwpwktg.html

start) echo "启动" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtfomvsmgi.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gtnmpspqio.html

*)     echo "未知命令" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtywpqjewu.html

esac
来源：http://dali.birdmap.top/Article/details/gtuharnrso.html

[R12] for 遍历文件
来源：http://dali.jinqigfzy.top/Article/details/gtbdnlrshu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknoqegzs.html

[R13] for 计数循环
来源：http://dali.ehwqpu.com/Article/details/gtqwqxgxuj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gtgbprhfek.html

[R14] C 风格 for
来源：http://dali.tianlin.xyz/Article/details/gtpdjndfei.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gttxkgtiyv.html

[R15] while 逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtctilnlus.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cucudq.cn/Article/details/gtjfwqgxpn.html

[R16] until 等待条件
来源：http://dali.chenjidiqi.icu/Article/details/gtxknbcsxx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gtnnosrxze.html

[R17] 数组定义与取值
来源：http://dali.shangyingyoupin.top/Article/details/gtquyknpst.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yvedp.cn/Article/details/gtgoephvme.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gtyhrhdivo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gogol.net.cn/Article/details/gtdutabsaa.html

[R19] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtvygfbukl.html

echo "${#arr[@]}"
来源：http://dali.yj20258.top/Article/details/gteutpfpvs.html

[R20] 关联数组（字典）
来源：http://dali.yvedp.cn/Article/details/gttjzcgjiw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtldfajowl.html

[R21] 字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gtosxtbrgp.html

echo "${#s}"
来源：http://dali.hongshengwenyu.top/Article/details/gtgismvrfx.html

[R22] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtrosoywna.html

echo "${s:0:5}"
来源：http://dali.hnqzz.top/Article/details/gteacoelpg.html

[R23] 字符串替换
来源：http://dali.chenjidiqi.icu/Article/details/gtcfknxlkv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.redwolf501.top/Article/details/gtizatqwns.html

[R24] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gthyrxctnl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxinkj.top/Article/details/gtxthvdved.html

[R25] 去后缀 / 去前缀
来源：http://dali.xylfe.cn/Article/details/gtfrnpugeo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnxiangtu.top/Article/details/gtrpuhmblu.html

[R26] 命令替换
来源：http://dali.yvedp.cn/Article/details/gtoofryobg.html

now=$(date +%F); echo "$now"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnqqacxe.html

[R27] 算术展开
来源：http://dali.guowangkeji.top/Article/details/gtwawrgbhr.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258.top/Article/details/gtyyqxxato.html

[R28] 浮点运算
来源：http://dali.jlsjyb.cn/Article/details/gtvoreihga.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gtmzqgygwi.html

[R29] 定义函数
来源：http://dali.sysykeji.top/Article/details/gtqylrytcu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.birdmap.top/Article/details/gtwpgbhiba.html

[R30] 函数返回状态码
来源：http://dali.guannengcc.top/Article/details/gtibrmfiny.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.9152youxi.cn/Article/details/gtozpdzzeb.html

[R31] 局部变量
来源：http://dali.yuxming.cn/Article/details/gtwvdkotui.html

f() { local x=1; echo "$x"; }
来源：http://dali.ybcxt.top/Article/details/gtiolegkvd.html

[R32] 参数个数校验
来源：http://dali.guowangkeji.top/Article/details/gtjozmgeya.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sweek.top/Article/details/gtkemxkbgv.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gtosfhphzf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhongyouzk.top/Article/details/gtxomiecel.html

[R34] 退出时清理
来源：http://dali.vqdsnc.cn/Article/details/gtrroiclvf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gtinjzkegz.html

[R35] 后台执行并等待
来源：http://dali.cheryme.top/Article/details/gtrkgooewg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuanzx.com/Article/details/gtlfgrrxad.html

[R36] 并发执行多个任务
来源：http://dali.sysykeji.top/Article/details/gtveqwafnw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shzxlz.cn/Article/details/gtgmzwmzve.html

[R37] 把输出赋给变量
来源：http://dali.sxryk.cn/Article/details/gtofumkmzo.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gtnqttwmud.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gtxocmjqig.html

cat a.txt | grep -i error | wc -l
来源：http://dali.svipenyu.cn/Article/details/gthmsnfbac.html

[R39] 重定向标准输出与错误
来源：http://dali.ydzc1.top/Article/details/gtwcuexhxr.html

cmd > out.log 2>&1
来源：http://dali.hysaishi.cn/Article/details/gtoasmrtuy.html

[R40] 追加写日志
来源：http://dali.dianchejie.cn/Article/details/gttfpyjgdd.html

echo "log" >> out.log
来源：http://dali.zdqjudy.top/Article/details/gtgjvuguqz.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gtiorejrsb.html

cmd >/dev/null 2>&1
来源：http://dali.jiagoushi.top/Article/details/gtdwsujoxv.html

[R42] 输入重定向
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxpqbbuc.html

wc -l < a.txt
来源：http://dali.bjfxy.top/Article/details/gtgojlbepx.html

[R43] 按名字查找文件
来源：http://dali.snrcjt.cn/Article/details/gtcfpudoue.html

find . -name "*.log" -type f
来源：http://dali.nwbrower.top/Article/details/gtqnkijwqq.html

[R44] 按修改时间查找
来源：http://dali.snrcjt.cn/Article/details/gtnumylfdu.html

find . -mtime -7 -type f
来源：http://dali.bjfxy.top/Article/details/gtfcljsunw.html

[R45] 批量删除
来源：http://dali.guannengcc.top/Article/details/gthqsejkrl.html

find . -name "*.tmp" -delete
来源：http://dali.nwbrower.top/Article/details/gtatbuyheo.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddlbzuju.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yvedp.cn/Article/details/gtlsgfqwai.html

[R47] sed 单行替换
来源：http://dali.daxiang520.top/Article/details/gtvnctxlyb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jiagoushi.top/Article/details/gthntxoslw.html

[R48] awk 取指定列
来源：http://dali.yongpay.top/Article/details/gtoamwzlrf.html

awk '{print $1, $3}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtnpwiufrb.html

[R49] awk 带条件
来源：http://dali.yuxming.cn/Article/details/gtzotruvnz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.smart0.xyz/Article/details/gtohbajvzw.html

[R50] awk 求和
来源：http://dali.yonumen.top/Article/details/gtwotcvlyy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtpheqczae.html

[R51] 排序去重取前几
来源：http://dali.xuetiantiany.cn/Article/details/gtwkzrawsl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqfpnesq.html

[R52] 统计行数
来源：http://dali.aizwys.cn/Article/details/gtihgvpnvw.html

wc -l a.txt
来源：http://dali.9152youxi.cn/Article/details/gtdorwgwtj.html

[R53] 查看文件头与实时尾
来源：http://dali.aibaodan.cn/Article/details/gtbfwvduog.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yueranfly.top/Article/details/gtcatgynbz.html

[R54] 比较两个文件
来源：http://dali.c1oappe.top/Article/details/gtljplnctj.html

diff a.txt b.txt
来源：http://dali.nanxinkj.top/Article/details/gtesdpwmiw.html

[R55] 压缩与解压
来源：http://dali.tanke756.top/Article/details/gtjhvfekji.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sysykeji.top/Article/details/gtrbagxide.html

[R56] 远程拷贝
来源：http://dali.ivvv.top/Article/details/gtskwmlris.html

scp file user@host:/path/
来源：http://dali.jiagoushi.top/Article/details/gtgvdhvqpn.html

[R57] 远程执行命令
来源：http://dali.cdnleiting.top/Article/details/gtjmkizbxf.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gtslhjfgnb.html

[R58] 下载文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxhziztl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xinyue.icu/Article/details/gtdecluijm.html

[R59] 发 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtojaghomu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tian-w.cn/Article/details/gtwclnkskf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodbyutya.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ehwqpu.com/Article/details/gtqqnewrrv.html

[R61] 磁盘占用
来源：http://dali.kuanghao11.cn/Article/details/gttxtsupjl.html

df -h;  du -sh *
来源：http://dali.pycfn.com/Article/details/gtrapmdhhu.html

[R62] 找最占空间的文件
来源：http://dali.yuxming.cn/Article/details/gtefhvrwpu.html

du -ah . | sort -rh | head -10
来源：http://dali.mhx1999.top/Article/details/gtejbobngf.html

[R63] 内存与进程
来源：http://dali.ydzc1.top/Article/details/gtybwezelo.html

free -h;  ps aux | grep nginx
来源：http://dali.zhengqikj.top/Article/details/gtpqljqhqx.html

[R64] 结束进程
来源：http://dali.zdqjudy.top/Article/details/gtncwyyoqt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cheryme.top/Article/details/gtzyzgfyso.html

[R65] 查看端口占用
来源：http://dali.zhixingplan.top/Article/details/gtfxqnpsen.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aibaodan.cn/Article/details/gtxvwkzweg.html

[R66] 定时任务
来源：http://dali.cucudq.cn/Article/details/gtebncmgof.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gtduqwhkaq.html

[R67] 生成随机十六进制串
来源：http://dali.jyoumei.cn/Article/details/gtogbnhhdm.html

openssl rand -hex 16
来源：http://dali.cdnleiting.top/Article/details/gttqbcrqua.html

[R68] 计算文件校验值
来源：http://dali.tanke756.top/Article/details/gtepuxjuss.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ppjwa.cn/Article/details/gtgwxmrdrv.html

[R69] 生成随机密码
来源：http://dali.vqdsnc.cn/Article/details/gtpfmwgdkm.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gtteofflku.html

[R70] 时间戳与互转
来源：http://dali.dashuyun.cn/Article/details/gtcdivykei.html

date +%s;  date -d @1700000000
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpkvujln.html

[R71] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtoueqcryt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.bjfxy.top/Article/details/gtbdnnihgu.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gtqengkocr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gtclkzsvou.html

[R73] 分割大日志
来源：http://dali.birdmap.top/Article/details/gtokvqwpuh.html

split -l 1000 big.log part_
来源：http://dali.jinqigufen.top/Article/details/gtlybkepbe.html

[R74] 批量重命名
来源：http://dali.sxryk.cn/Article/details/gtvdrbuezi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dashuyun.cn/Article/details/gtdrctqdwb.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gtjtrmbeqd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gtatugpiuq.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gtlijawsne.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gtlwlywimj.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gteolzefyx.html

read -rp "请输入: " ans
来源：http://dali.cqqwz.cn/Article/details/gttqeirfvi.html

[R78] 交互式菜单
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvithhwpg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.smart0.xyz/Article/details/gtheuznhbm.html

[R79] 解析命令行选项
来源：http://dali.chenzaomai.com/Article/details/gtnijuzbzh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgufenzy.top/Article/details/gtytfntmhe.html

[R80] 查看脚本执行耗时
来源：http://dali.zhongyouzk.top/Article/details/gtulmumnrh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gtiymzzzsd.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtfhnoagyv.html

S. C / C++ 专题
来源：http://dali.yueranfly.top/Article/details/gtahyttvcc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtvnpkwnws.html

[S01] C：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtutzvajbm.html

#include <stdio.h>
来源：http://dali.9152youxi.cn/Article/details/gtexrkpszl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gotoacloud.top/Article/details/gtzjbhapqy.html

[S02] C：变量与格式化输出
来源：http://dali.xylfe.cn/Article/details/gtdlbuufti.html

int a = 10; printf("%d\n", a);
来源：http://dali.jlsjyb.cn/Article/details/gtkmkylbaa.html

[S03] C：读入整数
来源：http://dali.gaohongyu789.top/Article/details/gtcvmkmrys.html

int x; scanf("%d", &x);
来源：http://dali.daria6918.cn/Article/details/gtjnycllpy.html

[S04] C：字符串复制
来源：http://dali.ybcxt.top/Article/details/gtqsuucffd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sufxvd.cn/Article/details/gttpojyarq.html

[S05] C：字符串长度
来源：http://dali.yongpay.top/Article/details/gtnjuwxpdx.html

strlen(s)
来源：http://dali.gzhubu.top/Article/details/gtzxutaemp.html

[S06] C：字符串比较
来源：http://dali.sxryk.cn/Article/details/gtjlshlzlb.html

strcmp(a, b) == 0
来源：http://dali.c1oappe.top/Article/details/gtzmivscjl.html

[S07] C：数组遍历求和
来源：http://dali.hnxiangtu.top/Article/details/gtercujiot.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrgvgsvj.html

[S08] C：动态内存分配与释放
来源：http://dali.kuanghao11.cn/Article/details/gtqrjlenbh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xinyue.icu/Article/details/gtmelypsfr.html

[S09] C：结构体定义与初始化
来源：http://dali.gotoacloud.top/Article/details/gtiupznulo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hfpthk.cn/Article/details/gttclinnay.html

[S10] C：指针与解引用
来源：http://dali.xylfe.cn/Article/details/gtcbpwjpjk.html

int *p = &a;  *p = 5;
来源：http://dali.smart0.xyz/Article/details/gtwndbazto.html

[S11] C：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtsnodhfhd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gtblcganup.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gtxqvgfbbn.html

fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtcmxxzbxu.html

[S12] C：写文件
来源：http://dali.0kj1m.cn/Article/details/gtkyiunsxm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtixhsarsy.html

[S13] C：宏定义
来源：http://dali.0kj1m.cn/Article/details/gttnfuhegm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gtxnbmeemm.html

[S14] C：枚举
来源：http://dali.fengsongda.top/Article/details/gtxicapbpy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.9152youxi.cn/Article/details/gtywclrvdt.html

[S15] C：类型转换
来源：http://dali.jianghu66.top/Article/details/gtjlphltma.html

(double) a / b
来源：http://dali.meibo888.top/Article/details/gttnginbkq.html

[S16] C：位操作置位
来源：http://dali.quarkkingdee.top/Article/details/gtgdcarrse.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtzsapunpf.html

[S17] C：安全拼接字符串
来源：http://dali.birdmap.top/Article/details/gtxxqueeoo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aibaodan.cn/Article/details/gthntfbpdr.html

[S18] C：命令行参数
来源：http://dali.birdmap.top/Article/details/gthqwqujye.html

int main(int argc, char **argv)
来源：http://dali.cheryme.top/Article/details/gtraupmjwg.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gtnxmlhfgo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gtttytllcd.html

[S20] C：二分查找
来源：http://dali.zdqjudy.top/Article/details/gtwzzdtbvm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gtndgxryju.html

[S21] C：字符类别判断
来源：http://dali.daria6918.cn/Article/details/gtcaksxylu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fengsongda.top/Article/details/gtricykmfc.html

[S22] C：字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfoypngmh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tianlin.xyz/Article/details/gtpgajhzkn.html

[S23] C：随机数
来源：http://dali.jinqigufen.top/Article/details/gtjbbzxzxs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yonumen.top/Article/details/gtbbtohwdz.html

[S24] C：获取本地时间
来源：http://dali.havefunace.top/Article/details/gtctuqxlfw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cheryme.top/Article/details/gtbptwnurg.html

[S25] C：内存拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtcwcxoava.html

memcpy(dst, src, n);
来源：http://dali.yongpay.top/Article/details/gtzoohakwi.html

[S26] C：内存清零
来源：http://dali.guowangkeji.top/Article/details/gtzbvvvdrw.html

memset(a, 0, sizeof a);
来源：http://dali.tianlin.xyz/Article/details/gtmhegjwts.html

[S27] C：定义常量
来源：http://dali.zycfv.cn/Article/details/gtcotjfgxl.html

const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtvqgmomlr.html

[S28] C：静态变量
来源：http://dali.hfpthk.cn/Article/details/gtavdkzksy.html

static int counter = 0;
来源：http://dali.havefunace.top/Article/details/gtfoyqzkwp.html

[S29] C：变参函数
来源：http://dali.daria6918.cn/Article/details/gtwuwqiyxj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yongpay.top/Article/details/gtqytlqpdw.html

[S30] C：头文件保护
来源：http://dali.jiagoushi.top/Article/details/gtinzblodh.html

#ifndef X_H
来源：http://dali.zhiwuduotai.top/Article/details/gtzjyuaqpe.html

#define X_H
来源：http://dali.zycfv.cn/Article/details/gthdbvkkhl.html

#endif
来源：http://dali.zhiwuduotai.top/Article/details/gtianiedrj.html

[S31] C++：Hello World
来源：http://dali.c1oappe.top/Article/details/gttvrpwaxo.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gthfnvqgxn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sweek.top/Article/details/gtqpxlfmav.html

[S32] C++：字符串
来源：http://dali.gogol.net.cn/Article/details/gtolgpepzk.html

std::string s = "hi";  s += "!";
来源：http://dali.gzhubu.top/Article/details/gtayunlaml.html

[S33] C++：vector 增删
来源：http://dali.jqgufenzy.top/Article/details/gtwlkxwcvs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangdashe.top/Article/details/gtddqboqro.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gtfewblghl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gtfyedtzlq.html


<!-- 参考信息 -->