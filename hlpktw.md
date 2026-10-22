代发 wailian999

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gtegyjukvq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gtuaaifvpy.html

[Q64] 提交事务
来源：http://dali.chenlongwang.top/Article/details/gtnkutqhks.html

COMMIT;
来源：http://dali.sweek.top/Article/details/gtpghtlidh.html

[Q65] 回滚事务
来源：http://dali.sufxvd.cn/Article/details/gthizstcqe.html

ROLLBACK;
来源：http://dali.ppjwa.cn/Article/details/gtopcxtmdk.html

[Q66] 行锁查询
来源：http://dali.nwbrower.top/Article/details/gtbbplwnmc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daxiang520.top/Article/details/gtjmxoulmb.html

[Q67] 设置隔离级别
来源：http://dali.aibaodan.cn/Article/details/gtbfwnkdbn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxuanxn.top/Article/details/gtjelyovrm.html

[Q68] 保存点
来源：http://dali.xylfe.cn/Article/details/gtywlkzuzd.html

SAVEPOINT sp1;
来源：http://dali.cheryme.top/Article/details/gtekjuydya.html

ROLLBACK TO sp1;
来源：http://dali.sweek.top/Article/details/gtydyjapju.html

[Q69] 查看执行计划
来源：http://dali.zhengqikj.top/Article/details/gtprprnkdt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gtyrdxoxdk.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gtigehsjxm.html

ANALYZE TABLE users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuemitnoz.html

[Q71] 查看建表语句
来源：http://dali.jqgufenzy.top/Article/details/gtdgtsttck.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yonumen.top/Article/details/gtdqraccsp.html

[Q72] 查看索引
来源：http://dali.cucudq.cn/Article/details/gtdyreazyy.html

SHOW INDEX FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtbbssjrkx.html

[Q73] 查看表状态
来源：http://dali.vqdsnc.cn/Article/details/gtlelpjarn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gtbpzgznht.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gtbgvpfbao.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gotoacloud.top/Article/details/gtkimvketg.html

[Q75] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtmwiwmplf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtkctnbxim.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hammf.cn/Article/details/gtgrunoijx.html

[Q76] 按天统计
来源：http://dali.mhx1999.top/Article/details/gtwdfykyjg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfrnkmfh.html

[Q77] 时间加减
来源：http://dali.feifeiyinyue.top/Article/details/gtnkzkoorw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tianlin.xyz/Article/details/gtwpmbftdm.html

[Q78] 当前时间
来源：http://dali.tanke756.top/Article/details/gtulzucqxe.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xziqi.cn/Article/details/gtofqemujr.html

[Q79] 字符串拼接
来源：http://dali.meibo888.top/Article/details/gtujbdnwga.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnqzz.top/Article/details/gtwagcciok.html

[Q80] 字符串截取
来源：http://dali.zhongyouzk.top/Article/details/gtejllnuvz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtcznmsldp.html

[Q81] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gtjxuttxao.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtogblbhhr.html

[Q82] 字符长度与字节长度
来源：http://dali.yueranfly.top/Article/details/gtqykrxcmy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtalrarqkh.html

[Q83] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtsiqcnyjb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtfrlwjrml.html

[Q84] 去除首尾空格
来源：http://dali.xinyue.icu/Article/details/gtwhrbhxeo.html

SELECT TRIM(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtiyqckcoz.html

[Q85] 数值取整
来源：http://dali.gaohongyu789.top/Article/details/gtbcczjelj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.smart0.xyz/Article/details/gtypamofvl.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gttjsjybwr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ybcxt.top/Article/details/gthakaimqf.html

[Q87] JSON 字段做条件
来源：http://dali.shangyingyoupin.top/Article/details/gtllpcolud.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hywenlv.cn/Article/details/gtvronudzb.html

[Q88] 行转列（条件聚合）
来源：http://dali.vqdsnc.cn/Article/details/gtqfdtlcau.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangdashe.top/Article/details/gtfaiegrno.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtltonqczz.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gtzvlppade.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tanke756.top/Article/details/gttpstyqze.html

[Q90] 生成序号列
来源：http://dali.sysykeji.top/Article/details/gtiwqmgnvz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sysykeji.top/Article/details/gtnrrhppnq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtyxajjazr.html

R. Bash 专题
来源：http://dali.zdqjudy.top/Article/details/gtwiwugxvu.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxtldpmnl.html

[R01] shebang 与严格模式
来源：http://dali.hfpthk.cn/Article/details/gtbmtsyfcq.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gtwmbibsvg.html

set -euo pipefail
来源：http://dali.9152youxi.cn/Article/details/gtmjqmmgmb.html

[R02] 变量赋值与使用
来源：http://dali.xuanzx.com/Article/details/gtoeduwvls.html

name="Tom"; echo "$name"
来源：http://dali.zycfv.cn/Article/details/gtofdvxvws.html

[R03] 只读变量
来源：http://dali.quarkkingdee.top/Article/details/gtwjgqcsuj.html

readonly PI=3.14
来源：http://dali.quarkkingdee.top/Article/details/gtamtqwori.html

[R04] 位置参数
来源：http://dali.birdmap.top/Article/details/gttabienfk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tian-w.cn/Article/details/gteokvdgwm.html

[R05] 参数默认值
来源：http://dali.guannengcc.top/Article/details/gtgbthczfj.html

name="${1:-default}"
来源：http://dali.iojbl.cn/Article/details/gtzwrhrizh.html

[R06] 判断命令是否存在
来源：http://dali.mhx1999.top/Article/details/gtsnbgukgq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlzvbkcef.html

[R07] if 判断文件
来源：http://dali.kuanghao11.cn/Article/details/gtxupcdmjk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuxming.cn/Article/details/gtwbykoklh.html

[R08] 数值比较
来源：http://dali.bjfxy.top/Article/details/gttxbczrrx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yueranfly.top/Article/details/gtwamxdbqv.html

[R09] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtxdtstwoo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yangfankeji.com/Article/details/gtvbzhuwwz.html

[R10] 正则匹配
来源：http://dali.jyoumei.cn/Article/details/gtlugvedmt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guannengcc.top/Article/details/gtnaaialec.html

[R11] case 多分支
来源：http://dali.zhixingplan.top/Article/details/gtershmivs.html

case "$1" in
来源：http://dali.redwolf501.top/Article/details/gtuyinjleg.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtlupacgot.html

stop)  echo "停止" ;;
来源：http://dali.andypj.xyz/Article/details/gtvysancfb.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gtveadocix.html

esac
来源：http://dali.fzhhl.top/Article/details/gtmuyuiygq.html

[R12] for 遍历文件
来源：http://dali.mhx1999.top/Article/details/gtwdhyqxac.html

for f in *.txt; do echo "$f"; done
来源：http://dali.redwolf501.top/Article/details/gtvsabitwn.html

[R13] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gtrxugvanx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gtgchuuzjy.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gtlouqluge.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gtbzcsriml.html

[R15] while 逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtuzrwfjcq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangdashe.top/Article/details/gtjzrtbbrk.html

[R16] until 等待条件
来源：http://dali.mhx1999.top/Article/details/gtthzategj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtotjdhobh.html

[R17] 数组定义与取值
来源：http://dali.meibo888.top/Article/details/gtbvvouvvb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cashguo.top/Article/details/gtwzyepnmc.html

[R18] 遍历数组
来源：http://dali.cheryme.top/Article/details/gtaparxmef.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hfpthk.cn/Article/details/gtfshhayoh.html

[R19] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gtmnbsofca.html

echo "${#arr[@]}"
来源：http://dali.aizwys.cn/Article/details/gtvwybtyqu.html

[R20] 关联数组（字典）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyyhnvpkk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtbravoovr.html

[R21] 字符串长度
来源：http://dali.yj202588.top/Article/details/gtqcswqebf.html

echo "${#s}"
来源：http://dali.tanke756.top/Article/details/gtdnroxslm.html

[R22] 截取子串
来源：http://dali.316326.xyz/Article/details/gtvpwrqxkm.html

echo "${s:0:5}"
来源：http://dali.birdmap.top/Article/details/gtakmsfxfw.html

[R23] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gtzpowcgvy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.feifeiyinyue.top/Article/details/gtxexlxxrz.html

[R24] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gttsbufdjl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dianchejie.cn/Article/details/gtrziswsoh.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj202588.top/Article/details/gtqhfrqtma.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.havefunace.top/Article/details/gtwbfxtwfg.html

[R26] 命令替换
来源：http://dali.gogol.net.cn/Article/details/gtumrlsoao.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gtuxohnbwr.html

[R27] 算术展开
来源：http://dali.yuanzhike.top/Article/details/gtcqfefzzm.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtisieehcm.html

[R28] 浮点运算
来源：http://dali.jyoumei.cn/Article/details/gtsirycuxd.html

echo "scale=2; 10/3" | bc
来源：http://dali.fzhhl.top/Article/details/gtrkhnxvdx.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gtckrvgspm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ivvv.top/Article/details/gtsxhyiqcd.html

[R30] 函数返回状态码
来源：http://dali.zdqjudy.top/Article/details/gtolucfdjx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.smart0.xyz/Article/details/gtfnlarlsw.html

[R31] 局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgufwgba.html

f() { local x=1; echo "$x"; }
来源：http://dali.hfpthk.cn/Article/details/gtunwdtwyw.html

[R32] 参数个数校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoemzgdku.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gtyoynyaaz.html

[R33] 捕获错误并提示行号
来源：http://dali.andypj.xyz/Article/details/gtiohzysfh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.meibo888.top/Article/details/gtxjcfmkmd.html

[R34] 退出时清理
来源：http://dali.chenlongwang.top/Article/details/gtiufuewiy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtxukvlqnm.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gttsqftdnx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuanzhike.top/Article/details/gtosskkqip.html

[R36] 并发执行多个任务
来源：http://dali.cucudq.cn/Article/details/gtctizaziw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhiwuduotai.top/Article/details/gtddlaruxv.html

[R37] 把输出赋给变量
来源：http://dali.jinqigfzy.top/Article/details/gtbitahpop.html

files=$(ls -1)
来源：http://dali.xinyue.icu/Article/details/gtxdrprguc.html

[R38] 管道串联
来源：http://dali.tanke756.top/Article/details/gtnrfwgdlp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sufxvd.cn/Article/details/gtgywsnedu.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258888.top/Article/details/gtqgihtpxm.html

cmd > out.log 2>&1
来源：http://dali.bjfxy.top/Article/details/gtsgiphzyv.html

[R40] 追加写日志
来源：http://dali.hfpthk.cn/Article/details/gtkacsepvm.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gtpgmzwqtk.html

[R41] 丢弃输出
来源：http://dali.ppjwa.cn/Article/details/gtrpnsvxgn.html

cmd >/dev/null 2>&1
来源：http://dali.cdnleiting.top/Article/details/gthzpaoqes.html

[R42] 输入重定向
来源：http://dali.birdmap.top/Article/details/gtsijvdvtg.html

wc -l < a.txt
来源：http://dali.tian-w.cn/Article/details/gtibbopoli.html

[R43] 按名字查找文件
来源：http://dali.chenlongwang.top/Article/details/gtofmncvpg.html

find . -name "*.log" -type f
来源：http://dali.sufxvd.cn/Article/details/gtolkqbrdv.html

[R44] 按修改时间查找
来源：http://dali.fzhhl.top/Article/details/gtfueuhoyo.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndkwtmrp.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gtaycavcuj.html

find . -name "*.tmp" -delete
来源：http://dali.zycfv.cn/Article/details/gtmwwbnxas.html

[R46] 递归替换文件内容
来源：http://dali.guannengcc.top/Article/details/gtyrjyxqdw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gzhubu.top/Article/details/gthjlknari.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gtekujnfgw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtavddibfr.html

[R48] awk 取指定列
来源：http://dali.bjfxy.top/Article/details/gtifmqaldh.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtunbqcqke.html

[R49] awk 带条件
来源：http://dali.tian-w.cn/Article/details/gtdffspebq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ydzc1.top/Article/details/gtsqcbmjhb.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gtyjggfgkj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fzhhl.top/Article/details/gtaimojpuf.html

[R51] 排序去重取前几
来源：http://dali.zhengqikj.top/Article/details/gtgutdswnn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yongpay.top/Article/details/gtsiyjtaon.html

[R52] 统计行数
来源：http://dali.birdmap.top/Article/details/gtdgfekarl.html

wc -l a.txt
来源：http://dali.316326.xyz/Article/details/gtqvkzxmir.html

[R53] 查看文件头与实时尾
来源：http://dali.gogol.net.cn/Article/details/gtghricfho.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258.top/Article/details/gtwhhnfpor.html

[R54] 比较两个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtrdclqzfd.html

diff a.txt b.txt
来源：http://dali.xziqi.cn/Article/details/gtkibgezmz.html

[R55] 压缩与解压
来源：http://dali.haohaochexian.top/Article/details/gtrhkbmivn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aibaodan.cn/Article/details/gtpihemgck.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gtelkoldta.html

scp file user@host:/path/
来源：http://dali.shangyingyoupin.top/Article/details/gtotdoaarf.html

[R57] 远程执行命令
来源：http://dali.fengsongda.top/Article/details/gtwsjdrcjb.html

ssh user@host 'uptime'
来源：http://dali.ydzc1.top/Article/details/gtskwyknyk.html

[R58] 下载文件
来源：http://dali.sysykeji.top/Article/details/gtbjmcwiyg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dashuyun.cn/Article/details/gtugmnpuza.html

[R59] 发 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gtiodcmhdt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.feifeiyinyue.top/Article/details/gtjfpktsqp.html

[R60] 只看 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gthdkexyri.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gtbtkjoptv.html

[R61] 磁盘占用
来源：http://dali.yongpay.top/Article/details/gtltzikncq.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gtmvyuvbzw.html

[R62] 找最占空间的文件
来源：http://dali.yvedp.cn/Article/details/gttukwoivb.html

du -ah . | sort -rh | head -10
来源：http://dali.yanxiufei.cn/Article/details/gtipyskplw.html

[R63] 内存与进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrfqaivp.html

free -h;  ps aux | grep nginx
来源：http://dali.cashguo.top/Article/details/gtzexwgmcn.html

[R64] 结束进程
来源：http://dali.gogol.net.cn/Article/details/gtopmfcthf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.mhx1999.top/Article/details/gtkpbcpkgn.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gtiziimait.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yvedp.cn/Article/details/gtvpfprbwh.html

[R66] 定时任务
来源：http://dali.hfpthk.cn/Article/details/gtcmkolqwd.html

crontab -e;  crontab -l
来源：http://dali.jinqigufen.top/Article/details/gtlgnlonws.html

[R67] 生成随机十六进制串
来源：http://dali.sweek.top/Article/details/gtekxyppvh.html

openssl rand -hex 16
来源：http://dali.meibo888.top/Article/details/gttkwuamhe.html

[R68] 计算文件校验值
来源：http://dali.yanxiufei.cn/Article/details/gtozelngsu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtopkggkfl.html

[R69] 生成随机密码
来源：http://dali.hywenlv.cn/Article/details/gteftskoex.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhongyouzk.top/Article/details/gthhhzzrrk.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gtwgryiejv.html

date +%s;  date -d @1700000000
来源：http://dali.aizwys.cn/Article/details/gtnycimxwv.html

[R71] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtvdoyfxou.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhengqikj.top/Article/details/gtlqcrmjop.html

[R72] 等待端口就绪
来源：http://dali.jianghu66.top/Article/details/gthbuwdjff.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gtfewfcfkv.html

[R73] 分割大日志
来源：http://dali.iojbl.cn/Article/details/gtmbjjpfky.html

split -l 1000 big.log part_
来源：http://dali.yuanzhike.top/Article/details/gtavrtlytp.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gtrovfpluy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ydzc1.top/Article/details/gtktldweuj.html

[R75] 导出环境变量
来源：http://dali.xinyue.icu/Article/details/gtvnpaokyi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ydzc1.top/Article/details/gtbwxalhfx.html

[R76] 使用临时文件
来源：http://dali.nwbrower.top/Article/details/gtnahntdpj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gtuiiijbho.html

[R77] 读取用户输入
来源：http://dali.kuanghao11.cn/Article/details/gtfmvlvwnm.html

read -rp "请输入: " ans
来源：http://dali.tian-w.cn/Article/details/gtyaewjynv.html

[R78] 交互式菜单
来源：http://dali.yj20258888.top/Article/details/gtgtswcxsk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yvedp.cn/Article/details/gtknbkhbot.html

[R79] 解析命令行选项
来源：http://dali.birdmap.top/Article/details/gtqkgjiuts.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gtptnfvouz.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gtouxfptjq.html

time ./run.sh
来源：http://dali.jlsjyb.cn/Article/details/gtclgykijd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gttzyjxjul.html

S. C / C++ 专题
来源：http://dali.sweek.top/Article/details/gtzqxjnfrn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtbeyeotzg.html

[S01] C：Hello World
来源：http://dali.tanke756.top/Article/details/gtbsweoqul.html

#include <stdio.h>
来源：http://dali.hongshengwenyu.top/Article/details/gtjelcbdhg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.0kj1m.cn/Article/details/gtgfrlfffl.html

[S02] C：变量与格式化输出
来源：http://dali.yonumen.top/Article/details/gtwwhdgjdg.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenzaomai.com/Article/details/gtcaukjlzh.html

[S03] C：读入整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjiwevjc.html

int x; scanf("%d", &x);
来源：http://dali.sufxvd.cn/Article/details/gtfnancrvr.html

[S04] C：字符串复制
来源：http://dali.fengsongda.top/Article/details/gtbzbfddon.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.mhx1999.top/Article/details/gtrmzvbkjk.html

[S05] C：字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gtcsfnyoeb.html

strlen(s)
来源：http://dali.havefunace.top/Article/details/gtxqzenepy.html

[S06] C：字符串比较
来源：http://dali.yj202588.top/Article/details/gtkjrzrvmy.html

strcmp(a, b) == 0
来源：http://dali.sysykeji.top/Article/details/gtbbkwleqy.html

[S07] C：数组遍历求和
来源：http://dali.jyoumei.cn/Article/details/gtthbvzwdh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.0kj1m.cn/Article/details/gtpyoahhli.html

[S08] C：动态内存分配与释放
来源：http://dali.ybcxt.top/Article/details/gtsomqnoyl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.birdmap.top/Article/details/gtubcyyryt.html

[S09] C：结构体定义与初始化
来源：http://dali.9152youxi.cn/Article/details/gtuinyiqhg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yanxiufei.cn/Article/details/gthlwyeeyx.html

[S10] C：指针与解引用
来源：http://dali.sweek.top/Article/details/gtweajlhlq.html

int *p = &a;  *p = 5;
来源：http://dali.pengpengdd.cyou/Article/details/gtcgzkgfvd.html

[S11] C：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtklkxukgp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinghuilouyu.cn/Article/details/gtbimzbdds.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtpdptbjsd.html

fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtxludfuaq.html

[S12] C：写文件
来源：http://dali.guowangkeji.top/Article/details/gthwmzkbuc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gtkjpqwkai.html

[S13] C：宏定义
来源：http://dali.yj20258888.top/Article/details/gtilslxxyl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gthwbtephj.html

[S14] C：枚举
来源：http://dali.cashguo.top/Article/details/gtofaethns.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daria6918.cn/Article/details/gtmmsktyvu.html

[S15] C：类型转换
来源：http://dali.zhongyouzk.top/Article/details/gtiffruzti.html

(double) a / b
来源：http://dali.nanxuanxn.top/Article/details/gtxzwnsxhn.html

[S16] C：位操作置位
来源：http://dali.gaohongyu789.top/Article/details/gtdqlceldd.html

x |= (1 << 3);
来源：http://dali.cheryme.top/Article/details/gtvksehpbq.html

[S17] C：安全拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtwfiwwfjb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangtech.top/Article/details/gttnkcvpwe.html

[S18] C：命令行参数
来源：http://dali.yueranfly.top/Article/details/gtqimszgtz.html

int main(int argc, char **argv)
来源：http://dali.xylfe.cn/Article/details/gtvpjpjiww.html

[S19] C：快速排序
来源：http://dali.chenzaomai.com/Article/details/gtdxlmilxt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gtlduuojln.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gtrbbfgevk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gtyzuxgrom.html

[S21] C：字符类别判断
来源：http://dali.haohaochexian.top/Article/details/gtjvfvlnmw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cashguo.top/Article/details/gtgrwrqvtm.html

[S22] C：字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gtevanmpdj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yonumen.top/Article/details/gtkgawofcq.html

[S23] C：随机数
来源：http://dali.bjfxy.top/Article/details/gtwmrasbzq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.birdmap.top/Article/details/gtsonsmvpm.html

[S24] C：获取本地时间
来源：http://dali.iojbl.cn/Article/details/gtfhlbokhm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gtwebgaukn.html

[S25] C：内存拷贝
来源：http://dali.yuxming.cn/Article/details/gttkqiaazd.html

memcpy(dst, src, n);
来源：http://dali.cdnleiting.top/Article/details/gtebxaaccy.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gtcresfmuq.html

memset(a, 0, sizeof a);
来源：http://dali.xylfe.cn/Article/details/gtfiyhixqn.html

[S27] C：定义常量
来源：http://dali.dianchejie.cn/Article/details/gtzijlxnws.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtcwucrpmc.html

[S28] C：静态变量
来源：http://dali.xuanzx.com/Article/details/gtnqnxosss.html

static int counter = 0;
来源：http://dali.redwolf501.top/Article/details/gtrfkariqf.html

[S29] C：变参函数
来源：http://dali.guannengcc.top/Article/details/gteakgwcqd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cucudq.cn/Article/details/gtjqyhiwzp.html

[S30] C：头文件保护
来源：http://dali.ehwqpu.com/Article/details/gtclofdjuz.html

#ifndef X_H
来源：http://dali.wangdashe.top/Article/details/gtassmljdk.html

#define X_H
来源：http://dali.9152youxi.cn/Article/details/gtcfuszehs.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gtteinfjsy.html

[S31] C++：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtyceizcfc.html

#include <iostream>
来源：http://dali.zycfv.cn/Article/details/gtkfbfebxm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxwawrrb.html

[S32] C++：字符串
来源：http://dali.vqdsnc.cn/Article/details/gtleysboex.html

std::string s = "hi";  s += "!";
来源：http://dali.gzhubu.top/Article/details/gtsaklsuwg.html


<!-- 参考信息 -->