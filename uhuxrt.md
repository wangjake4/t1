代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nwbrower.top/Article/details/gt2xbyxzjgw.html

[Q90] 生成序号列
来源：http://dali.iojbl.cn/Article/details/gt2clcsdrzw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2coyerzrh.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2wpomsgip.html

R. Bash 专题
来源：http://dali.yuanzhike.top/Article/details/gt2mkzkwybw.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2tupiebbh.html

[R01] shebang 与严格模式
来源：http://dali.sufxvd.cn/Article/details/gt2togvslyn.html

#!/usr/bin/env bash
来源：http://dali.zhoulong.xyz/Article/details/gt2rofzqrac.html

set -euo pipefail
来源：http://dali.zhengqikj.top/Article/details/gt2wmjvnmdu.html

[R02] 变量赋值与使用
来源：http://dali.yj202588.top/Article/details/gt2ialmduvq.html

name="Tom"; echo "$name"
来源：http://dali.xinyue.icu/Article/details/gt2dijtayjj.html

[R03] 只读变量
来源：http://dali.iojbl.cn/Article/details/gt2smaqwttr.html

readonly PI=3.14
来源：http://dali.sxryk.cn/Article/details/gt2kwgowpys.html

[R04] 位置参数
来源：http://dali.jianghu66.top/Article/details/gt2vuaqazqp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ppjwa.cn/Article/details/gt2scxhqqfw.html

[R05] 参数默认值
来源：http://dali.jqgfzy.top/Article/details/gt2sqdzbapq.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gt2hropypvn.html

[R06] 判断命令是否存在
来源：http://dali.dashuyun.cn/Article/details/gt2pruawlcv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2cnntrfkg.html

[R07] if 判断文件
来源：http://dali.yueranfly.top/Article/details/gt2ohavicic.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2uebqnfwl.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gt2rekhxcvt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxinkj.top/Article/details/gt2ukuqqljq.html

[R09] 字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ijqbrihe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenlongwang.top/Article/details/gt2mvykhglc.html

[R10] 正则匹配
来源：http://dali.cheryme.top/Article/details/gt2wlppdvdj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aibaodan.cn/Article/details/gt2ijzyiorq.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gt2ibjsqnkj.html

case "$1" in
来源：http://dali.birdmap.top/Article/details/gt2pljfbohy.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gt2hzgsrlnl.html

stop)  echo "停止" ;;
来源：http://dali.yueranfly.top/Article/details/gt2lsxedgmg.html

*)     echo "未知命令" ;;
来源：http://dali.andypj.xyz/Article/details/gt2cdusgzov.html

esac
来源：http://dali.jqgufenzy.top/Article/details/gt2rnjieoui.html

[R12] for 遍历文件
来源：http://dali.0kj1m.cn/Article/details/gt2llduoyuo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yueranfly.top/Article/details/gt2zbzonwfo.html

[R13] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gt2pikbcwhr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gt2epaykemg.html

[R14] C 风格 for
来源：http://dali.meibo888.top/Article/details/gt2istlhzmb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gt2ymjekkfk.html

[R15] while 逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gt2onfvkkvl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhixingplan.top/Article/details/gt2fxttwgmh.html

[R16] until 等待条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2opjmqkre.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gt2fuapglgg.html

[R17] 数组定义与取值
来源：http://dali.hongshengwenyu.top/Article/details/gt2dhepfztq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gt2voghlamr.html

[R18] 遍历数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2bkfoadrd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2jhknlmqv.html

[R19] 数组长度
来源：http://dali.ybcxt.top/Article/details/gt2jjkqtizb.html

echo "${#arr[@]}"
来源：http://dali.daxiang520.top/Article/details/gt2xfyaxcht.html

[R20] 关联数组（字典）
来源：http://dali.yvedp.cn/Article/details/gt2kzhimqeq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2chuvpabl.html

[R21] 字符串长度
来源：http://dali.pycfn.com/Article/details/gt2btioxmhd.html

echo "${#s}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2jwbbnvfh.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gt2ozqwvjod.html

echo "${s:0:5}"
来源：http://dali.yj20258888.top/Article/details/gt2mnywyzip.html

[R23] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gt2rhygckvm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2wrnevjxw.html

[R24] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gt2nfnkjkyc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ehwqpu.com/Article/details/gt2rydwskkt.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangdashe.top/Article/details/gt2klhfhnnj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ivvv.top/Article/details/gt2jpmrcese.html

[R26] 命令替换
来源：http://dali.dianchejie.cn/Article/details/gt2yipceipx.html

now=$(date +%F); echo "$now"
来源：http://dali.dianchejie.cn/Article/details/gt2iqurcjiq.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gt2shyjrmkz.html

echo $((1 + 2 * 3))
来源：http://dali.dashuyun.cn/Article/details/gt2hbcwnafv.html

[R28] 浮点运算
来源：http://dali.chenzaomai.com/Article/details/gt2qvgwwstd.html

echo "scale=2; 10/3" | bc
来源：http://dali.fengsongda.top/Article/details/gt2bxwviswm.html

[R29] 定义函数
来源：http://dali.yvedp.cn/Article/details/gt2daozucrn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gt2ytvsbxwd.html

[R30] 函数返回状态码
来源：http://dali.316326.xyz/Article/details/gt2iuhebffg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cqqwz.cn/Article/details/gt2ukantuqv.html

[R31] 局部变量
来源：http://dali.jlsjyb.cn/Article/details/gt2pmbkbxat.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2xkjwiyqa.html

[R32] 参数个数校验
来源：http://dali.chenzaomai.com/Article/details/gt2owlblxfi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gt2iicepndk.html

[R33] 捕获错误并提示行号
来源：http://dali.hfpthk.cn/Article/details/gt2buoxnriz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.haohaochexian.top/Article/details/gt2pixfzoes.html

[R34] 退出时清理
来源：http://dali.gotoacloud.top/Article/details/gt2rvsyjyvt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gt2whtcpmdz.html

[R35] 后台执行并等待
来源：http://dali.iojbl.cn/Article/details/gt2wooeyuho.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ehwqpu.com/Article/details/gt2ymozzsgk.html

[R36] 并发执行多个任务
来源：http://dali.jianghu66.top/Article/details/gt2eppumtmx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.redwolf501.top/Article/details/gt2jyyloawl.html

[R37] 把输出赋给变量
来源：http://dali.zhoulong.xyz/Article/details/gt2xfeftkan.html

files=$(ls -1)
来源：http://dali.sweek.top/Article/details/gt2kvmxwzuw.html

[R38] 管道串联
来源：http://dali.yj202588.top/Article/details/gt2esgddsnq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258888.top/Article/details/gt2xoumekvn.html

[R39] 重定向标准输出与错误
来源：http://dali.cheryme.top/Article/details/gt2gfpwnahn.html

cmd > out.log 2>&1
来源：http://dali.jyoumei.cn/Article/details/gt2badqlfus.html

[R40] 追加写日志
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvkvcouh.html

echo "log" >> out.log
来源：http://dali.shuidangran.top/Article/details/gt2oegwkjdr.html

[R41] 丢弃输出
来源：http://dali.xylfe.cn/Article/details/gt2bmtkhqiy.html

cmd >/dev/null 2>&1
来源：http://dali.dianchejie.cn/Article/details/gt2kljxjlyz.html

[R42] 输入重定向
来源：http://dali.hnqzz.top/Article/details/gt2zgccxdya.html

wc -l < a.txt
来源：http://dali.hammf.cn/Article/details/gt2fhrilxnt.html

[R43] 按名字查找文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kekdlwsn.html

find . -name "*.log" -type f
来源：http://dali.cqqwz.cn/Article/details/gt2axjmzfnr.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gt2mszeidnx.html

find . -mtime -7 -type f
来源：http://dali.c1oappe.top/Article/details/gt2daxiapbw.html

[R45] 批量删除
来源：http://dali.zhoulong.xyz/Article/details/gt2pkkjcxar.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gt2gierirux.html

[R46] 递归替换文件内容
来源：http://dali.redwolf501.top/Article/details/gt2myevlgfv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gt2pdremdvv.html

[R47] sed 单行替换
来源：http://dali.dashuyun.cn/Article/details/gt2jmjgfoah.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2namcpwpz.html

[R48] awk 取指定列
来源：http://dali.bjfxy.top/Article/details/gt2bwyaynvm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gt2dnevfpdd.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gt2qgalkaed.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzicrhui.html

[R50] awk 求和
来源：http://dali.fzhhl.top/Article/details/gt2gwucncbu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tian-w.cn/Article/details/gt2agoexgwo.html

[R51] 排序去重取前几
来源：http://dali.zycfv.cn/Article/details/gt2cofqamme.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yonumen.top/Article/details/gt2uacnjabt.html

[R52] 统计行数
来源：http://dali.yonumen.top/Article/details/gt2gcoocbwb.html

wc -l a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2qpjyfdsw.html

[R53] 查看文件头与实时尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ffabktbz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shangyingyoupin.top/Article/details/gt2rkcqbvov.html

[R54] 比较两个文件
来源：http://dali.ivvv.top/Article/details/gt2gtbewnlh.html

diff a.txt b.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2txhksadh.html

[R55] 压缩与解压
来源：http://dali.shuidangran.top/Article/details/gt2cevihecp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuanzx.com/Article/details/gt2zjfneudr.html

[R56] 远程拷贝
来源：http://dali.xziqi.cn/Article/details/gt2djlxxovq.html

scp file user@host:/path/
来源：http://dali.xuanzx.com/Article/details/gt2ycrjlwej.html

[R57] 远程执行命令
来源：http://dali.shzxlz.cn/Article/details/gt2ehrcticm.html

ssh user@host 'uptime'
来源：http://dali.mhx1999.top/Article/details/gt2bkkbaqzu.html

[R58] 下载文件
来源：http://dali.shuidangran.top/Article/details/gt2lqxsazrr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258.top/Article/details/gt2yowbrqpt.html

[R59] 发 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gt2rrwennud.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.feifeiyinyue.top/Article/details/gt2mkfrlwcl.html

[R60] 只看 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gt2mjuiumuu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zipcdzsn.html

[R61] 磁盘占用
来源：http://dali.kuanghao11.cn/Article/details/gt2qfmreqpk.html

df -h;  du -sh *
来源：http://dali.jiagoushi.top/Article/details/gt2pijwxtxx.html

[R62] 找最占空间的文件
来源：http://dali.sysykeji.top/Article/details/gt2ioaanqge.html

du -ah . | sort -rh | head -10
来源：http://dali.jyoumei.cn/Article/details/gt2emkjtigm.html

[R63] 内存与进程
来源：http://dali.shangyingyoupin.top/Article/details/gt2iesjrjjv.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gt2jjerdval.html

[R64] 结束进程
来源：http://dali.daria6918.cn/Article/details/gt2wadipzqx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ekemjpto.html

[R65] 查看端口占用
来源：http://dali.daria6918.cn/Article/details/gt2bynvbkdk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gt2xvtrmqaj.html

[R66] 定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbsmcsoi.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gt2rlptpvhm.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqjxfvot.html

openssl rand -hex 16
来源：http://dali.yj202588.top/Article/details/gt2weptqoyz.html

[R68] 计算文件校验值
来源：http://dali.yvedp.cn/Article/details/gt2fwjueprd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aizwys.cn/Article/details/gt2eqwagrgh.html

[R69] 生成随机密码
来源：http://dali.vqdsnc.cn/Article/details/gt2azehauwg.html

head -c 16 /dev/urandom | base64
来源：http://dali.ydzc1.top/Article/details/gt2ujvpapdo.html

[R70] 时间戳与互转
来源：http://dali.hysaishi.cn/Article/details/gt2arqvcoss.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gt2aaaivjwi.html

[R71] 日期格式化
来源：http://dali.yj20258.top/Article/details/gt2qhcxhwjr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.c1oappe.top/Article/details/gt2lrhpfgvi.html

[R72] 等待端口就绪
来源：http://dali.aibaodan.cn/Article/details/gt2livzjexl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gt2cklcntja.html

[R73] 分割大日志
来源：http://dali.birdmap.top/Article/details/gt2wjpnrtsb.html

split -l 1000 big.log part_
来源：http://dali.shzxlz.cn/Article/details/gt2gtoduond.html

[R74] 批量重命名
来源：http://dali.daria6918.cn/Article/details/gt2bbqkonls.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daxiang520.top/Article/details/gt2qxboajzq.html

[R75] 导出环境变量
来源：http://dali.hammf.cn/Article/details/gt2mnuugedu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gt2vdvhodex.html

[R76] 使用临时文件
来源：http://dali.bjfxy.top/Article/details/gt2hjfdlttc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gt2wkdwrgnu.html

[R77] 读取用户输入
来源：http://dali.gogol.net.cn/Article/details/gt2vuiiflca.html

read -rp "请输入: " ans
来源：http://dali.sweek.top/Article/details/gt2utpciybo.html

[R78] 交互式菜单
来源：http://dali.cheryme.top/Article/details/gt2uscrsuan.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnqzz.top/Article/details/gt2uirtgjii.html

[R79] 解析命令行选项
来源：http://dali.havefunace.top/Article/details/gt2hsxocfbw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sweek.top/Article/details/gt2yjvjwmqy.html

[R80] 查看脚本执行耗时
来源：http://dali.ehwqpu.com/Article/details/gt2hcxydmrk.html

time ./run.sh
来源：http://dali.hnqzz.top/Article/details/gt2rjhqgwgz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2jffxdibm.html

S. C / C++ 专题
来源：http://dali.haohaochexian.top/Article/details/gt2kvzupujg.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2qjnwyrup.html

[S01] C：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2kytrcixv.html

#include <stdio.h>
来源：http://dali.redwolf501.top/Article/details/gt2zwskiihb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yvedp.cn/Article/details/gt2bawekvaw.html

[S02] C：变量与格式化输出
来源：http://dali.sweek.top/Article/details/gt2qjldlxlj.html

int a = 10; printf("%d\n", a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qpmidhss.html

[S03] C：读入整数
来源：http://dali.xylfe.cn/Article/details/gt2bsmkdjrx.html

int x; scanf("%d", &x);
来源：http://dali.316326.xyz/Article/details/gt2ocztmnto.html

[S04] C：字符串复制
来源：http://dali.zhoulong.xyz/Article/details/gt2rgruuoxw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.quarkkingdee.top/Article/details/gt2qphlpjxx.html

[S05] C：字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2nfjfmdgk.html

strlen(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2abjumhrd.html

[S06] C：字符串比较
来源：http://dali.pycfn.com/Article/details/gt2hsghkhhj.html

strcmp(a, b) == 0
来源：http://dali.jqgfzy.top/Article/details/gt2dqkdjfkl.html

[S07] C：数组遍历求和
来源：http://dali.guowangkeji.top/Article/details/gt2edvjdoaa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sweek.top/Article/details/gt2fzaufuio.html

[S08] C：动态内存分配与释放
来源：http://dali.aibaodan.cn/Article/details/gt2sbmnimkx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cashguo.top/Article/details/gt2jbftatns.html

[S09] C：结构体定义与初始化
来源：http://dali.cucudq.cn/Article/details/gt2ztprihmr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xziqi.cn/Article/details/gt2oyftzviz.html

[S10] C：指针与解引用
来源：http://dali.hywenlv.cn/Article/details/gt2wnhczoyv.html

int *p = &a;  *p = 5;
来源：http://dali.jlsjyb.cn/Article/details/gt2wmfonnbs.html

[S11] C：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gt2bvaqxcgd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.iojbl.cn/Article/details/gt2zzyrzope.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yhgzukfv.html

fclose(f);
来源：http://dali.xuanzx.com/Article/details/gt2jvbmfpoc.html

[S12] C：写文件
来源：http://dali.zhixingplan.top/Article/details/gt2fhjbowqz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zycfv.cn/Article/details/gt2lotmujks.html

[S13] C：宏定义
来源：http://dali.aizwys.cn/Article/details/gt2ejuxczfk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xziqi.cn/Article/details/gt2vvzryzvr.html

[S14] C：枚举
来源：http://dali.aibaodan.cn/Article/details/gt2wmlwyngd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rqusvyxi.html

[S15] C：类型转换
来源：http://dali.snrcjt.cn/Article/details/gt2upuourdx.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gt2wnznapoo.html

[S16] C：位操作置位
来源：http://dali.bjfxy.top/Article/details/gt2bqwjemii.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bypekxld.html

[S17] C：安全拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gt2szipgdrd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnxiangtu.top/Article/details/gt2hgcemwow.html

[S18] C：命令行参数
来源：http://dali.sxryk.cn/Article/details/gt2hmswmjta.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xsmbwpup.html

[S19] C：快速排序
来源：http://dali.cqqwz.cn/Article/details/gt2cbtnnffr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fbwzppzy.html

[S20] C：二分查找
来源：http://dali.yj20258.top/Article/details/gt2qiulzmta.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gt2yeblcefx.html

[S21] C：字符类别判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2stvgkkvy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ydzc1.top/Article/details/gt2aoffybkg.html

[S22] C：字符串转数字
来源：http://dali.guowangkeji.top/Article/details/gt2sdjgfpmv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj202588.top/Article/details/gt2apxppofn.html

[S23] C：随机数
来源：http://dali.ybcxt.top/Article/details/gt2ilntgcni.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cashguo.top/Article/details/gt2zghrlops.html

[S24] C：获取本地时间
来源：http://dali.ehwqpu.com/Article/details/gt2ulrcmzsl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenzaomai.com/Article/details/gt2rgbcprwt.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lohidpyo.html

memcpy(dst, src, n);
来源：http://dali.ivvv.top/Article/details/gt2njkoxkgb.html

[S26] C：内存清零
来源：http://dali.yanxiufei.cn/Article/details/gt2vzajlulu.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gt2rtlxrrau.html

[S27] C：定义常量
来源：http://dali.yanxiufei.cn/Article/details/gt2vzadtbru.html

const double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2xzrfgdfc.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gt2jehyvkgh.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gt2mjlbzrvn.html

[S29] C：变参函数
来源：http://dali.sysykeji.top/Article/details/gt2vjscfdyl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gt2esqvodly.html

[S30] C：头文件保护
来源：http://dali.hnqzz.top/Article/details/gt2bxdsuakm.html

#ifndef X_H
来源：http://dali.sweek.top/Article/details/gt2ufjiyyuc.html

#define X_H
来源：http://dali.havefunace.top/Article/details/gt2wgqtpwpr.html

#endif
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hrxyqdaq.html

[S31] C++：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2veimadri.html

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2scmedofy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuanzhike.top/Article/details/gt2hidhmssx.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ccdkvftd.html

std::string s = "hi";  s += "!";
来源：http://dali.yj202588.top/Article/details/gt2kfloqqzp.html

[S33] C++：vector 增删
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rkhjlgem.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shzxlz.cn/Article/details/gt2hjmsvpak.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bctkwatn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sysykeji.top/Article/details/gt2jtsvzqds.html

[S35] C++：map
来源：http://dali.hywenlv.cn/Article/details/gt2kongmbes.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2taywipil.html

[S36] C++：unordered_map
来源：http://dali.ivvv.top/Article/details/gt2tvloitxa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2jfggudil.html

[S37] C++：set
来源：http://dali.dianchejie.cn/Article/details/gt2ianezdut.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gt2gutwlqdn.html

[S38] C++：排序
来源：http://dali.cashguo.top/Article/details/gt2sxhchwkw.html

std::sort(v.begin(), v.end());
来源：http://dali.sweek.top/Article/details/gt2lmirpyye.html

[S39] C++：自定义比较器排序
来源：http://dali.yonumen.top/Article/details/gt2ghyxxwlb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigfzy.top/Article/details/gt2qqkdxykb.html

[S40] C++：查找元素
来源：http://dali.ehwqpu.com/Article/details/gt2nfejhnfv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cashguo.top/Article/details/gt2tagmdakk.html

[S41] C++：类与构造函数
来源：http://dali.tanke756.top/Article/details/gt2ykjmogns.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shuidangran.top/Article/details/gt2wqwpiykf.html

[S42] C++：继承与虚函数
来源：http://dali.zhixingplan.top/Article/details/gt2gjattwyj.html

class B : public Base { public: void f() override {} };
来源：http://dali.gotoacloud.top/Article/details/gt2hzrfrcui.html

[S43] C++：智能指针
来源：http://dali.gotoacloud.top/Article/details/gt2ubzxqsui.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangdashe.top/Article/details/gt2gnlheutl.html

[S44] C++：引用传参
来源：http://dali.zhoulong.xyz/Article/details/gt2hwkebmbt.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gt2yjygbfcz.html

[S45] C++：lambda
来源：http://dali.yj20258888.top/Article/details/gt2evuxylmk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.kuanghao11.cn/Article/details/gt2cycxmxwf.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gt2ukbimqps.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gt2abuvyzdi.html

[S47] C++：结构化绑定遍历
来源：http://dali.shuidangran.top/Article/details/gt2dszzdjjp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gqvrtcur.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2mfjkywyd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dashuyun.cn/Article/details/gt2cefzxaaa.html

while (std::getline(in, line)) { }
来源：http://dali.xinyue.icu/Article/details/gt2gxjmmfqb.html

[S49] C++：写文件
来源：http://dali.ehwqpu.com/Article/details/gt2hpcxlnxw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aibaodan.cn/Article/details/gt2sisjrfth.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gt2jlwspgle.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2tnrlbkfl.html

[S51] C++：显式类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xarbbzew.html

static_cast<double>(a) / b
来源：http://dali.xuetiantiany.cn/Article/details/gt2jfwmxzxh.html

[S52] C++：const 与 noexcept
来源：http://dali.gogol.net.cn/Article/details/gt2jzuqxopp.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gt2oxtwotug.html

[S53] C++：移动语义
来源：http://dali.zhixingplan.top/Article/details/gt2pyfuntvm.html

std::vector<int> w = std::move(v);
来源：http://dali.vqdsnc.cn/Article/details/gt2mujjbwpy.html

[S54] C++：异常处理
来源：http://dali.9152youxi.cn/Article/details/gt2gzruhweq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2szxkfdjk.html

[S55] C++：结构化绑定
来源：http://dali.yj202588.top/Article/details/gt2pkadtujs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.c1oappe.top/Article/details/gt2lasenydx.html

[S56] C++：optional
来源：http://dali.vqdsnc.cn/Article/details/gt2lafydkoo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nwbrower.top/Article/details/gt2ugzdivwb.html

[S57] C++：编译期常量
来源：http://dali.snrcjt.cn/Article/details/gt2zofyckry.html

constexpr int N = 10;
来源：http://dali.tian-w.cn/Article/details/gt2ivgwnjvp.html

[S58] C++：命名空间
来源：http://dali.chenzaomai.com/Article/details/gt2srozhfxd.html

namespace ns { int f() { return 1; } }
来源：http://dali.smart0.xyz/Article/details/gt2qxdqjmcm.html

[S59] C++：静态断言
来源：http://dali.sxryk.cn/Article/details/gt2njzzbslx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gotoacloud.top/Article/details/gt2kurczmyr.html

[S60] C++：遍历并删除元素
来源：http://dali.tian-w.cn/Article/details/gt2sbfmemvi.html


<!-- 参考信息 -->