代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.yuanzhike.top/Article/details/gt2iurasifp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.0kj1m.cn/Article/details/gt2yxajudzb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2mfabxutw.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tbtbwhxr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yueranfly.top/Article/details/gt2kgyuveqq.html

[Q90] 生成序号列
来源：http://dali.zhixingplan.top/Article/details/gt2cltjdvgj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigfzy.top/Article/details/gt2ylwwnkjr.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2pfkpvxyx.html

R. Bash 专题
来源：http://dali.yuanzhike.top/Article/details/gt2mahhrcwv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2rovyhfgn.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ofyyqmsp.html

#!/usr/bin/env bash
来源：http://dali.gzhubu.top/Article/details/gt2lbyjhxgg.html

set -euo pipefail
来源：http://dali.tanke756.top/Article/details/gt2diagqgzv.html

[R02] 变量赋值与使用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2idkkisvz.html

name="Tom"; echo "$name"
来源：http://dali.yj20258888.top/Article/details/gt2xliwbehm.html

[R03] 只读变量
来源：http://dali.havefunace.top/Article/details/gt2qqtgmcco.html

readonly PI=3.14
来源：http://dali.ehwqpu.com/Article/details/gt2efkuptjw.html

[R04] 位置参数
来源：http://dali.sufxvd.cn/Article/details/gt2wgqfjmax.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tian-w.cn/Article/details/gt2gbgergfw.html

[R05] 参数默认值
来源：http://dali.jlsjyb.cn/Article/details/gt2tvtezecf.html

name="${1:-default}"
来源：http://dali.kuanghao11.cn/Article/details/gt2ggqugbnt.html

[R06] 判断命令是否存在
来源：http://dali.yj20258.top/Article/details/gt2ctjtqqlm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gt2vajjvrrz.html

[R07] if 判断文件
来源：http://dali.shuidangran.top/Article/details/gt2dyoayunb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2cbgtskfo.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gt2adnlbpdy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yueranfly.top/Article/details/gt2rfxfpztu.html

[R09] 字符串比较
来源：http://dali.dashuyun.cn/Article/details/gt2ekibunvv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.c1oappe.top/Article/details/gt2mogbhphm.html

[R10] 正则匹配
来源：http://dali.zdqjudy.top/Article/details/gt2kfwtomue.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgufenzy.top/Article/details/gt2amcwqdox.html

[R11] case 多分支
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhhyrazx.html

case "$1" in
来源：http://dali.iojbl.cn/Article/details/gt2zdrfrtxu.html

start) echo "启动" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eejqiqby.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vxohntez.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gt2vfawhtmw.html

esac
来源：http://dali.quarkkingdee.top/Article/details/gt2xjzmtgvs.html

[R12] for 遍历文件
来源：http://dali.yueranfly.top/Article/details/gt2lmpelsvn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xinyue.icu/Article/details/gt2oyzhpgsz.html

[R13] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gt2asiossqw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gt2hnyvooeo.html

[R14] C 风格 for
来源：http://dali.yangfankeji.com/Article/details/gt2zcrwtkmx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gt2hmzwpobu.html

[R15] while 逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lrpekedw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aibaodan.cn/Article/details/gt2xnxvfalj.html

[R16] until 等待条件
来源：http://dali.yangfankeji.com/Article/details/gt2kzongyje.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gt2zifxeuta.html

[R17] 数组定义与取值
来源：http://dali.fengsongda.top/Article/details/gt2ihqgpbkf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.andypj.xyz/Article/details/gt2kcorzyqq.html

[R18] 遍历数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2muayghgl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yvedp.cn/Article/details/gt2ervstbrd.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gt2hxcvjomy.html

echo "${#arr[@]}"
来源：http://dali.xziqi.cn/Article/details/gt2oufynvpi.html

[R20] 关联数组（字典）
来源：http://dali.guannengcc.top/Article/details/gt2jgqgxuno.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gt2yghysopy.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gt2pthbespy.html

echo "${#s}"
来源：http://dali.nwbrower.top/Article/details/gt2clbqfjft.html

[R22] 截取子串
来源：http://dali.fengsongda.top/Article/details/gt2tutkhxnj.html

echo "${s:0:5}"
来源：http://dali.yongpay.top/Article/details/gt2hvrhbojf.html

[R23] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gt2nioglain.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.bjfxy.top/Article/details/gt2crqyebea.html

[R24] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gt2yhynrozs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jiagoushi.top/Article/details/gt2yjzvdrpb.html

[R25] 去后缀 / 去前缀
来源：http://dali.aizwys.cn/Article/details/gt2vgkolmwi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gt2wesvfzau.html

[R26] 命令替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bahcjorn.html

now=$(date +%F); echo "$now"
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhoayovk.html

[R27] 算术展开
来源：http://dali.jiagoushi.top/Article/details/gt2qsqkuwar.html

echo $((1 + 2 * 3))
来源：http://dali.aizwys.cn/Article/details/gt2ptsgmgxy.html

[R28] 浮点运算
来源：http://dali.andypj.xyz/Article/details/gt2xwoxgfbp.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bmwubops.html

[R29] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gt2raqwsapv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zdqjudy.top/Article/details/gt2vrodokcx.html

[R30] 函数返回状态码
来源：http://dali.xziqi.cn/Article/details/gt2fkvrlwri.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhongyouzk.top/Article/details/gt2rdgvlzqn.html

[R31] 局部变量
来源：http://dali.tian-w.cn/Article/details/gt2wycxxfxu.html

f() { local x=1; echo "$x"; }
来源：http://dali.pycfn.com/Article/details/gt2alavztpp.html

[R32] 参数个数校验
来源：http://dali.ehwqpu.com/Article/details/gt2axtaecba.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gt2tueaczxp.html

[R33] 捕获错误并提示行号
来源：http://dali.ydzc1.top/Article/details/gt2goupbuhj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cdnleiting.top/Article/details/gt2htshlsod.html

[R34] 退出时清理
来源：http://dali.nanxuanxn.top/Article/details/gt2zzxwafpm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gt2advkyrjw.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gt2tuuqvyad.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shangyingyoupin.top/Article/details/gt2fpjobpgq.html

[R36] 并发执行多个任务
来源：http://dali.havefunace.top/Article/details/gt2wzhmgrib.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gt2isdizvwy.html

[R37] 把输出赋给变量
来源：http://dali.jqgfzy.top/Article/details/gt2zatlbwqj.html

files=$(ls -1)
来源：http://dali.yongpay.top/Article/details/gt2vfstocht.html

[R38] 管道串联
来源：http://dali.0kj1m.cn/Article/details/gt2fhdsqdox.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hysaishi.cn/Article/details/gt2bruhvjfh.html

[R39] 重定向标准输出与错误
来源：http://dali.feifeiyinyue.top/Article/details/gt2hxemsnlu.html

cmd > out.log 2>&1
来源：http://dali.zycfv.cn/Article/details/gt2pwmvindp.html

[R40] 追加写日志
来源：http://dali.hongshengwenyu.top/Article/details/gt2lkxuvjeg.html

echo "log" >> out.log
来源：http://dali.chenzaomai.com/Article/details/gt2yxgrlmaf.html

[R41] 丢弃输出
来源：http://dali.hfpthk.cn/Article/details/gt2gywznyvj.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tfkjqeft.html

[R42] 输入重定向
来源：http://dali.svipenyu.cn/Article/details/gt2qvxqlwpw.html

wc -l < a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2kaubqrxn.html

[R43] 按名字查找文件
来源：http://dali.dianchejie.cn/Article/details/gt2ewlpkdos.html

find . -name "*.log" -type f
来源：http://dali.kuanghao11.cn/Article/details/gt2wimrgwwg.html

[R44] 按修改时间查找
来源：http://dali.0kj1m.cn/Article/details/gt2wgwmzxcz.html

find . -mtime -7 -type f
来源：http://dali.guannengcc.top/Article/details/gt2utydlhxc.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gt2xlhhmwsm.html

find . -name "*.tmp" -delete
来源：http://dali.hnxiangtu.top/Article/details/gt2ptzutlgq.html

[R46] 递归替换文件内容
来源：http://dali.gogol.net.cn/Article/details/gt2nbifbybd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daxiang520.top/Article/details/gt2xvfxpqcm.html

[R47] sed 单行替换
来源：http://dali.shzxlz.cn/Article/details/gt2plkiofxt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuanzx.com/Article/details/gt2oxgwarjk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpugvcp.html

awk '{print $1, $3}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fheichof.html

[R49] awk 带条件
来源：http://dali.gaohongyu789.top/Article/details/gt2ljorzyza.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.redwolf501.top/Article/details/gt2tukfddrr.html

[R50] awk 求和
来源：http://dali.ehwqpu.com/Article/details/gt2rlbvgkqj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fengsongda.top/Article/details/gt2cjsqbnbi.html

[R51] 排序去重取前几
来源：http://dali.andypj.xyz/Article/details/gt2wdrktvkc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhengqikj.top/Article/details/gt2zpsnzktv.html

[R52] 统计行数
来源：http://dali.birdmap.top/Article/details/gt2kttshmzc.html

wc -l a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2wowdjgep.html

[R53] 查看文件头与实时尾
来源：http://dali.xinyue.icu/Article/details/gt2oessflhl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xinyue.icu/Article/details/gt2hmgzgkdr.html

[R54] 比较两个文件
来源：http://dali.xinyue.icu/Article/details/gt2pdmlhgxz.html

diff a.txt b.txt
来源：http://dali.guowangkeji.top/Article/details/gt2qlanptlu.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bipxmdha.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhoulong.xyz/Article/details/gt2awqlicjd.html

[R56] 远程拷贝
来源：http://dali.iojbl.cn/Article/details/gt2sztibays.html

scp file user@host:/path/
来源：http://dali.bjfxy.top/Article/details/gt2mlqbmesd.html

[R57] 远程执行命令
来源：http://dali.hammf.cn/Article/details/gt2srksfrag.html

ssh user@host 'uptime'
来源：http://dali.cheryme.top/Article/details/gt2xeeaiygw.html

[R58] 下载文件
来源：http://dali.hysaishi.cn/Article/details/gt2auyyolia.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pengpengdd.cyou/Article/details/gt2dasovgix.html

[R59] 发 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gt2yahsimqr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.birdmap.top/Article/details/gt2mckdopgz.html

[R60] 只看 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gt2buogphji.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.c1oappe.top/Article/details/gt2edtfscmm.html

[R61] 磁盘占用
来源：http://dali.wangshuangyany.cn/Article/details/gt2bhlxjqoy.html

df -h;  du -sh *
来源：http://dali.tian-w.cn/Article/details/gt2bupwfpnb.html

[R62] 找最占空间的文件
来源：http://dali.gotoacloud.top/Article/details/gt2qtxzhsdk.html

du -ah . | sort -rh | head -10
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgqiokxm.html

[R63] 内存与进程
来源：http://dali.cdnleiting.top/Article/details/gt2hnnhwpzo.html

free -h;  ps aux | grep nginx
来源：http://dali.yj202588.top/Article/details/gt2ckdvfohl.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqofpip.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ehwqpu.com/Article/details/gt2eisvgalw.html

[R65] 查看端口占用
来源：http://dali.zhongyouzk.top/Article/details/gt2megjphax.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gt2apestnwi.html

[R66] 定时任务
来源：http://dali.svipenyu.cn/Article/details/gt2btdzmotm.html

crontab -e;  crontab -l
来源：http://dali.xylfe.cn/Article/details/gt2ofhtfewl.html

[R67] 生成随机十六进制串
来源：http://dali.havefunace.top/Article/details/gt2fkghovfl.html

openssl rand -hex 16
来源：http://dali.tian-w.cn/Article/details/gt2pinuswhi.html

[R68] 计算文件校验值
来源：http://dali.pycfn.com/Article/details/gt2srfgjubf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2iyicjeoe.html

[R69] 生成随机密码
来源：http://dali.c1oappe.top/Article/details/gt2ojfvgcpk.html

head -c 16 /dev/urandom | base64
来源：http://dali.fzhhl.top/Article/details/gt2gqqfgljf.html

[R70] 时间戳与互转
来源：http://dali.ppjwa.cn/Article/details/gt2aetomxak.html

date +%s;  date -d @1700000000
来源：http://dali.dianchejie.cn/Article/details/gt2ptwsmdbl.html

[R71] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gt2zsefgagv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jiagoushi.top/Article/details/gt2jvrhyyzj.html

[R72] 等待端口就绪
来源：http://dali.zhoulong.xyz/Article/details/gt2vgddvkhf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gt2hjalhzbt.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xdicfnoo.html

split -l 1000 big.log part_
来源：http://dali.hammf.cn/Article/details/gt2akdhubcs.html

[R74] 批量重命名
来源：http://dali.yueranfly.top/Article/details/gt2fchejsvz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hysaishi.cn/Article/details/gt2gqkjkzaa.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gt2xebbnavt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.havefunace.top/Article/details/gt2lfepzaer.html

[R76] 使用临时文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgnqkrqk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqgvcqxt.html

[R77] 读取用户输入
来源：http://dali.hammf.cn/Article/details/gt2onwrrwgb.html

read -rp "请输入: " ans
来源：http://dali.cucudq.cn/Article/details/gt2pjisftms.html

[R78] 交互式菜单
来源：http://dali.tanke756.top/Article/details/gt2gznjiukl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yueranfly.top/Article/details/gt2sieuflcd.html

[R79] 解析命令行选项
来源：http://dali.yvedp.cn/Article/details/gt2fncoavjs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2buhdejgy.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gt2qbzfkrth.html

time ./run.sh
来源：http://dali.xziqi.cn/Article/details/gt2fnfhvjrc.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2vkmysybm.html

S. C / C++ 专题
来源：http://dali.bjfxy.top/Article/details/gt2rplmcvps.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2pdhpxfbu.html

[S01] C：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2rendlmfi.html

#include <stdio.h>
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jyhhehni.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmkvbxk.html

[S02] C：变量与格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2eexgjwcu.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigfzy.top/Article/details/gt2tjhghotv.html

[S03] C：读入整数
来源：http://dali.c1oappe.top/Article/details/gt2lylfbwtt.html

int x; scanf("%d", &x);
来源：http://dali.guowangkeji.top/Article/details/gt2esfjzcnj.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gt2imlkvltl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ydzc1.top/Article/details/gt2zitkqwrj.html

[S05] C：字符串长度
来源：http://dali.ppjwa.cn/Article/details/gt2tjmxgszo.html

strlen(s)
来源：http://dali.316326.xyz/Article/details/gt2poybtlod.html

[S06] C：字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gt2qkcixzjv.html

strcmp(a, b) == 0
来源：http://dali.yuxming.cn/Article/details/gt2czjwpzqo.html

[S07] C：数组遍历求和
来源：http://dali.xuanzx.com/Article/details/gt2lunztokc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sysykeji.top/Article/details/gt2kvnshhrl.html

[S08] C：动态内存分配与释放
来源：http://dali.dianchejie.cn/Article/details/gt2gcsiytao.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aizwys.cn/Article/details/gt2cnvudrpg.html

[S09] C：结构体定义与初始化
来源：http://dali.cashguo.top/Article/details/gt2tghyebwk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hywenlv.cn/Article/details/gt2dfhbpazy.html

[S10] C：指针与解引用
来源：http://dali.ivvv.top/Article/details/gt2illdibcz.html

int *p = &a;  *p = 5;
来源：http://dali.9152youxi.cn/Article/details/gt2xlfiiaub.html

[S11] C：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2tnmngifc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuanzx.com/Article/details/gt2oxdhlupy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jlsjyb.cn/Article/details/gt2ssfjmmom.html

fclose(f);
来源：http://dali.fengsongda.top/Article/details/gt2gldusjyw.html

[S12] C：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2ktxnceky.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gt2injicgwk.html

[S13] C：宏定义
来源：http://dali.nwbrower.top/Article/details/gt2kklmhvjr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangshuangyany.cn/Article/details/gt2fgfznytk.html

[S14] C：枚举
来源：http://dali.gzhubu.top/Article/details/gt2hkrxnyvt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ukxaljjx.html

[S15] C：类型转换
来源：http://dali.hywenlv.cn/Article/details/gt2ngqahfds.html

(double) a / b
来源：http://dali.gotoacloud.top/Article/details/gt2kcxgraaa.html

[S16] C：位操作置位
来源：http://dali.ppjwa.cn/Article/details/gt2gyrrmvfo.html

x |= (1 << 3);
来源：http://dali.daxiang520.top/Article/details/gt2rxgatdat.html

[S17] C：安全拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2tuyfvxzj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.quarkkingdee.top/Article/details/gt2firykkxn.html

[S18] C：命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gt2fxfibnci.html

int main(int argc, char **argv)
来源：http://dali.xziqi.cn/Article/details/gt2ckmewnms.html

[S19] C：快速排序
来源：http://dali.gotoacloud.top/Article/details/gt2hznrtoen.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gt2rdlqxniq.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qhbqbctr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gt2uiegsdlo.html

[S21] C：字符类别判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2qawhbeij.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gotoacloud.top/Article/details/gt2sudbroki.html

[S22] C：字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gt2rublsvgb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.haohaochexian.top/Article/details/gt2xtxlhjaz.html

[S23] C：随机数
来源：http://dali.smart0.xyz/Article/details/gt2gpjugnwh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmozggke.html

[S24] C：获取本地时间
来源：http://dali.birdmap.top/Article/details/gt2vvfllzzq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.birdmap.top/Article/details/gt2iqpdejri.html

[S25] C：内存拷贝
来源：http://dali.jinqigfzy.top/Article/details/gt2weccvvuh.html

memcpy(dst, src, n);
来源：http://dali.xinyue.icu/Article/details/gt2wecsowgc.html

[S26] C：内存清零
来源：http://dali.pengpengdd.cyou/Article/details/gt2rtjpsbgq.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gt2iyhcpedj.html

[S27] C：定义常量
来源：http://dali.yuanzhike.top/Article/details/gt2hectobqf.html

const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2hthrdlwy.html

[S28] C：静态变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2dzohdcti.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gt2glindgon.html

[S29] C：变参函数
来源：http://dali.yvedp.cn/Article/details/gt2potkbyjv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.birdmap.top/Article/details/gt2fyhdiusl.html

[S30] C：头文件保护
来源：http://dali.snrcjt.cn/Article/details/gt2uhbbhleg.html

#ifndef X_H
来源：http://dali.jqgufenzy.top/Article/details/gt2oreqgbfw.html

#define X_H
来源：http://dali.yonumen.top/Article/details/gt2afmozoqb.html

#endif
来源：http://dali.sweek.top/Article/details/gt2btuvchwl.html

[S31] C++：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2jpxqicll.html

#include <iostream>
来源：http://dali.guowangkeji.top/Article/details/gt2ocomgssg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.316326.xyz/Article/details/gt2hwqaqhxz.html

[S32] C++：字符串
来源：http://dali.fengsongda.top/Article/details/gt2czukcqua.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgufenzy.top/Article/details/gt2dwimccwx.html

[S33] C++：vector 增删
来源：http://dali.dianchejie.cn/Article/details/gt2xnnmimwn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2sfbvioky.html

[S34] C++：遍历 vector
来源：http://dali.316326.xyz/Article/details/gt2xtpcbjfx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2talbfbhr.html

[S35] C++：map
来源：http://dali.cdnleiting.top/Article/details/gt2drognetn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gt2rzjtngig.html

[S36] C++：unordered_map
来源：http://dali.quarkkingdee.top/Article/details/gt2hozxyaop.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2rqzlfeec.html

[S37] C++：set
来源：http://dali.yangfankeji.com/Article/details/gt2aosvwkon.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hammf.cn/Article/details/gt2femydyzx.html

[S38] C++：排序
来源：http://dali.ivvv.top/Article/details/gt2pkwlsfvl.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gt2rcmmqngt.html

[S39] C++：自定义比较器排序
来源：http://dali.bjfxy.top/Article/details/gt2bjemyvky.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jlsjyb.cn/Article/details/gt2swnrvdmy.html

[S40] C++：查找元素
来源：http://dali.zhengqikj.top/Article/details/gt2wtlpzhln.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.birdmap.top/Article/details/gt2hcqinthq.html

[S41] C++：类与构造函数
来源：http://dali.jyoumei.cn/Article/details/gt2unxglovr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gt2wdycswja.html

[S42] C++：继承与虚函数
来源：http://dali.cucudq.cn/Article/details/gt2qguvtesd.html

class B : public Base { public: void f() override {} };
来源：http://dali.hammf.cn/Article/details/gt2fywzgevj.html

[S43] C++：智能指针
来源：http://dali.haohaochexian.top/Article/details/gt2izchltmc.html

auto p = std::make_unique<int>(5);
来源：http://dali.sxryk.cn/Article/details/gt2bbdbuspb.html

[S44] C++：引用传参
来源：http://dali.gotoacloud.top/Article/details/gt2rtawznig.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gt2zvkcmxhy.html

[S45] C++：lambda
来源：http://dali.xylfe.cn/Article/details/gt2xbszdetr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.smart0.xyz/Article/details/gt2qpfnuzhv.html

[S46] C++：函数模板
来源：http://dali.shuidangran.top/Article/details/gt2naqrgtbf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgfzy.top/Article/details/gt2lwogxkyq.html

[S47] C++：结构化绑定遍历
来源：http://dali.hammf.cn/Article/details/gt2ossdiduk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenlongwang.top/Article/details/gt2jqoaljyk.html

[S48] C++：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gt2thxjozfp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hfpthk.cn/Article/details/gt2yunnagli.html

while (std::getline(in, line)) { }
来源：http://dali.yueranfly.top/Article/details/gt2xnpvykhf.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gt2yefatxqe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangshuangyany.cn/Article/details/gt2wwkzsvpk.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gt2ehqclyxh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2fakrxomd.html

[S51] C++：显式类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2zxxnxitz.html

static_cast<double>(a) / b
来源：http://dali.yj20258888.top/Article/details/gt2kokxorvj.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eweniozq.html

int size() const noexcept { return n_; }
来源：http://dali.daxiang520.top/Article/details/gt2qmyjffqr.html

[S53] C++：移动语义
来源：http://dali.xinyue.icu/Article/details/gt2eugjvnbm.html

std::vector<int> w = std::move(v);
来源：http://dali.hywenlv.cn/Article/details/gt2xjdvucxg.html

[S54] C++：异常处理
来源：http://dali.guannengcc.top/Article/details/gt2ftiymnty.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nanxinkj.top/Article/details/gt2pglldvfd.html

[S55] C++：结构化绑定
来源：http://dali.ybcxt.top/Article/details/gt2gutlmqpt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohasjmgn.html

[S56] C++：optional
来源：http://dali.vqdsnc.cn/Article/details/gt2nfolpafe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cdnleiting.top/Article/details/gt2rnpcgzst.html

[S57] C++：编译期常量
来源：http://dali.dashuyun.cn/Article/details/gt2ozvrvnch.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gt2yiczsjgr.html

[S58] C++：命名空间
来源：http://dali.nanxinkj.top/Article/details/gt2mqtwokps.html


<!-- 参考信息 -->