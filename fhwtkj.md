代发 wailian999

[Q65] 回滚事务
来源：http://dali.birdmap.top/Article/details/gt2ujadnyub.html

ROLLBACK;
来源：http://dali.yuanzhike.top/Article/details/gt2cslzocmu.html

[Q66] 行锁查询
来源：http://dali.ydzc1.top/Article/details/gt2aexfuoqh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ppjwa.cn/Article/details/gt2essxedaz.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gt2iswngjtr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guannengcc.top/Article/details/gt2dgawnbbs.html

[Q68] 保存点
来源：http://dali.hysaishi.cn/Article/details/gt2hzgbyzlj.html

SAVEPOINT sp1;
来源：http://dali.fengsongda.top/Article/details/gt2pmkfwivp.html

ROLLBACK TO sp1;
来源：http://dali.jlsjyb.cn/Article/details/gt2tntfqytt.html

[Q69] 查看执行计划
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhjhvkly.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yonumen.top/Article/details/gt2nhvfqgyb.html

[Q70] 更新统计信息
来源：http://dali.yvedp.cn/Article/details/gt2awoyiwop.html

ANALYZE TABLE users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2tadtxnhc.html

[Q71] 查看建表语句
来源：http://dali.xylfe.cn/Article/details/gt2pvigadcx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guannengcc.top/Article/details/gt2sjglwzdk.html

[Q72] 查看索引
来源：http://dali.hammf.cn/Article/details/gt2ohcalpoo.html

SHOW INDEX FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2cemxdfnm.html

[Q73] 查看表状态
来源：http://dali.ybcxt.top/Article/details/gt2lniavssc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dpybxmql.html

[Q74] 强制使用索引
来源：http://dali.c1oappe.top/Article/details/gt2cwgcdflw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gt2gliivpus.html

[Q75] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gt2bglupwdf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2geeqefxx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sxryk.cn/Article/details/gt2izctouam.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gt2ysuogrve.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.vqdsnc.cn/Article/details/gt2huxzpmry.html

[Q77] 时间加减
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gmkwfbki.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.haohaochexian.top/Article/details/gt2hownebph.html

[Q78] 当前时间
来源：http://dali.cashguo.top/Article/details/gt2voiurmmm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xinyue.icu/Article/details/gt2wzzltlli.html

[Q79] 字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gt2xavdoivd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ivvv.top/Article/details/gt2oeimdjts.html

[Q80] 字符串截取
来源：http://dali.jlsjyb.cn/Article/details/gt2thiltefg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2qupmgcod.html

[Q81] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gt2ftqejhat.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2npxzwutv.html

[Q82] 字符长度与字节长度
来源：http://dali.cheryme.top/Article/details/gt2hjhtbewr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2pbyqpcyz.html

[Q83] 大小写转换
来源：http://dali.meibo888.top/Article/details/gt2opadpmjz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2sjubsfju.html

[Q84] 去除首尾空格
来源：http://dali.jinqigfzy.top/Article/details/gt2bnsmlybd.html

SELECT TRIM(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2hebkipmn.html

[Q85] 数值取整
来源：http://dali.meibo888.top/Article/details/gt2mdxaxlip.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ybcxt.top/Article/details/gt2nvciqbcb.html

[Q86] 读取 JSON 字段
来源：http://dali.jianghu66.top/Article/details/gt2xiplnpsf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xziqi.cn/Article/details/gt2wyxfxnqz.html

[Q87] JSON 字段做条件
来源：http://dali.smart0.xyz/Article/details/gt2djkycibv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shzxlz.cn/Article/details/gt2sknqlcsu.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuanzhike.top/Article/details/gt2ewsvgwee.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fengsongda.top/Article/details/gt2hbvmjhmz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2zmktrigw.html

[Q89] 判断表是否存在
来源：http://dali.cheryme.top/Article/details/gt2nfwlglju.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ybcxt.top/Article/details/gt2ebsrozgd.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfjdbnbn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jlsjyb.cn/Article/details/gt2wqxmpvwe.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2gofzegkw.html

R. Bash 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnhsaast.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2unblzhnz.html

[R01] shebang 与严格模式
来源：http://dali.shangyingyoupin.top/Article/details/gt2nxyzromi.html

#!/usr/bin/env bash
来源：http://dali.xuetiantiany.cn/Article/details/gt2kyodlyye.html

set -euo pipefail
来源：http://dali.tanke756.top/Article/details/gt2gwdnnkde.html

[R02] 变量赋值与使用
来源：http://dali.sxryk.cn/Article/details/gt2ebdrngaw.html

name="Tom"; echo "$name"
来源：http://dali.cucudq.cn/Article/details/gt2fsvczuvv.html

[R03] 只读变量
来源：http://dali.iojbl.cn/Article/details/gt2zptmduxp.html

readonly PI=3.14
来源：http://dali.xinyue.icu/Article/details/gt2mmsbolmd.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2spzekrzn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cucudq.cn/Article/details/gt2jfcaejjf.html

[R05] 参数默认值
来源：http://dali.shangyingyoupin.top/Article/details/gt2gzonfsnd.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gt2neibhkee.html

[R06] 判断命令是否存在
来源：http://dali.zhongyouzk.top/Article/details/gt2lwydyrgl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gt2bqlrtlmy.html

[R07] if 判断文件
来源：http://dali.iojbl.cn/Article/details/gt2folpolrh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xinyue.icu/Article/details/gt2mwjfgvrl.html

[R08] 数值比较
来源：http://dali.jinqigufen.top/Article/details/gt2oypsnimr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.quarkkingdee.top/Article/details/gt2ngbfzjae.html

[R09] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xgwdkgxr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jiagoushi.top/Article/details/gt2ofywnheq.html

[R10] 正则匹配
来源：http://dali.yueranfly.top/Article/details/gt2jsyhkbpt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cheryme.top/Article/details/gt2iacpxfbt.html

[R11] case 多分支
来源：http://dali.yangfankeji.com/Article/details/gt2bcsdktid.html

case "$1" in
来源：http://dali.c1oappe.top/Article/details/gt2oovjgfyo.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tinluvvs.html

stop)  echo "停止" ;;
来源：http://dali.gotoacloud.top/Article/details/gt2rutlovtl.html

*)     echo "未知命令" ;;
来源：http://dali.yueranfly.top/Article/details/gt2rdcsfrcd.html

esac
来源：http://dali.jiagoushi.top/Article/details/gt2nzcblyok.html

[R12] for 遍历文件
来源：http://dali.shzxlz.cn/Article/details/gt2nibdtojf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2djuoajcp.html

[R13] for 计数循环
来源：http://dali.hammf.cn/Article/details/gt2tggvlchl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gt2tznnaexn.html

[R14] C 风格 for
来源：http://dali.hammf.cn/Article/details/gt2fkeuxmuu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qpibylfl.html

[R15] while 逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gt2pholiues.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sufxvd.cn/Article/details/gt2quwzsiyd.html

[R16] until 等待条件
来源：http://dali.jqgfzy.top/Article/details/gt2gmvphkbw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gt2pxtmyoph.html

[R17] 数组定义与取值
来源：http://dali.316326.xyz/Article/details/gt2qqtyuzvd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fengsongda.top/Article/details/gt2hnpktugr.html

[R18] 遍历数组
来源：http://dali.sufxvd.cn/Article/details/gt2ckwfufvh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuanzx.com/Article/details/gt2bjxetctq.html

[R19] 数组长度
来源：http://dali.yj20258888.top/Article/details/gt2jtjhmkrm.html

echo "${#arr[@]}"
来源：http://dali.gotoacloud.top/Article/details/gt2xuidehuf.html

[R20] 关联数组（字典）
来源：http://dali.zhoulong.xyz/Article/details/gt2tthvmrkk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hywenlv.cn/Article/details/gt2soaqknyx.html

[R21] 字符串长度
来源：http://dali.hysaishi.cn/Article/details/gt2zmndafmx.html

echo "${#s}"
来源：http://dali.yueranfly.top/Article/details/gt2npylsnzf.html

[R22] 截取子串
来源：http://dali.pycfn.com/Article/details/gt2slfawoje.html

echo "${s:0:5}"
来源：http://dali.ydzc1.top/Article/details/gt2nvdcvwos.html

[R23] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gt2xziodfai.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xylfe.cn/Article/details/gt2umfnkznw.html

[R24] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dxnklamv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ppjwa.cn/Article/details/gt2rouiwmjh.html

[R25] 去后缀 / 去前缀
来源：http://dali.aizwys.cn/Article/details/gt2qsacjldw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xziqi.cn/Article/details/gt2xvhujpld.html

[R26] 命令替换
来源：http://dali.tianlin.xyz/Article/details/gt2kciepeql.html

now=$(date +%F); echo "$now"
来源：http://dali.meibo888.top/Article/details/gt2ovcnqikt.html

[R27] 算术展开
来源：http://dali.zhixingplan.top/Article/details/gt2rtfgymtv.html

echo $((1 + 2 * 3))
来源：http://dali.guowangkeji.top/Article/details/gt2ufueqagj.html

[R28] 浮点运算
来源：http://dali.guowangkeji.top/Article/details/gt2nsojsoky.html

echo "scale=2; 10/3" | bc
来源：http://dali.fzhhl.top/Article/details/gt2qckexygx.html

[R29] 定义函数
来源：http://dali.yj202588.top/Article/details/gt2ixvuevos.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.haohaochexian.top/Article/details/gt2fcpufjpe.html

[R30] 函数返回状态码
来源：http://dali.yj20258.top/Article/details/gt2wqkbdcdp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenzaomai.com/Article/details/gt2bsfjqttg.html

[R31] 局部变量
来源：http://dali.ehwqpu.com/Article/details/gt2irqmwgfb.html

f() { local x=1; echo "$x"; }
来源：http://dali.yonumen.top/Article/details/gt2nrcwvshz.html

[R32] 参数个数校验
来源：http://dali.daria6918.cn/Article/details/gt2cnbelslj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gt2eozpqjra.html

[R33] 捕获错误并提示行号
来源：http://dali.yuxming.cn/Article/details/gt2bmdjxzaq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhongyouzk.top/Article/details/gt2ezpkcrsy.html

[R34] 退出时清理
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dszpcwts.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gt2cmznvfwk.html

[R35] 后台执行并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pyotaoxq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gt2oopqdkxo.html

[R36] 并发执行多个任务
来源：http://dali.zdqjudy.top/Article/details/gt2wvqmsgif.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hfpthk.cn/Article/details/gt2sfcwrfnh.html

[R37] 把输出赋给变量
来源：http://dali.wangdashe.top/Article/details/gt2khmfixud.html

files=$(ls -1)
来源：http://dali.chenlongwang.top/Article/details/gt2oxmhqayd.html

[R38] 管道串联
来源：http://dali.316326.xyz/Article/details/gt2oqabbsxk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gogol.net.cn/Article/details/gt2glpkjctq.html

[R39] 重定向标准输出与错误
来源：http://dali.smart0.xyz/Article/details/gt2omhpciuz.html

cmd > out.log 2>&1
来源：http://dali.nwbrower.top/Article/details/gt2trpylspa.html

[R40] 追加写日志
来源：http://dali.chenzaomai.com/Article/details/gt2ttjstqbh.html

echo "log" >> out.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yyxkkrrw.html

[R41] 丢弃输出
来源：http://dali.chenjidiqi.icu/Article/details/gt2oungwgxj.html

cmd >/dev/null 2>&1
来源：http://dali.ivvv.top/Article/details/gt2nexiiiux.html

[R42] 输入重定向
来源：http://dali.sufxvd.cn/Article/details/gt2ygxvcdhw.html

wc -l < a.txt
来源：http://dali.gzhubu.top/Article/details/gt2uqiplwtb.html

[R43] 按名字查找文件
来源：http://dali.guowangkeji.top/Article/details/gt2yypdsnov.html

find . -name "*.log" -type f
来源：http://dali.sxryk.cn/Article/details/gt2bzbkuosh.html

[R44] 按修改时间查找
来源：http://dali.cheryme.top/Article/details/gt2bqpsmchd.html

find . -mtime -7 -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fnqorjje.html

[R45] 批量删除
来源：http://dali.iojbl.cn/Article/details/gt2wsgxmedy.html

find . -name "*.tmp" -delete
来源：http://dali.hysaishi.cn/Article/details/gt2yjniknjn.html

[R46] 递归替换文件内容
来源：http://dali.wangshuangyany.cn/Article/details/gt2vghfvqzn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnqzz.top/Article/details/gt2puwunpes.html

[R47] sed 单行替换
来源：http://dali.smart0.xyz/Article/details/gt2xvczjpak.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2vdbmlzgp.html

[R48] awk 取指定列
来源：http://dali.havefunace.top/Article/details/gt2ytulvvab.html

awk '{print $1, $3}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2eqfwcops.html

[R49] awk 带条件
来源：http://dali.sweek.top/Article/details/gt2nluonfmv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xinyue.icu/Article/details/gt2iwtghtut.html

[R50] awk 求和
来源：http://dali.aibaodan.cn/Article/details/gt2nxnstcko.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hammf.cn/Article/details/gt2cnvktenz.html

[R51] 排序去重取前几
来源：http://dali.mhx1999.top/Article/details/gt2iyzxncsm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ehwqpu.com/Article/details/gt2ewwidatp.html

[R52] 统计行数
来源：http://dali.gaohongyu789.top/Article/details/gt2ilcsqmkm.html

wc -l a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2glhfixbn.html

[R53] 查看文件头与实时尾
来源：http://dali.vqdsnc.cn/Article/details/gt2xdmuosme.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pengpengdd.cyou/Article/details/gt2zaloippr.html

[R54] 比较两个文件
来源：http://dali.yj20258888.top/Article/details/gt2fhfmduac.html

diff a.txt b.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjglijjz.html

[R55] 压缩与解压
来源：http://dali.hfpthk.cn/Article/details/gt2mvmdpuof.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gt2sbegskdz.html

[R56] 远程拷贝
来源：http://dali.9152youxi.cn/Article/details/gt2gjrmdaqz.html

scp file user@host:/path/
来源：http://dali.zhixingplan.top/Article/details/gt2jlobfmpv.html

[R57] 远程执行命令
来源：http://dali.fengsongda.top/Article/details/gt2dcuoxqzl.html

ssh user@host 'uptime'
来源：http://dali.hnqzz.top/Article/details/gt2chhyhshd.html

[R58] 下载文件
来源：http://dali.yj202588.top/Article/details/gt2frnrwehl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gt2vzxqduvv.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gt2bvdubjdr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gt2hyitjlqx.html

[R60] 只看 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gt2zqvdjgjk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pycfn.com/Article/details/gt2oczycxsu.html

[R61] 磁盘占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xsjjcqpa.html

df -h;  du -sh *
来源：http://dali.ehwqpu.com/Article/details/gt2uvwyowrp.html

[R62] 找最占空间的文件
来源：http://dali.xuanzx.com/Article/details/gt2gkpwdggp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhoulong.xyz/Article/details/gt2hdmwljto.html

[R63] 内存与进程
来源：http://dali.havefunace.top/Article/details/gt2bchgfvau.html

free -h;  ps aux | grep nginx
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjakqius.html

[R64] 结束进程
来源：http://dali.cqqwz.cn/Article/details/gt2pnxibhtw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cqqwz.cn/Article/details/gt2zvhqdrpc.html

[R65] 查看端口占用
来源：http://dali.fzhhl.top/Article/details/gt2rasehjsa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhongyouzk.top/Article/details/gt2jpzxbkqk.html

[R66] 定时任务
来源：http://dali.tian-w.cn/Article/details/gt2buyuanzq.html

crontab -e;  crontab -l
来源：http://dali.cashguo.top/Article/details/gt2pyztigmn.html

[R67] 生成随机十六进制串
来源：http://dali.dianchejie.cn/Article/details/gt2bxykzjab.html

openssl rand -hex 16
来源：http://dali.pengpengdd.cyou/Article/details/gt2ipobkxlj.html

[R68] 计算文件校验值
来源：http://dali.yj20258.top/Article/details/gt2hpfbqqkt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2ldhhwvdc.html

[R69] 生成随机密码
来源：http://dali.gzhubu.top/Article/details/gt2gfwwsyyn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2twdaqnkv.html

[R70] 时间戳与互转
来源：http://dali.daxiang520.top/Article/details/gt2gglxensh.html

date +%s;  date -d @1700000000
来源：http://dali.jlsjyb.cn/Article/details/gt2vhwmbvam.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gt2tsnojyix.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.redwolf501.top/Article/details/gt2gdpfemqm.html

[R72] 等待端口就绪
来源：http://dali.sufxvd.cn/Article/details/gt2zpoayaye.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zizxxkdv.html

[R73] 分割大日志
来源：http://dali.jlsjyb.cn/Article/details/gt2cspyypnn.html

split -l 1000 big.log part_
来源：http://dali.andypj.xyz/Article/details/gt2rahbherg.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gt2fmtlhxoe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigufen.top/Article/details/gt2rtetjmjk.html

[R75] 导出环境变量
来源：http://dali.jyoumei.cn/Article/details/gt2ocfgefdk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dashuyun.cn/Article/details/gt2wjujvgbh.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gt2awwbazje.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gt2bedetnxq.html

[R77] 读取用户输入
来源：http://dali.yuxming.cn/Article/details/gt2vhuwvqzp.html

read -rp "请输入: " ans
来源：http://dali.cheryme.top/Article/details/gt2gsksnrlb.html

[R78] 交互式菜单
来源：http://dali.yj20258888.top/Article/details/gt2aalhohdh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2lotwqwwx.html

[R79] 解析命令行选项
来源：http://dali.zhengqikj.top/Article/details/gt2xarmlakk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.snrcjt.cn/Article/details/gt2wsybjpwz.html

[R80] 查看脚本执行耗时
来源：http://dali.yangfankeji.com/Article/details/gt2ikubjrxl.html

time ./run.sh
来源：http://dali.ppjwa.cn/Article/details/gt2vdepnnpn.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2kbosxjnj.html

S. C / C++ 专题
来源：http://dali.guowangkeji.top/Article/details/gt2fjjhctte.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2yaxilknt.html

[S01] C：Hello World
来源：http://dali.cashguo.top/Article/details/gt2yizhvwen.html

#include <stdio.h>
来源：http://dali.chenlongwang.top/Article/details/gt2lwxgcpnq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yongpay.top/Article/details/gt2kxrkgood.html

[S02] C：变量与格式化输出
来源：http://dali.316326.xyz/Article/details/gt2pciegsdo.html

int a = 10; printf("%d\n", a);
来源：http://dali.316326.xyz/Article/details/gt2jsjnhbuj.html

[S03] C：读入整数
来源：http://dali.yueranfly.top/Article/details/gt2tgvwlomz.html

int x; scanf("%d", &x);
来源：http://dali.zhiwuduotai.top/Article/details/gt2kruepjdo.html

[S04] C：字符串复制
来源：http://dali.cdnleiting.top/Article/details/gt2tptsbzld.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2milckatk.html

[S05] C：字符串长度
来源：http://dali.sxryk.cn/Article/details/gt2rganidho.html

strlen(s)
来源：http://dali.hfpthk.cn/Article/details/gt2vozxveie.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gt2qlsioanp.html

strcmp(a, b) == 0
来源：http://dali.sweek.top/Article/details/gt2vofpqiwd.html

[S07] C：数组遍历求和
来源：http://dali.zycfv.cn/Article/details/gt2ezwhdapm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sufxvd.cn/Article/details/gt2iupbfqyz.html

[S08] C：动态内存分配与释放
来源：http://dali.hfpthk.cn/Article/details/gt2rzxxpxxy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.snrcjt.cn/Article/details/gt2clpqlfas.html

[S09] C：结构体定义与初始化
来源：http://dali.smart0.xyz/Article/details/gt2rzglxypy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.quarkkingdee.top/Article/details/gt2pvpxvnkd.html

[S10] C：指针与解引用
来源：http://dali.xinyue.icu/Article/details/gt2soxudsbw.html

int *p = &a;  *p = 5;
来源：http://dali.chenzaomai.com/Article/details/gt2dgihbfji.html

[S11] C：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gt2naldhsgq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shuidangran.top/Article/details/gt2bmuuqvho.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ptgclvky.html

fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgmdqazo.html

[S12] C：写文件
来源：http://dali.guowangkeji.top/Article/details/gt2pnccgihy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tanke756.top/Article/details/gt2mdsfvxip.html

[S13] C：宏定义
来源：http://dali.dashuyun.cn/Article/details/gt2sndptbjr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.meibo888.top/Article/details/gt2perxgrjq.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gt2eqqdjvjs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kympbdxd.html

[S15] C：类型转换
来源：http://dali.daxiang520.top/Article/details/gt2ebmyoash.html

(double) a / b
来源：http://dali.ybcxt.top/Article/details/gt2zrquqdag.html

[S16] C：位操作置位
来源：http://dali.dashuyun.cn/Article/details/gt2dxsyxumx.html

x |= (1 << 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ggdjhmqk.html

[S17] C：安全拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gt2zwuafoek.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hywenlv.cn/Article/details/gt2ohmlabty.html

[S18] C：命令行参数
来源：http://dali.pycfn.com/Article/details/gt2gjzfblsw.html

int main(int argc, char **argv)
来源：http://dali.xuanzx.com/Article/details/gt2vlhwiswr.html

[S19] C：快速排序
来源：http://dali.jqgufenzy.top/Article/details/gt2egwpindd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2eufhwkpa.html

[S20] C：二分查找
来源：http://dali.zhiwuduotai.top/Article/details/gt2ywanlnki.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lpafovaz.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2iwhnuffz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuanzhike.top/Article/details/gt2hxkuyllw.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gt2ivnyepee.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.quarkkingdee.top/Article/details/gt2zvarxupx.html

[S23] C：随机数
来源：http://dali.quarkkingdee.top/Article/details/gt2lxggmuhx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qjoyupzs.html

[S24] C：获取本地时间
来源：http://dali.hnxiangtu.top/Article/details/gt2uohlaxuq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gt2stlxuqie.html

[S25] C：内存拷贝
来源：http://dali.jyoumei.cn/Article/details/gt2qpiltbxh.html

memcpy(dst, src, n);
来源：http://dali.nanxuanxn.top/Article/details/gt2axnfheog.html

[S26] C：内存清零
来源：http://dali.cdnleiting.top/Article/details/gt2ighwafim.html

memset(a, 0, sizeof a);
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvambpih.html

[S27] C：定义常量
来源：http://dali.yongpay.top/Article/details/gt2moeaspke.html

const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gt2mclymgru.html

[S28] C：静态变量
来源：http://dali.chenzaomai.com/Article/details/gt2hhjfalrk.html

static int counter = 0;
来源：http://dali.sweek.top/Article/details/gt2eurhpzjm.html

[S29] C：变参函数
来源：http://dali.gzhubu.top/Article/details/gt2btpedueq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangshuangyany.cn/Article/details/gt2cynwkkgh.html

[S30] C：头文件保护
来源：http://dali.9152youxi.cn/Article/details/gt2zayrtpvd.html

#ifndef X_H
来源：http://dali.ppjwa.cn/Article/details/gt2vckfyets.html

#define X_H
来源：http://dali.haohaochexian.top/Article/details/gt2ovgjcuab.html

#endif
来源：http://dali.nanxuanxn.top/Article/details/gt2vezctsgd.html

[S31] C++：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2heopcysm.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2iyprkytx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fzhhl.top/Article/details/gt2awxtilri.html

[S32] C++：字符串
来源：http://dali.tanke756.top/Article/details/gt2qsnbqjym.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gt2qvpsbbhg.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gt2aramnvvf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ppjwa.cn/Article/details/gt2yqkofqbh.html

[S34] C++：遍历 vector
来源：http://dali.chenlongwang.top/Article/details/gt2kmouovtz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zdqjudy.top/Article/details/gt2iefbcyys.html


<!-- 参考信息 -->