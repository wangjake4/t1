代发 wailian999

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fojdxkoh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nwbrower.top/Article/details/gt2tzudhnnd.html

[Q77] 时间加减
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2szcdlmfg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.vqdsnc.cn/Article/details/gt2fzutthvz.html

[Q78] 当前时间
来源：http://dali.sweek.top/Article/details/gt2cwjpghgk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jyoumei.cn/Article/details/gt2rkilwthk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iuboimsa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.birdmap.top/Article/details/gt2pzdlyabm.html

[Q80] 字符串截取
来源：http://dali.xziqi.cn/Article/details/gt2sascfzak.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2lljvsefe.html

[Q81] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gt2qnijumwu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2exchfdba.html

[Q82] 字符长度与字节长度
来源：http://dali.wangdashe.top/Article/details/gt2gikdmwvp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2uplrtcoe.html

[Q83] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gt2hqvfyayz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2ujnekplc.html

[Q84] 去除首尾空格
来源：http://dali.ydzc1.top/Article/details/gt2juzokdtl.html

SELECT TRIM(name) FROM users;
来源：http://dali.sweek.top/Article/details/gt2xhtbliju.html

[Q85] 数值取整
来源：http://dali.sxryk.cn/Article/details/gt2kjhjnztv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fzhhl.top/Article/details/gt2tvzufiqv.html

[Q86] 读取 JSON 字段
来源：http://dali.andypj.xyz/Article/details/gt2sdivskoc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pengpengdd.cyou/Article/details/gt2xrbnirvx.html

[Q87] JSON 字段做条件
来源：http://dali.cqqwz.cn/Article/details/gt2zaipgxmj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyltzmrr.html

[Q88] 行转列（条件聚合）
来源：http://dali.tianlin.xyz/Article/details/gt2ghtbmyis.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2zacszswz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2ubavkfxt.html

[Q89] 判断表是否存在
来源：http://dali.sysykeji.top/Article/details/gt2jotnxoes.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gt2tpehqlgq.html

[Q90] 生成序号列
来源：http://dali.nanxuanxn.top/Article/details/gt2cqwcldzt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vikzmiac.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2wylcgkhv.html

R. Bash 专题
来源：http://dali.yangfankeji.com/Article/details/gt2ydldusbj.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2jxkslssi.html

[R01] shebang 与严格模式
来源：http://dali.xuetiantiany.cn/Article/details/gt2syjztccb.html

#!/usr/bin/env bash
来源：http://dali.iojbl.cn/Article/details/gt2rngcnsai.html

set -euo pipefail
来源：http://dali.gotoacloud.top/Article/details/gt2qrmlfqww.html

[R02] 变量赋值与使用
来源：http://dali.dianchejie.cn/Article/details/gt2jrqqucas.html

name="Tom"; echo "$name"
来源：http://dali.yanxiufei.cn/Article/details/gt2uhernfqj.html

[R03] 只读变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2qdngqgep.html

readonly PI=3.14
来源：http://dali.ehwqpu.com/Article/details/gt2ovormncx.html

[R04] 位置参数
来源：http://dali.nanxuanxn.top/Article/details/gt2ygydqnim.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zdqjudy.top/Article/details/gt2vycfdadm.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gt2lsjzcnka.html

name="${1:-default}"
来源：http://dali.xylfe.cn/Article/details/gt2mnjjkmuq.html

[R06] 判断命令是否存在
来源：http://dali.zdqjudy.top/Article/details/gt2tjukxkia.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gt2jgcwyuzj.html

[R07] if 判断文件
来源：http://dali.nanxuanxn.top/Article/details/gt2rxntkxbh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gt2utsrqnay.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gt2rjqwihhm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guannengcc.top/Article/details/gt2ymxwrnck.html

[R09] 字符串比较
来源：http://dali.daxiang520.top/Article/details/gt2itjjtjsu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2qbvqqsst.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2lyllbdus.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.meibo888.top/Article/details/gt2cjoatejk.html

[R11] case 多分支
来源：http://dali.iojbl.cn/Article/details/gt2jmmoedio.html

case "$1" in
来源：http://dali.hywenlv.cn/Article/details/gt2mazfndhj.html

start) echo "启动" ;;
来源：http://dali.gogol.net.cn/Article/details/gt2twaicuvw.html

stop)  echo "停止" ;;
来源：http://dali.yangfankeji.com/Article/details/gt2hhgveevo.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigfzy.top/Article/details/gt2ktagsyzd.html

esac
来源：http://dali.ppjwa.cn/Article/details/gt2juwkrvcp.html

[R12] for 遍历文件
来源：http://dali.zhongyouzk.top/Article/details/gt2ibnnajwa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.haohaochexian.top/Article/details/gt2iojjmree.html

[R13] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gt2tjnqznij.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gt2cspvlenn.html

[R14] C 风格 for
来源：http://dali.ybcxt.top/Article/details/gt2lfnxsysv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gt2arnyxqxr.html

[R15] while 逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2zgpitnqg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shuidangran.top/Article/details/gt2xxaemsuy.html

[R16] until 等待条件
来源：http://dali.jlsjyb.cn/Article/details/gt2cfqffjjh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gt2cbsurpou.html

[R17] 数组定义与取值
来源：http://dali.cheryme.top/Article/details/gt2oxzlnktn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zycfv.cn/Article/details/gt2tkfpuerk.html

[R18] 遍历数组
来源：http://dali.ybcxt.top/Article/details/gt2egwxyytm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fengsongda.top/Article/details/gt2onfhplww.html

[R19] 数组长度
来源：http://dali.smart0.xyz/Article/details/gt2fsthzyoa.html

echo "${#arr[@]}"
来源：http://dali.zhoulong.xyz/Article/details/gt2aknujhau.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gt2vigdfxuc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nwbrower.top/Article/details/gt2mqguhxmk.html

[R21] 字符串长度
来源：http://dali.redwolf501.top/Article/details/gt2crkeccqi.html

echo "${#s}"
来源：http://dali.fengsongda.top/Article/details/gt2agxdsbtt.html

[R22] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gt2eluclcgx.html

echo "${s:0:5}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2wyfwxafx.html

[R23] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gt2febflbjm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnxiangtu.top/Article/details/gt2bholmluh.html

[R24] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gt2dffddwex.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sweek.top/Article/details/gt2bvgqrolq.html

[R25] 去后缀 / 去前缀
来源：http://dali.andypj.xyz/Article/details/gt2xecrwfdx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2twiyisbr.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gt2dmskeydz.html

now=$(date +%F); echo "$now"
来源：http://dali.ivvv.top/Article/details/gt2jzuhlubl.html

[R27] 算术展开
来源：http://dali.mhx1999.top/Article/details/gt2wjvqssaq.html

echo $((1 + 2 * 3))
来源：http://dali.cashguo.top/Article/details/gt2uifetmvd.html

[R28] 浮点运算
来源：http://dali.bjfxy.top/Article/details/gt2tlmrmdlb.html

echo "scale=2; 10/3" | bc
来源：http://dali.gogol.net.cn/Article/details/gt2beuftrwl.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gt2pbaptghp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cucudq.cn/Article/details/gt2xgqcbpsf.html

[R30] 函数返回状态码
来源：http://dali.feifeiyinyue.top/Article/details/gt2dcogphpu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gogol.net.cn/Article/details/gt2zkhmfunt.html

[R31] 局部变量
来源：http://dali.ybcxt.top/Article/details/gt2yyydnfcy.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgfzy.top/Article/details/gt2mmnjydye.html

[R32] 参数个数校验
来源：http://dali.yanxiufei.cn/Article/details/gt2gwuushck.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qecjyouq.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gt2yxsuondl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nwbrower.top/Article/details/gt2xihvykbf.html

[R34] 退出时清理
来源：http://dali.hysaishi.cn/Article/details/gt2fjrbdpfq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gt2lnfmlves.html

[R35] 后台执行并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qhcuklfr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pycfn.com/Article/details/gt2idnvyqur.html

[R36] 并发执行多个任务
来源：http://dali.yvedp.cn/Article/details/gt2rbtbuzpp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrhdgvh.html

[R37] 把输出赋给变量
来源：http://dali.tianlin.xyz/Article/details/gt2gnxsazsh.html

files=$(ls -1)
来源：http://dali.zycfv.cn/Article/details/gt2obuhrqfb.html

[R38] 管道串联
来源：http://dali.yuxming.cn/Article/details/gt2dlwrdwer.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yangfankeji.com/Article/details/gt2odvwbzjh.html

[R39] 重定向标准输出与错误
来源：http://dali.jyoumei.cn/Article/details/gt2xauhdkap.html

cmd > out.log 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gt2qdllnwuj.html

[R40] 追加写日志
来源：http://dali.smart0.xyz/Article/details/gt2gwpoholc.html

echo "log" >> out.log
来源：http://dali.hnqzz.top/Article/details/gt2ouzshtrb.html

[R41] 丢弃输出
来源：http://dali.tian-w.cn/Article/details/gt2ubzqyftb.html

cmd >/dev/null 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gt2bmkzlryc.html

[R42] 输入重定向
来源：http://dali.xinyue.icu/Article/details/gt2mqxkqwyf.html

wc -l < a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2xlefvadt.html

[R43] 按名字查找文件
来源：http://dali.hysaishi.cn/Article/details/gt2zxkultyx.html

find . -name "*.log" -type f
来源：http://dali.birdmap.top/Article/details/gt2ekbgxlpp.html

[R44] 按修改时间查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qjdqaykt.html

find . -mtime -7 -type f
来源：http://dali.hfpthk.cn/Article/details/gt2ndveflux.html

[R45] 批量删除
来源：http://dali.xuanzx.com/Article/details/gt2ehggggxh.html

find . -name "*.tmp" -delete
来源：http://dali.hnxiangtu.top/Article/details/gt2nepoicbb.html

[R46] 递归替换文件内容
来源：http://dali.9152youxi.cn/Article/details/gt2ctgkezxd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gt2mtebztvm.html

[R47] sed 单行替换
来源：http://dali.9152youxi.cn/Article/details/gt2wnacdtoq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2qrhlbnmf.html

[R48] awk 取指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2roqqjozo.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnqzz.top/Article/details/gt2hrzzqtsm.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gt2qcqbtbul.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dashuyun.cn/Article/details/gt2xpzmvwlu.html

[R50] awk 求和
来源：http://dali.wangshuangyany.cn/Article/details/gt2wurinuwm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.c1oappe.top/Article/details/gt2dkxsxfqm.html

[R51] 排序去重取前几
来源：http://dali.hywenlv.cn/Article/details/gt2mnzmfytw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sxryk.cn/Article/details/gt2esghjtiz.html

[R52] 统计行数
来源：http://dali.nanxinkj.top/Article/details/gt2ykbnquwp.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2lfocdctp.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gt2tokdduky.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.quarkkingdee.top/Article/details/gt2twxqqofu.html

[R54] 比较两个文件
来源：http://dali.daxiang520.top/Article/details/gt2cdwlccvw.html

diff a.txt b.txt
来源：http://dali.sweek.top/Article/details/gt2vpmqrahk.html

[R55] 压缩与解压
来源：http://dali.jqgfzy.top/Article/details/gt2obncwnmm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenlongwang.top/Article/details/gt2dspkqdua.html

[R56] 远程拷贝
来源：http://dali.dianchejie.cn/Article/details/gt2opdjuztf.html

scp file user@host:/path/
来源：http://dali.yangfankeji.com/Article/details/gt2tecwsjaj.html

[R57] 远程执行命令
来源：http://dali.yvedp.cn/Article/details/gt2fgbliepe.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kgdxueje.html

[R58] 下载文件
来源：http://dali.mhx1999.top/Article/details/gt2lilmgwui.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gt2jdsuhblm.html

[R59] 发 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gt2skdufyij.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gt2gjdnycxp.html

[R60] 只看 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gt2jhypdozb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.316326.xyz/Article/details/gt2bwbyvoky.html

[R61] 磁盘占用
来源：http://dali.hnxiangtu.top/Article/details/gt2jypsdnlv.html

df -h;  du -sh *
来源：http://dali.daxiang520.top/Article/details/gt2lupsgqlw.html

[R62] 找最占空间的文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2lvixhluw.html

du -ah . | sort -rh | head -10
来源：http://dali.yanxiufei.cn/Article/details/gt2njxyveym.html

[R63] 内存与进程
来源：http://dali.quarkkingdee.top/Article/details/gt2vrbohesy.html

free -h;  ps aux | grep nginx
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rcjmcktq.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gt2onofxmcm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.haohaochexian.top/Article/details/gt2qsreykvb.html

[R65] 查看端口占用
来源：http://dali.mhx1999.top/Article/details/gt2dathvvhi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.iojbl.cn/Article/details/gt2uqtxbibc.html

[R66] 定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjvrltpk.html

crontab -e;  crontab -l
来源：http://dali.haohaochexian.top/Article/details/gt2jcbvkdaq.html

[R67] 生成随机十六进制串
来源：http://dali.dashuyun.cn/Article/details/gt2tirdleix.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gt2qqjihnlv.html

[R68] 计算文件校验值
来源：http://dali.gzhubu.top/Article/details/gt2kromhiek.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cheryme.top/Article/details/gt2kgzevzby.html

[R69] 生成随机密码
来源：http://dali.tanke756.top/Article/details/gt2yzmzfozv.html

head -c 16 /dev/urandom | base64
来源：http://dali.aibaodan.cn/Article/details/gt2psrntqkq.html

[R70] 时间戳与互转
来源：http://dali.zhoulong.xyz/Article/details/gt2vuzlcirk.html

date +%s;  date -d @1700000000
来源：http://dali.shangyingyoupin.top/Article/details/gt2jphbovzj.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bmpdmcyt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.iojbl.cn/Article/details/gt2bggeioin.html

[R72] 等待端口就绪
来源：http://dali.hnqzz.top/Article/details/gt2vvqnpvmc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gt2qodidsjh.html

[R73] 分割大日志
来源：http://dali.havefunace.top/Article/details/gt2tirdgfuh.html

split -l 1000 big.log part_
来源：http://dali.yangfankeji.com/Article/details/gt2peoqwdxh.html

[R74] 批量重命名
来源：http://dali.pycfn.com/Article/details/gt2jerfhiia.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.kuanghao11.cn/Article/details/gt2pkxlaadq.html

[R75] 导出环境变量
来源：http://dali.guowangkeji.top/Article/details/gt2qulkkxjq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gt2yvkchvvn.html

[R76] 使用临时文件
来源：http://dali.yj202588.top/Article/details/gt2lririapj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2exkfnsjl.html

[R77] 读取用户输入
来源：http://dali.xinyue.icu/Article/details/gt2zlieojro.html

read -rp "请输入: " ans
来源：http://dali.jlsjyb.cn/Article/details/gt2lilfyqzv.html

[R78] 交互式菜单
来源：http://dali.wangshuangyany.cn/Article/details/gt2dvxyvmpw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aibaodan.cn/Article/details/gt2muqpcyxy.html

[R79] 解析命令行选项
来源：http://dali.feifeiyinyue.top/Article/details/gt2nipfjsiu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.quarkkingdee.top/Article/details/gt2ltodnscg.html

[R80] 查看脚本执行耗时
来源：http://dali.smart0.xyz/Article/details/gt2aqtmraod.html

time ./run.sh
来源：http://dali.kuanghao11.cn/Article/details/gt2usycsxad.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2kjyyglfr.html

S. C / C++ 专题
来源：http://dali.fzhhl.top/Article/details/gt2rjibkenm.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2vbqtwlek.html

[S01] C：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvxvrruz.html

#include <stdio.h>
来源：http://dali.tanke756.top/Article/details/gt2rrfjosya.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ugskrlxw.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gt2qckvbsha.html

int a = 10; printf("%d\n", a);
来源：http://dali.guannengcc.top/Article/details/gt2fkhjviic.html

[S03] C：读入整数
来源：http://dali.hnxiangtu.top/Article/details/gt2jshfdujo.html

int x; scanf("%d", &x);
来源：http://dali.sysykeji.top/Article/details/gt2ibbropjx.html

[S04] C：字符串复制
来源：http://dali.quarkkingdee.top/Article/details/gt2eelyzulq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhengqikj.top/Article/details/gt2conmycfg.html

[S05] C：字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gt2ykgpgbmz.html

strlen(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jcgfwzta.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gt2tmucczjy.html

strcmp(a, b) == 0
来源：http://dali.quarkkingdee.top/Article/details/gt2lhvpcaks.html

[S07] C：数组遍历求和
来源：http://dali.gzhubu.top/Article/details/gt2neujymhc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gotoacloud.top/Article/details/gt2jmijfamh.html

[S08] C：动态内存分配与释放
来源：http://dali.gzhubu.top/Article/details/gt2gvmltndx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnqzz.top/Article/details/gt2gjrvexmv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhoulong.xyz/Article/details/gt2kmtodzhd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pycfn.com/Article/details/gt2nwjhybci.html

[S10] C：指针与解引用
来源：http://dali.wangshuangyany.cn/Article/details/gt2awoemqtf.html

int *p = &a;  *p = 5;
来源：http://dali.vqdsnc.cn/Article/details/gt2ofgrnqak.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gt2awqnpoqt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenzaomai.com/Article/details/gt2mmhvxghd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgufenzy.top/Article/details/gt2twgykofc.html

fclose(f);
来源：http://dali.smart0.xyz/Article/details/gt2fpnavriq.html

[S12] C：写文件
来源：http://dali.fzhhl.top/Article/details/gt2xaufiuuc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yonumen.top/Article/details/gt2txbzchle.html

[S13] C：宏定义
来源：http://dali.snrcjt.cn/Article/details/gt2jfmihasj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnxiangtu.top/Article/details/gt2splfsafh.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gt2lwghkoip.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aibaodan.cn/Article/details/gt2jsoqifqf.html

[S15] C：类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2covqfqna.html

(double) a / b
来源：http://dali.yj202588.top/Article/details/gt2nfbnyukb.html

[S16] C：位操作置位
来源：http://dali.fengsongda.top/Article/details/gt2qroidhus.html

x |= (1 << 3);
来源：http://dali.yj20258.top/Article/details/gt2lhvkvegy.html

[S17] C：安全拼接字符串
来源：http://dali.c1oappe.top/Article/details/gt2fewgwcao.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.0kj1m.cn/Article/details/gt2pslgnrxi.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gt2mqtwlzyh.html

int main(int argc, char **argv)
来源：http://dali.mhx1999.top/Article/details/gt2hpksgubu.html

[S19] C：快速排序
来源：http://dali.feifeiyinyue.top/Article/details/gt2efuidnef.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gt2awaqgcxk.html

[S20] C：二分查找
来源：http://dali.dianchejie.cn/Article/details/gt2vdumbilj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gt2upjdsizw.html

[S21] C：字符类别判断
来源：http://dali.cashguo.top/Article/details/gt2isdpmgbv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ivvv.top/Article/details/gt2igxzdyzn.html

[S22] C：字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gt2txdumtvc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yongpay.top/Article/details/gt2qhzkvjwr.html

[S23] C：随机数
来源：http://dali.cdnleiting.top/Article/details/gt2ozxmwxob.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ehwqpu.com/Article/details/gt2hnmmkbvl.html

[S24] C：获取本地时间
来源：http://dali.pycfn.com/Article/details/gt2csgxiezk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.meibo888.top/Article/details/gt2fjltlsyc.html

[S25] C：内存拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nrsoxbqn.html

memcpy(dst, src, n);
来源：http://dali.jqgufenzy.top/Article/details/gt2xumuwrzz.html

[S26] C：内存清零
来源：http://dali.yj20258.top/Article/details/gt2rtfiwwhh.html

memset(a, 0, sizeof a);
来源：http://dali.sxryk.cn/Article/details/gt2ozikzkpd.html

[S27] C：定义常量
来源：http://dali.aizwys.cn/Article/details/gt2kqzspxvd.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gt2qrpzapax.html

[S28] C：静态变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2amcxfxjx.html

static int counter = 0;
来源：http://dali.daxiang520.top/Article/details/gt2jrebcmny.html

[S29] C：变参函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2loxkpuhz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.havefunace.top/Article/details/gt2uvbrcuqz.html

[S30] C：头文件保护
来源：http://dali.yongpay.top/Article/details/gt2mrewpcnm.html

#ifndef X_H
来源：http://dali.xinyue.icu/Article/details/gt2vobrfqqm.html

#define X_H
来源：http://dali.svipenyu.cn/Article/details/gt2kwqrzqyk.html

#endif
来源：http://dali.smart0.xyz/Article/details/gt2kuucskpw.html

[S31] C++：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2ipvakpux.html

#include <iostream>
来源：http://dali.cucudq.cn/Article/details/gt2cvgkrmyu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gogol.net.cn/Article/details/gt2mxrozpmk.html

[S32] C++：字符串
来源：http://dali.yongpay.top/Article/details/gt2kddbtumb.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gt2wtlwzmcn.html

[S33] C++：vector 增删
来源：http://dali.yj20258888.top/Article/details/gt2rklssikr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guannengcc.top/Article/details/gt2miruhrww.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mjmjhpvk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxinkj.top/Article/details/gt2iqikqxsw.html

[S35] C++：map
来源：http://dali.yanxiufei.cn/Article/details/gt2exaabehi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gt2qhhinica.html

[S36] C++：unordered_map
来源：http://dali.vqdsnc.cn/Article/details/gt2phxshucx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2gqnyxffd.html

[S37] C++：set
来源：http://dali.yuanzhike.top/Article/details/gt2wrfbwmll.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pjmvyyrc.html

[S38] C++：排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qlkxzhzo.html

std::sort(v.begin(), v.end());
来源：http://dali.ehwqpu.com/Article/details/gt2edmlzdrf.html

[S39] C++：自定义比较器排序
来源：http://dali.cheryme.top/Article/details/gt2jjaehmsg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.mhx1999.top/Article/details/gt2vfcgmfqe.html

[S40] C++：查找元素
来源：http://dali.birdmap.top/Article/details/gt2czshcoeb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hywenlv.cn/Article/details/gt2yzocyitr.html

[S41] C++：类与构造函数
来源：http://dali.xylfe.cn/Article/details/gt2mjppvqew.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gzhubu.top/Article/details/gt2siilkwag.html

[S42] C++：继承与虚函数
来源：http://dali.fzhhl.top/Article/details/gt2ucfqlfjo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhoulong.xyz/Article/details/gt2atozipqw.html

[S43] C++：智能指针
来源：http://dali.ybcxt.top/Article/details/gt2sqahgqqx.html

auto p = std::make_unique<int>(5);
来源：http://dali.cheryme.top/Article/details/gt2coxuwwpe.html

[S44] C++：引用传参
来源：http://dali.zhiwuduotai.top/Article/details/gt2lmjqmgsx.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gt2nulfyjll.html

[S45] C++：lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mrjglhki.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rqrkupkt.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gt2idpdqzdb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sxryk.cn/Article/details/gt2zoeicgnv.html


<!-- 参考信息 -->