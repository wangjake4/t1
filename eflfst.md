代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gt2dvlltnhf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gt2kugvilyt.html

[Q87] JSON 字段做条件
来源：http://dali.gzhubu.top/Article/details/gt2pnrbcbmp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aizwys.cn/Article/details/gt2mxlotnvf.html

[Q88] 行转列（条件聚合）
来源：http://dali.fengsongda.top/Article/details/gt2kqawuiss.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangshuangyany.cn/Article/details/gt2etryanzv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2pmwdfabm.html

[Q89] 判断表是否存在
来源：http://dali.hywenlv.cn/Article/details/gt2punguxdn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tian-w.cn/Article/details/gt2nouomggg.html

[Q90] 生成序号列
来源：http://dali.xziqi.cn/Article/details/gt2tcqaejoc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuanzhike.top/Article/details/gt2npaovolc.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2zwdedcal.html

R. Bash 专题
来源：http://dali.feifeiyinyue.top/Article/details/gt2eibjiioe.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2jiyhyymu.html

[R01] shebang 与严格模式
来源：http://dali.chenlongwang.top/Article/details/gt2vsfoujhx.html

#!/usr/bin/env bash
来源：http://dali.gotoacloud.top/Article/details/gt2aojslxhe.html

set -euo pipefail
来源：http://dali.gotoacloud.top/Article/details/gt2lujhwkhu.html

[R02] 变量赋值与使用
来源：http://dali.aibaodan.cn/Article/details/gt2stveyoku.html

name="Tom"; echo "$name"
来源：http://dali.cashguo.top/Article/details/gt2ibfrducq.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2medwgugb.html

readonly PI=3.14
来源：http://dali.ppjwa.cn/Article/details/gt2tjbhiycd.html

[R04] 位置参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2clzpysxq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2akndcnhn.html

[R05] 参数默认值
来源：http://dali.shzxlz.cn/Article/details/gt2kthajpxd.html

name="${1:-default}"
来源：http://dali.iojbl.cn/Article/details/gt2opnnuzjt.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gt2lgwedshb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gt2kfciffoe.html

[R07] if 判断文件
来源：http://dali.zhoulong.xyz/Article/details/gt2yxdxvrdk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xylfe.cn/Article/details/gt2vwfciuyq.html

[R08] 数值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxjgvnnu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuxming.cn/Article/details/gt2blhqavda.html

[R09] 字符串比较
来源：http://dali.sxryk.cn/Article/details/gt2qakgtzhj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gt2uziucexk.html

[R10] 正则匹配
来源：http://dali.havefunace.top/Article/details/gt2pksmmscr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhengqikj.top/Article/details/gt2piiknbza.html

[R11] case 多分支
来源：http://dali.yongpay.top/Article/details/gt2sogdecne.html

case "$1" in
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2duwijilc.html

start) echo "启动" ;;
来源：http://dali.snrcjt.cn/Article/details/gt2agoeknfp.html

stop)  echo "停止" ;;
来源：http://dali.yongpay.top/Article/details/gt2qnemkomq.html

*)     echo "未知命令" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gt2rlbqaipr.html

esac
来源：http://dali.c1oappe.top/Article/details/gt2chfzqlgf.html

[R12] for 遍历文件
来源：http://dali.ydzc1.top/Article/details/gt2ffhohehs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gt2jvhkcenj.html

[R13] for 计数循环
来源：http://dali.daxiang520.top/Article/details/gt2epcurzhl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2vknxfpmt.html

[R14] C 风格 for
来源：http://dali.chenzaomai.com/Article/details/gt2akccvldp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gt2ngxyrovg.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2znagvfhj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guannengcc.top/Article/details/gt2fpyssedz.html

[R16] until 等待条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2goqabqxd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gt2yqfejimx.html

[R17] 数组定义与取值
来源：http://dali.cashguo.top/Article/details/gt2vpjfehgd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jlsjyb.cn/Article/details/gt2kfceyaxf.html

[R18] 遍历数组
来源：http://dali.pengpengdd.cyou/Article/details/gt2npclydjq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2dlojyrzk.html

[R19] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gt2wgqqytbz.html

echo "${#arr[@]}"
来源：http://dali.andypj.xyz/Article/details/gt2kyhmfqgi.html

[R20] 关联数组（字典）
来源：http://dali.jqgufenzy.top/Article/details/gt2cmxwxhfw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cdnleiting.top/Article/details/gt2elfxfofr.html

[R21] 字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nyldcmad.html

echo "${#s}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rooryhhc.html

[R22] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gt2rwierpfp.html

echo "${s:0:5}"
来源：http://dali.vqdsnc.cn/Article/details/gt2lzudooyk.html

[R23] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gt2nfbkjmtn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.meibo888.top/Article/details/gt2ygpuirjt.html

[R24] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kfjsoxkp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ftqmcnyo.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gt2yvexzeoy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hydfpyvg.html

[R26] 命令替换
来源：http://dali.yangfankeji.com/Article/details/gt2dfjdcjds.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gt2fdrluvfm.html

[R27] 算术展开
来源：http://dali.wangdashe.top/Article/details/gt2xnfswrlq.html

echo $((1 + 2 * 3))
来源：http://dali.sysykeji.top/Article/details/gt2lzvptkhd.html

[R28] 浮点运算
来源：http://dali.haohaochexian.top/Article/details/gt2dyrxfkpm.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenlongwang.top/Article/details/gt2rgwcyume.html

[R29] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gt2spejmftl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ydzc1.top/Article/details/gt2nbdiazvt.html

[R30] 函数返回状态码
来源：http://dali.mhx1999.top/Article/details/gt2yxxzflud.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.haohaochexian.top/Article/details/gt2cxucqyzs.html

[R31] 局部变量
来源：http://dali.yuxming.cn/Article/details/gt2tqfvskej.html

f() { local x=1; echo "$x"; }
来源：http://dali.hammf.cn/Article/details/gt2yphckhwg.html

[R32] 参数个数校验
来源：http://dali.yueranfly.top/Article/details/gt2kugoqrnc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gt2mqgchcmf.html

[R33] 捕获错误并提示行号
来源：http://dali.hywenlv.cn/Article/details/gt2hjegfmtc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sxryk.cn/Article/details/gt2molxobaa.html

[R34] 退出时清理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rqxctwjn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gt2yrudscuo.html

[R35] 后台执行并等待
来源：http://dali.redwolf501.top/Article/details/gt2lfdigbmu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ehwqpu.com/Article/details/gt2zpcdkftl.html

[R36] 并发执行多个任务
来源：http://dali.hywenlv.cn/Article/details/gt2cqorbsgt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigufen.top/Article/details/gt2cwriiuml.html

[R37] 把输出赋给变量
来源：http://dali.fzhhl.top/Article/details/gt2uevjtjbj.html

files=$(ls -1)
来源：http://dali.sxryk.cn/Article/details/gt2xecswyko.html

[R38] 管道串联
来源：http://dali.haohaochexian.top/Article/details/gt2gsmvpeel.html

cat a.txt | grep -i error | wc -l
来源：http://dali.smart0.xyz/Article/details/gt2wretbnbk.html

[R39] 重定向标准输出与错误
来源：http://dali.meibo888.top/Article/details/gt2bnypoqct.html

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gt2dlsjwzsg.html

[R40] 追加写日志
来源：http://dali.smart0.xyz/Article/details/gt2mhoaycnk.html

echo "log" >> out.log
来源：http://dali.yuxming.cn/Article/details/gt2orswkmhl.html

[R41] 丢弃输出
来源：http://dali.jlsjyb.cn/Article/details/gt2cfjlwuew.html

cmd >/dev/null 2>&1
来源：http://dali.sufxvd.cn/Article/details/gt2fesevqpb.html

[R42] 输入重定向
来源：http://dali.yvedp.cn/Article/details/gt2czxosrbc.html

wc -l < a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2npdimucj.html

[R43] 按名字查找文件
来源：http://dali.guannengcc.top/Article/details/gt2bdbpgmnb.html

find . -name "*.log" -type f
来源：http://dali.tian-w.cn/Article/details/gt2pmocnehy.html

[R44] 按修改时间查找
来源：http://dali.dashuyun.cn/Article/details/gt2hlfksqvl.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gt2mczfrfyh.html

[R45] 批量删除
来源：http://dali.xinyue.icu/Article/details/gt2tfqbxlto.html

find . -name "*.tmp" -delete
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mtfsgqhp.html

[R46] 递归替换文件内容
来源：http://dali.hnqzz.top/Article/details/gt2czjlcoqf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctqowxkn.html

[R47] sed 单行替换
来源：http://dali.zhoulong.xyz/Article/details/gt2isogcxhe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2mfakutia.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gt2ktdipnhy.html

awk '{print $1, $3}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2jhtwuine.html

[R49] awk 带条件
来源：http://dali.ydzc1.top/Article/details/gt2ngawrqtq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aibaodan.cn/Article/details/gt2jdopxvyo.html

[R50] awk 求和
来源：http://dali.yangfankeji.com/Article/details/gt2dgbrvfsw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2opzbjcfw.html

[R51] 排序去重取前几
来源：http://dali.tanke756.top/Article/details/gt2cngwlhxh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xziqi.cn/Article/details/gt2dqxtoecn.html

[R52] 统计行数
来源：http://dali.chenzaomai.com/Article/details/gt2mhjnespb.html

wc -l a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2wwlaiiwv.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gt2vsopwvpo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sweek.top/Article/details/gt2puuastkq.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gt2mpmupuir.html

diff a.txt b.txt
来源：http://dali.haohaochexian.top/Article/details/gt2nhfwmkpb.html

[R55] 压缩与解压
来源：http://dali.jqgfzy.top/Article/details/gt2yrjabiar.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gt2pzlndffh.html

[R56] 远程拷贝
来源：http://dali.jyoumei.cn/Article/details/gt2cltrbdhf.html

scp file user@host:/path/
来源：http://dali.yangfankeji.com/Article/details/gt2laiwxsvc.html

[R57] 远程执行命令
来源：http://dali.vqdsnc.cn/Article/details/gt2puzscmjt.html

ssh user@host 'uptime'
来源：http://dali.xinyue.icu/Article/details/gt2cizbawzc.html

[R58] 下载文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2uwldcpnn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hammf.cn/Article/details/gt2ddevtpws.html

[R59] 发 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2scglhwda.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cucudq.cn/Article/details/gt2rfjmwmsd.html

[R60] 只看 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gt2xhwaaiic.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ydzc1.top/Article/details/gt2esdrkwgl.html

[R61] 磁盘占用
来源：http://dali.guowangkeji.top/Article/details/gt2nhsnuszb.html

df -h;  du -sh *
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lilbhlyx.html

[R62] 找最占空间的文件
来源：http://dali.tanke756.top/Article/details/gt2nuipmrhp.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigfzy.top/Article/details/gt2tnrcomev.html

[R63] 内存与进程
来源：http://dali.gzhubu.top/Article/details/gt2wcmdwvij.html

free -h;  ps aux | grep nginx
来源：http://dali.jyoumei.cn/Article/details/gt2bcdmieyn.html

[R64] 结束进程
来源：http://dali.zdqjudy.top/Article/details/gt2dntvbgrn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vypdutgh.html

[R65] 查看端口占用
来源：http://dali.gaohongyu789.top/Article/details/gt2adyhnity.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cqqwz.cn/Article/details/gt2lntnnazf.html

[R66] 定时任务
来源：http://dali.tianlin.xyz/Article/details/gt2yhjahpuo.html

crontab -e;  crontab -l
来源：http://dali.tanke756.top/Article/details/gt2oozlhtip.html

[R67] 生成随机十六进制串
来源：http://dali.shuidangran.top/Article/details/gt2rcytmokg.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gt2lpwuixld.html

[R68] 计算文件校验值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vjobpdkx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yongpay.top/Article/details/gt2xzjerrwv.html

[R69] 生成随机密码
来源：http://dali.daxiang520.top/Article/details/gt2ncdwbcqq.html

head -c 16 /dev/urandom | base64
来源：http://dali.yanxiufei.cn/Article/details/gt2qtxljyaj.html

[R70] 时间戳与互转
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqolrxrd.html

date +%s;  date -d @1700000000
来源：http://dali.daxiang520.top/Article/details/gt2gjqnudqc.html

[R71] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gt2gflvyyxy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jianghu66.top/Article/details/gt2bmjizwzw.html

[R72] 等待端口就绪
来源：http://dali.ydzc1.top/Article/details/gt2wnswhfcm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gt2vqgiudec.html

[R73] 分割大日志
来源：http://dali.daxiang520.top/Article/details/gt2zsfltmdg.html

split -l 1000 big.log part_
来源：http://dali.yj20258888.top/Article/details/gt2ohyjnkvc.html

[R74] 批量重命名
来源：http://dali.vqdsnc.cn/Article/details/gt2dvaewnhy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gzhubu.top/Article/details/gt2mgooxfsj.html

[R75] 导出环境变量
来源：http://dali.ivvv.top/Article/details/gt2vaplgtjp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.meibo888.top/Article/details/gt2ixznduov.html

[R76] 使用临时文件
来源：http://dali.aizwys.cn/Article/details/gt2acyfyyro.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gt2mqsvwncp.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzxozazv.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gt2satuzthw.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gt2vjpqicew.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gt2pnyoclae.html

[R79] 解析命令行选项
来源：http://dali.shzxlz.cn/Article/details/gt2xqecplxq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sweek.top/Article/details/gt2taprgdgy.html

[R80] 查看脚本执行耗时
来源：http://dali.tianlin.xyz/Article/details/gt2urybxleu.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gt2mlgrxcms.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2dhzaudhh.html

S. C / C++ 专题
来源：http://dali.nwbrower.top/Article/details/gt2uspyuugr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2ebliimlj.html

[S01] C：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2txxknyvx.html

#include <stdio.h>
来源：http://dali.yongpay.top/Article/details/gt2fquhhoay.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258.top/Article/details/gt2jpojvinr.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iceodclg.html

int a = 10; printf("%d\n", a);
来源：http://dali.xinyue.icu/Article/details/gt2txjqppic.html

[S03] C：读入整数
来源：http://dali.vqdsnc.cn/Article/details/gt2qfzqapht.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gt2hwqczdwy.html

[S04] C：字符串复制
来源：http://dali.yuanzhike.top/Article/details/gt2hqgyahwj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yjziqmxw.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gt2gkaqdwka.html

strlen(s)
来源：http://dali.meibo888.top/Article/details/gt2jfjqvjec.html

[S06] C：字符串比较
来源：http://dali.nanxinkj.top/Article/details/gt2dmadkyys.html

strcmp(a, b) == 0
来源：http://dali.ppjwa.cn/Article/details/gt2wpebpkaq.html

[S07] C：数组遍历求和
来源：http://dali.hysaishi.cn/Article/details/gt2savdjuxi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ydzc1.top/Article/details/gt2cqxdfoxy.html

[S08] C：动态内存分配与释放
来源：http://dali.tianlin.xyz/Article/details/gt2rqbbgrfs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tianlin.xyz/Article/details/gt2yiqwvfwr.html

[S09] C：结构体定义与初始化
来源：http://dali.hammf.cn/Article/details/gt2hbkxfvyx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gt2nqxeutla.html

[S10] C：指针与解引用
来源：http://dali.sweek.top/Article/details/gt2knwuitwj.html

int *p = &a;  *p = 5;
来源：http://dali.chenzaomai.com/Article/details/gt2ktysamxd.html

[S11] C：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gt2ctswcwtz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sxryk.cn/Article/details/gt2rveaynqd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guannengcc.top/Article/details/gt2nqgnlyck.html

fclose(f);
来源：http://dali.ydzc1.top/Article/details/gt2iomvvmee.html

[S12] C：写文件
来源：http://dali.hfpthk.cn/Article/details/gt2qokpshbo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gt2uwlokrxn.html

[S13] C：宏定义
来源：http://dali.hysaishi.cn/Article/details/gt2wkrrytbz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuxming.cn/Article/details/gt2dthvvniz.html

[S14] C：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gt2bgarioux.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dianchejie.cn/Article/details/gt2atxbhskw.html

[S15] C：类型转换
来源：http://dali.sysykeji.top/Article/details/gt2pgbhveku.html

(double) a / b
来源：http://dali.zhengqikj.top/Article/details/gt2pfhxotlr.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gt2tdugpjty.html

x |= (1 << 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ecawlonq.html

[S17] C：安全拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gt2quapojvp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gt2bsyrefbn.html

[S18] C：命令行参数
来源：http://dali.xylfe.cn/Article/details/gt2ddbewclq.html

int main(int argc, char **argv)
来源：http://dali.daria6918.cn/Article/details/gt2tjyjmqyj.html

[S19] C：快速排序
来源：http://dali.cucudq.cn/Article/details/gt2oebotfln.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gt2rowblars.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gt2fqvretbn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gt2gqjimmpz.html

[S21] C：字符类别判断
来源：http://dali.jqgufenzy.top/Article/details/gt2ehwbwurp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ybcxt.top/Article/details/gt2oqblcenc.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gt2qwxplzme.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nwbrower.top/Article/details/gt2eeyvmeko.html

[S23] C：随机数
来源：http://dali.316326.xyz/Article/details/gt2rbljprkk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwsqebqz.html

[S24] C：获取本地时间
来源：http://dali.aizwys.cn/Article/details/gt2sshiaetc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxinkj.top/Article/details/gt2nytlmigf.html

[S25] C：内存拷贝
来源：http://dali.daria6918.cn/Article/details/gt2gjxbtuwp.html

memcpy(dst, src, n);
来源：http://dali.ivvv.top/Article/details/gt2fxmadoxp.html

[S26] C：内存清零
来源：http://dali.cashguo.top/Article/details/gt2qlynwcnm.html

memset(a, 0, sizeof a);
来源：http://dali.chenlongwang.top/Article/details/gt2svnpmajw.html

[S27] C：定义常量
来源：http://dali.0kj1m.cn/Article/details/gt2vyfaryjt.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2hxhopwpf.html

[S28] C：静态变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2czokgfxl.html

static int counter = 0;
来源：http://dali.ivvv.top/Article/details/gt2lakqprzy.html

[S29] C：变参函数
来源：http://dali.aibaodan.cn/Article/details/gt2qghwtcdv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gt2zsbsnxpg.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gt2ebtqcakx.html

#ifndef X_H
来源：http://dali.daria6918.cn/Article/details/gt2pwavavnk.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gt2cfamvlat.html

#endif
来源：http://dali.xziqi.cn/Article/details/gt2ehoacnao.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2gjodshul.html

#include <iostream>
来源：http://dali.jiagoushi.top/Article/details/gt2fbdxbltt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.smart0.xyz/Article/details/gt2qcjhxpco.html

[S32] C++：字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2lqpufoyd.html

std::string s = "hi";  s += "!";
来源：http://dali.vqdsnc.cn/Article/details/gt2ejekcqya.html

[S33] C++：vector 增删
来源：http://dali.pycfn.com/Article/details/gt2jgfadmwm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2hscmldfy.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qznmzunm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ivazupva.html

[S35] C++：map
来源：http://dali.c1oappe.top/Article/details/gt2urfvackq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gt2tznjvjwu.html

[S36] C++：unordered_map
来源：http://dali.zhongyouzk.top/Article/details/gt2avufpeol.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2exkhdmab.html

[S37] C++：set
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ervaignt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nwbrower.top/Article/details/gt2mbytdlpx.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gt2nzzpelak.html

std::sort(v.begin(), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vhekchsh.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gt2dxfblqpi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dmdnesdi.html

[S40] C++：查找元素
来源：http://dali.chenzaomai.com/Article/details/gt2ufhfhndd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.meibo888.top/Article/details/gt2cbyepilr.html

[S41] C++：类与构造函数
来源：http://dali.xylfe.cn/Article/details/gt2ienxbssy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.iojbl.cn/Article/details/gt2qfksjwnf.html

[S42] C++：继承与虚函数
来源：http://dali.zycfv.cn/Article/details/gt2twidmhrs.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenlongwang.top/Article/details/gt2fceiazsk.html

[S43] C++：智能指针
来源：http://dali.ivvv.top/Article/details/gt2eqkcwezg.html

auto p = std::make_unique<int>(5);
来源：http://dali.smart0.xyz/Article/details/gt2mjkunouj.html

[S44] C++：引用传参
来源：http://dali.jyoumei.cn/Article/details/gt2tpnxzzqy.html

void inc(int &x) { ++x; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bvgyspzd.html

[S45] C++：lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ptdmwvcp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2timcpokh.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gt2jnqucxfp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bpuliddp.html

[S47] C++：结构化绑定遍历
来源：http://dali.xylfe.cn/Article/details/gt2slxdxhtv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dianchejie.cn/Article/details/gt2kknzzusx.html

[S48] C++：逐行读文件
来源：http://dali.pycfn.com/Article/details/gt2xvqgitow.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aitwhydc.html

while (std::getline(in, line)) { }
来源：http://dali.birdmap.top/Article/details/gt2aizpdblc.html

[S49] C++：写文件
来源：http://dali.meibo888.top/Article/details/gt2etfygwhq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nwbrower.top/Article/details/gt2hhgjqooa.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gt2mhbcobmj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gt2radymbgv.html

[S51] C++：显式类型转换
来源：http://dali.quarkkingdee.top/Article/details/gt2hbriirup.html

static_cast<double>(a) / b
来源：http://dali.fengsongda.top/Article/details/gt2pvqvtzac.html

[S52] C++：const 与 noexcept
来源：http://dali.shangyingyoupin.top/Article/details/gt2vapmaacs.html

int size() const noexcept { return n_; }
来源：http://dali.fengsongda.top/Article/details/gt2opfehcdx.html

[S53] C++：移动语义
来源：http://dali.shzxlz.cn/Article/details/gt2ftrfoini.html

std::vector<int> w = std::move(v);
来源：http://dali.zhoulong.xyz/Article/details/gt2qsrgoecz.html

[S54] C++：异常处理
来源：http://dali.snrcjt.cn/Article/details/gt2uxgpehgo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.mhx1999.top/Article/details/gt2rzdvkrcx.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gt2ugtmhjjo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.smart0.xyz/Article/details/gt2navjbyir.html

[S56] C++：optional
来源：http://dali.chenlongwang.top/Article/details/gt2trukclsz.html


<!-- 参考信息 -->