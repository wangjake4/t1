代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gt2ibvmveaj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghmuudis.html

[Q87] JSON 字段做条件
来源：http://dali.chenzaomai.com/Article/details/gt2ppxmwzbp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cdnleiting.top/Article/details/gt2uonxbfch.html

[Q88] 行转列（条件聚合）
来源：http://dali.yonumen.top/Article/details/gt2nhxiyrtc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.feifeiyinyue.top/Article/details/gt2bxzoawey.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2irslyxnp.html

[Q89] 判断表是否存在
来源：http://dali.meibo888.top/Article/details/gt2wsbhgkft.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.c1oappe.top/Article/details/gt2hllevhob.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2gumdcsix.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.kuanghao11.cn/Article/details/gt2uecccqes.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljkkppvr.html

R. Bash 专题
来源：http://dali.haohaochexian.top/Article/details/gt2ixaqvxao.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2aqvtehoi.html

[R01] shebang 与严格模式
来源：http://dali.zycfv.cn/Article/details/gt2ojkaxwtu.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gt2iynmlnto.html

set -euo pipefail
来源：http://dali.ybcxt.top/Article/details/gt2nhpltask.html

[R02] 变量赋值与使用
来源：http://dali.xuanzx.com/Article/details/gt2fmankbzi.html

name="Tom"; echo "$name"
来源：http://dali.shuidangran.top/Article/details/gt2aucfhknc.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gt2wfrjeopd.html

readonly PI=3.14
来源：http://dali.zhengqikj.top/Article/details/gt2udsxhafk.html

[R04] 位置参数
来源：http://dali.ppjwa.cn/Article/details/gt2senrwbnj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guannengcc.top/Article/details/gt2cztuvhti.html

[R05] 参数默认值
来源：http://dali.hammf.cn/Article/details/gt2yrcwdmid.html

name="${1:-default}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajhgevgp.html

[R06] 判断命令是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lsvoutft.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gt2brbvwxbs.html

[R07] if 判断文件
来源：http://dali.c1oappe.top/Article/details/gt2xgcieroo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fzhhl.top/Article/details/gt2bmsuswto.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gt2eipydvjv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fzhhl.top/Article/details/gt2ingfwmrb.html

[R09] 字符串比较
来源：http://dali.nanxinkj.top/Article/details/gt2mvjpjydv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ehwqpu.com/Article/details/gt2ujiwkkqw.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gt2hnlpstzb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.iojbl.cn/Article/details/gt2fjvesvpp.html

[R11] case 多分支
来源：http://dali.aizwys.cn/Article/details/gt2gxohzkev.html

case "$1" in
来源：http://dali.hfpthk.cn/Article/details/gt2vejpayfr.html

start) echo "启动" ;;
来源：http://dali.316326.xyz/Article/details/gt2xdvzumyz.html

stop)  echo "停止" ;;
来源：http://dali.zhengqikj.top/Article/details/gt2rzlzaxur.html

*)     echo "未知命令" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dtgnoctz.html

esac
来源：http://dali.yanxiufei.cn/Article/details/gt2oyvssncd.html

[R12] for 遍历文件
来源：http://dali.tian-w.cn/Article/details/gt2wbsbltgz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxhbklcw.html

[R13] for 计数循环
来源：http://dali.zhoulong.xyz/Article/details/gt2ngutencd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gt2tiwvvhif.html

[R14] C 风格 for
来源：http://dali.yvedp.cn/Article/details/gt2pjkcoezp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gt2gthhfnsj.html

[R15] while 逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gt2ixmxeffd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2cmfovamk.html

[R16] until 等待条件
来源：http://dali.fengsongda.top/Article/details/gt2jybgazbj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gt2tszlvriz.html

[R17] 数组定义与取值
来源：http://dali.nwbrower.top/Article/details/gt2vdkyryde.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.havefunace.top/Article/details/gt2rgvxbrjl.html

[R18] 遍历数组
来源：http://dali.zdqjudy.top/Article/details/gt2dglpuwff.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.havefunace.top/Article/details/gt2vderiadf.html

[R19] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gt2bahurfjb.html

echo "${#arr[@]}"
来源：http://dali.hfpthk.cn/Article/details/gt2ytkcxpie.html

[R20] 关联数组（字典）
来源：http://dali.quarkkingdee.top/Article/details/gt2wdxmsmcp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.bjfxy.top/Article/details/gt2uvmboitx.html

[R21] 字符串长度
来源：http://dali.snrcjt.cn/Article/details/gt2cjpdxffa.html

echo "${#s}"
来源：http://dali.aizwys.cn/Article/details/gt2ptwuowdz.html

[R22] 截取子串
来源：http://dali.guannengcc.top/Article/details/gt2tchrdpjd.html

echo "${s:0:5}"
来源：http://dali.gogol.net.cn/Article/details/gt2kqnpawvn.html

[R23] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gt2mwghnzmy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ybcxt.top/Article/details/gt2umrkevqz.html

[R24] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gt2ywojwary.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jiagoushi.top/Article/details/gt2wspuoyhw.html

[R25] 去后缀 / 去前缀
来源：http://dali.gogol.net.cn/Article/details/gt2kdsnfipe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.svipenyu.cn/Article/details/gt2oanjwtus.html

[R26] 命令替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dfirmjrb.html

now=$(date +%F); echo "$now"
来源：http://dali.jyoumei.cn/Article/details/gt2ognbveqv.html

[R27] 算术展开
来源：http://dali.cheryme.top/Article/details/gt2lflwkvxa.html

echo $((1 + 2 * 3))
来源：http://dali.xinyue.icu/Article/details/gt2amjydqos.html

[R28] 浮点运算
来源：http://dali.redwolf501.top/Article/details/gt2xqtpybpj.html

echo "scale=2; 10/3" | bc
来源：http://dali.pengpengdd.cyou/Article/details/gt2hoyypxwk.html

[R29] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gt2pfinotgs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yongpay.top/Article/details/gt2vkvstlme.html

[R30] 函数返回状态码
来源：http://dali.jyoumei.cn/Article/details/gt2sgzlrdlc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxuanxn.top/Article/details/gt2wysafdns.html

[R31] 局部变量
来源：http://dali.mhx1999.top/Article/details/gt2aowshqrw.html

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gt2ozrblqen.html

[R32] 参数个数校验
来源：http://dali.cdnleiting.top/Article/details/gt2cubswltb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gbaoqsej.html

[R33] 捕获错误并提示行号
来源：http://dali.ppjwa.cn/Article/details/gt2rijmhpxk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fzhhl.top/Article/details/gt2bktrgfhc.html

[R34] 退出时清理
来源：http://dali.tianlin.xyz/Article/details/gt2riboizyc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gt2hldsmzvj.html

[R35] 后台执行并等待
来源：http://dali.yangfankeji.com/Article/details/gt2sjfyzwcw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nvvnyrxt.html

[R36] 并发执行多个任务
来源：http://dali.xuanzx.com/Article/details/gt2yotevnld.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shzxlz.cn/Article/details/gt2snkfoedq.html

[R37] 把输出赋给变量
来源：http://dali.smart0.xyz/Article/details/gt2mpllajyr.html

files=$(ls -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2onnphtlh.html

[R38] 管道串联
来源：http://dali.ydzc1.top/Article/details/gt2ptpzaukc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gt2zxkzafhm.html

[R39] 重定向标准输出与错误
来源：http://dali.vqdsnc.cn/Article/details/gt2tzbqbwrr.html

cmd > out.log 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gt2ddrxfmfq.html

[R40] 追加写日志
来源：http://dali.ydzc1.top/Article/details/gt2kynvcodf.html

echo "log" >> out.log
来源：http://dali.hnxiangtu.top/Article/details/gt2adbnpfgk.html

[R41] 丢弃输出
来源：http://dali.quarkkingdee.top/Article/details/gt2awfqozbw.html

cmd >/dev/null 2>&1
来源：http://dali.yuanzhike.top/Article/details/gt2macaqupv.html

[R42] 输入重定向
来源：http://dali.yvedp.cn/Article/details/gt2csdmdjuj.html

wc -l < a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2uhkoskxf.html

[R43] 按名字查找文件
来源：http://dali.cqqwz.cn/Article/details/gt2aqjhcmhd.html

find . -name "*.log" -type f
来源：http://dali.tianlin.xyz/Article/details/gt2peiryreu.html

[R44] 按修改时间查找
来源：http://dali.wangdashe.top/Article/details/gt2axsizkcq.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gt2muyowibs.html

[R45] 批量删除
来源：http://dali.c1oappe.top/Article/details/gt2fpvwmdlj.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jlyqwdrs.html

[R46] 递归替换文件内容
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgherera.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.0kj1m.cn/Article/details/gt2kpnmsgpt.html

[R47] sed 单行替换
来源：http://dali.andypj.xyz/Article/details/gt2pvlhjgvw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cheryme.top/Article/details/gt2nkbkhxlp.html

[R48] awk 取指定列
来源：http://dali.smart0.xyz/Article/details/gt2jeiukxgq.html

awk '{print $1, $3}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nqgvjjdk.html

[R49] awk 带条件
来源：http://dali.zhixingplan.top/Article/details/gt2fnajbtlo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgfzy.top/Article/details/gt2qszalran.html

[R50] awk 求和
来源：http://dali.hongshengwenyu.top/Article/details/gt2xxpmtunm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2wptpvrqj.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uwopnhss.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guowangkeji.top/Article/details/gt2ejooqquf.html

[R52] 统计行数
来源：http://dali.yuanzhike.top/Article/details/gt2twmbhcoh.html

wc -l a.txt
来源：http://dali.havefunace.top/Article/details/gt2dsbtgryx.html

[R53] 查看文件头与实时尾
来源：http://dali.sysykeji.top/Article/details/gt2keevsvtq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2usnqghpt.html

[R54] 比较两个文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2jtjmiyxq.html

diff a.txt b.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2ymvcyifk.html

[R55] 压缩与解压
来源：http://dali.jyoumei.cn/Article/details/gt2ysoqphge.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cdnleiting.top/Article/details/gt2dwqlfsny.html

[R56] 远程拷贝
来源：http://dali.ybcxt.top/Article/details/gt2sedtcuoe.html

scp file user@host:/path/
来源：http://dali.316326.xyz/Article/details/gt2sjivcuuh.html

[R57] 远程执行命令
来源：http://dali.haohaochexian.top/Article/details/gt2ijzsyvij.html

ssh user@host 'uptime'
来源：http://dali.ppjwa.cn/Article/details/gt2tntlmpga.html

[R58] 下载文件
来源：http://dali.nwbrower.top/Article/details/gt2azjxaenk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gt2ivojaymb.html

[R59] 发 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gt2yrnqqsjx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gt2neczzcvx.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2puycfecc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gt2gqlopgoe.html

[R61] 磁盘占用
来源：http://dali.fzhhl.top/Article/details/gt2npoagkdu.html

df -h;  du -sh *
来源：http://dali.yueranfly.top/Article/details/gt2rdgjggru.html

[R62] 找最占空间的文件
来源：http://dali.cdnleiting.top/Article/details/gt2opkyuvpc.html

du -ah . | sort -rh | head -10
来源：http://dali.aibaodan.cn/Article/details/gt2izpmidbn.html

[R63] 内存与进程
来源：http://dali.nanxinkj.top/Article/details/gt2iqyifvcs.html

free -h;  ps aux | grep nginx
来源：http://dali.xuetiantiany.cn/Article/details/gt2wfzasqkx.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gt2fqfwlsur.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cqqwz.cn/Article/details/gt2siilbeby.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gt2ezyhvfpb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ydzc1.top/Article/details/gt2wnuhszux.html

[R66] 定时任务
来源：http://dali.zhixingplan.top/Article/details/gt2wkbndzwt.html

crontab -e;  crontab -l
来源：http://dali.yonumen.top/Article/details/gt2iiyqxrum.html

[R67] 生成随机十六进制串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ozkfiakk.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gt2jhyesaju.html

[R68] 计算文件校验值
来源：http://dali.yuanzhike.top/Article/details/gt2hoyqdlze.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2udsbebzu.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2esovsmjs.html

head -c 16 /dev/urandom | base64
来源：http://dali.cashguo.top/Article/details/gt2hopphjty.html

[R70] 时间戳与互转
来源：http://dali.hfpthk.cn/Article/details/gt2jotibtzp.html

date +%s;  date -d @1700000000
来源：http://dali.wangshuangyany.cn/Article/details/gt2gntasosq.html

[R71] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gt2ptfewthl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jlsjyb.cn/Article/details/gt2simkzdhz.html

[R72] 等待端口就绪
来源：http://dali.nanxuanxn.top/Article/details/gt2qvewcqxv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gt2kcjffpbk.html

[R73] 分割大日志
来源：http://dali.haohaochexian.top/Article/details/gt2dhhhbbvx.html

split -l 1000 big.log part_
来源：http://dali.vqdsnc.cn/Article/details/gt2ecraxogm.html

[R74] 批量重命名
来源：http://dali.gotoacloud.top/Article/details/gt2fvxuvewm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2lpadkwak.html

[R75] 导出环境变量
来源：http://dali.cheryme.top/Article/details/gt2fnytgglf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hfpthk.cn/Article/details/gt2vnphfkmy.html

[R76] 使用临时文件
来源：http://dali.tian-w.cn/Article/details/gt2meftpwok.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gt2hvfjqgaz.html

[R77] 读取用户输入
来源：http://dali.guowangkeji.top/Article/details/gt2rpfxebdi.html

read -rp "请输入: " ans
来源：http://dali.vqdsnc.cn/Article/details/gt2rmcjsulm.html

[R78] 交互式菜单
来源：http://dali.gotoacloud.top/Article/details/gt2keiexnic.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgfzy.top/Article/details/gt2wjayjwlx.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfohsiaa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hammf.cn/Article/details/gt2bucmoywr.html

[R80] 查看脚本执行耗时
来源：http://dali.ybcxt.top/Article/details/gt2yycyqbwa.html

time ./run.sh
来源：http://dali.hongshengwenyu.top/Article/details/gt2koqtjygg.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2xfbaxyxc.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gt2bestspaw.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2qzmbeekh.html

[S01] C：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2jbzxmnhq.html

#include <stdio.h>
来源：http://dali.yvedp.cn/Article/details/gt2zazphhoc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jianghu66.top/Article/details/gt2qixajbet.html

[S02] C：变量与格式化输出
来源：http://dali.smart0.xyz/Article/details/gt2zglfbdrm.html

int a = 10; printf("%d\n", a);
来源：http://dali.guannengcc.top/Article/details/gt2comeczdg.html

[S03] C：读入整数
来源：http://dali.guowangkeji.top/Article/details/gt2gfdsocsn.html

int x; scanf("%d", &x);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wxyxgqpi.html

[S04] C：字符串复制
来源：http://dali.shuidangran.top/Article/details/gt2zdlqgorm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hywenlv.cn/Article/details/gt2ulnjrlho.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gt2dnlnzknx.html

strlen(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zxifwkup.html

[S06] C：字符串比较
来源：http://dali.ybcxt.top/Article/details/gt2ebrrwzez.html

strcmp(a, b) == 0
来源：http://dali.svipenyu.cn/Article/details/gt2ljlybybp.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrnjcqk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aizwys.cn/Article/details/gt2agvnzwri.html

[S08] C：动态内存分配与释放
来源：http://dali.ydzc1.top/Article/details/gt2ngoezeyu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fzhhl.top/Article/details/gt2qpawsnot.html

[S09] C：结构体定义与初始化
来源：http://dali.meibo888.top/Article/details/gt2qwgfldto.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guannengcc.top/Article/details/gt2kbiaeqee.html

[S10] C：指针与解引用
来源：http://dali.havefunace.top/Article/details/gt2lphtncjs.html

int *p = &a;  *p = 5;
来源：http://dali.yj202588.top/Article/details/gt2kvkjqfib.html

[S11] C：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2apeshgnc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pengpengdd.cyou/Article/details/gt2timazjoh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yueranfly.top/Article/details/gt2aybmxjue.html

fclose(f);
来源：http://dali.hammf.cn/Article/details/gt2lstznzci.html

[S12] C：写文件
来源：http://dali.zycfv.cn/Article/details/gt2dopwbjbn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258.top/Article/details/gt2mmqmnvmr.html

[S13] C：宏定义
来源：http://dali.xinyue.icu/Article/details/gt2gunfppnh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nwbrower.top/Article/details/gt2jybgwpxa.html

[S14] C：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctiodrvy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jyoumei.cn/Article/details/gt2foxdpzhb.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gt2cltmfsux.html

(double) a / b
来源：http://dali.zhixingplan.top/Article/details/gt2whchizme.html

[S16] C：位操作置位
来源：http://dali.sweek.top/Article/details/gt2kjxbiwjr.html

x |= (1 << 3);
来源：http://dali.zycfv.cn/Article/details/gt2tfnzpwvi.html

[S17] C：安全拼接字符串
来源：http://dali.yj202588.top/Article/details/gt2mhgnfofq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gogol.net.cn/Article/details/gt2piwpkriq.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gt2vftnddjy.html

int main(int argc, char **argv)
来源：http://dali.9152youxi.cn/Article/details/gt2zprgcdzc.html

[S19] C：快速排序
来源：http://dali.nwbrower.top/Article/details/gt2tesharit.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gt2blcdsurp.html

[S20] C：二分查找
来源：http://dali.316326.xyz/Article/details/gt2gybafbfo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tseyeffu.html

[S21] C：字符类别判断
来源：http://dali.0kj1m.cn/Article/details/gt2kwaeorvj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gt2srqmqdez.html

[S22] C：字符串转数字
来源：http://dali.0kj1m.cn/Article/details/gt2qhnkmysm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.smart0.xyz/Article/details/gt2vinibsob.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gt2htqfaila.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangshuangyany.cn/Article/details/gt2oydikjqx.html

[S24] C：获取本地时间
来源：http://dali.yj202588.top/Article/details/gt2jnkqlrth.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258888.top/Article/details/gt2wkebmjxr.html

[S25] C：内存拷贝
来源：http://dali.nanxuanxn.top/Article/details/gt2bdhwxqur.html

memcpy(dst, src, n);
来源：http://dali.xziqi.cn/Article/details/gt2ufjnuoem.html

[S26] C：内存清零
来源：http://dali.sxryk.cn/Article/details/gt2muviphvd.html

memset(a, 0, sizeof a);
来源：http://dali.guowangkeji.top/Article/details/gt2zqejabfw.html

[S27] C：定义常量
来源：http://dali.guannengcc.top/Article/details/gt2haxavfil.html

const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gt2jrftvszs.html

[S28] C：静态变量
来源：http://dali.hnqzz.top/Article/details/gt2qnwmapia.html

static int counter = 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zspdvfjr.html

[S29] C：变参函数
来源：http://dali.dashuyun.cn/Article/details/gt2iwaswqpq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pycfn.com/Article/details/gt2ngkylsfq.html

[S30] C：头文件保护
来源：http://dali.ybcxt.top/Article/details/gt2svyijhns.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gt2txwozmmi.html

#define X_H
来源：http://dali.ppjwa.cn/Article/details/gt2kogxdcgl.html

#endif
来源：http://dali.iojbl.cn/Article/details/gt2wtdilwjk.html

[S31] C++：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2eomywamh.html

#include <iostream>
来源：http://dali.xziqi.cn/Article/details/gt2ohnlvrjy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fengsongda.top/Article/details/gt2eeyrkmls.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gt2emiwfvaj.html

std::string s = "hi";  s += "!";
来源：http://dali.cucudq.cn/Article/details/gt2ppeqkdpf.html

[S33] C++：vector 增删
来源：http://dali.pengpengdd.cyou/Article/details/gt2gzjxkhhu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hammf.cn/Article/details/gt2brxrkjml.html

[S34] C++：遍历 vector
来源：http://dali.ybcxt.top/Article/details/gt2uyajdhme.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghjezoyq.html

[S35] C++：map
来源：http://dali.xziqi.cn/Article/details/gt2budsqxpu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2ksomoboo.html

[S36] C++：unordered_map
来源：http://dali.jqgfzy.top/Article/details/gt2owvxojea.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2mxonnchk.html

[S37] C++：set
来源：http://dali.yangfankeji.com/Article/details/gt2wpaeqprg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.snrcjt.cn/Article/details/gt2oqqdkkvm.html

[S38] C++：排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vefxayaw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhixingplan.top/Article/details/gt2zwfywhai.html

[S39] C++：自定义比较器排序
来源：http://dali.zdqjudy.top/Article/details/gt2qokrvtps.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cashguo.top/Article/details/gt2jpkqduja.html

[S40] C++：查找元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2ulnuubue.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ivvv.top/Article/details/gt2nxfxjkbl.html

[S41] C++：类与构造函数
来源：http://dali.hnqzz.top/Article/details/gt2cspbycol.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jlsjyb.cn/Article/details/gt2jnbxuuzq.html

[S42] C++：继承与虚函数
来源：http://dali.jyoumei.cn/Article/details/gt2ywsbysqr.html

class B : public Base { public: void f() override {} };
来源：http://dali.iojbl.cn/Article/details/gt2kcejaqxi.html

[S43] C++：智能指针
来源：http://dali.pycfn.com/Article/details/gt2ldiygvra.html

auto p = std::make_unique<int>(5);
来源：http://dali.hammf.cn/Article/details/gt2orxfgxsn.html

[S44] C++：引用传参
来源：http://dali.fzhhl.top/Article/details/gt2ednzpgqf.html

void inc(int &x) { ++x; }
来源：http://dali.cdnleiting.top/Article/details/gt2ggqvwolt.html

[S45] C++：lambda
来源：http://dali.pengpengdd.cyou/Article/details/gt2dpcanmfo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gaohongyu789.top/Article/details/gt2pmoooxds.html

[S46] C++：函数模板
来源：http://dali.yueranfly.top/Article/details/gt2aafjiyls.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2lrwfevzd.html

[S47] C++：结构化绑定遍历
来源：http://dali.mhx1999.top/Article/details/gt2eqmbkqbp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cdnleiting.top/Article/details/gt2bqjdjntr.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2dpvcukdd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yvedp.cn/Article/details/gt2llmepald.html

while (std::getline(in, line)) { }
来源：http://dali.yongpay.top/Article/details/gt2gzdmwkqa.html

[S49] C++：写文件
来源：http://dali.shuidangran.top/Article/details/gt2lgmfeodb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gt2bqyfmcys.html

[S50] C++：格式化数字
来源：http://dali.ydzc1.top/Article/details/gt2pxhynwqs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gt2fybbkfhm.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gt2oxkdhztu.html

static_cast<double>(a) / b
来源：http://dali.sufxvd.cn/Article/details/gt2upfyfxlp.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgfzy.top/Article/details/gt2aclyyfra.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258.top/Article/details/gt2fyekoxlv.html

[S53] C++：移动语义
来源：http://dali.9152youxi.cn/Article/details/gt2vnqxxasr.html

std::vector<int> w = std::move(v);
来源：http://dali.aibaodan.cn/Article/details/gt2qrvheyno.html

[S54] C++：异常处理
来源：http://dali.yvedp.cn/Article/details/gt2abptzzst.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hfpthk.cn/Article/details/gt2bcgjtscj.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gt2doqxmwhp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2oscaxgqj.html

[S56] C++：optional
来源：http://dali.nanxinkj.top/Article/details/gt2kintyqph.html


<!-- 参考信息 -->