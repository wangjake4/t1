代发 wailian999

[Q63] 开启事务
来源：http://dali.yueranfly.top/Article/details/gtxrtipsse.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yangfankeji.com/Article/details/gtlqskfmfd.html

[Q64] 提交事务
来源：http://dali.tianlin.xyz/Article/details/gtqwfqodhe.html

COMMIT;
来源：http://dali.yj20258.top/Article/details/gtyexxcuhu.html

[Q65] 回滚事务
来源：http://dali.nanxinkj.top/Article/details/gtsisaorpb.html

ROLLBACK;
来源：http://dali.tian-w.cn/Article/details/gtbligiebn.html

[Q66] 行锁查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbwgclfo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yongpay.top/Article/details/gtistjqrui.html

[Q67] 设置隔离级别
来源：http://dali.tianlin.xyz/Article/details/gtovzughiq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hfpthk.cn/Article/details/gtwedjwmzw.html

[Q68] 保存点
来源：http://dali.kuanghao11.cn/Article/details/gtcbaonqkl.html

SAVEPOINT sp1;
来源：http://dali.jqgufenzy.top/Article/details/gtxnvoclgd.html

ROLLBACK TO sp1;
来源：http://dali.tianlin.xyz/Article/details/gtkbbiibtf.html

[Q69] 查看执行计划
来源：http://dali.nwbrower.top/Article/details/gtspujrijw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.smart0.xyz/Article/details/gtkdvvpegv.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gtclyjdvci.html

ANALYZE TABLE users;
来源：http://dali.meibo888.top/Article/details/gtqhrqbmsv.html

[Q71] 查看建表语句
来源：http://dali.svipenyu.cn/Article/details/gthfaegfmv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jyoumei.cn/Article/details/gtgpblwstl.html

[Q72] 查看索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfltvjuol.html

SHOW INDEX FROM users;
来源：http://dali.sxryk.cn/Article/details/gtnybqqcer.html

[Q73] 查看表状态
来源：http://dali.c1oappe.top/Article/details/gtscismgar.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jlsjyb.cn/Article/details/gtkjtjqizz.html

[Q74] 强制使用索引
来源：http://dali.gzhubu.top/Article/details/gtpslwphbu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sysykeji.top/Article/details/gtevpmfvbo.html

[Q75] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gtuisoiass.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsprahwfr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gzhubu.top/Article/details/gtttusovnu.html

[Q76] 按天统计
来源：http://dali.316326.xyz/Article/details/gtjzondlxt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yongpay.top/Article/details/gthvnhiptz.html

[Q77] 时间加减
来源：http://dali.yongpay.top/Article/details/gtdxryvyzl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgfzy.top/Article/details/gtxnvzrgan.html

[Q78] 当前时间
来源：http://dali.guannengcc.top/Article/details/gtmakxuexb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.kuanghao11.cn/Article/details/gtttbstvqj.html

[Q79] 字符串拼接
来源：http://dali.fengsongda.top/Article/details/gthazyqpda.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gtjlbgmysy.html

[Q80] 字符串截取
来源：http://dali.hongshengwenyu.top/Article/details/gtnjeovuds.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtcjxxogop.html

[Q81] 字符串替换
来源：http://dali.ivvv.top/Article/details/gtddapxoey.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuxming.cn/Article/details/gtanrbhnrd.html

[Q82] 字符长度与字节长度
来源：http://dali.zhiwuduotai.top/Article/details/gtfhtwtomi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtprkfkcof.html

[Q83] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gtwtwafanf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtneyosser.html

[Q84] 去除首尾空格
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlunnidlj.html

SELECT TRIM(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtcmteinpp.html

[Q85] 数值取整
来源：http://dali.yangfankeji.com/Article/details/gtqkutqjqb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuxming.cn/Article/details/gtgsgfxkfn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhengqikj.top/Article/details/gtjylxdthp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.iojbl.cn/Article/details/gthwyrpcbs.html

[Q87] JSON 字段做条件
来源：http://dali.ppjwa.cn/Article/details/gtgmdtfszw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.kuanghao11.cn/Article/details/gtshqeylwj.html

[Q88] 行转列（条件聚合）
来源：http://dali.0kj1m.cn/Article/details/gtxpfkajtg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xylfe.cn/Article/details/gtgvfcqmri.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtzmcqfpfb.html

[Q89] 判断表是否存在
来源：http://dali.guowangkeji.top/Article/details/gtbqpuzqhq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.mhx1999.top/Article/details/gtxrqwdwzy.html

[Q90] 生成序号列
来源：http://dali.chenlongwang.top/Article/details/gttinadpbh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuanzhike.top/Article/details/gttfpuzfpf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtnhmvetkg.html

R. Bash 专题
来源：http://dali.mhx1999.top/Article/details/gtrspokocv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlnmtmch.html

[R01] shebang 与严格模式
来源：http://dali.jiagoushi.top/Article/details/gtvwxesaug.html

#!/usr/bin/env bash
来源：http://dali.zycfv.cn/Article/details/gtsovyncgb.html

set -euo pipefail
来源：http://dali.xinyue.icu/Article/details/gtuxcxvsru.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gttpxopmrv.html

name="Tom"; echo "$name"
来源：http://dali.shangyingyoupin.top/Article/details/gtrvllgrfo.html

[R03] 只读变量
来源：http://dali.guowangkeji.top/Article/details/gtzisrdwsl.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gtduyttxlq.html

[R04] 位置参数
来源：http://dali.dianchejie.cn/Article/details/gtaoxfgmda.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.haohaochexian.top/Article/details/gtrmqdpsbj.html

[R05] 参数默认值
来源：http://dali.zhixingplan.top/Article/details/gtfbfhhcfr.html

name="${1:-default}"
来源：http://dali.yanxiufei.cn/Article/details/gtyfaynsdh.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gtzzzwmvwx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gtpcksruqe.html

[R07] if 判断文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkphxcos.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sysykeji.top/Article/details/gtjqpuxqof.html

[R08] 数值比较
来源：http://dali.ydzc1.top/Article/details/gtfomhyomi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtyhqekihq.html

[R09] 字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtidgcpped.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gtsvioxlag.html

[R10] 正则匹配
来源：http://dali.cqqwz.cn/Article/details/gtnaxjnmnq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zycfv.cn/Article/details/gtihvkmgmk.html

[R11] case 多分支
来源：http://dali.pengpengdd.cyou/Article/details/gtjvrmdaff.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gtfmjtbwbb.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtpvacjnxw.html

stop)  echo "停止" ;;
来源：http://dali.yonumen.top/Article/details/gtwigbkcsu.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gtwvunkxlp.html

esac
来源：http://dali.cucudq.cn/Article/details/gtrqnfwwsc.html

[R12] for 遍历文件
来源：http://dali.aizwys.cn/Article/details/gtemejvdnr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtdckrcygp.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gthnicisuq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtboarjvgx.html

[R14] C 风格 for
来源：http://dali.316326.xyz/Article/details/gtwnkxaqzo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gtlhvbqrlx.html

[R15] while 逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtmskpvoar.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ivvv.top/Article/details/gtprabgpyn.html

[R16] until 等待条件
来源：http://dali.fzhhl.top/Article/details/gtvnubuumg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gtudmytfkg.html

[R17] 数组定义与取值
来源：http://dali.jinqigufen.top/Article/details/gtpwnbpygd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guannengcc.top/Article/details/gtqdtwwfga.html

[R18] 遍历数组
来源：http://dali.tanke756.top/Article/details/gtqwvvugjl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cqqwz.cn/Article/details/gtildzzkfn.html

[R19] 数组长度
来源：http://dali.yj20258888.top/Article/details/gtcrebdsmk.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gtjvyrqsxa.html

[R20] 关联数组（字典）
来源：http://dali.birdmap.top/Article/details/gtzrlparor.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuanzhike.top/Article/details/gteuyztwsj.html

[R21] 字符串长度
来源：http://dali.hammf.cn/Article/details/gtvzxmadhx.html

echo "${#s}"
来源：http://dali.jyoumei.cn/Article/details/gtoqdzfdqz.html

[R22] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gtuemboaxx.html

echo "${s:0:5}"
来源：http://dali.xuanzx.com/Article/details/gtmehuricq.html

[R23] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtchryeeib.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.smart0.xyz/Article/details/gtdhyboeeo.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtarpponfg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuanzx.com/Article/details/gtwmseptmm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtyjpxmwej.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuxming.cn/Article/details/gttpvrvddm.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gtrnqkjutx.html

now=$(date +%F); echo "$now"
来源：http://dali.yongpay.top/Article/details/gtoifyndmp.html

[R27] 算术展开
来源：http://dali.ybcxt.top/Article/details/gtmhwubcfe.html

echo $((1 + 2 * 3))
来源：http://dali.zhongyouzk.top/Article/details/gtkhaliavr.html

[R28] 浮点运算
来源：http://dali.zhixingplan.top/Article/details/gtrvnnryao.html

echo "scale=2; 10/3" | bc
来源：http://dali.zycfv.cn/Article/details/gtotbmcsgf.html

[R29] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtiopenxle.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gtxarsuzov.html

[R30] 函数返回状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtrhxhar.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gttzewwxuu.html

[R31] 局部变量
来源：http://dali.c1oappe.top/Article/details/gtywmnkzuo.html

f() { local x=1; echo "$x"; }
来源：http://dali.ehwqpu.com/Article/details/gtbslydzca.html

[R32] 参数个数校验
来源：http://dali.haohaochexian.top/Article/details/gttiqvdftn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgcmecqkm.html

[R33] 捕获错误并提示行号
来源：http://dali.316326.xyz/Article/details/gtbbhtofli.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pengpengdd.cyou/Article/details/gtrerabcpe.html

[R34] 退出时清理
来源：http://dali.gaohongyu789.top/Article/details/gtmmikiano.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtwahitcuz.html

[R35] 后台执行并等待
来源：http://dali.ybcxt.top/Article/details/gtqppyeubi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gotoacloud.top/Article/details/gtpohvozcc.html

[R36] 并发执行多个任务
来源：http://dali.haohaochexian.top/Article/details/gtlymrhlrt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sufxvd.cn/Article/details/gtzkaustea.html

[R37] 把输出赋给变量
来源：http://dali.sufxvd.cn/Article/details/gtgcaywsjx.html

files=$(ls -1)
来源：http://dali.yanxiufei.cn/Article/details/gtypkzvvqx.html

[R38] 管道串联
来源：http://dali.zhixingplan.top/Article/details/gtrisjbfmv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhoulong.xyz/Article/details/gtkvjhujon.html

[R39] 重定向标准输出与错误
来源：http://dali.wangdashe.top/Article/details/gtqdsrvlhl.html

cmd > out.log 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtazbpwbjl.html

[R40] 追加写日志
来源：http://dali.xuanzx.com/Article/details/gtmhrcwjhh.html

echo "log" >> out.log
来源：http://dali.ehwqpu.com/Article/details/gtzrhomlbh.html

[R41] 丢弃输出
来源：http://dali.ybcxt.top/Article/details/gtnunkhnoo.html

cmd >/dev/null 2>&1
来源：http://dali.cheryme.top/Article/details/gtcrqvlqgh.html

[R42] 输入重定向
来源：http://dali.daria6918.cn/Article/details/gtbkaxmkbe.html

wc -l < a.txt
来源：http://dali.shzxlz.cn/Article/details/gtjbrlhvex.html

[R43] 按名字查找文件
来源：http://dali.birdmap.top/Article/details/gtbrqivogx.html

find . -name "*.log" -type f
来源：http://dali.gzhubu.top/Article/details/gtsqtmfwbq.html

[R44] 按修改时间查找
来源：http://dali.ybcxt.top/Article/details/gtgtdtoucj.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvavirhj.html

[R45] 批量删除
来源：http://dali.jqgfzy.top/Article/details/gtuqjnfxfm.html

find . -name "*.tmp" -delete
来源：http://dali.wangdashe.top/Article/details/gtxmltucyd.html

[R46] 递归替换文件内容
来源：http://dali.chenzaomai.com/Article/details/gtdbyrljhm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yvedp.cn/Article/details/gtywxmjdwt.html

[R47] sed 单行替换
来源：http://dali.316326.xyz/Article/details/gthflyhybq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtnguqxoxv.html

[R48] awk 取指定列
来源：http://dali.vqdsnc.cn/Article/details/gtolucukqg.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258888.top/Article/details/gttnxopwfv.html

[R49] awk 带条件
来源：http://dali.vqdsnc.cn/Article/details/gtovcmsncp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xziqi.cn/Article/details/gtwhnztzvs.html

[R50] awk 求和
来源：http://dali.hammf.cn/Article/details/gtblhaannd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gzhubu.top/Article/details/gtnrcmagps.html

[R51] 排序去重取前几
来源：http://dali.hysaishi.cn/Article/details/gtkatcjzet.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yonumen.top/Article/details/gtvyhldnsb.html

[R52] 统计行数
来源：http://dali.jianghu66.top/Article/details/gtilnvbgqb.html

wc -l a.txt
来源：http://dali.ppjwa.cn/Article/details/gtdgmxvfgv.html

[R53] 查看文件头与实时尾
来源：http://dali.chenlongwang.top/Article/details/gtrufwepgc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daria6918.cn/Article/details/gtjlejavfx.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gtoivhbivn.html

diff a.txt b.txt
来源：http://dali.kuanghao11.cn/Article/details/gtnuxakrbu.html

[R55] 压缩与解压
来源：http://dali.gzhubu.top/Article/details/gtwlpvtwnd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yangfankeji.com/Article/details/gtowlhqspv.html

[R56] 远程拷贝
来源：http://dali.ivvv.top/Article/details/gtziqplpab.html

scp file user@host:/path/
来源：http://dali.zhengqikj.top/Article/details/gtgtszwedj.html

[R57] 远程执行命令
来源：http://dali.dashuyun.cn/Article/details/gtpjvhiauc.html

ssh user@host 'uptime'
来源：http://dali.svipenyu.cn/Article/details/gthxigyidp.html

[R58] 下载文件
来源：http://dali.yangfankeji.com/Article/details/gtfxrpbgdx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gtjlgxlgnf.html

[R59] 发 POST JSON
来源：http://dali.cheryme.top/Article/details/gtflctdusy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hysaishi.cn/Article/details/gtlxzznrxq.html

[R60] 只看 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gtuypjwqvr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gtifvpghne.html

[R61] 磁盘占用
来源：http://dali.gzhubu.top/Article/details/gtwstkfccj.html

df -h;  du -sh *
来源：http://dali.zhongyouzk.top/Article/details/gtrxxgqfug.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gteolbuovo.html

du -ah . | sort -rh | head -10
来源：http://dali.c1oappe.top/Article/details/gtnfqqpupk.html

[R63] 内存与进程
来源：http://dali.jqgfzy.top/Article/details/gtxjpgmogg.html

free -h;  ps aux | grep nginx
来源：http://dali.xylfe.cn/Article/details/gtuouwkksi.html

[R64] 结束进程
来源：http://dali.hammf.cn/Article/details/gtquwenwya.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tianlin.xyz/Article/details/gtiuqigpws.html

[R65] 查看端口占用
来源：http://dali.yvedp.cn/Article/details/gtryvucqcs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangdashe.top/Article/details/gtzgrqlptc.html

[R66] 定时任务
来源：http://dali.hnqzz.top/Article/details/gtdpworxfe.html

crontab -e;  crontab -l
来源：http://dali.pengpengdd.cyou/Article/details/gtfcokkzwh.html

[R67] 生成随机十六进制串
来源：http://dali.quarkkingdee.top/Article/details/gtarsktsso.html

openssl rand -hex 16
来源：http://dali.316326.xyz/Article/details/gtwvzpmrnu.html

[R68] 计算文件校验值
来源：http://dali.sufxvd.cn/Article/details/gtygsjgbfq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daria6918.cn/Article/details/gtyatccmli.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gtheiihhhg.html

head -c 16 /dev/urandom | base64
来源：http://dali.daria6918.cn/Article/details/gtzvtpzmwc.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gtcuqeosyq.html

date +%s;  date -d @1700000000
来源：http://dali.ivvv.top/Article/details/gtkeztvzba.html

[R71] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gtftyvghpw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangdashe.top/Article/details/gtgmwbkbsj.html

[R72] 等待端口就绪
来源：http://dali.jqgufenzy.top/Article/details/gtfvmxuaiy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtgajsviqx.html

[R73] 分割大日志
来源：http://dali.zhongyouzk.top/Article/details/gtpqqtuuas.html

split -l 1000 big.log part_
来源：http://dali.yj202588.top/Article/details/gtqpcrhbfj.html

[R74] 批量重命名
来源：http://dali.guannengcc.top/Article/details/gthkatxunr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenzaomai.com/Article/details/gtgldzfgdr.html

[R75] 导出环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtvkdlmtqt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ydzc1.top/Article/details/gtolfqjtex.html

[R76] 使用临时文件
来源：http://dali.9152youxi.cn/Article/details/gtfeajpgzo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtifamakgv.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlmpgczr.html

read -rp "请输入: " ans
来源：http://dali.snrcjt.cn/Article/details/gtfhqsbugf.html

[R78] 交互式菜单
来源：http://dali.xuanzx.com/Article/details/gtcdkchwcl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daria6918.cn/Article/details/gtappycczn.html

[R79] 解析命令行选项
来源：http://dali.ybcxt.top/Article/details/gtgbspccsp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shuidangran.top/Article/details/gtgjwdvshl.html

[R80] 查看脚本执行耗时
来源：http://dali.c1oappe.top/Article/details/gthvzzhjha.html

time ./run.sh
来源：http://dali.xziqi.cn/Article/details/gtkgjrgbzy.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtpfkougcg.html

S. C / C++ 专题
来源：http://dali.dashuyun.cn/Article/details/gtxipmrwjk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkksnjstu.html

[S01] C：Hello World
来源：http://dali.daria6918.cn/Article/details/gtzndnrlrt.html

#include <stdio.h>
来源：http://dali.pengpengdd.cyou/Article/details/gttrafqtpo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenzaomai.com/Article/details/gttsxsvvid.html

[S02] C：变量与格式化输出
来源：http://dali.yongpay.top/Article/details/gtzppzcahx.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gtcacxqffe.html

[S03] C：读入整数
来源：http://dali.zhoulong.xyz/Article/details/gtiwxfgsba.html

int x; scanf("%d", &x);
来源：http://dali.meibo888.top/Article/details/gtbhylfrjg.html

[S04] C：字符串复制
来源：http://dali.jiagoushi.top/Article/details/gttjtjagek.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nwbrower.top/Article/details/gtushqdezn.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gtzpframig.html

strlen(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtnbohdhne.html

[S06] C：字符串比较
来源：http://dali.daxiang520.top/Article/details/gtfenfvhok.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwdgvzfg.html

[S07] C：数组遍历求和
来源：http://dali.jqgfzy.top/Article/details/gtbesfcsmz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xylfe.cn/Article/details/gtjijcltlz.html

[S08] C：动态内存分配与释放
来源：http://dali.chenzaomai.com/Article/details/gtaemkzfxi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.quarkkingdee.top/Article/details/gtczjbdsxd.html

[S09] C：结构体定义与初始化
来源：http://dali.yuxming.cn/Article/details/gtyjjubqvr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gtrnqnzwui.html

[S10] C：指针与解引用
来源：http://dali.xylfe.cn/Article/details/gtytvyrpys.html

int *p = &a;  *p = 5;
来源：http://dali.gogol.net.cn/Article/details/gtihmdgubd.html

[S11] C：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtifjldqho.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhixingplan.top/Article/details/gtfuutmblz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cheryme.top/Article/details/gtfzfrqguv.html

fclose(f);
来源：http://dali.zycfv.cn/Article/details/gtfddidugx.html

[S12] C：写文件
来源：http://dali.gzhubu.top/Article/details/gtfbscnhxb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258888.top/Article/details/gtdpwomxbx.html

[S13] C：宏定义
来源：http://dali.hammf.cn/Article/details/gtfmauzrir.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtviedpdlt.html

[S14] C：枚举
来源：http://dali.mhx1999.top/Article/details/gtlcspgmps.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cheryme.top/Article/details/gtklleapwk.html

[S15] C：类型转换
来源：http://dali.gotoacloud.top/Article/details/gthchbiegr.html

(double) a / b
来源：http://dali.hnxiangtu.top/Article/details/gtauckiksc.html

[S16] C：位操作置位
来源：http://dali.aibaodan.cn/Article/details/gtnnsjkbry.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtxlzhqcjs.html

[S17] C：安全拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtpllyozhq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gtuyllykcl.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gtyiutdvei.html

int main(int argc, char **argv)
来源：http://dali.sysykeji.top/Article/details/gtrqzyjolp.html

[S19] C：快速排序
来源：http://dali.pycfn.com/Article/details/gtklutszve.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gteakjkqtg.html

[S20] C：二分查找
来源：http://dali.ydzc1.top/Article/details/gtempifiqd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gthkgukfrd.html

[S21] C：字符类别判断
来源：http://dali.jqgufenzy.top/Article/details/gtczjpqjwm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xziqi.cn/Article/details/gtzyuayiku.html

[S22] C：字符串转数字
来源：http://dali.feifeiyinyue.top/Article/details/gtsqoagxkj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gtfeoebtgy.html

[S23] C：随机数
来源：http://dali.c1oappe.top/Article/details/gtyfqbvbul.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hysaishi.cn/Article/details/gtcknarjwg.html

[S24] C：获取本地时间
来源：http://dali.jyoumei.cn/Article/details/gtioknpvks.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jlsjyb.cn/Article/details/gtnszsfmoc.html

[S25] C：内存拷贝
来源：http://dali.yangfankeji.com/Article/details/gtwoxphzsi.html

memcpy(dst, src, n);
来源：http://dali.birdmap.top/Article/details/gtuhgzaxzx.html

[S26] C：内存清零
来源：http://dali.guowangkeji.top/Article/details/gtxqaxxsdc.html

memset(a, 0, sizeof a);
来源：http://dali.pengpengdd.cyou/Article/details/gthtfburar.html

[S27] C：定义常量
来源：http://dali.nanxuanxn.top/Article/details/gtwaswnlkg.html

const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gttfdehsqj.html

[S28] C：静态变量
来源：http://dali.pengpengdd.cyou/Article/details/gtafwathss.html

static int counter = 0;
来源：http://dali.hfpthk.cn/Article/details/gtboyyacdd.html

[S29] C：变参函数
来源：http://dali.feifeiyinyue.top/Article/details/gtffokncje.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fengsongda.top/Article/details/gtscljmxex.html

[S30] C：头文件保护
来源：http://dali.havefunace.top/Article/details/gtkgengfqf.html

#ifndef X_H
来源：http://dali.iojbl.cn/Article/details/gtzcqtzoao.html

#define X_H
来源：http://dali.yueranfly.top/Article/details/gtwwxiiatm.html

#endif
来源：http://dali.0kj1m.cn/Article/details/gtwvbtkidr.html

[S31] C++：Hello World
来源：http://dali.ivvv.top/Article/details/gtpjsldaas.html

#include <iostream>
来源：http://dali.vqdsnc.cn/Article/details/gtosasufin.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuanzx.com/Article/details/gtzyhiuehl.html

[S32] C++：字符串
来源：http://dali.yongpay.top/Article/details/gtgfxzhhhk.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gtlabtznzd.html


<!-- 参考信息 -->