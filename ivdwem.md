代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.tanke756.top/Article/details/gt2mrnzeyec.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhixingplan.top/Article/details/gt2gabcxghr.html

[Q68] 保存点
来源：http://dali.guannengcc.top/Article/details/gt2pyxrikjn.html

SAVEPOINT sp1;
来源：http://dali.meibo888.top/Article/details/gt2vsxpleem.html

ROLLBACK TO sp1;
来源：http://dali.tian-w.cn/Article/details/gt2lqpwwgya.html

[Q69] 查看执行计划
来源：http://dali.hongshengwenyu.top/Article/details/gt2xvqweytj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fengsongda.top/Article/details/gt2jlxifmrc.html

[Q70] 更新统计信息
来源：http://dali.guannengcc.top/Article/details/gt2ussoigbf.html

ANALYZE TABLE users;
来源：http://dali.tianlin.xyz/Article/details/gt2cvxtgdbc.html

[Q71] 查看建表语句
来源：http://dali.hongshengwenyu.top/Article/details/gt2ofxrixwr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jyoumei.cn/Article/details/gt2gzmqdzuq.html

[Q72] 查看索引
来源：http://dali.hongshengwenyu.top/Article/details/gt2xbrtabhn.html

SHOW INDEX FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rdfhmhgr.html

[Q73] 查看表状态
来源：http://dali.cheryme.top/Article/details/gt2lybnuyzn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.quarkkingdee.top/Article/details/gt2sjraxhqt.html

[Q74] 强制使用索引
来源：http://dali.jinqigufen.top/Article/details/gt2tluppqtx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shangyingyoupin.top/Article/details/gt2amqbnlim.html

[Q75] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gt2kljfmrei.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2pyoppveg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenlongwang.top/Article/details/gt2mtldihlr.html

[Q76] 按天统计
来源：http://dali.ybcxt.top/Article/details/gt2kdbekbbw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hfpthk.cn/Article/details/gt2hjyxtwlm.html

[Q77] 时间加减
来源：http://dali.tanke756.top/Article/details/gt2yyzhbzqv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pengpengdd.cyou/Article/details/gt2gweznobs.html

[Q78] 当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2olgyibsc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yanxiufei.cn/Article/details/gt2lbctuude.html

[Q79] 字符串拼接
来源：http://dali.yonumen.top/Article/details/gt2kpqgkfvr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aizwys.cn/Article/details/gt2taujbonj.html

[Q80] 字符串截取
来源：http://dali.zhiwuduotai.top/Article/details/gt2afuisdft.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tlciiijg.html

[Q81] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gt2mcbqrjio.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ajqmridr.html

[Q82] 字符长度与字节长度
来源：http://dali.ybcxt.top/Article/details/gt2dtoalocd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2recdwpum.html

[Q83] 大小写转换
来源：http://dali.havefunace.top/Article/details/gt2jzykulsy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2anknsgjf.html

[Q84] 去除首尾空格
来源：http://dali.bjfxy.top/Article/details/gt2pmjykhri.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2gzqouipa.html

[Q85] 数值取整
来源：http://dali.hnxiangtu.top/Article/details/gt2hfzqjyqs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhengqikj.top/Article/details/gt2pduvsndz.html

[Q86] 读取 JSON 字段
来源：http://dali.cashguo.top/Article/details/gt2krhufiku.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ybcxt.top/Article/details/gt2vwtqqgqq.html

[Q87] JSON 字段做条件
来源：http://dali.shuidangran.top/Article/details/gt2lpujayfi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gaohongyu789.top/Article/details/gt2spfckvdh.html

[Q88] 行转列（条件聚合）
来源：http://dali.vqdsnc.cn/Article/details/gt2vxljjlkq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.meibo888.top/Article/details/gt2wnfbozir.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2wsekefmf.html

[Q89] 判断表是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2btuajpyj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jiagoushi.top/Article/details/gt2mklmqnge.html

[Q90] 生成序号列
来源：http://dali.jqgufenzy.top/Article/details/gt2eftlhfim.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.mhx1999.top/Article/details/gt2jcmspooz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2hfcierkg.html

R. Bash 专题
来源：http://dali.quarkkingdee.top/Article/details/gt2unireuux.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2lauxhbme.html

[R01] shebang 与严格模式
来源：http://dali.cdnleiting.top/Article/details/gt2smsusdnn.html

#!/usr/bin/env bash
来源：http://dali.yangfankeji.com/Article/details/gt2hjrwqyhe.html

set -euo pipefail
来源：http://dali.daria6918.cn/Article/details/gt2xvdsmbph.html

[R02] 变量赋值与使用
来源：http://dali.quarkkingdee.top/Article/details/gt2aiocpiwl.html

name="Tom"; echo "$name"
来源：http://dali.havefunace.top/Article/details/gt2rkqmqfio.html

[R03] 只读变量
来源：http://dali.andypj.xyz/Article/details/gt2tkcamfut.html

readonly PI=3.14
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yujsajpv.html

[R04] 位置参数
来源：http://dali.smart0.xyz/Article/details/gt2tcjycrfg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuanzhike.top/Article/details/gt2adzexkey.html

[R05] 参数默认值
来源：http://dali.hnxiangtu.top/Article/details/gt2rrrzdtjp.html

name="${1:-default}"
来源：http://dali.xuanzx.com/Article/details/gt2qhygqkho.html

[R06] 判断命令是否存在
来源：http://dali.316326.xyz/Article/details/gt2fmlswjaq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sweek.top/Article/details/gt2qygdhque.html

[R07] if 判断文件
来源：http://dali.hammf.cn/Article/details/gt2atqzwxph.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zycfv.cn/Article/details/gt2fjgheouz.html

[R08] 数值比较
来源：http://dali.iojbl.cn/Article/details/gt2nqvizbfc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuxming.cn/Article/details/gt2smzrxskf.html

[R09] 字符串比较
来源：http://dali.guowangkeji.top/Article/details/gt2neiyruqj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gt2iufxhfsk.html

[R10] 正则匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2thztmczd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shuidangran.top/Article/details/gt2tddgxcpm.html

[R11] case 多分支
来源：http://dali.wangdashe.top/Article/details/gt2xkjbwxci.html

case "$1" in
来源：http://dali.yongpay.top/Article/details/gt2vxjptbrz.html

start) echo "启动" ;;
来源：http://dali.cheryme.top/Article/details/gt2bmknabuo.html

stop)  echo "停止" ;;
来源：http://dali.kuanghao11.cn/Article/details/gt2jnazaxvw.html

*)     echo "未知命令" ;;
来源：http://dali.nwbrower.top/Article/details/gt2aeegxxfk.html

esac
来源：http://dali.jlsjyb.cn/Article/details/gt2kdjhcgnc.html

[R12] for 遍历文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2bwpcrnvi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cheryme.top/Article/details/gt2utibitor.html

[R13] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gt2nqchathm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gt2mtdabvnl.html

[R14] C 风格 for
来源：http://dali.xuanzx.com/Article/details/gt2nfbzoqsk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gt2quqqseuv.html

[R15] while 逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gt2myhzjlwz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.haohaochexian.top/Article/details/gt2chwadlzi.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gt2dgzoeeva.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gt2wfvlxmvx.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gt2rxfqtopn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daxiang520.top/Article/details/gt2nqzqadwt.html

[R18] 遍历数组
来源：http://dali.jinqigfzy.top/Article/details/gt2iprswlkb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cdnleiting.top/Article/details/gt2pdkdxjrt.html

[R19] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gt2odonhbpk.html

echo "${#arr[@]}"
来源：http://dali.hnxiangtu.top/Article/details/gt2ntyxlydp.html

[R20] 关联数组（字典）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cyznovkx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuanzhike.top/Article/details/gt2xysispte.html

[R21] 字符串长度
来源：http://dali.gzhubu.top/Article/details/gt2rietqxhb.html

echo "${#s}"
来源：http://dali.chenzaomai.com/Article/details/gt2xvelzrsx.html

[R22] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gt2gdetgmzc.html

echo "${s:0:5}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2vtpltdho.html

[R23] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gt2ysdqnwnh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cqqwz.cn/Article/details/gt2usxkmcte.html

[R24] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gt2tjolobjj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhongyouzk.top/Article/details/gt2rhbfvkph.html

[R25] 去后缀 / 去前缀
来源：http://dali.xziqi.cn/Article/details/gt2lupamwdi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olbixrlv.html

[R26] 命令替换
来源：http://dali.316326.xyz/Article/details/gt2masneyao.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigfzy.top/Article/details/gt2vgbovzez.html

[R27] 算术展开
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nkejdjvm.html

echo $((1 + 2 * 3))
来源：http://dali.nwbrower.top/Article/details/gt2mxinpvet.html

[R28] 浮点运算
来源：http://dali.tanke756.top/Article/details/gt2dlgpeath.html

echo "scale=2; 10/3" | bc
来源：http://dali.daria6918.cn/Article/details/gt2dvtyamsi.html

[R29] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gt2oitoqygp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cashguo.top/Article/details/gt2skxbsnsd.html

[R30] 函数返回状态码
来源：http://dali.ehwqpu.com/Article/details/gt2wwxmsuav.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shuidangran.top/Article/details/gt2ruztdfkv.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gt2dhrhksij.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gt2czzybnbi.html

[R32] 参数个数校验
来源：http://dali.jqgufenzy.top/Article/details/gt2kmddfghm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kqrinzwg.html

[R33] 捕获错误并提示行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eadtmrhh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sxryk.cn/Article/details/gt2zngdsfpv.html

[R34] 退出时清理
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqecskle.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gt2jbmdlcix.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wbubmgsz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ppjwa.cn/Article/details/gt2wrgcdsls.html

[R36] 并发执行多个任务
来源：http://dali.hammf.cn/Article/details/gt2puiqqixc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.redwolf501.top/Article/details/gt2anravmqc.html

[R37] 把输出赋给变量
来源：http://dali.jinqigfzy.top/Article/details/gt2betwjmzs.html

files=$(ls -1)
来源：http://dali.dashuyun.cn/Article/details/gt2izjkqgli.html

[R38] 管道串联
来源：http://dali.cdnleiting.top/Article/details/gt2eirccvso.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yanxiufei.cn/Article/details/gt2rvuaizvk.html

[R39] 重定向标准输出与错误
来源：http://dali.smart0.xyz/Article/details/gt2xjeerynz.html

cmd > out.log 2>&1
来源：http://dali.dashuyun.cn/Article/details/gt2efcnlrbr.html

[R40] 追加写日志
来源：http://dali.xziqi.cn/Article/details/gt2vpsraxog.html

echo "log" >> out.log
来源：http://dali.zhixingplan.top/Article/details/gt2bdfmqmnx.html

[R41] 丢弃输出
来源：http://dali.sufxvd.cn/Article/details/gt2rrkyfegq.html

cmd >/dev/null 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmikcpjv.html

[R42] 输入重定向
来源：http://dali.fzhhl.top/Article/details/gt2dyfaeabo.html

wc -l < a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wheepoxw.html

[R43] 按名字查找文件
来源：http://dali.cqqwz.cn/Article/details/gt2jyziegmo.html

find . -name "*.log" -type f
来源：http://dali.0kj1m.cn/Article/details/gt2ydvwapgx.html

[R44] 按修改时间查找
来源：http://dali.aibaodan.cn/Article/details/gt2tpxsqllj.html

find . -mtime -7 -type f
来源：http://dali.xuetiantiany.cn/Article/details/gt2ysurjccy.html

[R45] 批量删除
来源：http://dali.zdqjudy.top/Article/details/gt2dlmwvftk.html

find . -name "*.tmp" -delete
来源：http://dali.sufxvd.cn/Article/details/gt2haddwakw.html

[R46] 递归替换文件内容
来源：http://dali.feifeiyinyue.top/Article/details/gt2icwrxjzo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.0kj1m.cn/Article/details/gt2mpfvlvfz.html

[R47] sed 单行替换
来源：http://dali.hysaishi.cn/Article/details/gt2ypflaqbo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lsnkitxc.html

[R48] awk 取指定列
来源：http://dali.redwolf501.top/Article/details/gt2tttajjni.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2gpvxniee.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yassyqhw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfyhlevs.html

[R50] awk 求和
来源：http://dali.zycfv.cn/Article/details/gt2ffkyyenx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jianghu66.top/Article/details/gt2qaviyybg.html

[R51] 排序去重取前几
来源：http://dali.shzxlz.cn/Article/details/gt2gixcawib.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guowangkeji.top/Article/details/gt2kdlbuevo.html

[R52] 统计行数
来源：http://dali.hnqzz.top/Article/details/gt2qinbqqbr.html

wc -l a.txt
来源：http://dali.hnqzz.top/Article/details/gt2poenranf.html

[R53] 查看文件头与实时尾
来源：http://dali.xinyue.icu/Article/details/gt2cuwognwe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gzhubu.top/Article/details/gt2daghaqth.html

[R54] 比较两个文件
来源：http://dali.shuidangran.top/Article/details/gt2rgeerytj.html

diff a.txt b.txt
来源：http://dali.bjfxy.top/Article/details/gt2prbbhxkz.html

[R55] 压缩与解压
来源：http://dali.cashguo.top/Article/details/gt2nmdyzmxl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sufxvd.cn/Article/details/gt2meusweep.html

[R56] 远程拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gt2eyytqgwx.html

scp file user@host:/path/
来源：http://dali.316326.xyz/Article/details/gt2ubikzvpt.html

[R57] 远程执行命令
来源：http://dali.cdnleiting.top/Article/details/gt2qavyakyc.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lpwhnvml.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gt2wnvwusyh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvjurnhs.html

[R59] 发 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gt2lkkndwyn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sxryk.cn/Article/details/gt2ayubpbuk.html

[R60] 只看 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2byqnxktu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jyoumei.cn/Article/details/gt2dpzmkbef.html

[R61] 磁盘占用
来源：http://dali.cqqwz.cn/Article/details/gt2irubtebk.html

df -h;  du -sh *
来源：http://dali.mhx1999.top/Article/details/gt2woqnezyc.html

[R62] 找最占空间的文件
来源：http://dali.kuanghao11.cn/Article/details/gt2frifylgt.html

du -ah . | sort -rh | head -10
来源：http://dali.yonumen.top/Article/details/gt2donzhwlp.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gt2svkjssfe.html

free -h;  ps aux | grep nginx
来源：http://dali.hysaishi.cn/Article/details/gt2lypsdhkz.html

[R64] 结束进程
来源：http://dali.mhx1999.top/Article/details/gt2xmprxokk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gt2qwosiepn.html

[R65] 查看端口占用
来源：http://dali.jiagoushi.top/Article/details/gt2lrpdsmsg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhixingplan.top/Article/details/gt2lfhcxswh.html

[R66] 定时任务
来源：http://dali.ybcxt.top/Article/details/gt2lijmkjmv.html

crontab -e;  crontab -l
来源：http://dali.shuidangran.top/Article/details/gt2oqztujme.html

[R67] 生成随机十六进制串
来源：http://dali.yueranfly.top/Article/details/gt2uexvffjz.html

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gt2sgboecjl.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gxlaypai.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2texejqzh.html

[R69] 生成随机密码
来源：http://dali.nanxuanxn.top/Article/details/gt2ujzqbsnu.html

head -c 16 /dev/urandom | base64
来源：http://dali.sxryk.cn/Article/details/gt2lpymrsek.html

[R70] 时间戳与互转
来源：http://dali.tian-w.cn/Article/details/gt2cermspfq.html

date +%s;  date -d @1700000000
来源：http://dali.nanxuanxn.top/Article/details/gt2izcezxnb.html

[R71] 日期格式化
来源：http://dali.cashguo.top/Article/details/gt2yzjcvyeu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.iojbl.cn/Article/details/gt2ologiits.html

[R72] 等待端口就绪
来源：http://dali.hywenlv.cn/Article/details/gt2bsilalsn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gt2eqqtgouy.html

[R73] 分割大日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uqjvxaqi.html

split -l 1000 big.log part_
来源：http://dali.iojbl.cn/Article/details/gt2mcblsjww.html

[R74] 批量重命名
来源：http://dali.chenzaomai.com/Article/details/gt2xvgczznt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ppjwa.cn/Article/details/gt2mjiywvda.html

[R75] 导出环境变量
来源：http://dali.aibaodan.cn/Article/details/gt2axdsoxnu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gogol.net.cn/Article/details/gt2yfzrcmvd.html

[R76] 使用临时文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2oqfxuqiy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gt2dfbmzjic.html

[R77] 读取用户输入
来源：http://dali.redwolf501.top/Article/details/gt2trxgpuje.html

read -rp "请输入: " ans
来源：http://dali.wangdashe.top/Article/details/gt2qvgjammj.html

[R78] 交互式菜单
来源：http://dali.redwolf501.top/Article/details/gt2gnwayztl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.bjfxy.top/Article/details/gt2slgdwqma.html

[R79] 解析命令行选项
来源：http://dali.jqgufenzy.top/Article/details/gt2aribgbar.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daxiang520.top/Article/details/gt2eshzxoyf.html

[R80] 查看脚本执行耗时
来源：http://dali.wangshuangyany.cn/Article/details/gt2yalvkacf.html

time ./run.sh
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yeunxkzv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2gsqtpbrt.html

S. C / C++ 专题
来源：http://dali.chenjidiqi.icu/Article/details/gt2qevdgqwf.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2vctrojvj.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2dhkarhej.html

#include <stdio.h>
来源：http://dali.zhengqikj.top/Article/details/gt2crptxior.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yonumen.top/Article/details/gt2ldbutobi.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gt2xgxaaqix.html

int a = 10; printf("%d\n", a);
来源：http://dali.shuidangran.top/Article/details/gt2tyenrexd.html

[S03] C：读入整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgolfnat.html

int x; scanf("%d", &x);
来源：http://dali.kuanghao11.cn/Article/details/gt2mfdxthhu.html

[S04] C：字符串复制
来源：http://dali.cqqwz.cn/Article/details/gt2rbxrojei.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gt2wpscrpaj.html

[S05] C：字符串长度
来源：http://dali.yongpay.top/Article/details/gt2xvnbswbm.html

strlen(s)
来源：http://dali.jyoumei.cn/Article/details/gt2bmfmvqym.html

[S06] C：字符串比较
来源：http://dali.shzxlz.cn/Article/details/gt2qahbahxn.html

strcmp(a, b) == 0
来源：http://dali.9152youxi.cn/Article/details/gt2gnimlpsw.html

[S07] C：数组遍历求和
来源：http://dali.hywenlv.cn/Article/details/gt2amktdaia.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fengsongda.top/Article/details/gt2eewogexr.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258.top/Article/details/gt2vktpqhco.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djtzdmmt.html

[S09] C：结构体定义与初始化
来源：http://dali.gaohongyu789.top/Article/details/gt2kvgscrey.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgfzy.top/Article/details/gt2tlupzmvg.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jadbazge.html

int *p = &a;  *p = 5;
来源：http://dali.xziqi.cn/Article/details/gt2ilnkkiym.html

[S11] C：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2zgnzfebx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oovtgpqo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.birdmap.top/Article/details/gt2pxxydlby.html

fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gt2xolvegpi.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2stangqly.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gt2hnfaloxm.html

[S13] C：宏定义
来源：http://dali.jlsjyb.cn/Article/details/gt2kwrlpill.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.kuanghao11.cn/Article/details/gt2rkfkzmof.html

[S14] C：枚举
来源：http://dali.shuidangran.top/Article/details/gt2rbvnpjkj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cheryme.top/Article/details/gt2zxhuhyma.html

[S15] C：类型转换
来源：http://dali.xziqi.cn/Article/details/gt2aajpfctr.html

(double) a / b
来源：http://dali.fengsongda.top/Article/details/gt2lbhqswbe.html

[S16] C：位操作置位
来源：http://dali.yj202588.top/Article/details/gt2cmhklway.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gt2qqpyxljn.html

[S17] C：安全拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2pdfjutec.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hfpthk.cn/Article/details/gt2hthlnzjh.html

[S18] C：命令行参数
来源：http://dali.cdnleiting.top/Article/details/gt2bxnagbzt.html

int main(int argc, char **argv)
来源：http://dali.nwbrower.top/Article/details/gt2vovlmkex.html

[S19] C：快速排序
来源：http://dali.shuidangran.top/Article/details/gt2encjrmeh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nknkbyqm.html

[S20] C：二分查找
来源：http://dali.yj20258.top/Article/details/gt2zrdmddcz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gt2nfhninzu.html

[S21] C：字符类别判断
来源：http://dali.aibaodan.cn/Article/details/gt2icwselgx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wngohgvb.html

[S22] C：字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gt2tqlikshh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ppjwa.cn/Article/details/gt2dkieyals.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gt2dqnlqkti.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ppjwa.cn/Article/details/gt2fpvxyjno.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2enqupmsq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhoulong.xyz/Article/details/gt2bjdpbgyl.html

[S25] C：内存拷贝
来源：http://dali.ppjwa.cn/Article/details/gt2tudthhvk.html

memcpy(dst, src, n);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wgvkslgg.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gt2cfgcjndr.html

memset(a, 0, sizeof a);
来源：http://dali.wangdashe.top/Article/details/gt2dcxxxpbb.html

[S27] C：定义常量
来源：http://dali.nanxinkj.top/Article/details/gt2ncagcxnd.html

const double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2sydzkxxp.html

[S28] C：静态变量
来源：http://dali.hammf.cn/Article/details/gt2cwwhymsy.html

static int counter = 0;
来源：http://dali.yvedp.cn/Article/details/gt2guvakhya.html

[S29] C：变参函数
来源：http://dali.9152youxi.cn/Article/details/gt2svarbwqk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yvedp.cn/Article/details/gt2namksjbs.html

[S30] C：头文件保护
来源：http://dali.hysaishi.cn/Article/details/gt2fzfgmdyg.html

#ifndef X_H
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfmeaiei.html

#define X_H
来源：http://dali.zhongyouzk.top/Article/details/gt2fnufcogr.html

#endif
来源：http://dali.pengpengdd.cyou/Article/details/gt2krhpmboq.html

[S31] C++：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2jqjuifnz.html

#include <iostream>
来源：http://dali.ppjwa.cn/Article/details/gt2sisfmwhf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.iojbl.cn/Article/details/gt2rhwjtkjk.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gt2wbgcthaq.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gt2cdbgmrkp.html

[S33] C++：vector 增删
来源：http://dali.daxiang520.top/Article/details/gt2clxjacnc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gt2syasswcr.html

[S34] C++：遍历 vector
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xuklzvuh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tianlin.xyz/Article/details/gt2eocwztti.html

[S35] C++：map
来源：http://dali.wangshuangyany.cn/Article/details/gt2upycsjox.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gt2ozwbgtkf.html

[S36] C++：unordered_map
来源：http://dali.c1oappe.top/Article/details/gt2bzamikui.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gt2wemeqzpx.html


<!-- 参考信息 -->